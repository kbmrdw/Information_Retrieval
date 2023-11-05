# Information_Retrieval
## Tên đề tài: Tìm hiểu và cài đặt mô hình Vector Space (VSM) và Latent Semantic Indexing (LSI)
## File báo cáo: [Report](VectorSpace_LSI.pdf)
## Tổng quan:
### Dataset: 
***Nhóm sử dụng 2 tập dữ liệu văn bản [Cranfield](Cranfield.zip) và [NFCorpus](NFCorpus.zip)***
### Mô hình truy vấn thông tin:
- **Mô hình Vector Space:** mỗi văn bản được biểu diễn thành một vector trong không gian đa chiều, mỗi chiều tương ứng với một thuộc tính hoặc từ trong văn bản. Tuy nhiên, VSM có hạn chế lớn khi phải xử lý các văn bản dài.
- **Mô hình LSI:** LSI khắc phục nhược điểm của VSM bằng cách sử dụng phương pháp SVD (Singular Value Decomposition) để giảm chiều dữ liệu và tìm ra những khái niệm ẩn trong văn bản. Kết quả của LSI là một không gian vector mới có số chiều thấp hơn so với vector space, trong đó các vector biểu diễn văn bản dựa trên các khái niệm ẩn thay vì các thuộc tính cụ thể.
### Thực nghiệm: 
- Folder: [Code](Code)




