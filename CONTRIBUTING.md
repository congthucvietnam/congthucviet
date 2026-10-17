# 🤝 Hướng Dẫn Đóng Góp Cho Công Thức Việt

Cảm ơn Quý Thầy/Cô và các bạn đã quan tâm đến việc đóng góp xây dựng hệ sinh thái **Công Thức Việt**.

Mặc dù mã nguồn ứng dụng lõi (Word Add-in, C++ Core) được giữ bản quyền độc quyền để đảm bảo an ninh và tính ổn định, chúng tôi mở rộng cánh cửa tiếp nhận mọi đóng góp cộng đồng qua **Pull Request (PR)** ở các lĩnh vực sau:

---

## 1. Đóng Góp Mẫu Đề Thi GDPT 2018 (`templates/`)

Công Thức Việt hỗ trợ Studio Trợ lý AI tạo đề thi tự động. Quý Thầy/Cô có thể đóng góp các bộ khung đề kiểm tra:
- Thư mục lưu trữ: `templates/<mon-hoc>/<cap-hoc>/` (Ví dụ: `templates/toan/thpt/de_giua_ky_1_toan_12.json`).
- Cấu trúc đề chuẩn GDPT 2018:
  - **Phần I:** Trắc nghiệm nhiều lựa chọn (4 phương án A, B, C, D).
  - **Phần II:** Trắc nghiệm Đúng / Sai (mỗi câu 4 ý a, b, c, d).
  - **Phần III:** Trắc nghiệm trả lời ngắn.
  - **Phần IV (nếu có):** Tự luận.
  - Kèm ma trận điểm và bảng đáp án chi tiết.

## 2. Đóng Góp Thư Viện Ký Hiệu & Phím Tắt (`snippets/`)

- Thư viện phím tắt LaTeX viết nhanh (Ví dụ: `\hpt` thành hệ phương trình, `\tichphan` thành tích phân từng phần...).
- Ký hiệu đặc thù môn Vật lý (mạch điện, quang học), Hóa học (công thức cấu tạo, mũi tên phản ứng cân bằng), Sinh học (di truyền học).

## 3. Đóng Góp Tài Liệu & Hướng Dẫn Sử Dụng (`docs/`)

- Hướng dẫn các mẹo căn chỉnh tài liệu Word đẹp.
- Hướng dẫn chuyển đổi hàng loạt từ MathType cũ sang Công Thức Việt OLE 7.0.
- Video hướng dẫn / hình ảnh minh họa bài giảng.

---

## Quy Trình Gửi Pull Request (PR)

1. **Fork** kho lưu trữ `congthucvietnam/congthucviet` về tài khoản GitHub của Thầy/Cô.
2. Tạo một nhánh mới (Branch) đặt tên gợi nhớ: `git checkout -b them-mau-de-toan-12`.
3. Thêm file đóng góp vào thư mục tương ứng.
4. Commit và đẩy lên GitHub cá nhân: `git push origin them-mau-de-toan-12`.
5. Tạo **Pull Request (PR)** vào nhánh `main` của `congthucvietnam/congthucviet`.
6. Ban quản trị sẽ rà soát và merge đóng góp của Thầy/Cô vào phiên bản phát hành tiếp theo!
