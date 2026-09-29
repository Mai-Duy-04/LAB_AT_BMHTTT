Họ Và Tên: Mai Nguyễn Trường Duy 
Mã Số Sinh Viên: 1150070006 
Lớp: 11_ĐH_TMĐT 
Tên bài LAB: LAB_4 
Nội Dung Đã Thực Hiện: Đã cấu hình mạng Host-Only giữa Kali Linux và Windows Server 2025, kiểm tra địa chỉ IP và kết nối giữa hai máy. Sau đó cài đặt Nmap và thực hiện các kiểu quét gồm Host Discovery, TCP Connect, SYN, FIN, Xmas, NULL, ACK, UDP, nhận diện dịch vụ, hệ điều hành và kiểm tra SMB bằng NSE. Ngoài ra đã lưu kết quả quét dưới dạng TXT, XML và grepable, đồng thời cài công cụ để chuyển XML sang HTML.
Kết Quả Thực Hiện: Hai máy đã kết nối được trong cùng mạng Host-Only và Nmap phát hiện được 3 host đang hoạt động. Windows Server có cổng 5985/tcp mở, Nmap nhận diện dịch vụ Microsoft HTTPAPI và hệ điều hành thuộc họ Windows. Cổng SMB 445/tcp ở trạng thái filtered, các script SMB chưa đủ thông tin để kết luận về lỗ hổng. Các kết quả quét cũng đã được lưu thành các file để làm bằng chứng cho báo cáo.
