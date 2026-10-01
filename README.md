# **ĐỀ TÀI:** PHÂN TÍCH KHÁM PHÁ DỮ LIỆU (HOUSE PRICES ADVANCED REGRESSION)  

# Phân công 

> **Phân công:**

> 💻 **Code:** Tất cả thành viên cùng tham gia

> 📝 **Báo cáo:** Thành viên 1 & Thành viên 2

> 🎨 **Slide & Thuyết trình:** Thành viên 3

---

## Bảng phân công chi tiết công việc

| Thành viên | Nhiệm vụ chính | Chi tiết công việc | Sản phẩm bàn giao |
| :--- | :--- | :--- | :--- |
| **Cao Ngọc Hân** | **Code Part 1**<br>+ **Báo cáo Part 1** | • **Code:** Khởi tạo môi trường, nạp dữ liệu, kiểm tra tổng quan & ép kiểu biến (`MSSubClass`, `MoSold`,...)[cite: 1].<br>• **Báo cáo:** Soạn Mở đầu, Tổng quan đề tài, Mô tả bộ dữ liệu Ames Housing & Lý thuyết phân loại biến[cite: 1]. | • Đoạn code Part 1 chạy chuẩn.<br>• Nửa đầu bài Báo cáo (Word). |
| **Trần Đỗ Khánh Linh** | **Code Part 2**<br>+ **Báo cáo Part 2** | • **Code:** Xử lý biến mục tiêu `SalePrice`, tính thống kê mô tả (Mean, Std, Min, Max...) & biến đổi Logarithm[cite: 1].<br>• **Báo cáo:** Viết nhận xét chuyên sâu phần thống kê, giải thích lý do cần Log-transform & tổng hợp toàn bộ bài Báo cáo[cite: 1]. | • Đoạn code Part 2 chạy chuẩn.<br>• Nửa sau bài Báo cáo + File Word hoàn chỉnh. |
| **Nguyễn An Nhung** | **Code Part 3**<br>+ **Slide & Presentation** | • **Code:** Phân loại biến Định tính / Định lượng, xuất toàn bộ bảng số liệu & hình biểu đồ (`.png`) cho nhóm[cite: 1].<br>• **Slide:** Thiết kế PowerPoint, tóm tắt ý chính từ Báo cáo, chèn biểu đồ/bảng số liệu & chuẩn bị kịch bản thuyết trình[cite: 1]. | • Đoạn code Part 3 + Folder biểu đồ.<br>• File Slide (`.pptx`) + Kịch bản nói. |

---

## 🛠️ Chi tiết phần công việc code 

- **Cao Ngọc Hân (Tiền xử lý cơ bản):** Nạp thư viện, đọc `train.csv`, kiểm tra `shape`, `info()`, đổi tên cột và ép kiểu các biến số nguyên sang dạng chuỗi[cite: 1].
- **Trần Đỗ Khánh Linh (Phân tích biến mục tiêu):** Lấy danh sách biến định lượng/định tính, vẽ biểu đồ phân phối `SalePrice`, tính các chỉ số thống kê & lấy Logarithm `LogSalePrice`[cite: 1].
- **Nguyễn An Nhung (Trực quan hóa & Xuất File):** Lọc danh sách biến định tính/định lượng còn lại, vẽ biểu đồ đối chiếu và export toàn bộ file `.png` cho cả nhóm làm Slide & Báo cáo[cite: 1].

---

## 🔄 Quy trình phối hợp

1. **Bước 1 (Ghép Code):** Cả 3 người làm xong phần code của mình -> Ráp lại thành 1 file Jupyter Notebook hoàn chỉnh.
2. **Bước 2 (Xuất dữ liệu):** Thành viên 3 xuất toàn bộ biểu đồ & bảng kết quả gửi vào nhóm[cite: 1].
3. **Bước 3 (Báo cáo & Slide):** 
   - Thành viên 1 & 2 chia nhau viết Báo cáo Word.
   - Thành viên 3 hốt Báo cáo + Biểu đồ đưa lên Slide PowerPoint[cite: 1].
4. **Bước 4 (Dò lại bài):** Cả nhóm họp kiểm tra khớp số liệu giữa **Code - Báo cáo - Slide** trước khi nộp.
