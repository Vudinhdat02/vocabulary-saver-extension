# 📚 Auto Vocab Saver - Chrome Extension

**Auto Vocab Saver** là một tiện ích mở rộng trên trình duyệt Google Chrome giúp người học tiếng Anh tra cứu và nạp từ vựng tự động. Chỉ cần bôi đen từ mới và nhấn `Ctrl + C`, extension sẽ tự động tra cứu loại từ, các nét nghĩa thông dụng nhất và lưu lại danh sách để xuất ra file `.csv` làm dữ liệu học tập (Anki, Quizlet, Excel...).

---

## ✨ Tính năng nổi bật

- ⚡ **Tự động lưu từ vựng:** Bôi đen từ/cụm từ tiếng Anh trên trang web và nhấn `Ctrl + C`, từ vựng sẽ tự động được tra cứu và lưu lại.
- 📖 **Phân loại từ & Nghĩa phổ thông:** Tự động nhận diện loại từ (`n`, `v`, `adj`, `adv`...) và chỉ lọc ra tối đa 4 nghĩa tiếng Việt thông dụng nhất, giúp bạn không bị rợp bởi quá nhiều nghĩa hiếm gặp.
- 📌 **Widget cố định & Linh hoạt:**
  - Hiển thị danh sách từ vựng dạng bảng 2 cột trực tiếp trên góc màn hình web.
  - Cho phép **kéo thả di chuyển** vị trí popup và **thay đổi kích thước (phóng to/thu nhỏ)** theo ý muốn.
  - Tích hợp nút ẩn/hiện nhanh khi nhấp vào icon Extension trên thanh công cụ.
- 📥 **Xuất file CSV chuẩn UTF-8:** Cho phép tải danh sách từ vựng về máy dưới dạng `.csv` hỗ trợ hiển thị tiếng Việt chuẩn trên Excel (không bị lỗi font).

---

## 🛠️ Hướng dẫn cài đặt

1. **Tải mã nguồn về máy:**
   - Bấm nút **Code** > **Download ZIP** trên GitHub repository này và giải nén.
   - Hoặc clone dự án về máy bằng Git:
     ```bash
     git clone [https://github.com/username/vocab-saver-extension.git](https://github.com/username/vocab-saver-extension.git)
     ```

2. **Cài đặt vào Google Chrome:**
   - Mở trình duyệt Chrome và truy cập đường dẫn: `chrome://extensions/`
   - Bật công tắc **Developer mode** (Chế độ dành cho nhà phát triển) ở góc trên bên phải.
   - Nhấn nút **Load unpacked** (Tải tiện ích đã giải nén) ở góc trái.
   - Chọn thư mục `vocab-saver-extension` chứa mã nguồn.

---

## 🚀 Hướng dẫn sử dụng

1. Mở trang web tiếng Anh bất kỳ (đảm bảo `F5` lại trang sau khi cài đặt extension).
2. **Lưu từ vựng:** Bôi đen từ vựng (tối đa 4 từ) và nhấn **`Ctrl + C`**. Bảng danh sách góc phải màn hình sẽ tự động cập nhật từ mới cùng nghĩa và loại từ.
3. **Di chuyển / Đổi kích thước Popup:**
   - Nhấn giữ chuột vào thanh tiêu đề màu xanh để **kéo vị trí** bảng đi chỗ khác.
   - Kéo góc dưới bên phải của bảng để **phóng to/thu nhỏ**.
4. **Tải file CSV:** Nhấn vào nút **`📥 CSV`** trên thanh tiêu đề của Widget để tải danh sách về máy.
5. **Ẩn/Hiện Widget:** Nhấp vào biểu tượng icon của Extension trên thanh công cụ trình duyệt để bật hoặc tắt Widget.

---

## 🧰 Công cụ & Công nghệ sử dụng

- JavaScript (ES6+) / HTML5 / CSS3
- Chrome Extension Manifest V3
- Google Translate Dictionary API
- Chrome Storage API
