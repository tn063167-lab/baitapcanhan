# AI Usage Log

## 1. Công cụ AI
ChatGPT.

## 2. Mục đích sử dụng
- Hỗ trợ lập bảng khảo sát website thương mại điện tử.
- Gợi ý một vấn đề giao diện có phạm vi phù hợp với HTML/CSS.
- Hỗ trợ tạo bản nháp HTML5/CSS3 responsive.
- Giải thích cấu trúc mã nguồn và chuẩn bị checklist kiểm thử.

## 3. Prompt đã sử dụng
### Prompt 1 – Phân tích website
“Bạn là chuyên gia phân tích nghiệp vụ và thiết kế trải nghiệm người dùng cho website thương mại điện tử. Hãy phân tích trang chủ, danh mục sản phẩm, chi tiết sản phẩm, tìm kiếm và giỏ hàng của Coolmate. Với mỗi khu vực, nêu mục đích, thành phần giao diện, điểm thuận tiện, vấn đề có thể phát sinh và đề xuất cải tiến. Không khẳng định tính năng chưa được kiểm chứng; phân biệt quan sát với đề xuất.”

### Prompt 2 – Đề xuất giao diện
“Tôi thực hiện bài tập phát triển giao diện website thương mại điện tử bằng HTML5 và CSS3. Tôi muốn cải tiến thẻ sản phẩm cho khách hàng mua sắm trực tuyến tại Việt Nam. Hãy đề xuất bố cục, thành phần HTML, tổ chức CSS, cách hiển thị trên máy tính/điện thoại và các điểm cần kiểm tra về khả năng sử dụng. Trước tiên giải thích phương án thiết kế.”

### Prompt 3 – Tạo mã nguồn
“Dựa trên phương án đã thống nhất, hãy tạo một trang giao diện thương mại điện tử bằng HTML5 và CSS3. Có tiêu đề, ít nhất bốn sản phẩm mẫu; mỗi sản phẩm có hình ảnh, tên, giá và nút thao tác; responsive; HTML rõ ràng; CSS tách riêng; không backend/cơ sở dữ liệu. Giải thích cách chạy và những phần cần kiểm tra.”

## 4. Kết quả AI đề xuất
- Trang có phần tiêu đề, khu vực giới thiệu và danh sách sản phẩm.
- Thẻ sản phẩm có ảnh, nhãn, tên, giá, giá gốc, tỷ lệ giảm giá, kích cỡ và nút thao tác.
- CSS Grid và media query giúp bố cục thích ứng với nhiều kích thước màn hình.

## 5. Kiểm tra và điều chỉnh
- Đối chiếu tên danh mục và ví dụ giá với thông tin được hiển thị trên website Coolmate tại thời điểm khảo sát.
- Ghi rõ giao diện này là bản minh họa, không phải website chính thức.
- Dùng ảnh minh họa từ nguồn bên ngoài; cần kiểm tra ảnh khi chạy và thay ảnh nếu liên kết không hoạt động.
- Kiểm tra giao diện trên Chrome ở kích thước desktop và mobile; điều chỉnh breakpoint, khoảng cách và kích thước chữ.
- Nút “Chọn sản phẩm” chỉ là thành phần giao diện, không có chức năng đặt hàng thật.

## 6. Phần tôi hiểu và có thể giải thích
- `header`, `nav`, `main`, `section`, `article`, `footer`: tổ chức nội dung theo ngữ nghĩa HTML.
- `img` và `alt`: hiển thị hình ảnh và cung cấp mô tả thay thế.
- `class`: gán tên cho nhóm thành phần để định dạng bằng CSS.
- `display: grid` và `grid-template-columns`: chia danh sách sản phẩm thành các cột.
- `@media`: thay đổi bố cục theo độ rộng màn hình.
- `object-fit: cover`: giữ vùng ảnh lấp đầy khung mà không làm méo tỷ lệ.
- `:root` và biến CSS: quản lý màu sắc tập trung.
