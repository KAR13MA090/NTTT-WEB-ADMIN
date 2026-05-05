
# NTTT-WEB-ADMIN


## Các lệnh để chạy hệ thống

1. **Cấp quyền thực thi cho script:**
   ```bash
   chmod +x AdminHack.sh
   chmod +x src/ReloadInstall.sh
   ```

2. **Chạy tool chính:**
   ```bash
   bash AdminHack.sh
   ```

3. **Cài đặt lại tool (Reload):**
   ```bash
   cd src
   bash ReloadInstall.sh
   ```

4. **Cài đặt các gói cần thiết (nếu chưa có):**
   ```bash
   pkg install curl wget bash
   pkg install ncurses-util toilet
   ```

---

## Hướng dẫn sử dụng

1. **Chạy script:**
   - Mở terminal tại thư mục chứa file `AdminHack.sh`.
   - Chạy lệnh: `bash AdminHack.sh`

2. **Nhập thông tin:**
   - Nhập tên website cần kiểm tra (ví dụ: `example.com`).
   - Nhập đường dẫn wordlist (hoặc nhấn Enter để dùng mặc định `wordlist.txt`).
   - Chọn lưu kết quả hay không (yes/no).
   - Nhập số lượng luồng (threads) muốn sử dụng (hoặc Enter để mặc định).

3. **Kết quả:**
   - Kết quả quét sẽ hiển thị trên màn hình.
   - Nếu chọn lưu, kết quả sẽ nằm trong thư mục tên website vừa nhập.

## Yêu cầu
- Hệ điều hành: Linux hoặc môi trường hỗ trợ bash.
- Đã cài đặt: `curl`, `wget`, `bash`.

## Miễn trừ trách nhiệm

Phần mềm này chỉ được sử dụng cho mục đích học tập, kiểm thử bảo mật hợp pháp hoặc nghiên cứu cá nhân. Tác giả không chịu bất kỳ trách nhiệm nào đối với việc sử dụng sai mục đích, gây thiệt hại hoặc vi phạm pháp luật từ phía người dùng.

**Hãy đảm bảo bạn có sự cho phép trước khi kiểm thử bất kỳ hệ thống nào!**
