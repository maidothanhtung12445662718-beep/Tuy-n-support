# Tuyen-Support
<!DOCTYPE html>
<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Discord Support Recruitment 💜</title>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700&display=swap" rel="stylesheet">
    <style>
        :root {
            --bg-color: #2f3136;
            --container-bg: #36393f;
            --text-color: #dcddde;
            --text-muted: #b9bbbe;
            --discord-blue: #5865f2;
            --discord-green: #3ba55d;
            --discord-danger: #ed4245;
            --input-bg: #202225;
            --border-radius: 8px;
        }

        * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
            font-family: 'Inter', sans-serif;
        }

        body {
            background-color: var(--bg-color);
            color: var(--text-color);
            display: flex;
            flex-direction: column;
            align-items: center;
            min-height: 100vh;
            padding: 20px 10px;
        }

        .container {
            background-color: var(--container-bg);
            width: 100%;
            max-width: 700px;
            border-radius: var(--border-radius);
            box-shadow: 0 8px 24px rgba(0, 0, 0, 0.2);
            padding: 25px 20px;
            border: 1px solid rgba(255, 255, 255, 0.05);
            margin-bottom: 30px;
        }

        .header {
            text-align: center;
            margin-bottom: 30px;
            border-bottom: 2px solid rgba(255, 255, 255, 0.05);
            padding-bottom: 15px;
        }

        .header h1 {
            color: #fff;
            font-size: 22px;
            font-weight: 700;
            margin-bottom: 10px;
            display: flex;
            justify-content: center;
            align-items: center;
            gap: 8px;
        }

        .header p {
            color: var(--text-muted);
            font-size: 13px;
        }

        .form-group {
            margin-bottom: 22px;
        }

        .form-group label {
            display: block;
            color: #fff;
            font-size: 14px;
            font-weight: 600;
            margin-bottom: 8px;
            line-height: 1.4;
        }

        .form-group label span {
            color: var(--discord-danger);
        }

        input[type="text"], textarea {
            width: 100%;
            background-color: var(--input-bg);
            border: 1px solid transparent;
            border-radius: 4px;
            color: #fff;
            padding: 12px;
            font-size: 14px;
            transition: border-color 0.2s ease;
            outline: none;
        }

        input[type="text"]:focus, textarea:focus {
            border-color: var(--discord-blue);
        }

        textarea {
            resize: vertical;
            min-height: 80px;
        }

        .radio-group, .checkbox-group {
            display: flex;
            flex-direction: column;
            gap: 8px;
            background: var(--input-bg);
            padding: 12px;
            border-radius: var(--border-radius);
        }

        .radio-option, .checkbox-option {
            display: flex;
            align-items: center;
            gap: 10px;
            cursor: pointer;
            color: var(--text-color);
            font-size: 14px;
        }

        .radio-option input, .checkbox-option input {
            accent-color: var(--discord-blue);
            width: 18px;
            height: 18px;
        }

        .btn-submit {
            background-color: var(--discord-blue);
            color: #fff;
            border: none;
            width: 100%;
            padding: 14px;
            font-size: 15px;
            font-weight: 600;
            border-radius: 4px;
            cursor: pointer;
            transition: background-color 0.2s ease;
            margin-top: 10px;
        }

        .btn-submit:hover { background-color: #4752c4; }

        /* Modal Thông Báo */
        .modal-overlay {
            position: fixed;
            top: 0; left: 0; width: 100%; height: 100%;
            background: rgba(0, 0, 0, 0.8);
            display: flex; justify-content: center; align-items: center;
            opacity: 0; pointer-events: none; transition: opacity 0.3s ease;
            z-index: 1000; padding: 20px;
        }

        .modal-overlay.active { opacity: 1; pointer-events: auto; }

        .modal {
            background-color: var(--container-bg);
            padding: 30px 20px;
            border-radius: var(--border-radius);
            max-width: 450px;
            width: 100%;
            text-align: center;
            border: 1px solid rgba(255, 255, 255, 0.1);
        }

        .badge {
            display: inline-block;
            padding: 6px 12px;
            border-radius: 20px;
            font-weight: 700;
            font-size: 12px;
            margin: 10px 0;
        }
        .badge-owner { background-color: #f1c40f; color: #000; }
        .badge-admin { background-color: var(--discord-danger); color: #fff; }

        .btn-close {
            background-color: #4f545c; color: #fff; border: none;
            padding: 8px 20px; border-radius: 4px; font-weight: 600; margin-top: 15px;
        }

        /* KHU VỰC QUẢN LÝ ĐƠN NỘP */
        .admin-section {
            background-color: #202225;
            width: 100%;
            max-width: 700px;
            border-radius: var(--border-radius);
            padding: 20px;
            border: 2px dashed #4f545c;
        }

        .admin-section h3 {
            color: #fff; margin-bottom: 15px; font-size: 16px;
            display: flex; align-items: center; gap: 8px;
        }

        .applicant-card {
            background: var(--container-bg);
            padding: 15px;
            border-radius: 6px;
            margin-top: 15px;
            border-left: 4px solid var(--discord-blue);
        }

        .applicant-card p {
            font-size: 13px; margin-bottom: 6px; line-height: 1.4;
        }

        .applicant-card strong { color: #fff; }

        .btn-danger {
            background-color: var(--discord-danger);
            color: white; border: none; padding: 6px 12px;
            border-radius: 4px; font-size: 12px; cursor: pointer; margin-top: 8px;
        }
        .btn-danger:hover { background-color: #c93b3e; }
    </style>
</head>
<body>

    <div class="container">
        <div class="header">
            <h1>🔮 TUYỂN SUPPORT DISCORD 🔮</h1>
            <p>Vui lòng điền đầy đủ thông tin bên dưới</p>
        </div>

        <form id="recruitmentForm">
            <div class="form-group">
                <label>1. ID Discord của bạn là gì? 🆔 <span>*</span></label>
                <input type="text" id="discordId" placeholder="Ví dụ: wumpus#1234" required>
            </div>

            <div class="form-group">
                <label>2. Bạn có thể online cố định vào khung giờ nào? ⏰ <span>*</span></label>
                <div class="checkbox-group">
                    <label class="checkbox-option"><input type="checkbox" name="timeframe" value="Sáng"> 🌅 Sáng (06h-12h)</label>
                    <label class="checkbox-option"><input type="checkbox" name="timeframe" value="Chiều"> ☀️ Chiều (12h-18h)</label>
                    <label class="checkbox-option"><input type="checkbox" name="timeframe" value="Tối"> 🌌 Tối (18h-00h)</label>
                    <label class="checkbox-option"><input type="checkbox" name="timeframe" value="Đêm"> 🦉 Đêm (00h-06h)</label>
                </div>
            </div>

            <div class="form-group">
                <label>3. Bạn dự định gắn bó với server trong bao lâu? 🤝 <span>*</span></label>
                <input type="text" id="commitment" placeholder="Ví dụ: Lâu dài, 6 tháng..." required>
            </div>

            <div class="form-group">
                <label>4. Nếu bận đột xuất vài ngày, bạn báo cáo thế nào? 📑 <span>*</span></label>
                <textarea id="emergency" placeholder="Cách bạn xin phép nghỉ..." required></textarea>
            </div>

            <div class="form-group">
                <label>5. Bạn có ngại làm việc sau 12h đêm không? 🌙 <span>*</span></label>
                <div class="radio-group">
                    <label class="radio-option"><input type="radio" name="lateNight" value="Có ngại" required> ❌ Có ngại</label>
                    <label class="radio-option"><input type="radio" name="lateNight" value="Không ngại"> 🟢 Không ngại</label>
                </div>
            </div>

            <div class="form-group">
                <label>6. Kinh nghiệm về thông báo, chia sẻ hack? 💻 <span>*</span></label>
                <textarea id="experience" required></textarea>
            </div>

            <div class="form-group">
                <label>7. Nếu bị Member xúc phạm, chửi bới bạn làm gì? 🤬 <span>*</span></label>
                <textarea id="abuseHandle" required></textarea>
            </div>

            <div class="form-group">
                <label>8. Nếu thành viên bị scam, bạn sẽ làm gì? 💸 <span>*</span></label>
                <textarea id="scamHandle" required></textarea>
            </div>

            <div class="form-group">
                <label>9. Nếu thành viên cãi nhau bạn sẽ làm gì? ⚔️ <span>*</span></label>
                <textarea id="argumentHandle" required></textarea>
            </div>

            <div class="form-group">
                <label>10. Cam kết giữ bí mật kênh nội bộ Staff? 🤫 <span>*</span></label>
                <div class="radio-group">
                    <label class="radio-option"><input type="radio" name="secretCommit" value="Có cam kết" required> ✅ Cam kết tuyệt đối</label>
                    <label class="radio-option"><input type="radio" name="secretCommit" value="Không"> ❌ Không</label>
                </div>
            </div>

            <div class="form-group">
                <label>11. Gặp câu hỏi khó từ mem không biết trả lời làm gì? 🧠 <span>*</span></label>
                <textarea id="hardQuestion" required></textarea>
            </div>

            <div class="form-group">
                <label>12. Điều gì ở Support khiến bạn ghét nhất? Cách tránh? 🛑 <span>*</span></label>
                <textarea id="hateTraits" required></textarea>
            </div>

            <button type="submit" class="btn-submit">🚀 BẤM NỘP ĐƠN</button>
        </form>
    </div>

    <div class="admin-section">
        <h3>📊 DANH SÁCH ĐƠN ĐÃ GỬI (DÀNH CHO NGƯỜI TẠO WEB)</h3>
        <div id="applicantList"></div>
    </div>

    <div class="modal-overlay" id="modalOverlay">
        <div class="modal">
            <h2 style="color:#fff; font-size:20px; margin-bottom:10px;">🎉 Nộp Thành Công!</h2>
            <div id="modalBody"></div>
            <button class="btn-close" onclick="closeModal()">Đóng</button>
        </div>
    </div>

    <script>
        if (!localStorage.getItem('applicantCount')) localStorage.setItem('applicantCount', '0');

        const form = document.getElementById('recruitmentForm');
        const modalOverlay = document.getElementById('modalOverlay');
        const modalBody = document.getElementById('modalBody');

        // Tự động tải danh sách đơn khi vừa mở trang web
        window.onload = function() {
            renderApplicants();
        };

        form.addEventListener('submit', function(e) {
            e.preventDefault();
            
            let count = parseInt(localStorage.getItem('applicantCount')) + 1;
            localStorage.setItem('applicantCount', count.toString());

            let applicants = JSON.parse(localStorage.getItem('allApplicants') || '[]');
            let timeframes = [];
            document.querySelectorAll('input[name="timeframe"]:checked').forEach(cb => timeframes.push(cb.value));

            if(timeframes.length === 0) {
                alert("Vui lòng chọn ít nhất một khung giờ online! ⏰");
                return;
            }

            let newApplicant = {
                id: count,
                discordId: document.getElementById('discordId').value,
                timeframes: timeframes.join(', '),
                commitment: document.getElementById('commitment').value,
                emergency: document.getElementById('emergency').value,
                lateNight: document.querySelector('input[name="lateNight"]:checked').value,
                experience: document.getElementById('experience').value,
                abuseHandle: document.getElementById('abuseHandle').value,
                scamHandle: document.getElementById('scamHandle').value,
                argumentHandle: document.getElementById('argumentHandle').value,
                secretCommit: document.querySelector('input[name="secretCommit"]:checked').value,
                hardQuestion: document.getElementById('hardQuestion').value,
                hateTraits: document.getElementById('hateTraits').value
            };

            applicants.push(newApplicant);
            localStorage.setItem('allApplicants', JSON.stringify(applicants));

            let privilegeMsg = "";
            if (count === 1) {
                privilegeMsg = `<br><span class="badge badge-owner">👑 ĐẶC QUYỀN: OWNER</span><br><strong>Bạn là người đầu tiên, nhận ngay quyền Owner!</strong>`;
            } else if (count === 2 || count === 3) {
                privilegeMsg = `<br><span class="badge badge-admin">🛠️ ĐẶC QUYỀN: ADMIN</span><br><strong>Bạn thuộc top 3 người đầu tiên, nhận quyền Admin!</strong>`;
            }

            modalBody.innerHTML = `
                <p>Đơn số <strong>#${count}</strong> đã được gửi lên hệ thống.</p>
                <p>⌛ <strong>Vui lòng chờ:</strong> 1 - 5 ngày để Người tạo web duyệt.</p>
                ${privilegeMsg}
            `;
            modalOverlay.classList.add('active');
        });

        function closeModal() {
            modalOverlay.classList.remove('active');
            form.reset();
            renderApplicants();
        }

        function renderApplicants() {
            const listDiv = document.getElementById('applicantList');
            const applicants = JSON.parse(localStorage.getItem('allApplicants') || '[]');
            
            if(applicants.length === 0) {
                listDiv.innerHTML = "<p style='color:var(--text-muted); font-size:13px; margin-top:5px;'>Chưa có ai nộp đơn hết.</p>";
                return;
            }

            listDiv.innerHTML = "";
            applicants.forEach((user, index) => {
                let role = "Thành viên";
                if(user.id === 1) role = "👑 OWNER";
                else if(user.id === 2 || user.id === 3) role = "🛠️ ADMIN";

                listDiv.innerHTML += `
                    <div class="applicant-card">
                        <p><strong>STT đơn:</strong> #${user.id} - <strong>Quyền nhận:</strong> <span style="color:#f1c40f; font-weight:bold;">${role}</span></p>
                        <p><strong>ID Discord:</strong> ${user.discordId}</p>
                        <p><strong>Khung giờ:</strong> ${user.timeframes}</p>
                        <p><strong>Gắn bó:</strong> ${user.commitment}</p>
                        <p><strong>Bận đột xuất:</strong> ${user.emergency}</p>
                        <p><strong>Online muộn:</strong> ${user.lateNight}</p>
                        <p><strong>Kinh nghiệm Hack:</strong> ${user.experience}</p>
                        <p><strong>Bị chửi xử lý:</strong> ${user.abuseHandle}</p>
                        <p><strong>Mem bị Scam:</strong> ${user.scamHandle}</p>
                        <p><strong>Mem cãi nhau:</strong> ${user.argumentHandle}</p>
                        <p><strong>Bảo mật:</strong> ${user.secretCommit}</p>
                        <p><strong>Câu hỏi khó:</strong> ${user.hardQuestion}</p>
                        <p><strong>Ghét nhất ở bộ phận support:</strong> ${user.hateTraits}</p>
                        <button class="btn-danger" onclick="deleteApplicant(${index})">Xóa đơn này</button>
                    </div>
                `;
            });
        }

        function deleteApplicant(index) {
            if(confirm("Bạn có chắc chắn muốn xóa đơn này không?")) {
                let applicants = JSON.parse(localStorage.getItem('allApplicants') || '[]');
                applicants.splice(index, 1);
                localStorage.setItem('allApplicants', JSON.stringify(applicants));
                renderApplicants();
            }
        }
    </script>
</body>
</html>
