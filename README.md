![Photo01](https://github.com/kysutrung/yolo_maddog_public/blob/main/media_00/repo_cover_yolo_maddog.png)

# YOLO MadDog

[Click here for English](https://www.youtube.com/shorts/F-JnS-b4YgA)

Hệ thống phần mềm và mô hình điều khiển tự hành đa nhiệm cho drone nền ArduPilot

Keyword: automation, computer vision, rescue drone, kamikaze drone.

## 📑 Mô Tả Dự Án

Hệ thống là một nền tảng phần mềm kết hợp với mô hình điều khiển tự hành, được phát triển nhằm mở rộng năng lực cho các drone sử dụng [ArduPilot](https://github.com/ArduPilot). Giải pháp cho phép chuyển đổi nhiều cấu hình drone khác nhau thành phương tiện bay tự động có khả năng thực hiện nhiệm vụ theo kịch bản được thiết lập trước hoặc được điều phối theo thời gian thực. Hệ thống hỗ trợ quản lý nhiệm vụ, điều hướng tự động, phối hợp tác vụ và thích ứng với nhiều mục đích sử dụng như cứu trợ, giám sát, hậu cần hoặc các nhiệm vụ chuyên biệt khác. Với kiến trúc linh hoạt và khả năng tích hợp cao, giải pháp góp phần nâng cao mức độ tự động hóa, tính sẵn sàng triển khai và hiệu quả vận hành của drone trong môi trường thực tế.

## 💻 Danh Sách Các Chức Năng Của Hệ Thống

__Bộ Phận Phân Tích Hình Ảnh__
- [x] Phát hiện vật thể với mô hình học máy YOLO tự huấn luyện
- [x] Gửi cảnh báo đến thiết bị nhận cảnh báo từ xe thông qua sóng ESP-NOW

__Bộ Phận Cảnh Báo Từ Xa__
- [x] Nhận cảnh báo qua sóng ESP-NOW
- [x] Cảnh báo dựa trên thông điệp nhận được kết hợp cài đặt trường hợp cảnh báo
- [ ] Giao diện người dùng đẹp sử dụng SquareLine Studio
- [ ] Lưu lịch sử cảnh báo
- [ ] Có cổng kết nối thiết bị ngoại vi
- [x] Báo mất kết nối với trung tâm điều khiển

__Bộ Phận Theo Dõi Tự Động__
- [x] Tự động xoay camera theo đối tượng vi phạm phát hiện được

__Ứng Dụng Điều Khiển Window__
- [x] Whole system work right in Windows OS
- [x] Control UI
- [x] Display realtime video
- [x] Select prohibited objects in each area
- [ ] Running with every PC



## 📥 Installation Guide



## 👏 References

[Ultralytics](https://github.com/ultralytics/ultralytics) - YOLO


## 📞 Support
If you have any questions or suggestions, feel free!!!
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.