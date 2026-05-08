Câu hỏi 1: Giải thích tại sao dùng thẻ <ul> cho thanh điều hướng lại tốt cho SEO và Screen Reader?. Lý do hiểu bản chất để bảo vệ mã nguồn trước Tech Lead.
Câu hỏi 2: Tại sao bắt buộc phải git checkout main trước khi tạo nhánh mới từ main?. Lý do để tránh tạo nhánh con của nhánh tính năng (Nested branches), giúp sơ đồ Git sạch sẽ.
Câu hỏi 3: Nếu tôi đang làm dở trên nhánh feature mà sếp bắt sửa lỗi gấp trên main, làm sao để 'cất' code đi?. Lý do đọc về lệnh git stash để xử lý tình huống khẩn cấp.
Cho ví dụ về một đoạn mã khi bị Merge Conflict và cách đọc các ký hiệu <<<<<<<?	Chuẩn bị cho việc xử lý xung đột thủ công.

Vấn đáp

Tại sao dùng <ul> bọc trong <nav>?

Trả lời: <nav> xác định đây là vùng điều hướng. <ul> (Danh sách không thứ tự) giúp máy hiểu đây là một danh sách các liên kết đồng cấp. Điều này giúp SEO hiểu rõ cấu trúc trang web và hỗ trợ người khiếm thị biết họ đang đứng ở một danh sách có bao nhiêu mục.

Xử lý Conflict khi hai nhánh cùng sửa một dòng?

Trả lời: Git sẽ đánh dấu vùng xung đột bằng các ký hiệu <<<<<<<, =======, >>>>>>>. Em sẽ rà soát thủ công, chọn giữ lại cả hai phần code Semantic mới nhất hoặc kết hợp chúng lại, sau đó git add và git commit để hoàn tất việc merge.