# Ghi nhận các thành phần bên thứ ba

## VieNeu-TTS

- Tác giả: **Phạm Nguyễn Ngọc Bảo** và các cộng tác viên của VieNeu-TTS.
- Mã nguồn gốc: https://github.com/pnnbao97/VieNeu-TTS
- Giấy phép trong mã nguồn được sử dụng: **Apache License 2.0**.
- Bản sao giấy phép được giữ trong [LICENSE](LICENSE).

MG Voice Studio là bản tùy chỉnh giao diện và chức năng ứng dụng, không phải
bản phát hành chính thức của tác giả VieNeu-TTS. Các thay đổi được thực hiện
trong tháng 10/2026 gồm tên MG Voice Studio, giao diện studio, lưu dự án,
hàng đợi, lịch sử bản thu và thao tác xóa, biểu tượng nam/nữ cho giọng đọc.

## Các thành phần sử dụng

Các thành phần có thể có trong bộ cài hoặc được tải khi sử dụng gồm:

- Python và các thư viện Python phục vụ giao diện/xử lý audio, gồm Gradio,
  NumPy, SoundFile, ONNX Runtime, Hugging Face Hub và các phụ thuộc.
- sea-g2p: https://github.com/pnnbao97/sea-g2p
- VieNeu-TTS v3 Turbo: https://huggingface.co/pnnbao-ump/VieNeu-TTS-v3-Turbo
- VieNeu-TTS v3 Nano: https://huggingface.co/pnnbao-ump/VieNeu-TTS-v3-Nano
- MOSS-Audio-Tokenizer-Nano:
  https://huggingface.co/OpenMOSS-Team/MOSS-Audio-Tokenizer-Nano
- Các thành phần GPU tùy cấu hình, chẳng hạn PyTorch và thành phần NVIDIA.

Danh sách này là ghi nhận nguồn gốc, không thay thế giấy phép riêng của từng
thư viện/model. Giấy phép Apache 2.0 của VieNeu-TTS không tự áp dụng cho tất
cả thành phần khác.

Bộ cài được phân phối qua GitHub Releases.
Mỗi bộ cài phát hành cần giữ các tệp giấy phép/thông báo của thành phần được
đóng gói và có danh sách phụ thuộc tương ứng với đúng bản dựng đó.

