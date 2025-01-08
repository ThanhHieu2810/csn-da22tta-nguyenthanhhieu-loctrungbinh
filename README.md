# csn-da22tta-nguyenthanhhieu-loctrungbinh

## Cải thiện chất lượng hình ảnh dựa trên kỹ thuật lọc trung bình

---

## 🔹 Giới thiệu
Dự án này tập trung vào việc cải thiện chất lượng ảnh số bị nhiễu bằng kỹ thuật **lọc trung bình (Mean Filtering)**.  
Mục tiêu chính:
-  **Loại bỏ nhiễu** Gaussian, Poisson, mã hóa và muối tiêu.
-  **So sánh hiệu quả của bộ lọc trung bình** với các mặt nạ lọc và các loại nhiễu khác nhau.
-  **Đánh giá kết quả** bằng các chỉ số **PSNR** (Peak Signal-to-Noise Ratio) và **SSIM** (Structural Similarity Index).

---

## 🔹 Công nghệ sử dụng
-  **Python** - Ngôn ngữ lập trình chính.
-  **Google Colab** - Chạy thử nghiệm online.

---

## 🚀 Cách chạy chương trình trên Google Colab

### **1️⃣ Mở Notebook trên Google Colab**
Nhấp vào link dưới đây để mở notebook trên Google Colab:  
👉 [MỞ NOTEBOOK TRÊN GOOGLE COLAB](https://colab.research.google.com/github/ThanhHieu2810/csn-da22tta-nguyenthanhhieu-loctrungbinh//blob/main/src/CSN_LOCTRUNGBINH.ipynb)

### **2️⃣ Kết nối với GPU (nếu cần)**
1. Vào **Runtime** → **Change runtime type**.
2. Chọn **GPU** để tăng tốc xử lý (không bắt buộc).

### **3️⃣ Cài đặt thư viện (nếu cần)**
Nếu chưa cài đặt thư viện, chạy lệnh sau trong notebook:
```python
!pip install opencv-python numpy matplotlib

```

---

## 📂 Cấu trúc thư mục
```
👤 csn-da22tta-nguyenthanhhieu-loctrungbinh
 ├── 📂 setup               # Cài đặt chương trình, dữ liệu thử nghiệm
 ├── 📂 src                 # Chứa mã nguồn xử lý ảnh
 ├── 📂 progress-report     # Báo cáo tiến độ hàng tuần
 ├── 📂 thesis              # Tài liệu đồ án
 │   ├── 📂 doc            # Tài liệu Word
 │   ├── 📂 pdf            # Tài liệu PDF
 │   ├── 📂 abs            # Slide báo cáo (.ppt), video
 │   ├── 📂 refs           # Tài liệu tham khảo
 ├── README.md              # Mô tả tổng quan về đồ án
 ├── .gitignore             # File bỏ qua khi push lên GitHub
```

---

## Kết quả và đánh giá
Kết quả của thuật toán được đánh giá bằng các chỉ số sau:
- **PSNR (Peak Signal-to-Noise Ratio)**: Đo mức độ cải thiện chất lượng ảnh.
- **SSIM (Structural Similarity Index)**: Đánh giá độ tương đồng giữa ảnh gốc và ảnh đã xử lý.

---

##  Báo cáo tiến độ
 Báo cáo tiến độ được cập nhật **hàng tuần** tại thư mục `progress-report/`

🔗 [Xem báo cáo tuần gần nhất](progress-report/)

---

##  Liên hệ
 **Nguyễn Thanh Hiếu**  
 Email: thhhieu2810@gmail.com  
 Trường Đại học Trà Vinh  
