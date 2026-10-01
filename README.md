# 🏡 House Prices: Exploratory Data Analysis (EDA)

> **Báo cáo:** Lab03 - Phân tích khám phá dữ liệu

> **Môn học:** Máy học (Machine Learning)  

> **Giảng viên hướng dẫn:** Đỗ Như Tài  

---

## 📌 1. Giới thiệu Dự án (Overview)

Dự án thực hiện phân tích khám phá dữ liệu (EDA) và tiền xử lý dữ liệu cho bài toán dự đoán giá nhà dựa trên tập dữ liệu **House Prices - Advanced Regression Techniques** từ Kaggle.

* **Nguồn dữ liệu:** Kaggle Dataset (`train.csv`)
* **Kích thước dữ liệu:** 1,460 dòng, 81 cột
* **Biến mục tiêu (Target Variable):** `SalePrice` (Giá nhà)
* **Phân loại thuộc tính:** 
  * 35 biến định lượng (Numerical Variables)
  * 46 biến định tính (Categorical Variables)

---

## 2. Phân công Nhiệm vụ (Task Assignment)

| STT | Thành viên | MSSV | Chi tiết công việc trong Notebook / Project |
| :-: | :--- | :-: | :--- |
| 1 | **Nguyễn An Nhung** | 3124411203 | • Tổng hợp project, thiết kế & soạn toàn bộ Slide báo cáo (PPT).<br>• Nạp các thư viện cốt lõi (`numpy`, `pandas`, `matplotlib`, `seaborn`, `scipy`) & cấu hình môi trường.<br>• Kiểm tra và nạp dữ liệu thô (`train.csv`), xác nhận kích thước tập dữ liệu (`df_raw.shape`). |
| 2 | **Cao Ngọc Hân** | 3124411083 | • Tổng quan & Chuẩn hóa kiểu dữ liệu.<br>• Chuẩn hóa tên cột, ép kiểu dữ liệu cho các biến rời rạc (`MSSubClass`, `MoSold`, `YrSold`).<br>• Phân loại biến định lượng (35 biến) & biến định tính (46 biến).<br>• Tính thống kê 5 số (`describe().T`) cho các biến diện tích & giá trị cốt lõi.<br>• Lập bảng thống kê tần số cho biến `MSSubClass`. |
| 3 | **Trần Đỗ Khánh Linh** | 3124411151 | • Phân tích biến mục tiêu & Biến đổi phân phối.<br>• Trực quan hóa & so sánh phân phối giữa `SalePrice` gốc và `LogSalePrice`.<br>• Tính toán độ lệch (Skewness) và độ nhọn (Kurtosis).<br>• Vẽ đồ thị phân phối (Histogram) và QQ-Plot để đánh giá tính chuẩn của biến mục tiêu. |
---

## 🛠️ 3. Công nghệ & Thư viện Sử dụng (Tech Stack)

* **Ngôn ngữ:** Python 3.x
* **Môi trường phát triển:** Jupyter Notebook / Google Colab
* **Thư viện chính:**
  * `pandas`, `numpy`: Thao tác và xử lý dữ liệu cấu trúc.
  * `matplotlib`, `seaborn`: Trực quan hóa dữ liệu và biểu đồ thống kê.
  * `scipy`: Kiểm định và tính toán các chỉ số thống kê (Skewness, Kurtosis, QQ-Plot).
