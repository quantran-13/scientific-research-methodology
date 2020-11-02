# COMPUTATIONAL THINKING (TƯ DUY MÁY TÍNH)

Nhóm: N005

- 16521206 - Phạm Ngọc Phúc Thuần
- 17520943 - Trần Nguyễn Hồng Quân
- 17520964 - Nguyễn Đình Quyết

---

**Computational thinking** là một trong những kỹ năng cần thiết cho công việc và đời sống của con người. Thuật ngữ “Computational Thinking” được đề cập lần đầu tiên trong quyển sách MINDSTORMS (xuất bản năm 1980) nói về ngôn ngữ lập trình LOGO của Nhà khoa học Seymour Papert. Sau đó, thuật ngữ này được phát triển chính thức bởi Giáo sư Jeannette Marie Wing trong bài báo khoa học “Computational Thinking” vào năm 2006. Computational thinking hay tư duy máy tính là các quá trình tư duy bao gồm việc phân tích và đưa ra phương pháp giải quyết vấn đề, phương pháp phải được diễn đạt theo cách mà một máy tính cũng có thể thực hiện được. Đây là kỹ năng cần thiết cho tất cả mọi người, không chỉ cho những người hoạt động trong lĩnh vực máy tính.

Computational thinking được chia thành 4 yếu tố:

- Decomposition: chia vấn đề phức tạp thành những vấn đề nhỏ, dế hiểu và có thể giải quyết được.
- Pattern recognition: tìm sự tương đồng hoặc mối liên hệ giữa các vấn đề, hoặc mối liên hệ giữa vấn đề nhỏ với các vấn đề đã giải quyết trước đó.
- Abstraction: loại bỏ các chi tiết không cần thiết và chỉ tập trung vào giải quyết vấn đề chính.
- Algorithmic thinking: tạo ra tập hợp các bước hợp lý để chỉ dẫn cách giải quyết vấn đề. Các bước này có thể được thực hiện bởi con người, máy tính hoặc sự kết hợp giữa con người và máy tính.

Việc vận dụng tư duy máy tính trong giải quyết vấn đề giúp con người phát triển khả năng nhận thức tình huống và giải quyết vấn đề theo hướng tối ưu.

Ví dụ: Ứng dụng tư duy máy tính trong giải quyết bài toán phát hiện đối tượng trên ảnh.

Bài toán này được chia thành hai bài toán con là xác định vị trí của đối tượng và xác định đối tượng thuộc lớp nào.
Đầu tiên ta xác định các phần có thể có đối tượng trong hình bằng phương pháp Selective search. Sau đó lấy từng phần đã xác định và phân lớp cho đối tượng có trong nó. Việc phân lớp có thể thực hiện như sau:

- Rút trích các đặc trưng từ phần có đối tượng và chuyển thành dạng vector.
- Đưa vector đã rút trích được qua các thuật toán phân lớp như Support vector machine để phân lớp cho đối tượng có trong ảnh.
