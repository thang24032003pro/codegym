Giảng viên :Tại sao phải commit code cũ vào main trước?
Học sinh: Để tạo một "điểm xuất phát" (Base). Nếu không có commit đầu tiên, Git sẽ không biết nhánh feature được rẽ ra từ đâu, và chúng ta không thể so sánh sự khác biệt giữa cái cũ và cái mới.

Giảng viên :Dùng <ol> làm menu được không?
Học sinh: Được về mặt kỹ thuật, nhưng sai về mặt ngữ nghĩa. <ol> dùng cho danh sách có thứ tự (như các bước nấu ăn). Menu trang web thì các mục như "Trang chủ" hay "Khách sạn" có vai trò ngang hàng, không cần đánh số thứ tự, nên dùng <ul> là chuẩn nhất.

Giảng viên :Khi checkout sang nhánh khác, file trên máy tính thay đổi thế nào?
Học sinh: Git sẽ thay đổi nội dung của file vật lý trên ổ cứng để khớp với phiên bản (snapshot) của nhánh đó. Khi em từ nhánh feature quay về main, các thẻ <ul> em vừa viết sẽ biến mất và thay bằng đoạn code cũ cho đến khi em thực hiện lệnh merge.