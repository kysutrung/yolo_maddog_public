![Photo01](https://github.com/kysutrung/yolo_maddog_public/blob/main/media_00/repo_cover_yolo_maddog.png)

# YOLO MadDog

[Click here for English](https://www.youtube.com/shorts/F-JnS-b4YgA)

Hệ thống phần mềm và mô hình điều khiển tự hành đa nhiệm cho drone nền ArduPilot

Keyword: automation, computer vision, rescue drone, kamikaze drone.

## 📑 Mô Tả Dự Án

Hệ thống là một nền tảng phần mềm kết hợp với mô hình điều khiển tự hành, được phát triển nhằm mở rộng năng lực cho các drone sử dụng [ArduPilot](https://github.com/ArduPilot) - một trong những nền tảng drone được sử dụng phổ biến nhất hiện nay. 

Giải pháp cho phép chuyển đổi nhiều cấu hình drone khác nhau thành phương tiện bay tự động có khả năng thực hiện nhiệm vụ theo kịch bản được thiết lập trước hoặc được điều phối theo thời gian thực. Hệ thống hỗ trợ quản lý nhiệm vụ, điều hướng tự động, phối hợp tác vụ và thích ứng với nhiều mục đích sử dụng như cứu trợ, giám sát, hậu cần hoặc các nhiệm vụ chuyên biệt khác. Với kiến trúc linh hoạt và khả năng tích hợp cao, giải pháp góp phần nâng cao mức độ tự động hóa, tính sẵn sàng triển khai và hiệu quả vận hành của drone trong môi trường thực tế.

![Photo02](https://github.com/kysutrung/yolo_maddog_public/blob/main/media_00/quy_dao_01.png)

## 💻 Danh Sách Các Chức Năng Của Hệ Thống

__Phần Mềm Điều Khiển__
__Điều Khiển Tự Động__
- [x] Theo dấu giữ khoảng cách với mục tiêu
- [x] Tiếp cận mục tiêu và dừng lại khoảng cách an toàn
- [x] Tiếp cận mục tiêu và hạ cánh ở khoảng cách an toàn
- [x] Tương tác vật lý với mục tiêu (Chỉ có ở bản dành cho nhà phát triển)
- [x] Tự động thả hàng khi đã tiếp cận mục tiêu

__Xử Lý Hình Ảnh__
- [x] Phát hiện và phân loại các đối tượng vật thể trong khung hình
- [x] Gán ID cho từng đối tượng
- [x] Cơ chế chống mất ID của đối tượng
- [x] Cơ chế chọn và khóa mục tiêu theo dõi
- [x] Khi bị mất dấu, ra lệnh tự động tìm khóa mục tiêu lại

__Cơ Cấu Điều Hướng Bay__
- [x] Nhận tín hiệu tay cầm điều khiển vật lý
- [x] Điều khiển drone ngay cả khi không có tay cầm vật lý
- [x] Cơ chế đồng bộ tín hiệu điều khiển an toàn cho tay cầm vật lý
- [x] Cơ chế phanh khẩn cấp tránh đâm vào người
- [x] Cơ chế chống bấm nhầm nút
- [x] Cơ chế thả hàng thủ công

__Cơ Cấu Giám Sát Chuyến Bay__
- [x] Theo dõi thông số điều hướng realtime
- [x] Theo dõi log hệ thống

__Mô Hình Thiết Lập Phần Cứng__
- [x] Tương thích với các drone cơ bản không yêu cầu máy tính nhúng riêng biệt
- [x] Nhận lệnh điều khiển từ trạm mặt đất
- [x] Truyền trạng thái drone về trạm mặt đất


## 📥 Yêu Cầu Hệ Thống

- Fligh Controller chạy firmware Ardupilot
- Máy tính chạy hệ điều hành Windows có GPU Nvidia
- Telemetry USB
- Tay cầm chơi game hoặc tay cầm điều khiển drone chuyên dụng
- Bộ chuyển đổi VRX sang HDMI

## 📥 Installation Guide

__Source code của dự án có trong repo này__


## 📞 Support

__Liên Hệ Trực Tiếp Để Được Hỗ Trợ Cài Đặt !!!__