
\# Hệ thống giám sát nhiệt độ đa kênh LM35



Dự án theo dõi nhiệt độ sử dụng cảm biến LM35 và Arduino, hỗ trợ xuất dữ liệu định dạng JSON qua Serial.



\## Tính năng chính

\- \[x] Đọc dữ liệu nhiệt độ từ 3 cảm biến LM35 (Kênh A0, A1, A2).

\- \[x] Xuất dữ liệu chuẩn định dạng \*\*JSON\*\* giúp dễ dàng tích hợp với Web/App.

\- \[x] Quản lý mã nguồn chuyên nghiệp bằng Git \& GitHub.



## Danh sách linh kiện

| Linh kiện | Số lượng | Cổng kết nối |
| :--- | :---: | :--- |
| Arduino Uno R3 | 01 | USB |
| Cảm biến LM35 | 03 | A0, A1, A2 |
| Breadboard & Dây cắm | 01 | - |


\## Cấu trúc thư mục

\- `firmware/`: Chứa mã nguồn Arduino (.ino)

\- `docs/`: Chứa tài liệu hướng dẫn và sơ đồ nguyên lý.



\## Thành viên thực hiện

1\. \*\*Tô Bích Nguyên\*\* - (SV A): Thiết kế phần cứng, thêm kênh A2.

2\. \*\*Hồng Như\*\* - (SV B): Cải tiến giao thức JSON, xử lý xung đột code.

# **Arduino LM35 Temperature Monitor**


**1. Giới thiệu dự án**

* Đây là dự án thực hành thuộc học phần Mạng cảm biến. Dự án này thực hiện việc thu thập dữ liệu nhiệt độ từ 3 cảm biến LM35 sử dụng Arduino UNO và gửi dữ liệu về máy tính thông qua giao tiếp Serial. Ngoài ra, dự án còn ứng dụng Git và GitHub để quản lý phiên bản mã nguồn trong quá trình phát triển hệ thống.



**2. Các tính năng chính**

* Đo nhiệt độ đa kênh: Hỗ trợ đọc dữ liệu đồng thời từ 03 cảm biến LM35 thông qua các cổng Analog A0, A1 và A2.
* Định dạng dữ liệu JSON: Dữ liệu gửi qua Serial được đóng gói dưới dạng JSON (Key-Value) giúp dễ dàng tích hợp với các ứng dụng Web hoặc IoT.
* Cấu trúc dự án chuẩn: Tổ chức thư mục rõ ràng, bao gồm mã nguồn firmware, sơ đồ mô phỏng và ứng dụng trên máy tính.
* Quản lý phiên bản chuyên nghiệp: Sử dụng quy trình Git (Branch, Pull Request) và giải quyết xung đột (Conflict resolution) trong cộng tác nhóm.



**3. Danh sách phần cứng và phần mềm**



**Phần cứng**

|**STT**|**Linh kiện**|**Số lượng**|**Ghi chú**|
|-|-|-|-|
|1|Arduino UNO R3|1|Board mạch điều khiển chính|
|2|Cảm biến LM35	03|3|Cảm biến nhiệt độ Analog|
|3|Breadboard \& Dây cắm|1|Kết nối linh kiện|





**Phần mềm**

* Arduino IDE: Lập trình và nạp firmware.
* Git Bash: Quản lý phiên bản và đẩy mã nguồn lên GitHub.
* Proteus: Mô phỏng mạch điện tử.
* VS Code / Notepad++: Chỉnh sửa mã nguồn và tài liệu.





**4. Cấu trúc thư mục dự án**



Arduino\_LM35\_TempMonitor/

├── .git/

├── docs/

├── firmware/

│   └── LM35\_TempReader/

│       └── LM35\_TempReader.ino

├── libs/

├── pc\_app/

├── simulation/

├── .gitignore

├── .gitkeep

└── README

**5. Thành viên thực hiện**



* Tô Bích Nguyên (SV A): tạo repository, lập trình thêm kênh A2.


* Đỗ Thị Hồng Như (SV B): Cải tiến giao thức JSON, xử lý xung đột code.

