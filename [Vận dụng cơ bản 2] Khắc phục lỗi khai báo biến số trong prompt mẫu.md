# 1.Khắc phục lỗi khai báo biến số trong prompt mẫu 


### **Bước 1: Phân tích lỗi**

Em nhận thấy prompt sử dụng hai cách khai báo biến khác nhau là `[language]` và `[audience]`. Điều này khiến AI khó nhận diện và thay thế biến , gây khó khăn khi tự động hóa prompt cho nhiều người

### **Bước 2: Đồng bộ biến số**

Em sửa lại prompt bằng cách đưa tất cả biến về dạng `[Tên_Biến]` và viết hoa rõ ràng

**Prompt sau khi sửa:**

Hãy viết một bài chia sẻ về Kỹ thuật Prompting Nâng cao (Logic Chuỗi) bằng ngôn ngữ [Ngôn_Ngữ]. Bài viết dành cho đối tượng [Đối_Tượng]. Sử dụng cách diễn đạt dễ hiểu, nội dung đầy đủ và phù hợp với người đọc

### **Bước 3: Kết quả chạy thử**

**Dữ liệu điền vào biến:**

-   (Ngôn Ngữ) : Tiếng Việt
    
-   (Đối Tượng) : Sinh viên năm nhất ngành Công nghệ Thông tin
    

**Kết quả chạy thử:**

Kỹ thuật Prompting Nâng cao (Logic Chuỗi) giúp người dùng tạo câu lệnh AI hiệu quả hơn

-   **Logic:** Giúp AI phân tích yêu cầu theo trình tự, suy luận và đưa ra câu trả lời hợp lý
    
-   **Chuỗi (Prompt Chaining):** Chia một nhiệm vụ lớn thành nhiều bước nhỏ, sử dụng kết quả của bước trước làm đầu vào cho bước tiếp theo
    

 Em nhận xét như sau : hai kỹ thuật này giúp sinh viên sử dụng AI hiệu quả hơn, giảm sai sót và nâng cao chất lượng trong học tập
