# NP Market – Công cụ xử lý ảnh sản phẩm

Web app chạy **hoàn toàn trong trình duyệt** (ảnh không upload lên server) để xử lý ảnh sản phẩm hàng loạt cho cửa hàng online NP Market.

## Tính năng
- **Watermark chìm** lặp chéo phủ toàn ảnh (mặc định "NP Supermarket"), chỉnh được nội dung / độ mờ / góc / mật độ / màu.
- **Tách nền AI**: xuất nền **trong suốt (PNG)** hoặc **nền xám nhẹ / màu tùy chọn**.
- **Enhance**: lấy nét, độ sáng, tương phản, độ bão hòa màu.
- **Khung vuông chuẩn** e-commerce, canh giữa sản phẩm.
- **Batch**: kéo-thả nhiều ảnh (hoặc cả thư mục), xử lý 1 lần, tải về ZIP.
- Hỗ trợ **HEIC (iPhone)**, JPG, PNG, WebP.

## Dùng thế nào
Mở link GitHub Pages → kéo ảnh vào → (tùy chọn) chỉnh cấu hình → **Xử lý tất cả** → **Tải ZIP**.
Nhân viên chỉ cần dùng preset **"NP Market chuẩn"** là xong.

## Công nghệ
- Xử lý ảnh: Canvas API thuần.
- Tách nền: [@imgly/background-removal](https://github.com/imgly/background-removal-js) (ONNX chạy trong trình duyệt).
- HEIC: heic2any · Nén ZIP: JSZip.
- Model AI tải 1 lần ở lần dùng đầu, sau đó cache offline.

## Riêng tư
Mọi xử lý diễn ra trong máy người dùng. Ảnh **không** được gửi đi bất kỳ đâu.
