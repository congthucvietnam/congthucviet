# 📋 Nhật Ký Thay Đổi (Changelog)

Toàn bộ các phiên bản phát hành của **Công Thức Việt** được ghi lại tại đây.

---

## [1.1.0-dev.20261017] - 2026-10-17 (Kênh Thử Nghiệm)
### ⚡ Tính năng thử nghiệm (Experimental Features)
- Thử nghiệm Studio tạo đề AI thế hệ mới với cơ chế đính kèm đề cương trực tiếp.
- Thử nghiệm tính năng chuyển đổi 6 chiều Word-MathType-LaTeX.
- Dành riêng cho cộng đồng kiểm thử sớm trước khi đưa vào bản Stable.

---

## [1.0.0] - 2026-10-17 (Bản Ổn Định Chính Thức)
### ✨ Tính năng nổi bật (Key Features)
- **Studio Trợ Lý AI Tạo Đề Thi GDPT 2018:**
  - Hỗ trợ tạo đề kiểm tra và đề cương ôn tập tự động theo chuẩn cấu trúc GDPT 2018 (Phần I Trắc nghiệm 4 lựa chọn, Phần II Đúng/Sai, Phần III Trả lời ngắn, Bảng đáp án có lời giải chi tiết).
  - Tùy chọn "Đính kèm tệp sau" để người dùng gửi file đề cương trực tiếp qua ChatGPT / Gemini.
  - Tùy chọn "Có đáp án" (mặc định được chọn).
  - Tự động chuẩn hóa và xuất ra cả định dạng `.json` và `.md` có công thức toán học và hình ảnh chuẩn.
- **Nút Cập Nhật & Góp Ý trên Ribbon Word:**
  - Nút kiểm tra bản cập nhật mới tự động theo 2 kênh Stable và Dev.
  - Nút Báo lỗi / Góp ý liên kết trực tiếp với GitHub Issues & Google Form.
  - Nút Hỏi đáp liên kết với GitHub Discussions cộng đồng `congthucvietnam/congthucviet`.
- **Động cơ Toán học OLE 7.0 Native:**
  - Tương thích 100% MathType OLE (Equation.DSMT4).
  - Chèn công thức chuẩn Word OLE, nhấp đúp để sửa, không lệch dòng (baseline) khi in ấn.

### 🛠️ Cải tiến & Sửa lỗi (Fixes & Improvements)
- **Chỉ số dưới (Subscript):** Bôi đen chữ/số bấm chỉ số dưới tự động chuyển đổi thông minh thành `_x` (tương tự như số mũ trên `^x`).
- **Gõ tiếng Việt UniKey:** Rà soát và bảo vệ toàn diện bộ đệm phím, khắc phục triệt để lỗi không gõ được tiếng Việt có dấu khi đang mở editor.
- **Tắt cửa sổ trống an toàn:** Khi công thức trống rỗng, bấm nút đóng hoặc hủy sẽ thoát ngay lập tức, không gây treo tiến trình.

---

## [2.0.0] - 2026-10-01
### ✨ Phiên bản nền tảng (Foundation Release)
- Động cơ chèn công thức Word OLE 7.0 (DSMT4) tương thích 100% MathType.
- Soạn thảo LaTeX trực quan không cần cài đặt Python.
- Bộ cài đặt 1-Click thông minh tự động cấu hình VSTO Add-in và font toán học.
