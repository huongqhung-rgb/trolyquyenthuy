# Trợ lý Quyên trên iPhone (cài như ứng dụng web)

File APK chỉ cài được trên Android. iPhone dùng cách này: đưa app lên một địa chỉ web (GitHub Pages, miễn phí), rồi thêm vào Màn hình chính bằng Safari.

## Phần A. Anh làm trên máy tính (khoảng 10 phút)
1. Vào github.com, đăng nhập, bấm **+ > New repository**. Đặt tên `trolyquyen`, chọn **Public** (gói miễn phí cần Public để bật Pages). Bấm **Create repository**.
   Nội dung đưa lên chỉ là mã app, không có dữ liệu cá nhân; dữ liệu của chị Quyên nằm trong điện thoại của chị.
2. Bấm **uploading an existing file**. Giải nén file zip này, chọn **toàn bộ 7 file bên trong** (index.html, manifest.webmanifest, sw.js, 3 file .png, README.md) kéo vào trình duyệt, bấm **Commit changes**.
3. Vào **Settings > Pages**. Mục Source chọn **Deploy from a branch**, Branch chọn **main**, thư mục **/ (root)**, bấm **Save**.
4. Chờ 1 đến 3 phút, tải lại trang Pages. Địa chỉ app hiện ở đầu trang, dạng `https://TÊN-TÀI-KHOẢN.github.io/trolyquyen/`. Gửi địa chỉ này cho chị Quyên.

## Phần B. Chị Quyên làm trên iPhone
1. Mở **Safari** (bắt buộc là Safari, không dùng Chrome, Zalo hay Messenger) và gõ địa chỉ trên.
2. Bấm nút **Chia sẻ** (hình vuông có mũi tên hướng lên) ở thanh dưới.
3. Kéo xuống chọn **Thêm vào Màn hình chính**, giữ tên "Trợ lý Quyên", bấm **Thêm**. Nếu có công tắc **Mở dưới dạng ứng dụng web**, hãy bật.
4. Từ nay chỉ mở app bằng biểu tượng mới trên Màn hình chính. Không nhập dữ liệu trong Safari trước, vì Safari và biểu tượng trên Màn hình chính lưu dữ liệu riêng, không chia sẻ cho nhau.

## Giới hạn trên iPhone (cần biết trước)
- Không có thông báo nhắc việc khi tắt app, không có widget màn hình khóa, không mở khóa bằng Face ID. Muốn nhắc đúng giờ, chị Quyên nên đặt thêm nhắc trong ứng dụng Lời nhắc hoặc Lịch của iPhone.
- Micro có thể không dùng được khi mở từ Màn hình chính. Nếu vậy, gõ chữ vào ô thêm nhanh.
- Két sắt vẫn mã hóa bằng PIN 6 số nhưng không có Face ID. Quên PIN thì mất dữ liệu trong két.
- Dữ liệu chỉ nằm trên chiếc iPhone đó. Xóa app khỏi Màn hình chính hoặc xóa dữ liệu Safari là mất dữ liệu. Hãy thường xuyên bấm ⚙ > Sao lưu, chép nội dung gửi cho chính mình qua Ghi chú hoặc email.

## Cập nhật bản mới
Anh thay file `index.html` trên GitHub (mở file, bấm bút chì, dán nội dung mới, Commit). Chị Quyên đóng hẳn app rồi mở lại 1 đến 2 lần để nhận bản mới.

## Muốn có app thật trên iPhone (có thông báo, widget, Face ID)
Cần máy Mac có Xcode và tài khoản Apple Developer (99 USD/năm) để gửi qua TestFlight; dùng Apple ID miễn phí thì app hết hạn sau 7 ngày và phải cài lại. Gói này chưa gồm phần đó.
