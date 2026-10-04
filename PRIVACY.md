# Dữ liệu và quyền riêng tư

## Chế độ model cục bộ

Văn bản và audio mẫu được xử lý trên máy chạy ứng dụng khi dùng model cục bộ
(CPU/GPU). Các file audio tạo ra, hồ sơ giọng và dự án được lưu trên máy.
Kho phát hành GitHub không nhận hoặc lưu các nội dung này tự động.

Tải model và tải thêm thành phần GPU cần kết nối đến nhà cung cấp tài nguyên,
chẳng hạn Hugging Face và kho gói Python. Các nhà cung cấp đó có chính sách
riêng. Nếu sử dụng chế độ máy chủ/remote, dữ liệu suy luận được gửi đến máy
chủ đã cấu hình; nhận định xử lý cục bộ ở trên không áp dụng cho chế độ đó.

## Các dữ liệu có thể được lưu

- Nội dung và thiết lập của dự án đã lưu.
- Hồ sơ giọng do người dùng lưu từ audio mẫu.
- WAV/MP3/SRT, nội dung, giọng, model, thời điểm và thời lượng trong lịch sử.
- Model đã tải, cấu hình thiết bị và log vận hành.
- File tạm/cache phục vụ nghe và tải audio trong giao diện.

Ứng dụng desktop lưu dữ liệu mặc định tại `%LOCALAPPDATA%\VieNeu`;
`VIENEU_HOME` có thể thay đổi vị trí này. Khi chạy trực tiếp từ mã nguồn,
thư mục mặc định là `%USERPROFILE%\.vieneu`.

## Xóa dữ liệu

Tab Lịch sử cho phép xóa bản đang chọn hoặc xóa các bản được liệt kê trong
xác nhận xóa toàn bộ. Thao tác này xóa file của bản thu trong thư mục `history`.
Các bản cũ nhất cũng được tự dọn để giữ tối đa 300 bản và 1 GB trong lịch sử.

Audio riêng của dự án, bản đã tải xuống và file cache/tạm nằm ngoài thư mục
lịch sử không bị xóa bởi thao tác đó. Để xóa dữ liệu còn lại, đóng ứng dụng
rồi kiểm tra đúng thư mục trước khi xóa thủ công.

## Báo lỗi trên GitHub

Issue là nội dung công khai nếu kho công khai. Không đăng token, mật khẩu,
audio riêng tư hoặc nội dung tài liệu nhạy cảm trong Issue hay log đính kèm.
