Dự Án: Ứng Dụng Của Hàm Số Mũ Trong Vấn Đề Tài Chính

## 📖 1. Giới Thiệu & Lý Do Chọn Đề Tài

### 1.1. Giới thiệu chung
Dự án **"Ứng dụng của hàm số mũ trong vấn đề tài chính"** là một nghiên cứu hệ thống nhằm kết nối kiến thức toán học thuần túy (hàm số mũ) với các bài toán kinh tế - tài chính thực tế, giúp cấu trúc lại tư duy tài chính cá nhân và quản trị rủi ro một cách khoa học. Dự án giải thích cơ chế vận hành của dòng tiền, tốc độ tăng trưởng tài sản cũng như sự suy giảm giá trị tiền tệ theo thời gian. 

---

### 1.2. Lý do chọn đề tài
* **Khoảng cách giữa lý thuyết và thực tiễn:** Trong chương trình phổ thông, hàm số mũ thường được tiếp cận qua các công thức và phương trình khô khan, khiến người học khó hình dung tính ứng dụng thực tế.
* **Tầm quan trọng của tư duy tài chính:** Các hiện tượng như *lãi kép*, *lạm phát*, hay *khấu hao tài sản* đều vận hành dựa trên bản chất của hàm số mũ. Việc không hiểu rõ mô hình này có thể dẫn đến các quyết định đầu tư sai lầm hoặc rơi vào bẫy nợ nần.
* **Lợi ích lâu dài :** Hiểu được sự tăng trưởng theo cấp số nhân giúp cá nhân và tổ chức lập kế hoạch tích lũy, đầu tư và quản trị rủi ro một cách khoa học.

---

### 1.3. Mục tiêu dự án
* Hệ thống hóa cơ sở toán học của hàm số mũ liên quan đến các mô hình kinh tế.
* Ứng dụng toán học để giải quyết 3 bài toán lớn: **Tích lũy tài sản (Lãi kép)**, **Suy giảm tài sản (Lạm phát/Khấu hao)**, và **Định giá dòng tiền**.
* Trực quan hóa dữ liệu bằng biểu đồ để so sánh sự khác biệt giữa tăng trưởng tuyến tính và tăng trưởng hàm mũ.

---
## 🗂 2. Cấu trúc nội dung dự án
Dự án được kết cấu thành **4 phần chính** logic từ lý thuyết đến thực tiễn:

* **Phần I: Cơ sở toán học của hàm số mũ:** Định nghĩa hàm số \(y = a^x\), tính chất biến thiên, đạo hàm tốc độ tăng trưởng tức thời (\(e^x\)), so sánh tăng trưởng tuyến tính và tăng trưởng mũ.
* * **Phần II: Bài toán tăng trưởng tài sản (tích lũy):** Công thức lãi kép rời rạc định kỳ, mô hình lãi kép liên tục (\(A = P \cdot e^{rt}\)), tính Giá trị tương lai (FV) của dòng tiền đầu tư.
* **Phần III: Bài toán suy giảm tài sản (lạm phát & khấu hao):** Mô hình hàm số mũ suy giảm \(y = a(1-r)^x\), đo lường sức mua hao hụt do lạm phát và tính khấu hao tài sản cố định.
* **Phần IV: Mô hình hóa thực tế & công cụ trực quan:** Xây dựng kịch bản giả định (gửi tiết kiệm vs vay nợ), vẽ đồ thị minh họa điểm "bùng nổ" tài sản và đưa ra khuyến nghị thực tế.

---
## 📅 3. Kế hoạch Tiến độ trong 2 Tuần

Dự án được triển khai cuốn chiếu trong vòng 14 ngày với các mốc mục tiêu cụ thể:

### 📅 Tuần 1: Nghiên cứu lý thuyết & thu thập số liệu ( từ tài liêu tham khảo )

### 📅 Tuần 2: Mô hình hóa, trực quan & toàn thiện báo cáo

---

## 🛠 4. Cấu trúc Thư mục Dự án (Repository Structure)

Khi đưa lên GitHub, các file trong dự án của bạn sẽ được quản lý ngăn nắp theo cấu trúc sau:

```text
├── README.md               # File giới thiệu tổng quan dự án (File này)
├── docs/                   # Thư mục chứa tài liệu báo cáo chi tiết
│   ├── chuong1_co_so.md    # Chi tiết cơ sở toán học
│   └── chuong2_3_4.md      # Chi tiết các bài toán ứng dụng
├── src/                    # Thư mục chứa công cụ tính toán (nếu có)
│   ├── financial_calc.py   # Code Python tính toán và vẽ đồ thị
│   └── calculator.xlsx     # File Excel tính lãi kép & lạm phát tự động
└── assets/                 # Thư mục chứa hình ảnh, sơ đồ, đồ thị minh họa
    └── charts.png          # Đồ thị so sánh tăng trưởng tài sản
```
