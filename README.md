<div align="center"> 
  
# 🌸 Window Maker: The Phantasmagoria of Desktop Customization 🌸
# 【 Hướng dẫn cách dùng Window Maker ![Wmaker](https://github.com/slimulv1/slimulv1/blob/main/wmaker.png) 】
  <img src="https://img.shields.io/badge/Gensokyo-Approved-ff69b4?style=for-the-badge&logo=konami" alt="Gensokyo Approved">
  <img src="https://img.shields.io/badge/Spell_Card-High_Quality-blueviolet?style=for-the-badge" alt="Spell Card">
 
![Repo size](https://img.shields.io/github/repo-size/slimulv1/huong-dan-wmaker?style=badge&logo=protondrive&logoColor=fff&colorA=363a4f&colorB=blue)
![GitHub last commit (branch)](https://img.shields.io/github/last-commit/slimulv1/huong-dan-wmaker/main?style=badge&label=Last%20Commit&logo=git&logoColor=fff&colorA=363a4f&colorB=purple)
<!-- style=for-the-badge / style string
Possible values: [flat, flat-square, plastic, badge, for-the-badge, social] -->
</div>

## ⛩️ Lời tựa
Bài hướng dẫn này nhằm giúp người dùng Window Maker hiểu rõ hơn về những tính năng tuyệt vời của trình quản lý cửa sổ này. Cuốn Hướng dẫn Sử dụng Chính thức (Users Guide) rất đáng để đọc; bạn có thể truy cập tài liệu này từ trang web của Window Maker. Ngoài ra, các bài hướng dẫn và mẹo khác cũng có thể được tìm thấy tại nhiều trang web khác nhau trên Internet. Việc tìm kiếm từ khóa "Window Maker guide how-to" có thể cung cấp cho bạn thêm nhiều thông tin hữu ích.  

Thông tin trong bài hướng dẫn này dựa trên phiên bản Window Maker 0.95.3. Bạn hãy kiểm tra phiên bản mình đang dùng bằng cách mở WPrefs.app (công cụ Tùy chỉnh Window Maker). Số phiên bản được hiển thị ngay bên dưới tiêu đề "Window Maker Preferences" tại cửa sổ WPrefs chính. Bạn cũng có thể chạy lệnh wmaker --version trong cửa sổ terminal (không nhập dấu ngoặc kép). Lệnh này sẽ trả về số phiên bản Window Maker hiện đang được cài đặt trên máy.

## 📜 Mục lục
1. [Tùy chỉnh (Preferences)](#preferences)
2. [Cửa sổ (Windows)](#windows)
3. [Menu (Menus)](#menus)
4. [Dock](#dock1)
5. [Clip](#clip)
6. [Hình nền và chủ đề (Backgrounds and themes)](#backgrounds-and-themes)
7. [Các mục khác (Miscellaneous)](#miscellaneous)

<a name="preferences"></a>
🛠️ Preferences 🛠️
----------------------
<p align="left">
  <img src="/img/wprefs.jpg" alt="Preferences">
</p>

## WPrefs.app
WPrefs.app chính là trái tim của quá trình cấu hình trong Window Maker. Sau khi cài đặt và khởi chạy Window Maker lần đầu tiên, ứng dụng WPrefs thường có sẵn dưới dạng một biểu tượng trên thanh Dock theo mặc định:
<p align="left">
  <img src="/img/dock_tile.png" alt="WPrefs.app">
</p>

Tuy nhiên, tùy thuộc vào bản phân phối Linux bạn đang dùng, vị trí, mục menu hoặc biểu tượng có thể sẽ khác nhau. Thông thường, các bản phân phối Linux đặt WPrefs ở vị trí biểu tượng thứ hai hoặc thứ ba trong - cột Dock theo mặc định, nằm ngay phía trên hoặc phía dưới biểu tượng terminal.<br>
Nhấp đúp chuột vào biểu tượng này để mở cửa sổ WPrefs.app. Dọc theo phía trên cùng của cửa sổ là một dãy các biểu tượng, mỗi biểu tượng tương ứng với một nhóm các tùy chọn thiết lập. Ở góc dưới bên trái của cửa sổ  
WPrefs.app có một ô đánh dấu (checkbox) để bật balloon help (trợ giúp dạng bong bóng). Phần lớn nội dung dưới đây được trích dẫn trực tiếp từ các hộp thoại trợ giúp này. <br> 

💠 **Giải nghĩa một số thuật ngữ.**
- Dock: Thanh neo đậu ứng dụng (thanh công cụ đặc trưng của Window Maker).
- Distribution (distro): Bản phân phối (ví dụ: Ubuntu, Debian, Arch Linux...).
- Balloon help: Chỉ dẫn xuất hiện trong một "bong bóng" nhỏ khi bạn di chuột qua một mục nào đó.
- Checkbox: Ô đánh dấu tích.

<br>
<p align="left">
  <img src="/img/prefs0.png" alt="">
</p>
  WPrefs.app sau khi khởi chạy
  
## 🎨 Các thiết lập tùy chỉnh hiện có
  - [Window focus](#window-focus)
  - [Window handling](#window-handling)
  - [Menu](#menu)
  - [Icon](#icon)
  - [Ergonomy](#ergonomy)
  - [Search Path](#search-path)
  - [Thanh Dock](#thanh-dock)
  - [Workspace](#workspace)
  - [Other](#other)
  - [Applications menu](#applications-menu)
  - [Keyboard shortcut](#keyboard-shortcut)
  - [Mouse](#mouse)
  - [Appearance](#appearance)
  - [Font configuration](#font-configuration)
  - [Expert user](#expert-user)
  - [Editing the configuration file](#editing-the-configuration-file)

💠 **Giải thích thêm cho một số thuật ngữ:**
- Window focus: Trong tin học, đây là trạng thái một cửa sổ đang "được chọn" để nhận lệnh từ bàn phím/chuột.
- Ergonomy: Các thiết lập giúp tối ưu hóa sự tiện lợi và sức khỏe người dùng (như tốc độ di chuột, độ trễ phím).
- Dock: Bạn nên giữ nguyên vì đây là thuật ngữ riêng của Window Maker (giống như thanh Taskbar trên Windows).
- Expert user: Phần dành cho người dùng đã am hiểu sâu, thường chứa các tùy chỉnh nâng cao hoặc nguy hiểm.

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

💠 **Giải thích thêm một số thuật ngữ kỹ thuật:**
- Focus (Tiêu điểm): Trạng thái một cửa sổ đang hoạt động và sẵn sàng nhận lệnh.
- Colormap: Một bảng màu kỹ thuật (thường liên quan đến các hệ thống hiển thị cũ như X11 để tránh xung đột màu sắc giữa các ứng dụng).
- Window raise: Hành động đưa một cửa sổ đang bị che khuất lên vị trí trên cùng của màn hình.

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

💠 **Ghi chú thuật ngữ:**
- Geometry: Trong ngữ cảnh này là kích thước và tọa độ của cửa sổ.
- Opaque (Đục/Không trong suốt): Trong kỹ thuật phần mềm, "Opaque move" ám chỉ việc di chuyển cả khối cửa sổ thay vì chỉ di chuyển cái khung dây (wireframe).
- Super key: Thường là phím Windows trên bàn phím PC hoặc phím Command trên Mac.

<a name="#menu"></a>
Menu
----------------------
<p align="left">
  <img src="/img/prefs3.png" alt="">
</p>

Tùy chỉnh menu trong WPrefs.app  

Bảng điều khiển này cho phép bạn thiết lập tốc độ cuộn menu và cách căn lề của menu con (submenu) so với menu cha. Ngoài ra, có ba ô đánh dấu (checkbox) được cung cấp với các chức năng sau:
- Ô trên cùng: Bắt buộc các menu con luôn mở bên trong phạm vi màn hình thay vì phải cuộn khi chúng bị tràn ra ngoài cạnh màn hình.
- Ô ở giữa: Cho phép các menu con được mở tràn ra ngoài màn hình, nhưng sẽ khiến các menu này tự động cuộn lại khi con trỏ chuột di chuyển lên trên chúng. Thiết lập này cũng rất có giá trị nếu bạn sử dụng tính năng "tear off" (tách rời menu và đặt cố định trên màn hình). Trong trường hợp đó, bạn có thể muốn "đậu" menu ở sát mép màn hình (ví dụ chỉ để lộ thanh tiêu đề) và để nó hiện ra đầy đủ khi bạn di chuột qua. Điều này rất tiện lợi trong một số quy trình làm việc, chẳng hạn như khi bạn mở nhiều ứng dụng và sử dụng menu danh sách cửa sổ để chuyển đổi qua lại giữa chúng.
- Ô dưới cùng: Cho phép bạn gán các tổ hợp phím tắt kiểu Vim (Vim-like keybindings) để lựa chọn các mục trong menu.

💠 **Ghi chú thuật ngữ:**
- Tear off: Tính năng cho phép bạn tách một menu ra khỏi vị trí gốc và biến nó thành một cửa sổ nhỏ nằm cố định trên màn hình để tiện sử dụng.
- Vim-like keybindings: Cách điều khiển bằng các phím chữ cái (như h, j, k, l) thay vì phím mũi tên, phổ biến trong trình soạn thảo văn bản Vim.
- Parent menu / Submenu: menu cha và menu con (cấp thấp hơn).

<a name="#icon"></a>
Icon
----------------------
<p align="left">
  <img src="/img/prefs4.png" alt="">
</p>

Tùy chỉnh biểu tượng trong WPrefs.app  

Thiết lập các tùy chọn xử lý biểu tượng hoặc cửa sổ thu nhỏ (miniwindow).
- Vị trí biểu tượng (Icon positioning)
  - Khu vực này định nghĩa vị trí ban đầu mà các cửa sổ thu nhỏ (miniwindows) hoặc biểu tượng sẽ được hiển thị: dưới cùng, trên cùng, bên phải, bên trái...
- Kích thước biểu tượng (Icon size)
  - Lựa chọn kích thước của các biểu tượng được hiển thị khi một cửa sổ được thu nhỏ (miniaturized) và cho các biểu tượng ứng dụng. Các nhà phát triển "dockapp" thường mặc định rằng các ô biểu tượng sẽ là 64x64 pixel, vì vậy có lẽ tốt nhất là nên để nguyên ở kích thước đó, trừ khi bạn biết chắc mình sẽ không sử dụng "dockapps".
- Xem trước thu nhỏ cho biểu tượng (Mini-Previews for Icons)
  - Cho phép hiển thị nội dung của cửa sổ khi di chuột qua biểu tượng ứng dụng đã được thu nhỏ (minimised). Thanh trượt cho phép thiết lập kích thước của phần xem trước.
- Hoạt ảnh thu nhỏ biểu tượng (Iconification animation)
   - Khi cửa sổ của một ứng dụng được thu nhỏ (miniaturized), kiểu hoạt ảnh thu nhỏ cung cấp bốn lựa chọn hoạt ảnh:
     - "Shrinking/Zooming",
     - "Spinning/Twisting",
     - "3D Flipping", hoặc
     - "None"
- Các ô đánh dấu (Checkboxes)
   - Ô trên cùng cho phép/vô hiệu hóa việc tự động sắp xếp các biểu tượng.
   - Ô ở giữa sẽ đặt các cửa sổ thu nhỏ (miniwindows) của các ứng dụng đang mở trên tất cả các không gian làm việc hiện có (vạn năng (omnipresent)).
   - Ô dưới cùng cho phép sử dụng nhấp chuột đơn cho các biểu tượng đã thu nhỏ (minimized) hoặc đã được đưa vào dock (docked icon) thay vì phải nhấp đúp chuột.

<a name="#ergonomy"></a>
Ergonomy
----------------------
<p align="left">
  <img src="/img/prefs5.png" alt="">
</p>

Thiết lập ergonomy trong WPrefs.app  

Nhiều loại thông tin khác nhau được định nghĩa trong bảng điều khiển này.
- Hiển thị kích thước (Size display)
  - Window Maker cung cấp một hộp thông tin cho bạn biết về kích thước của một cửa sổ trong quá trình thay đổi kích thước (resizing). Bạn có thể chọn hiển thị này ở (a) chính giữa màn hình, (b) chính giữa màn hình, (c) chính giữa cửa sổ đang được thay đổi kích thước (resized), (d) ở cạnh và đáy cửa sổ dưới dạng hiển thị kích thước giống như bản vẽ kỹ thuật hoặc (e) không hiển thị.
- Hiển thị vị trí (Position display)
   - Thông tin tương tự như trên nhưng liên quan đến vị trí trên màn hình của một cửa sổ trong khi di chuyển (moving) (không có tùy chọn dạng bản vẽ kỹ thuật).
- Biểu tượng ứng dụng nhấp nhô (Appicon bouncing)
   - Bạn có thể thiết lập hành vi nhấp nhô của "AppIcons" tại đây.
- Hiển thị văn bản bong bóng cho (Show balloon text for)
  - Việc chọn các ô đánh dấu sẽ hiển thị văn bản bong bóng cho: tiêu đề cửa sổ không đầy đủ, tiêu đề cửa sổ thu nhỏ (miniwindow), các biểu tượng ứng dụng và "dock icon", hoặc trợ giúp nội bộ. Điều này có thể hữu ích cho người dùng mới nhưng nhiều người cảm thấy việc các bong bóng trợ giúp hiện ra khắp nơi trên màn hình nền sẽ nhanh chóng gây khó chịu. Tôi thường sử dụng các tùy chọn tiêu đề cửa sổ không đầy đủ và tiêu đề cửa sổ thu nhỏ (miniwindow) và không dùng các tùy chọn khác.
- Đường viền không gian làm việc (Workspace border)
  - Bạn có thể thiết lập một đường viền nhỏ cho không gian làm việc. Điều này cho phép bạn dễ dàng truy cập "clip" (chẳng hạn) khi các cửa sổ đang được phóng to (maximized).

<a name="#search-path"></a>
Search Path
----------------------
<p align="left">
  <img src="/img/prefs6.png" alt="">
</p>

Thiết lập đường dẫn tìm kiếm biểu tượng và ảnh mảng (pixmap) trong WPrefs.app  

Bảng điều khiển này được sử dụng để thêm hoặc xóa các đường dẫn thư mục dùng cho việc tìm kiếm các biểu tượng và "pixmaps". Những đường dẫn này được sử dụng trong các hộp thoại settings cho "dockapps" và các biểu tượng ứng dụng đã được đưa vào dock (docked), vì vậy việc có một bộ đường dẫn được định nghĩa đầy đủ và chuẩn xác là rất quan trọng. Điều này có thể đòi hỏi một số can thiệp thủ công, đặc biệt là khi thiết lập ban đầu (initial setup), vì một số đường dẫn mặc định sẽ không tồn tại trên hệ thống của bạn, trong khi những đường dẫn khác chưa được định nghĩa trước thì lại có sẵn. Hãy sử dụng các hộp thoại "add" (thêm) và "remove" (xóa) để cấu hình dựa theo những gì thực sự có sẵn trên máy.

<a name="#thanh-dock"></a>
Thanh Dock
----------------------
<p align="left">
  <img src="/img/prefs7.png" alt="">
</p>

Thiết lập tùy chỉnh "Dock" trong WPrefs.app  

Trong bảng điều khiển này, bạn có thể tinh chỉnh hành vi của "Dock"/"Clip"/"Drawer".
- Độ trễ tự động thu gọn Clip và độ trễ tự động nổi lên của Clip (Clip autocollapsing delays and Clip autoraising delays) cho phép bạn chọn khoảng thời gian trễ cho việc mở rộng (expansion), thu gọn (collapsing), nổi lên (raising) và hạ xuống (lowering) của "Clip".
- Dock/Clip/Drawer
  - Biểu tượng đầu tiên cho phép/vô hiệu hóa "Dock", thanh dọc dành cho các "appicons" và ứng dụng của bạn.
  - Biểu tượng thứ hai cho phép bật/tắt "Clip", ô biểu tượng có hình cái kẹp giấy.
  - Biểu tượng cuối cùng cho phép bật/tắt "Drawer" - một "dockapp" đặc biệt dùng để chứa các biểu tượng ứng dụng theo chiều ngang.

<a name="#workspace"></a>
Workspace
----------------------
<p align="left">
  <img src="/img/prefs8.png" alt="">
</p>

Thiết lập tùy chỉnh không gian làm việc trong WPrefs.app  

Bảng điều khiển này định nghĩa các tính năng điều hướng bên trong không gian làm việc.
- Điều hướng không gian làm việc (Workspace navigation)
   - Việc chọn ô đánh dấu đầu tiên cho phép chuyển đổi (switching) sang không gian làm việc đầu tiên khi bạn chuyển tiếp qua không gian làm việc cuối cùng và ngược lại.
   - Việc chọn ô đánh dấu thứ hai cho phép các cửa sổ được kéo (dragged) từ không gian làm việc này sang không gian làm việc khác.
   - Việc chọn ô đánh dấu thứ ba sẽ khiến một không gian làm việc mới được tạo ra khi các cửa sổ được kéo (dragged) ra khỏi không gian làm việc cuối cùng đang tồn tại. <br>

Một menu lựa chọn cho phép bạn định nghĩa nơi tên không gian làm việc được hiển thị mỗi khi bạn di chuyển từ một không gian làm việc này sang một không gian làm việc khác (hoặc chọn không hiển thị tên không gian làm việc).


<a name="#Other"></a>
Other
----------------------
<p align="left">
  <img src="/img/prefs9.png" alt="">
</p>

Thiết lập cấu hình không gian làm việc khác trong WPrefs.app  

Bảng điều khiển này thiết lập tốc độ trượt biểu tượng, tốc độ hoạt ảnh cuộn lên (shade), làm mịn hình ảnh và kiểu điều khiển (nút bấm) trên thanh tiêu đề. Các hoạt ảnh và âm thanh cũng được định nghĩa tại đây.
- Tốc độ trượt biểu tượng (Icon slide speed): Chọn biểu tượng bên trái sẽ cho kết quả chậm nhất, chọn biểu tượng bên phải sẽ cho kết quả nhanh nhất.
- Tốc độ hoạt ảnh cuộn lên (Shade animation speed): Tương tự như tốc độ trượt biểu tượng.
- Kiểu thanh tiêu đề (Titlebar style): Để chọn thanh tiêu đề mang phong cách "NeXTish" nhiều hay ít. (Phiên bản trên cùng là "mới hơn", trong khi phía dưới bên trái là khoảng năm 1990 và phía dưới bên phải là khoảng năm 1988.)
- Hoạt ảnh (Animations): Việc chọn biểu tượng hoạt ảnh sẽ kích hoạt các hoạt ảnh cho việc thu nhỏ (miniaturization) cửa sổ, cuộn lên (shading) và các hiệu ứng khác. Việc chọn biểu tượng "superfluous" sẽ kích hoạt hiệu ứng "đổ bóng" (ghosting) cho "dock" (khi di chuyển - đặc biệt là khi di chuyển từ cạnh này sang cạnh kia của màn hình) và hoạt ảnh nổ tung cho các biểu tượng mà bạn xóa khỏi "dock".
- Làm mịn hình ảnh (Smooth scaling): Nếu được chọn, tính năng này sẽ trung hòa hiệu ứng vỡ ảnh (pixelization) trên các ảnh nền. Tác dụng phụ là làm chậm quá trình tải ảnh nền.
- Phối màu cho màn hình 8bpp (Dithering colormap for 8bpp): Dành cho các màn hình 8-bit (liệu còn ai sử dụng loại này không?), tùy chọn này kích hoạt khả năng phối màu (dithering) và thay đổi số lượng màu sắc dự phòng cho các ứng dụng hoặc cho Window Maker. Thiết lập "Default" hầu như luôn mang lại kết quả tốt nhất.

<a name="#applications-menu"></a>
Applications menu
----------------------
<p align="left">
  <img src="/img/prefs10.png" alt="">
</p>

Cấu hình menu ứng dụng trong WPrefs.app  

Trong bảng điều khiển này, menu ứng dụng và các lệnh để khởi chạy từng ứng dụng có thể được định nghĩa. Bảng điều khiển này đã được thay đổi kể từ phiên bản 0.63 trở đi. Hiện tại, nó hiển thị menu thực tế, từ đó cho phép chỉnh sửa trực tiếp (direct editing). Việc này chỉ có thể thực hiện được nếu menu ở định dạng "property list". Các menu ở định dạng văn bản thuần túy (plain text format) không thể chỉnh sửa được trong WPrefs. Hãy kiểm tra tệp "README" trong thư mục Window Maker để biết cách sử dụng định dạng này hay định dạng kia.

💠 **Gợi ý nhỏ cho bạn:** Nếu bạn đang mở WPrefs mà thấy phần này bị xám (không chỉnh sửa được), có khả năng file menu của bạn vẫn đang ở dạng script cũ. Bạn có thể dùng lệnh ```bash wmmenugen ``` để tạo lại menu mới tương thích với giao diện đồ họa này đấy!



<a name="#keyboard-shortcut"></a>
Keyboard shortcut
----------------------
<p align="left">
  <img src="/img/prefs11.png" alt="">
</p>

Thiết lập phím tắt bàn phím trong WPrefs.app

Nhiều hành động trong Window Maker đã được định nghĩa sẵn các phím tắt bàn phím. Các hành động này chủ yếu liên quan đến cửa sổ và không gian làm việc. Việc thay đổi, thêm hoặc xóa các phím tắt có thể được thực hiện trong bảng điều khiển này. Việc định nghĩa một phím tắt có thể được thực hiện một cách tương tác (interactively), thông qua việc ghi lại (capturing) tổ hợp phím.

<a name="#mouse"></a>
Mouse
----------------------
<p align="left">
  <img src="/img/prefs12.png" alt="">
</p>

Cấu hình chuột trong WPrefs.app

"Mouse grab modifier" đại diện cho phím tắt bàn phím được sử dụng cho các hành động như kéo (dragging) cửa sổ bằng chuột hoặc nhấp chuột bên trong cửa sổ. "Mod1 (Alt)" là giá trị mặc định.

Bảng điều khiển này thiết lập tốc độ chuột và độ trễ nhấp đúp. Các liên kết nút chuột có thể được định nghĩa và có thể được vô hiệu hóa hoặc kích hoạt.

Thiết lập mặc định liên kết nút chuột phải với menu ứng dụng, nút giữa với menu danh sách cửa sổ và nút trái với việc chọn cửa sổ (tiêu điểm (focus)). Tất nhiên, với loại chuột hai nút, liên kết nút giữa sẽ không hoạt động. Tuy nhiên, trên một số hệ điều hành, việc nhấn cả hai nút cùng lúc sẽ cho kết quả tương tự như khi sử dụng nút giữa.

Bắt đầu từ phiên bản 0.65 trở đi, con lăn chuột có thể được sử dụng để chuyển đổi (switch) không gian làm việc. Đây không phải là hành vi mặc định và phải được kích hoạt tại đây.

Nếu chuột có nhiều hơn 3 nút và/hoặc có con lăn nghiêng (tilt), chúng có thể được liên kết với một số hành động nhất định.

<a name="#appearance"></a>
Appearance
----------------------
<p align="left">
  <img src="/img/prefs13.png" alt="">
</p>

Thiết lập giao diện trong WPrefs.app

Trong bảng điều khiển này, mọi thứ liên quan đến giao diện của GUI (ngoại trừ màu nền hoặc hình nền) đều có thể được cấu hình. Cửa sổ, menu và biểu tượng có thể có "texture" (kết cấu) nền riêng, nghĩa là các kiểu độ dốc màu (color gradients) khác nhau có thể được cấu hình tại đây. "Texture", màu sắc, kiểu menu và căn lề tiêu đề có thể được tùy chỉnh hoàn toàn.

<a name="#font-configuration"></a>
Font configuration
----------------------
<p align="left">
  <img src="/img/prefs14.png" alt="">
</p>

Các tùy chọn cấu hình phông chữ trong Wprefs.app

Bảng điều khiển này cho phép bạn cấu hình phông chữ cho thanh tiêu đề của cửa sổ và menu, cho phần văn bản nội dung của menu, và cho văn bản của biểu tượng cũng như "clip". Ngoài ra, một phông chữ có thể được định nghĩa cho các thông điệp trên màn hình nền.

<a name="#expert-user"></a>
Expert user
----------------------
<p align="left">
  <img src="/img/prefs15.png" alt="">
</p>

Thiết lập dành cho người dùng chuyên gia trong WPrefs.app

Việc sử dụng bảng điều khiển này ngụ ý rằng bạn đã có những kiến thức nhất định. Rất nhiều tùy chọn có sẵn tại đây, bao gồm:
- Vô hiệu hóa các cửa sổ thu nhỏ (miniwindows) (hữu ích khi sử dụng cùng với KDE và GNOME)
- Sử dụng (hoặc không) "xset"
- Lưu phiên làm việc khi thoát (rất được khuyến khích!)
- Sử dụng "SaveUnder" trong các đối tượng khác nhau
- Sử dụng kiểu xoay vòng (cycling) cửa sổ dạng "Win" (được thêm từ phiên bản 0.63.0)
- Vô hiệu hóa bảng xác nhận cho lệnh "kill"
- Vô hiệu hóa việc làm nổi bật màu sắc khi xoay vòng (cycling) qua các biểu tượng
- Các tùy chọn liên quan đến đa màn hình (Multi head)
- Hút dính (snapping) vào cạnh màn hình

<a name="#editing-the-configuration-filer"></a>
Editing the configuration file
----------------------

Nếu cần thiết, tệp cấu hình mặc định nằm tại đường dẫn ``` $(HOME)/GNUstep/Defaults/WindowMaker ``` có thể được chỉnh sửa bằng tay. Tệp này là một cơ sở dữ liệu với cú pháp "property list". Khi bạn chọn một tùy chọn trong WPrefs.app, lựa chọn đó sẽ được ghi lại vào tệp này. Khi thay đổi tệp mặc định này, việc tuân thủ đúng cú pháp là vô cùng quan trọng.
> Lưu ý nhỏ: Vì đây là tệp dạng "property list" (plist), chỉ cần thiếu một dấu ngoặc hay dấu chấm phẩy cũng có thể khiến Window Maker không khởi động được giao diện người dùng. Bạn nên sao lưu tệp này trước khi chỉnh sửa thủ công nhé!

<a name="#windows"></a>
🛠️ Windows 🛠️
----------------------

- [Mô tả (Description)](#Description)
- [Tiêu điểm (Focusing)](#Focusing)
- [Sắp xếp lại (Reordering)](#Reordering)
- [Di chuyển (Moving)](#Moving)
- [Phóng to (Maximizing)](#Maximizing)
- [Thu nhỏ (Miniaturizing)](#Miniaturizing)
- [Thay đổi kích thước (Resizing)](#Resizing)
- [Cuộn lên (Shading)](#Shading)
- [Ẩn (Hiding)](#Hiding)
- [Đóng (Closing)](#Closing)
- [Menu lệnh (Commands menu)](#Commands-menu)

<a name="#Description"></a>
Description
----------------------

Bố cục chung của một cửa sổ:
- Thanh tiêu đề (Titlebar): Cung cấp tên của ứng dụng, tài liệu hoặc cửa sổ. Màu sắc của nó (thường là) cho biết trạng thái tiêu điểm (focus) (cửa sổ đang hoạt động hoặc không hoạt động). Tôi nói là (thường là) vì một số kiểu dáng và chủ đề không cung cấp các màu sắc khác nhau cho cửa sổ được lấy tiêu điểm (focused) hoặc không được lấy tiêu điểm (unfocused) - mặc dù trường hợp này rất hiếm (và tôi xin nói thêm là, thật tàn nhẫn!).
- Nút thu nhỏ (Miniaturize button): Nhấp vào nút bên trái của thanh tiêu đề sẽ tạo biểu tượng (iconifies) cho cửa sổ.
- Nút đóng (Close button): Nhấp vào nút bên phải của thanh tiêu đề sẽ đóng cửa sổ hoặc buộc dừng ứng dụng.
- Thanh thay đổi kích thước (Resizebar): Phần dưới cùng của cửa sổ. Kéo (dragging) thanh thay đổi kích thước bằng chuột sẽ thay đổi kích thước (resizes) cửa sổ.
- Vùng ứng dụng (Client area): Nội dung của cửa sổ. Nó có thể là một ứng dụng, một đoạn văn bản, một bức tranh...

<a name="#Focusing"></a>
Focusing
----------------------

Một cửa sổ có thể ở hai trạng thái: được lấy tiêu điểm (focused) hoặc không được lấy tiêu điểm (unfocused). Cửa sổ được lấy tiêu điểm (focused) là cửa sổ đang hoạt động, là cửa sổ nhận các thao tác phím. Thanh tiêu đề của nó có một màu sắc khác biệt (thường là vậy!). Các cửa sổ hộp thoại hoặc bảng điều khiển được mở từ một cửa sổ chính sẽ tự động nhận tiêu điểm. Ngay sau khi chúng được đóng lại, cửa sổ chính sẽ nhận lại tiêu điểm.   

Một cửa sổ có thể ở hai trạng thái: được lấy tiêu điểm (focused) hoặc không được lấy tiêu điểm (unfocused). Cửa sổ được lấy tiêu điểm (focused) là cửa sổ đang hoạt động, là cửa sổ nhận các thao tác phím. Thanh tiêu đề của nó có một màu sắc khác biệt (thường là vậy!). Các cửa sổ hộp thoại hoặc bảng điều khiển được mở từ một cửa sổ chính sẽ tự động nhận tiêu điểm. Ngay sau khi chúng được đóng lại, cửa sổ chính sẽ nhận lại tiêu điểm.   

Có hai chế độ sẵn có để lấy tiêu điểm (focus) cho một cửa sổ:
- Chế độ "Click to focus": nhấp vào bất kỳ phần nào của cửa sổ để kích hoạt nó.
- Chế độ "Focus follows mouse": di chuyển con trỏ chuột lên trên cửa sổ để kích hoạt nó.

<a name="#Reordering"></a>
Reordering
----------------------

Các cửa sổ có thể nằm đè lên nhau, trong trường hợp đó, một số cửa sổ sẽ che khuất toàn bộ hoặc một phần của các cửa sổ khác. Việc nhấp chuột trái vào thanh tiêu đề hoặc thanh thay đổi kích thước sẽ đưa cửa sổ đó ra "phía trước" (và cấp tiêu điểm (focus) cho cửa sổ đó). Chọn một cửa sổ từ menu danh sách cửa sổ cũng mang lại kết quả tương tự.   

Một số tổ hợp phím được cung cấp và rất hữu ích khi một cửa sổ bị ẩn đằng sau các cửa sổ khác:
- Phím Meta + nhấp chuột trái vào thanh tiêu đề:
Đưa cửa sổ ra phía sau và cấp tiêu điểm (focus) cho cửa sổ nằm trên cùng.
- Phím Meta + nhấp chuột trái vào vùng ứng dụng (client area):
Đưa cửa sổ ra phía trước và lấy tiêu điểm (focus) cho nó.
- Phím Meta + Phím Mũi tên Lên:
Đưa cửa sổ hiện đang được lấy tiêu điểm (focused) ra phía trước.
- Phím Meta + Phím Mũi tên Xuống:
Đưa cửa sổ hiện đang được lấy tiêu điểm (focused) ra phía sau.

Nhiều thuộc tính cửa sổ có thể được thay đổi từ bảng thuộc tính trong menu lệnh cửa sổ (bằng cách nhấp chuột phải vào thanh tiêu đề). Kể từ phiên bản 0.62.0, việc xoay vòng (cycling) cửa sổ đã được thay đổi sang kiểu của Windows (Alt-Tab).

<a name="#Moving"></a>
Moving
----------------------

Việc nhấp vào thanh tiêu đề của một cửa sổ và kéo (dragging) nó bằng cách nhấn giữ nút chuột trái sẽ di chuyển cửa sổ đó. Hộp nhỏ ở giữa màn hình sẽ hiển thị vị trí hiện tại tính bằng "pixel" so với góc trên cùng bên trái của màn hình (+0 +0). Các tổ hợp phím bổ sung giúp việc thao tác linh hoạt hơn:
- Kéo thanh tiêu đề bằng nút chuột giữa: di chuyển cửa sổ mà không thay đổi thứ tự lớp (stacking order) của nó.
- Kéo thanh tiêu đề + phím Ctrl: di chuyển cửa sổ mà không lấy tiêu điểm (focusing) cho nó.
- Kéo vùng ứng dụng hoặc thanh thay đổi kích thước + phím Meta: di chuyển cửa sổ.

💠 **Bạn có biết?** Trong Window Maker, phím Meta thường mặc định là phím Alt trên bàn phím PC. Nếu bạn thấy tổ hợp phím này không hoạt động, có thể kiểm tra lại trong phần "Keyboard Shortcut Settings" mà chúng ta đã dịch ở trên để xem nó có bị gán cho phím khác (như phím Windows) không nhé!

<a name="#Maximizing"></a>
Maximizing
----------------------

- Nhấp đúp vào thanh tiêu đề trong khi giữ phím Ctrl: thay đổi kích thước chiều cao của cửa sổ lên toàn màn hình.
- Nhấp đúp vào thanh tiêu đề trong khi giữ phím Shift: thay đổi kích thước chiều rộng của cửa sổ lên toàn màn hình.
- Nhấp đúp vào thanh tiêu đề trong khi giữ cả hai phím Ctrl và Shift: thay đổi cả chiều cao và chiều rộng của cửa sổ lên toàn màn hình.
- Nhấp đúp vào thanh tiêu đề trong khi giữ phím Ctrl hoặc Shift (lần nữa): khôi phục kích thước ban đầu của cửa sổ.

Để ngăn một cửa sổ đã phóng to (maximized) che khuất "dock", tùy chọn "Keep on top" phải được chọn từ menu của "dock".

💠 **Mẹo nhỏ:** Nếu bạn muốn cửa sổ tự động tránh vùng không gian của "dock" mà không cần đặt "dock" luôn nổi lên trên, bạn có thể thiết lập "Workspace border" trong WPrefs.app để tạo một khoảng trống an toàn tại cạnh màn hình nơi đặt thanh "dock" của mình.

<a name="#Miniaturizing"></a>
Miniaturizing
----------------------

Việc nhấp vào nút thu nhỏ (nút bên trái trên thanh tiêu đề) sẽ thu gọn cửa sổ thành một cửa sổ thu nhỏ (miniwindow) bao gồm một biểu tượng và một tiêu đề, sau đó đặt nó ở phía dưới cùng của màn hình. Nhấn phím tắt đã được chỉ định cũng mang lại kết quả tương tự. (Mặc định là Meta + m.)

Cửa sổ thu nhỏ (miniwindow) khác với biểu tượng ứng dụng ở chỗ nó không thể được đưa vào dock (docked).
- Nhấp đúp vào miniwindow: khôi phục cửa sổ đã thu nhỏ về trạng thái ban đầu.
- Nhấp đúp chuột giữa vào biểu tượng ứng dụng: khôi phục tất cả các cửa sổ đã thu nhỏ và bị ẩn của ứng dụng đó.

💠 **Bạn có biết?** Trong Window Maker, các cửa sổ thu nhỏ này thường xếp hàng ngăn nắp ở đáy màn hình. Nếu bạn thấy chúng chiếm quá nhiều diện tích, bạn có thể cân nhắc sử dụng tính năng "Hiding" (Ẩn) để dọn dẹp không gian làm việc gọn gàng hơn mà vẫn giữ ứng dụng chạy ngầm.

<a name="#Resizing"></a>
Resizing
----------------------

Thanh thay đổi kích thước (resizebar) ở dưới cùng của cửa sổ được chia thành ba vùng: vùng đầu bên trái, vùng giữa và vùng đầu bên phải. Tùy thuộc vào vùng bạn nhấp vào, thao tác thay đổi kích thước sẽ bị giới hạn theo một hướng nhất định.
- Vùng giữa: Nhấp vào vùng giữa của thanh thay đổi kích thước và kéo (dragging) theo chiều dọc sẽ thay đổi chiều cao của cửa sổ.
- Vùng trái hoặc phải: Nhấp vào một trong hai vùng đầu và kéo (dragging) theo chiều ngang sẽ thay đổi chiều rộng của cửa sổ.
- Kéo với phím Shift: Nhấn giữ phím Shift trong khi kéo cũng mang lại kết quả tương tự như trên.
- Kéo theo đường chéo: Nhấp vào một trong hai vùng đầu và kéo (dragging) theo đường chéo sẽ thay đổi cả chiều cao và chiều rộng.

Các tổ hợp phím cung cấp thêm nhiều lựa chọn:
- Phím Meta + nhấp chuột phải vào vùng ứng dụng (client area) và kéo: Thay đổi kích thước cửa sổ.
- Nút chuột giữa + kéo thanh thay đổi kích thước: Thay đổi kích thước cửa sổ mà không đưa nó ra phía trước.
- Phím Ctrl + kéo thanh thay đổi kích thước: Thay đổi kích thước cửa sổ mà không lấy tiêu điểm (focusing) cho nó.

💠 **Gợi ý:** Nếu bạn thấy thanh ``` resizebar ``` này hơi khó bấm trúng (vì nó thường khá mỏng), bạn có thể dùng tổ hợp phím Alt + Chuột phải (phím Meta mặc định) ở bất kỳ đâu bên trong cửa sổ để thay đổi kích thước nhanh hơn nhiều đấy!

<a name="#Shading"></a>
Shading
----------------------

Việc nhấp đúp vào thanh tiêu đề của một cửa sổ sẽ cuộn (shades) nó lại. Điều này có nghĩa là cửa sổ sẽ cuốn lên chỉ còn lại thanh tiêu đề. Một cửa sổ đã cuộn có hầu hết các thuộc tính giống như một cửa sổ bình thường: nó vẫn có thể được thu nhỏ hoặc đóng lại.

Kể từ phiên bản 0.80.0, bạn có thể cuộn lên/hạ xuống (shade/unshade) một cửa sổ bằng cách sử dụng con lăn chuột trên thanh tiêu đề của nó. Tất nhiên, điều này giả định rằng hệ thống của bạn có khả năng quản lý con lăn chuột.

Tệp ``` WMGLOBAL ``` trong thư mục ``` $HOME/GNUstep/Defaults ``` của bạn nên chứa hai chỉ thị mới: ``` MouseWheelUp ``` và ``` MouseWheelDown ```

<a name="#Hiding"></a>
Hiding
----------------------

Việc nhấp chuột phải vào nút thu nhỏ (nút bên trái trên thanh tiêu đề) sẽ ẩn ứng dụng đó đi. Sử dụng nút chuột giữa sẽ hiện (unhides) ứng dụng, đồng thời mở menu danh sách cửa sổ và chọn ứng dụng đang ẩn. (Trên một số hệ điều hành, việc nhấn cả hai nút cùng lúc với loại chuột hai nút sẽ mang lại kết quả tương tự).

Nếu cách này không hiệu quả, hãy sử dụng tổ hợp phím F11 (mặc định) để mở menu danh sách cửa sổ.

💠  **Sự khác biệt quan trọng:** Khác với "Miniaturizing" (thu nhỏ thành một biểu tượng nhỏ ở dưới màn hình), "Hiding" sẽ làm toàn bộ các cửa sổ của ứng dụng đó biến mất hoàn toàn khỏi không gian nhìn thấy, giúp màn hình của bạn cực kỳ gọn gàng. Bạn có thể tìm lại chúng nhanh chóng thông qua danh sách cửa sổ (F11).

<a name="#Closing"></a>
Closing
----------------------

Việc nhấp vào nút đóng (nút bên phải trên thanh tiêu đề) sẽ đóng cửa sổ đó lại. Khi nút đóng có hình dạng khác (không phải hình chữ X), điều đó có nghĩa là một ứng dụng đang chạy trong cửa sổ đó. Nhấp đúp vào nút đóng này sẽ buộc dừng (kills) ứng dụng. Thao tác này cũng có thể được thực hiện bằng cách nhấn giữ phím Ctrl + nhấp vào nút đóng.

Thông thường, việc thoát một ứng dụng từ bên trong (ví dụ: thông qua menu của chính ứng dụng đó) sẽ tốt hơn nhiều.

💠  **Lưu ý quan trọng:** Nút đóng có hình X: Thường dùng cho các cửa sổ phụ hoặc hộp thoại
- Nút đóng có hình ô vuông nhỏ (hoặc biểu tượng khác): Đại diện cho tiến trình chính của ứng dụng.

Việc "kill" ứng dụng bằng cách nhấp đúp là biện pháp mạnh tay (giống như ```xkill```), nó có thể khiến bạn mất dữ liệu chưa kịp lưu. Vì vậy, hãy luôn ưu tiên sử dụng lệnh Exit hoặc Quit trong menu của ứng dụng trước nhé!

<a name="#Commands-menu"></a>
Commands menu
----------------------

Việc nhấp chuột phải vào thanh tiêu đề của một cửa sổ sẽ mở ra một menu chứa các lệnh áp dụng riêng cho cửa sổ đó. Tổ hợp phím Ctrl + Esc có thể được sử dụng để thay thế cho việc nhấp chuột vào thanh tiêu đề. Phím Esc dùng để đóng menu này.

💠  **Bạn nên biết:** menu này là "cứu cánh" khi bạn cần tinh chỉnh nhanh một cửa sổ cụ thể. Tại đây, bạn có thể tìm thấy các tùy chọn nâng cao như:
- Attributes: Chỉnh sửa thuộc tính chuyên sâu (như loại bỏ thanh tiêu đề, làm cửa sổ luôn nổi trên cùng).
- Options: Thiết lập các quy tắc riêng cho ứng dụng đó (ví dụ: luôn mở ở một không gian làm việc nhất định).
- Kill: Buộc dừng ứng dụng nếu nó bị treo.

### Danh sách các lệnh trong menu lệnh (Commands Menu):
- Phóng to/Thu nhỏ (Maximize/Unmaximize): Phóng đại cửa sổ lên toàn màn hình hoặc đưa cửa sổ trở về kích thước ban đầu.
- Thu nhỏ (Miniaturize): Thu gọn cửa sổ thành một cửa sổ thu nhỏ (miniwindow). Phím tắt mặc định là Meta + m.
- Cuộn/Hạ xuống (Shade/Unshade): Cuộn cửa sổ lên (chỉ còn thanh tiêu đề) hoặc hạ nó xuống lại.
- Ẩn (Hide): Ẩn tất cả các cửa sổ của ứng dụng đó. Nhấp vào biểu tượng ứng dụng (appicon) để hiện lại các cửa sổ.
- Ẩn các cửa sổ khác (Hide Others): Từ phiên bản 0.80.1, bạn có thể ẩn tất cả các cửa sổ khác ngoại trừ cửa sổ hiện tại. Sử dụng menu danh sách cửa sổ để hiện lại bằng cách chọn cửa sổ bạn muốn hiển thị.
- Thay đổi kích thước/Di chuyển (Resize/Move): Khi tùy chọn này được chọn, cửa sổ đã sẵn sàng để được di chuyển hoặc thay đổi kích thước (một hộp nhỏ chứa tọa độ sẽ hiển thị bên trong cửa sổ). Nhấp vào thanh tiêu đề để hủy chọn tùy chọn này.
- Chọn (Select): Dùng để chọn cửa sổ, sau đó có thể di chuyển hoặc thay đổi kích thước... Chọn lại tùy chọn này một lần nữa sẽ hủy chọn cửa sổ.
- Chuyển đến (Move to): Cho phép chuyển cửa sổ sang một không gian làm việc khác (nếu có!).
- Thuộc tính (Attributes): Mở bảng thuộc tính để chỉnh sửa các đặc tính và tùy chọn cho cửa sổ. Bảng này có 5 phần chính:

### 1. Định danh cửa sổ (Window specification) 
Xác định rằng cấu hình sẽ áp dụng cho các cửa sổ có thuộc tính ```WM_CLASS``` khớp với tên được chọn. Điều này cần thiết vì các cửa sổ có thể có tên tiêu đề khác nhau nhưng cùng một lớp ứng dụng. Từ phiên bản 0.65.0, bạn có thể nhấp chọn trực tiếp cửa sổ để lấy đúng định danh.
### 2. Thuộc tính cửa sổ (Window attributes)
Cho phép bạn đánh dấu chọn để:
- Vô hiệu hóa thanh tiêu đề (disable titlebar)
- Vô hiệu hóa thanh thay đổi kích thước (disable resizebar)
- Vô hiệu hóa nút đóng (disable close button)
- Vô hiệu hóa nút thu nhỏ (disable miniaturize button)
- Vô hiệu hóa đường viền (disable border)
- Luôn nổi trên cùng (keep on top)
- Luôn nằm dưới cùng (keep at bottom)
- Xuất hiện trên mọi không gian làm việc (omnipresent)
- Khởi chạy ở trạng thái thu nhỏ (start miniaturized)
- Khởi chạy ở trạng thái phóng to (start maximized)
- Phóng to toàn màn hình (full screen maximization)
### 3. Tùy chọn nâng cao (Advanced options)
- Không gán phím tắt (don't bind keyboard shortcuts)
- Không nhận nhấp chuột (don't bind mouse clicks)
- Không hiển thị trong danh sách cửa sổ (don't show in the window list)
- Không cho phép cửa sổ nhận tiêu điểm (don't let the window take focus)
- Giữ cửa sổ luôn nằm trong màn hình (keep inside screen)
- Bỏ qua lệnh "Ẩn các cửa sổ khác" (ignore "Hide others")
- Bỏ qua lệnh "Lưu phiên làm việc" (ignore "Save session")
- Mô phỏng biểu tượng ứng dụng (emulate application icon)
### 4. Biểu tượng và Không gian làm việc ban đầu (Icon and initial workspace)
- Chọn biểu tượng bằng cách duyệt thư mục.
- Bỏ qua biểu tượng do ứng dụng cung cấp (ignore client supplied icon).
- Xác định không gian làm việc mặc định khi khởi chạy.
### 5. Đặc thù ứng dụng (Application specific)
- Khởi chạy ở trạng thái ẩn hoặc không có biểu tượng ứng dụng.
- Gom nhóm các biểu tượng ứng dụng (từ phiên bản 0.65.0).
- Từ phiên bản 0.80.0, tùy chọn "Shared application icon" (Biểu tượng ứng dụng dùng chung) thay thế cho việc gom nhóm. Bạn có thể mở nhiều cửa sổ từ cùng một ứng dụng nhưng chỉ có một biểu tượng duy nhất trên màn hình.
- Tùy chọn (Options): menu con (Submenu) cho phép:
  - Giữ cửa sổ trên cùng/dưới cùng/mọi nơi.
  - Thiết lập phím tắt cho cửa sổ: Có 10 phím tắt khả dụng (được đặt tên là "Shortcut for window + số"). Khi nhấn phím tắt đã định nghĩa, tiêu điểm sẽ ngay lập tức được chuyển đến cửa sổ đó.
- Đóng (Close): Đóng cửa sổ.
- Buộc dừng (Kill): Buộc đóng ứng dụng. Đây là tùy chọn dự phòng cho các trường hợp khẩn cấp (ứng dụng bị treo).
💠  **Lời khuyên:** Phần Attributes là nơi mạnh mẽ nhất của Window Maker. Nếu bạn muốn một ứng dụng như trình nghe nhạc luôn nằm ở mọi không gian làm việc và không có thanh tiêu đề để tiết kiệm diện tích, đây chính là nơi để thiết lập!

