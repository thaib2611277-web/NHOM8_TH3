# NHÓM8_TH3|
Mã SV trong bảng Chuyên cần).
 Điểm chữ: Dò ⁠Điểm theo thang điểm 10⁠ trong Bảng quy đổi điểm1. Thực hành Microsoft Excel (Tập tin: ⁠Buoi03_Ho_ten_Bai_1.docx⁠ & tập tin Excel)
a. Chuẩn bị dữ liệu (Sheet Tổng hợp điểm)
 Họ và Tên: Lấy 8 ký tự cuối của Mã SV, dò trong bảng Danh sách Sinh viên (⁠Các bảng tham chiếu & Thống kê⁠).
 Điểm TH1, TH2, TH3: Lấy 8 ký tự cuối của Mã SV, dò trong bảng Điểm thực hành các buổi.
 Điểm BT lớn: Lấy 8 ký tự cuối của Mã SV, dò trong bảng Điểm bài tập lớn.
 Điểm LT: Lấy 8 ký tự cuối của Mã SV, dò trong bảng Điểm lý thuyết.
b. Tính toán & Xử lý điểm
 Điểm tổng (làm tròn 1 chữ số thập phân):
 Nếu \text{Điểm LT} = -3 \Rightarrow \text{Điểm tổng} = 0.
 Ngược lại: \text{Điểm tổng} = \text{Điểm TH1} + \text{Điểm TH2} + \text{Điểm TH3} + \text{Điểm BT lớn} + 0.6 \times \text{Điểm LT}.
 Điểm theo thang điểm 10 (làm tròn 1 chữ số thập phân):
 Nếu \text{Điểm BT lớn} = 0 hoặc ký tự đầu của Mã SV > 2 (nghỉ quá 2 buổi) \Rightarrow \text{Điểm} = 0.
 Ngược lại: \text{Điểm} = \text{Điểm tổng} + \text{Điểm chuyên cần} (dò ký tự đầu.
c. Trích lọc dữ liệu & Tiện ích
 Tạo 2 Sheet mới:
 ⁠Sinh viên điểm < 7⁠: Lọc các SV có Điểm thang 10 < 7.
 ⁠Sinh viên điểm >= 7⁠: Lọc các SV có Điểm thang 10 \ge 7 và Điểm chữ là ⁠B+⁠ hoặc ⁠A⁠.
 Cố định dòng/cột (⁠Freeze Panes⁠): Đóng băng dòng 1–6 và các cột A, B, C khi cuộn màn hình.
d. Thống kê & Vẽ biểu đồ (Sheet ⁠Các bảng tham chiếu & Thống kê⁠)
 Thống kê:
 Thống kê số lượng SV theo từng loại Điểm chữ.
 Thống kê số SV có \text{Điểm BT lớn} = 0 hoặc \text{Điểm LT} = -3.
 Thống kê số SV có Điểm thang 10 \ge 7 và Điểm chữ là ⁠B+⁠ hoặc ⁠A⁠.
 Vẽ biểu đồ: Tạo biểu đồ hình tròn (Pie chart) thể hiện tỉ lệ Số lượng sinh viên theo Điểm chữ.
2. Thực hành Google Sheets (Tập tin: ⁠Buoi11_Ho_ten_Bai_2.gsheet⁠)
a. Nhập dữ liệu
 Tạo sheet ⁠Tong_hop⁠ và nhập bảng dữ liệu thông tin sinh viên, học phần, điểm số.
b. Truy vấn dữ liệu bằng hàm ⁠QUERY⁠
 Sheet ⁠1. SV nganh CNTT⁠: Lọc danh sách SV (MSSV, Họ, Tên) thuộc ngành Information Technology.
 Sheet ⁠2. SV lop_DI18T9A1 mon NT_CNTT⁠: Lọc danh sách SV lớp DI18T9A1 học môn Fundamentals of Information Technology.
 Sheet ⁠3. SV_Diem_D_F⁠: Lọc SV học môn System Administration có kết quả điểm ⁠D⁠ hoặc ⁠F⁠.
 Sheet ⁠4. SV dang ky hoc hon 1 mon⁠: Lọc danh sách sinh viên đăng ký nhiều hơn 1 môn học.
