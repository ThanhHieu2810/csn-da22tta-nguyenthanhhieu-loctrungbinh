# 📋 csn-da22tta-nguyenthanhhieu-loctrungbinh

## 🖼️ Cải thiện chất lượng hình ảnh dựa trên kỹ thuật lọc trung bình

---

## 🔹 Giới thiệu
Dự án này tập trung vào việc cải thiện chất lượng ảnh số bị nhiễu bằng kỹ thuật **lọc trung bình (Mean Filtering)**.  
Mục tiêu chính:
- 🎨 **Loại bỏ nhiễu** Gaussian, Poisson, mã hóa và muối tiêu.
- 🔎 **So sánh hiệu quả của bộ lọc trung bình** với các mặt nạ lọc và các loại nhiễu khác nhau.
- 📊 **Đánh giá kết quả** bằng các chỉ số **PSNR** (Peak Signal-to-Noise Ratio) và **SSIM** (Structural Similarity Index).

---

## 🔹 Công nghệ sử dụng
- 🐖 **Python** - Ngôn ngữ lập trình chính.
- 📸 **OpenCV** - Thư viện xử lý ảnh.
- 💯 **NumPy** - Xử lý ma trận ảnh.
- 📊 **Google Colab** - Chạy thử nghiệm online.

---

## 🚀 Cách chạy chương trình
### **1️⃣ Cài đặt môi trường**
Yêu cầu Python **>=3.8**.  
Cài đặt thư viện bằng lệnh:
```sh
pip install opencv-python numpy matplotlib
```

### **2️⃣ Clone repository về máy**
```sh
git clone https://github.com/nguyenthanhhieu/csn-da22tta-nguyenthanhhieu-loctrungbinh.git
cd csn-da22tta-nguyenthanhhieu-loctrungbinh
```

### **3️⃣ Chạy chương trình**
```sh
python src/main.py
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

## 📊 Kết quả và đánh giá
Kết quả của thuật toán được đánh giá bằng các chỉ số sau:
- **PSNR (Peak Signal-to-Noise Ratio)**: Đo mức độ cải thiện chất lượng ảnh.
- **SSIM (Structural Similarity Index)**: Đánh giá độ tương đồng giữa ảnh gốc và ảnh đã xử lý.

---

## 🔔 Báo cáo tiến độ
📍 Báo cáo tiến độ được cập nhật **hàng tuần** tại thư mục `progress-report/`

🔗 [Xem báo cáo tuần gần nhất](progress-report/tuan1.md)

---

## 📞 Liên hệ
👤 **Nguyễn Thanh Hiếu**  
📞 Email: thhhieu2810@gmail.com  
📚 Trường Đại học Trà Vinh  
