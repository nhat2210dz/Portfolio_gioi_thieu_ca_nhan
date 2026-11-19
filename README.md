
 TÀI LIỆU BÀN GIAO DỰ ÁN: PORTFOLIO CÁ NHÂN PHONG CÁCH TẾT

Tài liệu này cung cấp đầy đủ thông tin kỹ thuật, cấu trúc mã nguồn, hướng dẫn vận hành và các đầu việc cần tiếp tục triển khai dành cho người tiếp nhận dự án.

 1. Thông Tin Chung Về Dự Án

• Tên dự án: Website Portfolio Giới thiệu Bản thân - Chủ đề Khai Xuân Đinh Mùi 2027.
• Ngữ cảnh thực hiện: Bài tập lớn A3 - Học phần Thiết kế Web và Triển khai Hệ thống Phần mềm (FIT4014), Trường Đại học Đại Nam.
• Người bàn giao: Nguyễn Việt Nhật 
• Người tiếp nhận: [Họ tên người tiếp nhận / Thành viên nhóm]
• Trạng thái hiện tại: Đã hoàn thiện giao diện tĩnh (HTML5/CSS3), hiệu ứng chuyển động, tính năng tương tác cơ bản (JS) và tương thích đa thiết bị (Responsive).
• Liên kết Kho mã nguồn (GitHub): https://github.com/nhat2210dz/Portfolio_gioi_thieu_ca_nhan.git
• Liên kết Bản chạy thử (Live Demo): https://nhat2210dz.github.io/Portfolio_gioi_thieu_ca_nhan/

 2. Kiến Trúc Mã Nguồn & Cấu Trúc Thư Mục

Dự án được xây dựng theo kiến trúc tách biệt hoàn toàn giữa nội dung (HTML) và định dạng (CSS), không phụ thuộc vào các framework bên ngoài để người tiếp nhận dễ dàng đọc hiểu và bảo trì:
text
Hãy thận trọng khi sử dụng mã.
BaiTapLon_A3/
│
├── index.html          # [Tệp chính] Chứa toàn bộ khung nội dung, bố cục các phần và script hái lộc
├── style.css           # [Tệp giao diện] Chứa hệ thống biến màu, hiệu ứng hoa rơi, layout & responsive
├── README.md           # [Tài liệu] Hướng dẫn bàn giao kỹ thuật (tệp hiện tại)
└── AI_LOG.md           # [Tài liệu] Nhật ký ghi chép quá trình sử dụng công cụ hỗ trợ (nếu cần nộp)

 3. Hướng Dẫn Thiết Lập & Chỉnh Sửa Nhanh (Dành cho người tiếp nhận)


Bước 1: Tải mã nguồn về máy

Mở Terminal hoặc Git Bash và chạy lệnh sau để lấy phiên bản mới nhất:
bash
Hãy thận trọng khi sử dụng mã.
git clone https://github.com/[username]/[ten-repo].git
cd [ten-repo]

Bước 2: Môi trường phát triển

• Mở thư mục bằng Visual Studio Code.
• Khuyến nghị cài đặt tiện ích mở rộng Live Server để xem trực tiếp các thay đổi giao diện theo thời gian thực khi lưu tệp (Ctrl + S).

Bước 3: Bản đồ các vị trí cần tùy chỉnh trong mã nguồn

Nếu bạn cần cập nhật nội dung hoặc thay đổi giao diện, hãy tìm đúng các khu vực đã được đánh dấu chú thích sẵn trong tệp:
1. Thay đổi thông tin cá nhân & nội dung (index.html):
	• Tìm thẻ <header> (dòng 26–35): Thay đổi tiêu đề chính và câu đối Tết.
	• Tìm thẻ <section id="tong-quan"> (dòng 40–68): Cập nhật Họ tên, Mã sinh viên, Lớp và Email.
	• Tìm thẻ <section id="ky-nang"> (dòng 89–114): Điều chỉnh tên kỹ năng và thuộc tính style="width: XX%;" của thanh .progress-fill để thay đổi phần trăm năng lực.
	• Tìm thẻ <script> ở cuối tệp (dòng 150–168): Chỉnh sửa mảng const wishes = [...] để thêm hoặc bớt các câu chúc Tết ngẫu nhiên.
2. Thay đổi màu sắc chủ đạo & hiệu ứng (style.css):
	• Tìm khối :root (dòng 6–15): Toàn bộ bảng màu Tết (--red-tet, --gold-tet, --green-tet, --bg-creamy) được khai báo tập trung tại đây. Chỉ cần đổi mã màu tại :root, toàn bộ trang web sẽ tự động cập nhật đồng bộ.
	• Tìm khối /* HIỆU ỨNG HOA RƠI */ (dòng 31–68): Điều chỉnh animation-duration tại các lớp .petal:nth-child(n) nếu muốn hoa rơi nhanh hoặc chậm hơn.
	• Tìm khối /* ĐÁP ỨNG DI ĐỘNG */ (dòng 350–392): Chứa các quy tắc @media (max-width: 768px) xử lý giao diện trên điện thoại.

 4. Danh Sách Công Việc Tồn Đọng & Đề Xuất Phát Triển Tiếp

Người tiếp nhận có thể tiếp tục hoàn thiện các hạng mục sau trước khi chốt phiên bản bàn giao cuối cùng:
• [ ] Thay thế dữ liệu mẫu: Điền đầy đủ thông tin thật của sinh viên vào các trường đang để trống/giả định trong index.html.
• [ ] Nâng cấp ảnh đại diện: Thay thế biểu tượng cảm xúc trong lớp .avatar-emoticon bằng thẻ <img> trỏ tới ảnh chân dung thật (khuyến nghị ảnh vuông tỉ lệ 1:1, dung lượng dưới 500KB).
• [ ] Kiểm thử chéo trình duyệt (Cross-browser Testing): Kiểm tra lại độ mượt của hiệu ứng @keyframes fall trên trình duyệt Safari (iOS) và Firefox.
• [ ] Cập nhật phiên bản triển khai: Sau khi chỉnh sửa xong, cần commit lên nhánh main và kiểm tra lại đường dẫn GitHub Pages để đảm bảo bản chạy trực tuyến khớp với mã nguồn mới nhất.

 5. Lưu Ý Kỹ Thuật Quan Trọng

• Đường dẫn tương đối: Tuyệt đối giữ tệp index.html và style.css nằm cùng một cấp thư mục gốc, nếu di chuyển style.css vào thư mục con (ví dụ css/style.css), bắt buộc phải cập nhật lại thẻ <link rel="stylesheet" href="..."> ở dòng 9 của tệp index.html.
• Quy chuẩn bàn giao: Mọi thay đổi lớn về giao diện cần được chụp ảnh màn hình trước/sau để bổ sung vào phần minh chứng kiểm thử trong báo cáo kỹ thuật.

 6. Khai Báo Nguồn & Bản Quyền (Đáp ứng TC7)

• Tài nguyên hình ảnh/biểu tượng: Sử dụng bộ ký tự Unicode Emoji tiêu chuẩn, không vi phạm bản quyền hình ảnh bên thứ ba.
• Công cụ hỗ trợ: Dự án có tham khảo cấu trúc gợi ý mã nguồn từ công cụ AI tạo sinh; toàn bộ nội dung cá nhân, kiểm thử thực tế, chỉnh sửa giao diện và triển khai lên GitHub Pages đều do sinh viên trực tiếp thực hiện và chịu trách nhiệm. Chi tiết các câu lệnh được lưu đầy đủ trong tệp AI_LOG.md.
