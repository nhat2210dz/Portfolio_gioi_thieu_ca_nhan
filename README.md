
 PORTFOLIO SINH VIÊN NĂM NHẤT CNTT - CHÀO XUÂN ĐINH MÙI 2027

Dự án website tĩnh giới thiệu bản thân (Personal Portfolio) được thiết kế theo phong cách Tết cổ truyền Việt Nam. Sản phẩm thuộc Bài tập lớn A3 của học phần FIT4014 - Thiết kế Web và Triển khai Hệ thống Phần mềm, Khoa Công nghệ Thông tin, Trường Đại học Đại Nam.

 1. Thông Tin Sinh Viên & Học Phần

• Họ và tên sinh viên: Nguyễn Việt Nhật 
• Mã số sinh viên: 2071020147
• Lớp / Ngành: CNTT K21 - Công nghệ Thông tin
• Giảng viên hướng dẫn: ThS. Lê Thái Bảo
• Liên kết Repository:https://github.com/nhat2210dz/Portfolio_gioi_thieu_ca_nhan.git
• Liên kết Website (GitHub Pages): https://nhat2210dz.github.io/Portfolio_gioi_thieu_ca_nhan/

 2. Mục Tiêu & Phạm Vi Dự Án (Đáp ứng TC1)

• Đối tượng người xem: Giảng viên chấm bài, bạn bè cùng lớp và nhà tuyển dụng thực tập sinh IT.
• Mục tiêu: Trình bày thông tin cá nhân, lộ trình học tập năm nhất và năng lực lập trình cơ bản thông qua giao diện web sinh động, mang không khí tích cực ngày Tết.
• Phạm vi kỹ thuật: Website tĩnh thuần túy sử dụng HTML5 ngữ nghĩa và CSS3 (tích hợp kỹ thuật Flexbox, CSS Grid, CSS Animations và Media Queries cho giao diện Responsive), kết hợp một hàm JavaScript cơ bản cho tính năng tương tác "Hái lộc đầu năm". Không sử dụng thư viện CSS/JS bên ngoài để đảm bảo tốc độ tải trang tối đa.

 3. Cấu Trúc Thư Mục Dự Án (Đáp ứng TC2b)

Toàn bộ mã nguồn được tổ chức gọn gàng, tách biệt hoàn toàn giữa cấu trúc nội dung và định dạng giao diện:
text
Hãy thận trọng khi sử dụng mã.
BaiTapLon_A3/
│
├── index.html          # Tệp cấu trúc nội dung chính (HTML5 Semantics) & logic hái lộc
├── style.css           # Tệp định dạng giao diện, màu sắc Tết, hiệu ứng hoa rơi & Responsive
├── README.md           # Tài liệu hướng dẫn sử dụng, triển khai và bàn giao dự án
└── AI_LOG.md           # Nhật ký khai báo quá trình sử dụng công cụ AI hỗ trợ (nếu có)

 4. Hướng Dẫn Cài Đặt & Chạy Dự Án (Đáp ứng TC3 & TC5)


Cách 1: Chạy trực tiếp trên máy tính cá nhân (Local)

1. Tải toàn bộ thư mục dự án về máy tính hoặc clone qua Git:
bash
Hãy thận trọng khi sử dụng mã.
   git clone https://github.com/[username]/[ten-repo].git
1. Mở thư mục dự án bằng phần mềm Visual Studio Code.
2. Đảm bảo tệp index.html và style.css nằm cùng một cấp thư mục.
3. Nhấp chuột phải vào tệp index.html chọn Open with Live Server (hoặc nhấp đúp chuột để mở trực tiếp bằng trình duyệt Chrome, Edge, Safari).

Cách 2: Truy cập trực tuyến

Truy cập trực tiếp vào đường dẫn GitHub Pages đã được triển khai công khai ở Mục 1 trên cả máy tính và điện thoại di động để kiểm tra tính năng tương thích màn hình (Responsive).

 5. Kết Quả Kiểm Thử & Giới Hạn Đã Biết (Đáp ứng TC4)

• Trạng thái hiển thị: Đã kiểm thử thành công trên màn hình Desktop (1920x1080) và chế độ giả lập điện thoại di động (375x812 - iPhone 11/12/13). Thanh điều hướng tự động xếp dọc và bảng thông tin tự động căn giữa trên màn hình hẹp.
• Giới hạn hiện tại:
	• Hiệu ứng hoa mai/đào rơi sử dụng biểu tượng cảm xúc (Emoji) hệ thống nên hình dạng biểu tượng có thể hiển thị hơi khác nhau giữa hệ điều hành Windows và macOS/iOS.
	• Website là trang tĩnh (Static Web) nên dữ liệu lời chúc hiện đang được lưu cố định trong mảng JavaScript thay vì kết nối cơ sở dữ liệu.

 6. Khai Báo Nguồn & Bản Quyền (Đáp ứng TC7)

• Tài nguyên hình ảnh/biểu tượng: Sử dụng bộ ký tự Unicode Emoji tiêu chuẩn, không vi phạm bản quyền hình ảnh bên thứ ba.
• Công cụ hỗ trợ: Dự án có tham khảo cấu trúc gợi ý mã nguồn từ công cụ AI tạo sinh; toàn bộ nội dung cá nhân, kiểm thử thực tế, chỉnh sửa giao diện và triển khai lên GitHub Pages đều do sinh viên trực tiếp thực hiện và chịu trách nhiệm. Chi tiết các câu lệnh được lưu đầy đủ trong tệp AI_LOG.md.
