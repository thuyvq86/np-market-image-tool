# Hướng dẫn sử dụng – NP Market Image Tool

**Link công cụ:** https://thuyvq86.github.io/np-market-image-tool/

> Mở bằng **Chrome** hoặc **Edge** (có sẵn trên máy). Mọi ảnh được xử lý **ngay trong máy bạn**, không tải lên mạng.

---

## Dùng nhanh trong 3 bước

1. **Kéo-thả ảnh** sản phẩm vào khung (hoặc bấm **Chọn ảnh** / **Chọn cả thư mục**). Hỗ trợ ảnh iPhone (HEIC), JPG, PNG.
2. Bấm **Xử lý tất cả** và chờ thanh tiến trình chạy xong.
   - *Lần đầu* dùng tách nền, công cụ tải model AI (~10–30 giây). Những lần sau nhanh hơn.
3. Bấm **⬇ Tải ZIP** để lấy toàn bộ ảnh đã xử lý.

> Muốn dùng đúng chuẩn NP Market: bấm **↺ Đặt lại "NP Market chuẩn"** ở cột trái là xong, không cần chỉnh gì thêm.

---

## Các tùy chọn (cột trái)

**Watermark** – chữ chìm chống sao chép
- Bật/tắt, đổi nội dung (mặc định *NP Supermarket*), độ mờ, góc nghiêng, mật độ, màu chữ.

**Xử lý hình ảnh**
- *Lấy nét, Độ sáng, Tương phản, Độ bão hòa màu*: kéo thanh trượt để ảnh tươi, rõ hơn.
- *Khung vuông chuẩn*: đưa sản phẩm vào khung vuông, canh giữa (chuẩn ảnh gian hàng).

**Nền (Background)**
- *Giữ nguyên*: không đổi nền.
- *Trong suốt*: tách nền, xuất PNG nền trong (ghép lên nền nào cũng được).
- *Xám nhẹ* / *Màu khác*: tách nền rồi đặt lên nền xám/màu tùy chọn.

**Xuất file**
- Định dạng (Tự động / PNG / JPG), chất lượng, tiền tố tên file (mặc định `NP_`).

Muốn xem thử trước khi chạy cả loạt: bấm **Xem trước** để so sánh ảnh gốc ↔ sau xử lý.

---

## 📸 Mẹo chụp để tách nền luôn sạch

Tách nền AI dễ sai khi **sản phẩm trắng/trong suốt chụp trên nền trắng** (AI không phân biệt được). Khắc phục ngay từ khâu chụp:

1. **Nền tương phản với sản phẩm (quan trọng nhất)**
   - Hàng *trắng / trong suốt / sáng màu* (bánh phở, đồ đông lạnh túi trong) → chụp trên **nền xám hoặc xanh dương nhạt**, đừng nền trắng.
   - Hàng *tối màu* → nền trắng hoặc xám sáng.
2. **Ánh sáng đều, tránh bóng đổ gắt** (chụp gần cửa sổ hoặc 2 đèn hắt 2 bên).
3. **Chụp thẳng mặt trước**, đặt sản phẩm giữa khung, chừa khoảng trống quanh mép.
4. **Để độ phân giải cao**, lấy nét vào chữ trên bao bì. Nếu được, chỉnh iPhone xuất JPG thay vì HEIC (*Cài đặt → Camera → Định dạng → Tương thích nhất*).

---

## Câu hỏi thường gặp

**Ảnh của tôi có bị tải lên mạng không?** Không. Mọi xử lý diễn ra trong trình duyệt trên máy bạn.

**Tách nền bị khuyết một mảng?** Thường do hàng trắng/trong chụp trên nền trắng — xem mẹo chụp ở trên, hoặc chọn *Giữ nguyên* nền cho ảnh đó.

**Mở bằng Safari được không?** Được phần lớn, nhưng nên dùng **Chrome/Edge** để đầy đủ (chọn cả thư mục).

**Lần đầu chạy hơi chậm?** Đúng — công cụ tải model AI 1 lần rồi lưu lại, các lần sau nhanh.
