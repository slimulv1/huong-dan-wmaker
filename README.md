# 【 Hướng dẫn cách dùng Window Maker ![Wmaker](https://github.com/slimulv1/slimulv1/blob/main/wmaker.png) 】
## Lời tựa
Bài hướng dẫn này nhằm giúp người dùng Window Maker hiểu rõ hơn về những tính năng tuyệt vời của trình quản lý cửa sổ này. Cuốn Hướng dẫn Sử dụng Chính thức (Users Guide) rất đáng để đọc; bạn có thể truy cập tài liệu này từ trang web của Window Maker. Ngoài ra, các bài hướng dẫn và mẹo khác cũng có thể được tìm thấy tại nhiều trang web khác nhau trên Internet. Việc tìm kiếm từ khóa "Window Maker guide how-to" có thể cung cấp cho bạn thêm nhiều thông tin hữu ích.

Thông tin trong bài hướng dẫn này dựa trên phiên bản Window Maker 0.95.3. Bạn hãy kiểm tra phiên bản mình đang dùng bằng cách mở WPrefs.app (công cụ Tùy chỉnh Window Maker). Số phiên bản được hiển thị ngay bên dưới tiêu đề "Window Maker Preferences" tại cửa sổ WPrefs chính. Bạn cũng có thể chạy lệnh wmaker --version trong cửa sổ terminal (không nhập dấu ngoặc kép). Lệnh này sẽ trả về số phiên bản Window Maker hiện đang được cài đặt trên máy.

Mục lục
-----------------
1. [Tùy chỉnh (Preferences)](#preferences)
2. [Cửa sổ (Windows)](#windows)
3. [Menu (Menus)](#menus)
4. [Dock](#dock)
5. [Clip](#clip)
6. [Hình nền và chủ đề (Backgrounds and themes)](#backgrounds-and-themes)
7. [Các mục khác (Miscellaneous)](#miscellaneous)

<a name="preferences"></a>
Preferences
----------------------
![image](https://github.com/slimulv1/huong-dan-wmaker/blob/main/img/wprefs.jpg)
## WPrefs.app
WPrefs.app chính là trái tim của quá trình cấu hình trong Window Maker. Sau khi cài đặt và khởi chạy Window Maker lần đầu tiên, ứng dụng WPrefs thường có sẵn dưới dạng một biểu tượng trên thanh Dock theo mặc định:
<p align="left">
  <img src="/img/dock_tile.png" alt="dock title">
</p>
Tuy nhiên, tùy thuộc vào bản phân phối Linux bạn đang dùng, vị trí, mục trình đơn (menu) hoặc biểu tượng có thể sẽ khác nhau. Thông thường, các bản phân phối Linux đặt WPrefs ở vị trí biểu tượng thứ hai hoặc thứ ba trong - cột Dock theo mặc định, nằm ngay phía trên hoặc phía dưới biểu tượng terminal.
- Nhấp đúp chuột vào biểu tượng này để mở cửa sổ WPrefs.app. Dọc theo phía trên cùng của cửa sổ là một dãy các biểu tượng, mỗi biểu tượng tương ứng với một nhóm các tùy chọn thiết lập. Ở góc dưới bên trái của cửa sổ WPrefs.app có một ô đánh dấu (checkbox) để bật balloon help (trợ giúp dạng bong bóng). Phần lớn nội dung dưới đây được trích dẫn trực tiếp từ các hộp thoại trợ giúp này.
<br>
<p align="left">
  <img src="/img/prefs0.png">
</p>
WPrefs.app sau khi khởi chạy

### Các thiết lập tùy chỉnh hiện có
- [Tiêu điểm cửa sổ (Window focus)](#window-focus)
- [Xử lý cửa sổ (Window handling)](#window-handling)
- [Trình đơn (Menu)](#menu)
- [Biểu tượng (Icon)](#icon)
- [Ergonomy](#ergonomy)
- [Đường dẫn tìm kiếm (Search Path)](#search-path)
- [Dock](#dock)
- [Không gian làm việc (Workspace)](#workspace)
- [Khác (Other)](#other)
- [Trình quản lý ứng dụng (Applications menu)](#applications-menu)
- [Phím tắt bàn phím (Keyboard shortcut)](#keyboard-shortcut)
- [Chuột (Mouse)](#mouse)
- [Giao diện (Appearance)](#appearance)
- [Cấu hình phông chữ (Font configuration)](#font-configuration)
- [Người dùng chuyên gia (Expert user)](#expert-user)
- [Chỉnh sửa tệp cấu hình (Editing the configuration file)](#editing-the-configuration-file)
