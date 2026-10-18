# Học cùng AI · 8 câu lệnh

Trang web tĩnh, không cần cài thư viện hoặc chạy bước build.

## Mã nguồn tại thư mục gốc

- `index.html`: giao diện trang.
- `style.css`: bố cục và màu sắc.
- `data.js`: 8 mã lệnh đã đối chiếu với hình ảnh video.
- `app.js`: nhập chủ đề, chuyển chế độ, lọc và sao chép.
- `vercel.json`: cấu hình triển khai Vercel.

## Triển khai trên Vercel

1. Đưa thư mục gốc TIPS lên kho Git và import vào Vercel.
2. Chọn Framework Preset: Other; Root Directory: thư mục gốc (`.`).
3. Không cần Install Command hoặc Build Command. Output Directory là `.` theo cấu hình có sẵn.
4. Bấm Deploy. Không cần biến môi trường.

Hoặc chạy `vercel` ngay tại thư mục gốc nếu đã cài Vercel CLI.

`.vercelignore` loại các bản lưu Sites và tài liệu video khỏi nội dung triển khai. Chỉnh sửa các file tại thư mục gốc cho các lần triển khai Vercel tiếp theo.
