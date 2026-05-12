# Peer Review Response - Lab 6 AES-CBC Socket

## Thông tin nhóm
- **Thành viên 1**: Đỗ Trung Kiên (MSSV: 1871020344)
- **Thành viên 2**: Nguyễn Việt Cường (MSSV: 1871020114)

## Phản hồi đánh giá
- **Tính đầy đủ**: Nhóm đã hoàn thành toàn bộ các module mã nguồn (`sender.py`, `receiver.py`, `aes_socket_utils.py`) và các file báo cáo theo yêu cầu của đề bài.
- **Cơ chế hoạt động**: Hệ thống đã tách biệt thành công kênh truyền khóa (KEY_PORT) và kênh truyền dữ liệu (DATA_PORT).
- **An toàn bảo mật**: Nhóm thừa nhận điểm yếu của việc truyền khóa plaintext qua socket và đã phân tích kỹ trong file `threat-model-1page.md`.
- **Khắc phục**: Các lỗi về padding và kết nối socket đã được kiểm thử và xử lý thông qua bộ test case trong thư mục `tests/`.