<div align="center"> 
  
# 🌸 Window Maker: The Phantasmagoria of Desktop Customization 🌸
# 【 Hướng dẫn cách dùng Window Maker ![Wmaker](https://github.com/slimulv1/slimulv1/blob/main/wmaker.png) 】
  <img src="https://img.shields.io/badge/Gensokyo-Approved-ff69b4?style=for-the-badge&logo=konami" alt="Gensokyo Approved">
  <img src="https://img.shields.io/badge/Spell_Card-High_Quality-blueviolet?style=for-the-badge" alt="Spell Card">
 
![Repo size](https://img.shields.io/github/repo-size/slimulv1/huong-dan-wmaker?style=badge&logo=protondrive&logoColor=fff&colorA=363a4f&colorB=blue)
![GitHub last commit (branch)](https://img.shields.io/github/last-commit/slimulv1/huong-dan-wmake/main?style=badge&label=Last%20Commit&logo=git&logoColor=fff&colorA=363a4f&colorB=purple)
<!-- style=for-the-badge / style string
Possible values: [flat, flat-square, plastic, badge, for-the-badge, social] -->
</div>

## ⛩️ Lời tựa
Bài hướng dẫn này nhằm giúp người dùng Window Maker hiểu rõ hơn về những tính năng tuyệt vời của trình quản lý cửa sổ này. Cuốn Hướng dẫn Sử dụng Chính thức (Users Guide) rất đáng để đọc; bạn có thể truy cập tài liệu này từ trang web của Window Maker. Ngoài ra, các bài hướng dẫn và mẹo khác cũng có thể được tìm thấy tại nhiều trang web khác nhau trên Internet. Việc tìm kiếm từ khóa "Window Maker guide how-to" có thể cung cấp cho bạn thêm nhiều thông tin hữu ích.  
Thông tin trong bài hướng dẫn này dựa trên phiên bản Window Maker 0.95.3. Bạn hãy kiểm tra phiên bản mình đang dùng bằng cách mở WPrefs.app (công cụ Tùy chỉnh Window Maker). Số phiên bản được hiển thị ngay bên dưới tiêu đề "Window Maker Preferences" tại cửa sổ WPrefs chính. Bạn cũng có thể chạy lệnh wmaker --version trong cửa sổ terminal (không nhập dấu ngoặc kép). Lệnh này sẽ trả về số phiên bản Window Maker hiện đang được cài đặt trên máy.

📜 Mục lục
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
Tuy nhiên, tùy thuộc vào bản phân phối Linux bạn đang dùng, vị trí, mục trình đơn (menu) hoặc biểu tượng có thể sẽ khác nhau. Thông thường, các bản phân phối Linux đặt WPrefs ở vị trí biểu tượng thứ hai hoặc thứ ba trong - cột Dock theo mặc định, nằm ngay phía trên hoặc phía dưới biểu tượng terminal.<br>
Nhấp đúp chuột vào biểu tượng này để mở cửa sổ WPrefs.app. Dọc theo phía trên cùng của cửa sổ là một dãy các biểu tượng, mỗi biểu tượng tương ứng với một nhóm các tùy chọn thiết lập. Ở góc dưới bên trái của cửa sổ  
WPrefs.app có một ô đánh dấu (checkbox) để bật balloon help (trợ giúp dạng bong bóng). Phần lớn nội dung dưới đây được trích dẫn trực tiếp từ các hộp thoại trợ giúp này.
<br>
<p align="left">
  <img src="/img/prefs0.png" alt="">
</p>
  WPrefs.app sau khi khởi chạy
  
## 🎨 Các thiết lập tùy chỉnh hiện có
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

<a name="preferences"></a>
Window focus
----------------------
<p align="left">
  <img src="/img/prefs1.png" alt="">
</p>

Điều khiển tiêu điểm cửa sổ (Window Focus) trong WPrefs.app  
Biểu tượng đầu tiên từ phía bên trái dùng để điều khiển cách các cửa sổ nhận tiêu điểm (cách chúng được kích hoạt).
- Chế độ tiêu điểm đầu vào (có hai lựa chọn):
  - Thủ công (Manual): Nhấp chuột vào cửa sổ để thiết lập tiêu điểm nhập liệu từ bàn phím.
  - Tự động (Auto): Tự động đặt tiêu điểm nhập liệu bàn phím cho cửa sổ nằm dưới con trỏ chuột.
- Cài đặt bảng màu (Colormap) trong cửa sổ (Install colormap in the window)
  - Lựa chọn cài đặt bảng màu cho: (a) cửa sổ đang có tiêu điểm đầu vào hoặc (b) cửa sổ đang nằm dưới con trỏ chuột.
- Độ trễ tự động nâng cửa sổ (Automatic window raise delay):
  - Thiết lập khoảng thời gian chờ (tính bằng mili giây - msec) để cửa sổ tự động nổi lên trên cùng.
- Các ô đánh dấu (Checkboxes):
  - Ô trên cùng: Ngăn ứng dụng nhận cú nhấp chuột dùng để lấy tiêu điểm (tôi không rõ tại sao bạn lại cần dùng tính năng này, nhưng rõ ràng là một số người thấy nó hữu ích).
  - Ô ở giữa: Cho phép bạn chọn việc các cửa sổ ứng dụng mới mở sẽ tự động nhận tiêu điểm, hay phải nhấp chuột vào mới có thể lấy được tiêu điểm.
  - Ô dưới cùng: Cho phép bạn đưa cửa sổ lên phía trên (nổi lên trên các cửa sổ khác) khi đang sử dụng bàn phím.

<a name="#window-handling"></a>
Window handling
----------------------
<p align="left">
  <img src="/img/prefs2.png" alt="">
</p>

Tùy chỉnh xử lý cửa sổ trong WPrefs.app  
Nhấp vào biểu tượng thứ hai để lựa chọn các tùy chọn xử lý cửa sổ. Biểu tượng này mở ra một bảng điều khiển cho phép bạn định nghĩa vị trí mặc định và các thuộc tính của cửa sổ trong không gian làm việc.
- Sắp xếp cửa sổ (Window placement)
  - Bạn có thể sử dụng các thanh trượt xung quanh hình mô phỏng màn hình để thay đổi vị trí ban đầu. Công cụ này cho phép Window Maker sắp xếp thứ tự cửa sổ trên màn hình theo các chế độ: Ngẫu nhiên (Random), Thủ công (Manual), Bậc thang (Cascade) hoặc Thông minh (Smart). Chế độ mặc định là Tự động (Automatic).
- Kéo một cửa sổ đang phóng to (Dragging a maximized window)
  - Thiết lập hành vi của cửa sổ đang phóng to khi bạn nhấp vào thanh tiêu đề và kéo bằng chuột. Các hành động có thể thiết lập bao gồm:
    - Thay đổi vị trí của cửa sổ.
    - Khôi phục lại kích thước trước khi phóng to (unmaximized geometry).
    - Coi như cửa sổ hiện đã thoát chế độ phóng to.
    - Không di chuyển cửa sổ.
- Độ kháng cạnh (Edge resistance)
  - Thiết lập độ kháng của cạnh màn hình và chọn xem nó sẽ đẩy (resists) hay hút (attracts) các cửa sổ. Tùy theo lựa chọn, các cửa sổ sẽ đẩy hoặc hút khi được di chuyển lại gần các cửa sổ khác hoặc cạnh màn hình. Thanh trượt dùng để xác định ngưỡng tác động (threshold).
  - Lưu ý: Thanh tiêu đề của một số ứng dụng có thể biến mất ở phía trên cùng nếu cửa sổ quá cao so với màn hình. Việc đặt độ kháng cạnh về mức "0" có thể giải quyết vấn đề này.
- Phím Mod + Cuộn chuột (Mod+Wheel)
  - Bạn có thể xác định cửa sổ sẽ tăng/giảm bao nhiêu pixel khi sử dụng tổ hợp phím bổ trợ (modifier keys) + cuộn chuột. Theo mặc định, CTRL + cuộn chuột sẽ thay đổi kích thước cửa sổ theo chiều ngang, trong khi phím SUPER + cuộn chuột sẽ thay đổi theo chiều dọc.
- Khi phóng to (When maximizing)
  - Tùy chọn này cho phép cửa sổ che phủ (hoặc không che phủ) các biểu tượng hoặc thanh Dock khi được phóng to toàn màn hình.
- Di chuyển/Thay đổi kích thước hiển thị nội dung (Opaque move/resize)
  - Opaque move: Khi chọn mục này, cửa sổ sẽ hiển thị toàn bộ nội dung bên trong khi di chuyển. Nếu không chọn, chỉ có khung viền được hiển thị.
  - Opaque resize: Giúp nội dung cửa sổ hiển thị rõ trong quá trình thay đổi kích thước, nếu không chỉ có khung viền được hiển thị.

<a name="#menu"></a>
Menu
----------------------
<p align="left">
  <img src="/img/prefs3.png" alt="">
</p>

Tùy chỉnh trình đơn (menu) trong WPrefs.app  
Bảng điều khiển này cho phép bạn thiết lập tốc độ cuộn trình đơn và cách căn lề của trình đơn con (submenu) so với trình đơn cha. Ngoài ra, có ba ô đánh dấu (checkbox) được cung cấp với các chức năng sau:
- Ô trên cùng: Bắt buộc các trình đơn con luôn mở bên trong phạm vi màn hình thay vì phải cuộn khi chúng bị tràn ra ngoài cạnh màn hình.
- Ô ở giữa: Cho phép các trình đơn con được mở tràn ra ngoài màn hình, nhưng sẽ khiến các trình đơn này tự động cuộn lại khi con trỏ chuột di chuyển lên trên chúng. Thiết lập này cũng rất có giá trị nếu bạn sử dụng tính năng "tear off" (tách rời trình đơn và đặt cố định trên màn hình). Trong trường hợp đó, bạn có thể muốn "park" trình đơn ở sát mép màn hình (ví dụ chỉ để lộ thanh tiêu đề) và để nó hiện ra đầy đủ khi bạn di chuột qua. Điều này rất tiện lợi trong một số quy trình làm việc, chẳng hạn như khi bạn mở nhiều ứng dụng và sử dụng trình đơn danh sách cửa sổ để chuyển đổi qua lại giữa chúng.
- Ô dưới cùng: Cho phép bạn gán các tổ hợp phím tắt kiểu Vim (Vim-like keybindings) để lựa chọn các mục trong trình đơn.

<a name="#icon"></a>
Icon
----------------------
<p align="left">
  <img src="/img/prefs4.png" alt="">
</p>
