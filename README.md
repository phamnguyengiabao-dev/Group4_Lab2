# Đồ án Data Mining: Nhóm 04

## Hướng dẫn Khởi tạo môi trường Julia trong VS Code

Để đảm bảo code chạy ổn định và không bị lỗi thiếu thư viện, bạn cần khởi tạo môi trường của dự án. Hãy làm theo các bước sau trong Visual Studio Code:

1. **Mở thư mục dự án**: 
   Mở thư mục chính chứa file `README.md` này (thư mục `Group_04`) bằng phần mềm VS Code.

2. **Khởi động Julia REPL**: 
   Mở Command Palette bằng tổ hợp phím `Ctrl+Shift+P` (Windows/Linux) hoặc `Cmd+Shift+P` (Mac). Gõ `Julia: Start REPL` và nhấn Enter để mở Terminal tương tác của Julia.

3. **Chuyển sang chế độ Quản lý Gói (Package Manager - Pkg)**: 
   Trong cửa sổ Terminal vừa mở (xuất hiện chữ `julia>`), hãy ấn phím `]` trên trình gõ phím. Dấu nhắc lệnh sẽ chuyển sang màu xanh lam báo hiệu đã vào chế độ Pkg (ví dụ: `(@v1.9) pkg>`).

4. **Kích hoạt môi trường của dự án**: 
   Để quản lý gọn gàng bằng file `Project.toml`, hãy gõ lệnh sau rồi nhấn Enter:
   ```julia
   activate .
   ```

5. **Cài đặt thư viện bắt buộc**: 
   Dự án này khuyến khích dùng các cấu trúc dữ liệu cơ bản của Julia. Bạn cần cài bằng cách gõ:
   ```julia
   add DataStructures
   ```

6. **Hoàn tất và quay lại REPL mặc định**: 
   Khi quá trình cài đặt hiển thị thông báo thành công, nhấn phím `Backspace` (hoặc `Delete`) để quay về cửa sổ lập trình Julia thông thường (`julia>`). Bây giờ môi trường của bạn đã được thiết lập và sẵn sàng để chạy thử các thuật toán!
