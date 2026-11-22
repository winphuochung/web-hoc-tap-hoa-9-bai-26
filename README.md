# Web/app học tập — Hóa học 9, Bài 26

**Bài 26: Ethylic alcohol**
Môn Khoa học tự nhiên 9 (phân môn Hóa học) — Chương trình GDPT 2018, sách Kết nối tri thức với cuộc sống.

Giáo viên: Lê Văn Thắng — Trường TH và THCS Phước Hưng, xã Nhơn Hội, tỉnh An Giang.

## Nội dung

Web/app học tập 6 phần: Khởi động, Khám phá, Mô phỏng, Sơ đồ tư duy, Luyện tập (10 câu trắc nghiệm tự chấm), Vận dụng.

Mô phỏng gồm:
1. Đốt cháy ethylic alcohol (SGK trang 119): bát sứ + que đóm dài + ngọn lửa màu xanh mờ; kèm lưu ý an toàn (3 bước).
2. Natri và ethylic alcohol (SGK trang 120): ống nghiệm + mẩu natri + bọt khí hydrogen; mẩu natri tan dần (3 bước).

Châm ngôn intro: “Rượu etylic — biết đúng, dùng đúng mới có ích.”
Châm ngôn outro: “Hiểu về cồn, em biết tự bảo vệ mình và mọi người.”

Khóa đáp án trắc nghiệm: **1B 2C 3A 4A 5B 6D 7C 8D 9B 10D**.

## Trạng thái: CHỜ /exec

Khóa `hoa9-bai26` chưa có Apps Script Web App URL (Google đang chặn tạo dự án mới).
File `index.html` hiện **không** có fetch gửi điểm về Google Sheets — điểm trắc nghiệm
chỉ lưu localStorage (điểm cao nhất). Sau khi deploy Apps Script xong, patch thêm
fetch vào `index.html` (và đồng bộ `Web_Hoc_Tap_Hoa9_Bai26.md`) theo mẫu Bài 1 Hóa 8.

## Cách dùng

- Mở file `index.html` bằng trình duyệt bất kì (không cần máy chủ).
- Học sinh đăng nhập bằng Họ tên + Lớp, học 6 phần, làm 10 câu trắc nghiệm rồi nộp bài.
- Điểm cao nhất lưu trên máy học sinh (localStorage).

## File trong repo

- `index.html` — web/app hoàn chỉnh, tự chứa (hình ảnh nhúng base64).
- `Web_Hoc_Tap_Hoa9_Bai26.md` — bản sao toàn bộ mã nguồn kèm khóa đáp án.
- `Code.gs` — Apps Script ghi điểm về Google Sheets (tab `KetQua`), dùng sau khi deploy.
- `assets-flow/` — 3 ảnh nền gốc (Gemini, 1376×768) + logo cá nhân của Thầy.
