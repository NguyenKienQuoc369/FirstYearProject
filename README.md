# Dự án cuối kì (Năm nhất) — Python Console Apps

Repo này gồm một notebook Python tổng hợp 4 bài/mini-project dạng **chương trình chạy trên terminal** (menu + nhập liệu), tập trung vào các bài toán quản lý và tính toán cơ bản.

## Nội dung
Tất cả nằm trong `NguyenKienQuoc_K254141631.ipynb`:

- **Bài 1 — Hệ thống xếp hạng tín dụng khách hàng**
  - Nhập danh sách khách hàng (thu nhập, tỷ lệ tiết kiệm, lịch sử thanh toán: 0–100)
  - Tính điểm tín dụng theo trọng số và **xếp loại A/B/C/D**
  - Menu: thêm/xóa khách hàng, hiển thị bảng xếp hạng

- **Bài 2 — Phân tích rủi ro danh mục cổ phiếu (Portfolio)**
  - Quản lý danh mục (mã CP, tỷ trọng, lợi suất kỳ vọng, độ lệch chuẩn)
  - Tính **lợi suất kỳ vọng** và **độ lệch chuẩn danh mục**
  - Có thể lưu nhật ký ra file `lich_su_phan_tich.txt`

- **Bài 3 — Mô phỏng hệ thống ngân hàng (QUOCBANK)**
  - Tạo/đăng nhập tài khoản, sao kê, nạp/rút/chuyển tiền (có phí)
  - Quên mật khẩu qua câu hỏi bảo mật
  - Lưu/đọc dữ liệu bằng `pickle` vào `ngan_hang_data.pkl`

- **Bài 4 — Quản lý hợp đồng vay tín chấp**
  - Thêm/xóa/tìm hợp đồng; tính **lãi đơn** và tổng phải trả
  - Hiển thị bảng kê tổng hợp; xuất báo cáo `.txt`
  - Lưu/đọc dữ liệu bằng `pickle` vào `quan_ly_vay.pkl`

## Yêu cầu chạy
- Python 3.x
- Không dùng thư viện ngoài (chỉ dùng thư viện chuẩn như: `math`, `datetime`, `os`, `re`, `pickle`, `getpass`)

## Cách chạy
### Cách 1: Chạy trong VS Code (khuyến nghị)
1. Mở `NguyenKienQuoc_K254141631.ipynb`
2. Chạy từng cell code tương ứng với **Bài 1/2/3/4**
3. Tương tác qua ô nhập (stdin) ở Terminal/Notebook theo hướng dẫn menu

### Cách 2: Chạy bằng Jupyter Notebook
- Mở notebook và chạy cell tương tự như trên.

## Dữ liệu phát sinh khi chạy
Tùy bài bạn chạy, project có thể tạo thêm các file sau trong cùng thư mục:
- `lich_su_phan_tich.txt` (Bài 2)
- `ngan_hang_data.pkl` (Bài 3)
- `quan_ly_vay.pkl` và `Bao_Cao_Vay_*.txt` (Bài 4)

## Tác giả
- Nguyễn Kiên Quốc — `K254141631`
