# Phần 1: Bảng so sánh Absolute Path và Relative Path
## Đường dẫn tuyệt đối (Absolute Path):

- Tiêu chí: C:\Users\An-K26\FarmProject\data\logs.csv
- Độ dài và cấu trúc; Dài, cồng kềnh, chứa đầy đủ đường dẫn gốc từ tên ổ đĩa (C:\) tới file.
- Tính di động: Kém

## Đường dẫn tương đối (Relative Path):
- Tiêu chí: ../data/logs.csv
- Độ dài và cấu trúc: Ngắn gọn, chỉ rõ vị trí tương đối tính từ thư mục chứa script đang thực thi.
- Tính di động: Cao
# Phần 2: Lựa chọn giải pháp tối ưu và ý nghĩa ký hiệu
## 1. Lựa chọn giải pháp tối ưu
Giải pháp tối ưu và chuẩn mực trong lập trình là sử dụng đường dẫn tương đối (../data/logs.csv).

## 2. Ý nghĩa của ký hiệu .. trong lựa chọn đó
Ký hiệu .. (hai dấu chấm) đại diện cho thư mục cha (parent directory) của thư mục hiện tại mà script Python đang chạy.

Khi kết hợp vào đường dẫn (../data/logs.csv), nó có ý nghĩa: "Di chuyển ngược lên một cấp thư mục từ vị trí hiện tại của script, sau đó truy cập vào thư mục data để tìm file logs.csv". Việc này giúp script không bị phụ thuộc vào vị trí thư mục gốc cố định trên một ổ đĩa cụ thể của cá nhân nào.
