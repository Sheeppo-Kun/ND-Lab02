

# NDLab02 – Advanced OSPF Redundant WAN

## Giới thiệu
Thiết kế và mô phỏng hệ thống mạng có khả năng dự phòng bằng Cisco Packet Tracer 9.0.1.

## Mô hình mạng
- 4 Router, 4 Switch, 10 PC.
- 4 mạng LAN và 5 kết nối WAN.
- Sử dụng OSPF Area 0.
- Các subnet sử dụng địa chỉ `/24`.

## Kiểm thử
- Kiểm tra kết nối bằng `ping` và `tracert`.
- Kiểm tra láng giềng và bảng định tuyến OSPF.
- Ngắt WAN5 để kiểm tra khả năng chuyển sang đường dự phòng.
- Khôi phục WAN5 và kiểm tra lại kết nối.

## File nộp
- `Lab02.pkt`: File mô phỏng mạng Cisco Packet Tracer.

