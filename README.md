# NHÓM8_TH3|
# BÁO CÁO BÀI THỰC HÀNH EXCEL & GOOGLE SHEETS
## TÓM TẮT NỘI DUNG THỰC HÀNH
### 1. Thực hành Microsoft Excel (File: `Buoi03_Ho_ten_Bai_1.docx`)
#### a. Điền dữ liệu & Dò tìm thông tin
- **Họ và Tên:** Sử dụng hàm dò tìm dựa trên 8 ký tự cuối của *Mã SV* từ bảng *Danh sách Sinh viên*[span_0](start_span)[span_0](end_span).
- **Điểm TH1, TH2, TH3:** Dò tìm từ bảng *Điểm thực hành các buổi*[span_1](start_span)[span_1](end_span).
- **Điểm BT lớn & Điểm LT:** Dò tìm lần lượt từ bảng *Điểm bài tập lớn* và *Điểm lý thuyết*[span_2](start_span)[span_2](end_span).
#### b. Tính toán & Xử lý kết quả
- **Điểm tổng:** 
  - Nếu $\text{Điểm LT} = -3$ thì $\text{Điểm tổng} = 0$[span_3](start_span)[span_3](end_span).
  - Ngược lại: $\text{Điểm tổng} = \text{Điểm TH1} + \text{Điểm TH2} + \text{Điểm TH3} + \text{Điểm BT lớn} + 0.6 \times \text{Điểm LT}$ (làm tròn 1 chữ số thập phân)[span_4](start_span)[span_4](end_span).
- **Điểm theo thang điểm 10:**
  - Nếu $\text{Điểm BT lớn} = 0$ hoặc nghỉ quá 2 buổi (ký tự đầu Mã SV $> 2$) thì điểm bằng $0$[span_5](start_span)[span_5](end_span).
  - Ngược lại: $\text{Điểm 10} = \text{Điểm tổng} + \text{Điểm chuyên cần}$ (làm tròn 1 chữ số thập phân)[span_6](start_span)[span_6](end_span).
- **Điểm chữ:** Dò tìm dựa trên *Điểm theo thang điểm 10* từ *Bảng quy đổi điểm*[span_7](start_span)[span_7](end_span).
#### c. Trích lọc dữ liệu & Đóng băng dòng/cột
- **Tạo 2 sheet trích lọc mới:**
  - `Sinh viên điểm < 7`: Lọc các sinh viên có điểm thang 10 nhỏ hơn 7[span_8](start_span)[span_8](end_span).
  - `Sinh viên điểm >= 7`: Lọc các sinh viên có điểm thang 10 $\ge 7$ và có Điểm chữ là `B+` hoặc `A`[span_9](start_span)[span_9](end_span).
- **Freeze Panes:** Đóng băng cố định dòng 1 đến dòng 6 và các cột A, B, C[span_10](start_span)[span_10](end_span).
#### d. Thống kê & Vẽ biểu đồ
- **Thống kê:** Tính số lượng sinh viên theo từng loại Điểm chữ, thống kê SV bỏ bài tập/nghỉ thi, và SV đạt điểm giỏi[span_11](start_span)[span_11](end_span).
- **Vẽ biểu đồ:** Tạo biểu đồ hình tròn (Pie chart) biểu diễn tỷ lệ **Số lượng sinh viên theo Điểm chữ**[span_12](start_span)[span_12](end_span).
### 2. Thực hành Google Sheets (File: `Buoi11_Ho_ten_Bai_2.gsheet`)
#### a. Nhập dữ liệu ban đầu
- Nhập bảng tổng hợp thông tin sinh viên, mã ngành, mã môn học và điểm số vào sheet `Tong_hop`[span_13](start_span)[span_13](end_span).
#### b. Truy vấn dữ liệu nâng cao bằng hàm `QUERY`
- **Sheet `1. SV nganh CNTT`:** Lọc danh sách sinh viên thuộc ngành *Information Technology*[span_14](start_span)[span_14](end_span).
- **Sheet `2. SV lop_DI18T9A1 mon NT_CNTT`:** Lọc sinh viên lớp *DI18T9A1* học môn *Fundamentals of Information Technology*[span_15](start_span)[span_15](end_span).
- **Sheet `3. SV_Diem_D_F`:** Lọc sinh viên học môn *System Administration* có điểm kết quả là `D` hoặc `F`[span_16](start_span)[span_16](end_span).
- **Sheet `4. SV dang ky hoc hon 1 mon`:** Lọc danh sách các sinh viên đăng ký nhiều hơn 1 môn học[span_17](start_span)[span_17](end_span).
