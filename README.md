\# Hệ thống giám sát nhiệt độ đa kênh LM35



Dự án theo dõi nhiệt độ sử dụng cảm biến LM35 và Arduino, hỗ trợ xuất dữ liệu định dạng JSON qua Serial.



\## Tính năng chính

\- \[x] Đọc dữ liệu nhiệt độ từ 3 cảm biến LM35 (Kênh A0, A1, A2).

\- \[x] Xuất dữ liệu chuẩn định dạng \*\*JSON\*\* giúp dễ dàng tích hợp với Web/App.

\- \[x] Quản lý mã nguồn chuyên nghiệp bằng Git \& GitHub.



\## Danh sách linh kiện

| Linh kiện | Số lượng | Cổng kết nối |

| :--- | :---: | :--- |

| Arduino Uno R3 | 01 | USB |

| Cảm biến LM35 | 03 | A0, A1, A2 |

| Breadboard \& Dây cắm | 01 | - |



\## Cấu trúc thư mục

\- `firmware/`: Chứa mã nguồn Arduino (.ino)

\- `docs/`: Chứa tài liệu hướng dẫn và sơ đồ nguyên lý.



\## Thành viên thực hiện

1\. \*\*Tô Bích Nguyên\*\* - (SV A): Thiết kế phần cứng, thêm kênh A2.

2\. \*\*Hồng Như\*\* - (SV B): Cải tiến giao thức JSON, xử lý xung đột code.

