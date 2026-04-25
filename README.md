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

## ⛩️ Giới thiệu (Introduction)
[Window Maker](https://github.com/window-maker/wmaker/) là một [trình quản lý cửa sổ](https://en.wikipedia.org/wiki/Window_manager) dành cho hệ thống [X11](https://vi.wikipedia.org/wiki/H%E1%BB%87_th%E1%BB%91ng_X_Window), ban đầu được thiết kế để hỗ trợ tích hợp cho môi trường máy tính [GNUstep](http://gnustep.org), dù nó hoàn toàn có thể hoạt động độc lập. Bằng mọi cách có thể, Window Maker tái hiện lại diện mạo và cảm giác sang trọng, tinh tế của giao diện người dùng [NeXTSTEP](https://en.wikipedia.org/wiki/NeXTSTEP) huyền thoại.

**Các tính năng chính của Window Maker:**
- Quản lý cửa sổ dạng xếp chồng (Stacking): Đi kèm với khả năng quản lý cửa sổ theo dạng lát gạch (tiling) bán tự động.
- Nhẹ và nhanh đến kinh ngạc: Tối ưu hóa hiệu suất tối đa cho hệ thống.
- Dễ sử dụng: Giao diện trực quan, không gây bối rối cho người mới.
- Khả năng tùy biến cực cao: Bạn có thể tinh chỉnh gần như mọi thành phần.
- Phím tắt linh hoạt: Khả năng gán phím tắt cho một loạt các hành động khác nhau.
- Menu động (Dynamic menus): Các mục trong menu có thể thay đổi nội dung dựa trên trạng thái hệ thống.
- Các ứng dụng nhỏ gọn ([Dockapps](https://www.dockapps.net/)): Những tiện ích nhỏ có thể gắn trực tiếp vào Dock (như đồng hồ, trình theo dõi CPU).
- Cấu hình thân thiện: Các tệp cấu hình dễ đọc đối với con người và có sẵn ứng dụng đồ họa (WPrefs.app) để chỉnh sửa trực quan.
- Miễn phí và mã nguồn mở: Hoàn toàn tự do sử dụng và sửa đổi.
- Cộng đồng năng động: Nhận được sự hỗ trợ từ người dùng trên toàn thế giới.

Nếu bạn là người yêu thích sự tối giản nhưng vẫn muốn có một chút âm hưởng của thập niên 90 (thời đại của máy tính **NeXT** mà **Steve Jobs** từng dẫn dắt), Window Maker chính là "cỗ máy thời gian" hoàn hảo nhất trên Linux hiện nay.

Thông tin trong bài hướng dẫn này dựa trên phiên bản Window Maker 0.95.3. Bạn hãy kiểm tra phiên bản mình đang dùng bằng cách mở **WPrefs.app** (công cụ Tùy chỉnh Window Maker). Số phiên bản được hiển thị ngay bên dưới tiêu đề "Window Maker Preferences" tại cửa sổ WPrefs chính. Bạn cũng có thể chạy lệnh wmaker --version trong cửa sổ terminal (không nhập dấu ngoặc kép). Lệnh này sẽ trả về số phiên bản Window Maker hiện đang được cài đặt trên máy.

## 📜 Mục lục
1. [Tùy chỉnh (Preferences)](#preferences)
2. [Cửa sổ (Windows)](#windows)
3. [Menus (Menus)](#menus)
4. [Dock](#dock)
5. [Clip](#clip)
6. [Hình nền và chủ đề (Backgrounds and themes)](#backgrounds-and-themes)
7. [Các mục khác (Miscellaneous)](#miscellaneous)
8. [Screenshot](#screenshot)

<a name="preferences"></a>
🛠️ Preferences
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
WINDOWS
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

<a name="#menus"></a>
Menus
----------------------
- [Danh sách các menu (Menu List)](#menu-list)
- [menu cửa sổ gốc (Root window menu)](#root-window-menu)
- [menu danh sách cửa sổ (Window list menu)](#window-list-menu)
- [menu không gian làm việc (Workspaces menu)](#workspaces-menu)
- [menu biểu tượng ứng dụng (Application icon menu)](#application-icon-menu)

💠 **Gợi ý:** Bạn có thể tùy chỉnh hoàn toàn nội dung của Root window menu bằng cách sử dụng WPrefs.app hoặc chỉnh sửa trực tiếp tệp cấu hình để tạo ra một danh sách các ứng dụng yêu thích theo ý mình đấy!

<a name="#menu-list"></a>
Menu List
----------------------
- menu cửa sổ gốc (Root window menu): Đây là menu chính của hệ thống, xuất hiện khi bạn nhấp chuột phải vào vùng trống trên màn hình nền (desktop). Nó thường chứa các lệnh chạy ứng dụng, cấu hình hệ thống và thoát chương trình.
- menu danh sách cửa sổ (Window list menu): Hiển thị danh sách tất cả các cửa sổ đang mở trên tất cả các không gian làm việc. Giúp bạn chuyển đổi nhanh giữa các ứng dụng hoặc hiện lại các cửa sổ đang bị ẩn.
- menu không gian làm việc (Workspaces menu): Cho phép bạn quản lý, thêm mới, xóa hoặc di chuyển nhanh giữa các màn hình ảo (workspaces).
- menu biểu tượng ứng dụng (Application icon menu): Xuất hiện khi bạn nhấp chuột phải vào biểu tượng của một ứng dụng đang chạy (nằm ở phía dưới màn hình hoặc trong Dock). menu này chứa các lệnh đặc thù cho ứng dụng đó như ẩn, đóng hoặc thiết lập thuộc tính biểu tượng.

💠 **Gợi ý:** Bạn có thể tùy chỉnh hoàn toàn nội dung của Root window menu bằng cách sử dụng WPrefs.app hoặc chỉnh sửa trực tiếp tệp cấu hình để tạo ra một danh sách các ứng dụng yêu thích theo ý mình đấy!

<a name="#root-window-menu"></a>
Root window menu
----------------------
<p align="left">
  <img src="/img/menu_applications.png" alt="">
</p>

Root window menu (applications menu)  

menu cửa sổ gốc (còn gọi là menu ứng dụng) được mở bằng cách nhấp chuột phải vào một vùng trống trên không gian làm việc hoặc nhấn tổ hợp phím tắt đã được thiết lập sẵn (mặc định là F12).

menu này dùng để:
- Khởi chạy các ứng dụng.
- Tùy chỉnh không gian làm việc (thay đổi hình nền, chủ đề/themes...).
- Quản lý các đặc tính khác của không gian làm việc bằng các tiện ích X tiêu chuẩn (như ```xprop```, ```xfontsel```, ```xcmap```...).

**Cấu hình menu**
Nội dung của menu hoàn toàn có thể cấu hình được, bằng cách sử dụng WPrefs.app hoặc chỉnh sửa trực tiếp tệp menu dạng văn bản thuần túy (plain text). Hướng dẫn cách cấu hình cho từng phương thức có thể được tìm thấy trong thư mục WindowMaker của bản phân phối.

**Lưu ý kỹ thuật:** Để sử dụng được WPrefs.app, các menu phải ở định dạng "property list" (```plmenu```). Nếu bạn đang có một menu dạng văn bản cũ, bạn có thể sử dụng một công cụ chuyển đổi có sẵn tên là ```wm-oldmenu2new``` để chuyển sang định dạng mới này.

💠 **Mẹo nhỏ:** Nếu bạn thường xuyên cài đặt phần mềm mới, việc học cách biên tập tệp ```plmenu``` sẽ giúp bạn sắp xếp các ứng dụng vào từng mục (như Internet, Graphics, Editors) một cách khoa học và nhanh chóng hơn nhiều so với việc dùng giao diện đồ họa đấy!

<a name="#window-list-menu"></a>
Window list menu
----------------------
<p align="left">
  <img src="/img/menu_window_list.png" alt="">
</p>

menu danh sách cửa sổ (Window list menu)

Việc nhấp chuột giữa vào một vùng trống trên không gian làm việc sẽ mở menu danh sách cửa sổ. Với chuột hai nút, nhấp cả hai nút cùng lúc thường sẽ cho kết quả tương tự. F11 là phím tắt mặc định để mở menu này.

menu này liệt kê tất cả các cửa sổ — dù đang hoạt động hay không — trên mọi không gian làm việc.
- Vị trí cửa sổ: Tên của không gian làm việc chứa cửa sổ đó được hiển thị ở bên phải tên cửa sổ.
- Cửa sổ hiện tại: Cửa sổ đang được lấy tiêu điểm (focus) sẽ được đánh dấu bằng một ký hiệu hình kim cương (♦) ở bên trái tên cửa sổ.
- Thao tác nhanh: Nhấp vào bất kỳ cửa sổ nào trong danh sách sẽ ngay lập tức lấy tiêu điểm cho cửa sổ đó, đưa nó lên phía trước và đưa bạn đến đúng không gian làm việc nơi cửa sổ đó đang tọa lạc.

💠 **Mẹo nhỏ:** Đây là công cụ hữu ích nhất khi bạn bị "lạc" giữa hàng tá cửa sổ đang mở hoặc khi một ứng dụng bị ẩn mất mà bạn không nhớ nó đang ở màn hình ảo nào. Chỉ cần nhấn F11, bạn sẽ có cái nhìn toàn cảnh về mọi thứ đang chạy trên hệ thống của mình.

<a name="#workspaces-menu"></a>
Workspaces menu
----------------------
<p align="left">
  <img src="/img/menu_workspaces.png" alt="">
</p>

**menu không gian làm việc (Workspaces menu)**
menu không gian làm việc là một phần của menu gốc (menu ứng dụng). Mục này có ba tùy chọn chính: New (Mới), Destroy last (Xóa mục cuối) và Last used (Sử dụng gần đây nhất).
- New: Tạo một không gian làm việc mới và tự động chuyển bạn sang đó.
- Destroy last: Xóa không gian làm việc cuối cùng trong danh sách, với điều kiện không có cửa sổ nào đang mở bên trong nó.
- Last used: Chuyển về không gian làm việc mà bạn vừa truy cập trước đó.

Mỗi không gian làm việc sẽ có một mục tương ứng trong menu này. Không gian làm việc đang hoạt động được đánh dấu bằng một hình kim cương ở bên trái tên hoặc số thứ tự. Nhấp vào bất kỳ mục nào sẽ giúp bạn chuyển đổi nhanh giữa các màn hình ảo.
**Cách đổi tên không gian làm việc:**
1. "Ghim" (stick) menu bằng cách nhấp chuột trái vào thanh tiêu đề của menu đó.
2. Nhấn giữ Ctrl + nhấp chuột vào mục muốn đổi tên để chuyển sang chế độ chỉnh sửa.
3. Nhập tên mới và nhấn Enter để lưu (hoặc Escape để hủy).

**Phím tắt di chuyển:**
Thông thường, bạn có thể sử dụng tổ hợp phím Meta + (Số) để di chuyển. Phím Meta thường là phím Alt, và (Số) tương ứng với số thứ tự của không gian làm việc.
- Ví dụ: Meta + 2 để chuyển nhanh sang không gian làm việc số 2.

Các phím tắt này có thể được thiết lập hoặc thay đổi trong hộp thoại "Keyboard Shortcut" của WPrefs.app.
💠 **Bạn có biết?** Window Maker hỗ trợ số lượng không gian làm việc gần như không giới hạn. Việc đặt tên riêng cho từng không gian (ví dụ: "Work", "Web", "Music") kết hợp với phím tắt sẽ giúp năng suất làm việc của bạn tăng lên đáng kể đấy!

<a name="#application-icon-menu"></a>
Application icon menu
----------------------
<p align="left">
  <img src="/img/menu_application_icon.png" alt="">
</p>

menu biểu tượng ứng dụng (Application icon menu)

Nhấp chuột phải vào một biểu tượng trong Dock sẽ mở ra một menu để tùy chỉnh ứng dụng đó. Đối với các ứng dụng đã được đưa vào Dock (docked) nhưng chưa chạy, một số tùy chọn sẽ bị mờ đi (greyed out).

**1. menu con của Dock (Dock submenu)**
Đây là các tùy chọn mang tính toàn cục cho Dock, bao gồm ba chế độ:
- Normal (Bình thường): Dock hoạt động mặc định; nó có thể bị các cửa sổ khác che khuất, và việc nhấp vào bất kỳ mục nào trên Dock sẽ đưa nó nổi lên trên.
- Auto raise & lower (Tự động nổi lên/ẩn xuống): Tương tự chế độ bình thường, nhưng bạn không cần nhấp chuột—chỉ cần di chuyển con trỏ chuột vào phần hiển thị của Dock hoặc các biểu tượng là nó sẽ tự động nổi lên.
- Keep on top (Luôn ở trên cùng): Dock sẽ luôn nằm trên tất cả các cửa sổ đang mở.
- Add a drawer (Thêm ngăn kéo): Thêm một biểu tượng đặc biệt dùng để nhóm các ứng dụng lại với nhau. Xem phần Dock để biết thêm chi tiết về "drawers".

**2. Các lệnh thực thi**
- Launch (Chạy): Khởi chạy ứng dụng mà không cần nhấp đúp vào biểu tượng.
- Bring here (Đưa về đây): Hiện ứng dụng ngay tại không gian làm việc hiện tại của bạn.
- Hide (Ẩn): Ẩn ứng dụng hoặc hiện lại nếu nó đang ẩn. Khi hiện lại, ứng dụng sẽ xuất hiện tại đúng không gian làm việc mà nó đang tọa lạc. (Tùy chọn này có thể không hoạt động nếu ứng dụng có tính năng ẩn riêng trong menu của chính nó).
- Settings (Cài đặt): Cho phép sửa đổi đường dẫn ứng dụng, các tham số dòng lệnh và thay đổi biểu tượng hiển thị.
- Kill (Buộc dừng): Đóng ứng dụng ngay lập tức. Chỉ nên sử dụng khi thật sự cần thiết (như khi ứng dụng bị treo).

💠 **Có thể bạn chưa biết:** Tính năng "Settings" trong menu này cực kỳ hữu dụng để tùy biến giao diện. Bạn có thể gán bất kỳ hình ảnh ```.xpm``` hoặc ```.png``` nào cho biểu tượng ứng dụng để bộ Dock của mình trông cá tính và đồng bộ hơn!

<a name="#dock"></a>
DOCK
----------------------
Nội dung
- [Dock ứng dụng (Application dock)](#application-dock)
- [Khởi chạy ứng dụng (Starting an application)](#starting-an-application)
- [Tùy biến (Customizing)](#customizing)
- [Cấu hình (Configuring)](#configuring)

<a name="#application-dock"></a>
Application-dock
----------------------
Dock là một cột biểu tượng nằm mặc định ở phía bên phải của màn hình.

**Thêm và xóa ứng dụng**

Bất kỳ ứng dụng nào cũng có thể được gắn vào Dock. Để thực hiện:
1. Mở ứng dụng bạn muốn.
2. Nhấp chuột trái và kéo biểu tượng của ứng dụng đó (appicon) vào vị trí cuối cùng trên Dock.
3. Dock sẽ tự động "hút" biểu tượng đó vào. Nó sẽ nằm cố định ở đó cho đến khi bạn gỡ bỏ (bằng cách nhấp chuột trái và kéo biểu tượng ra khỏi Dock — nó sẽ biến mất).

Nếu bạn đã lưu phiên làm việc (session) trước khi đăng xuất (hoặc thiết lập Window Maker tự động lưu phiên), bất kỳ biểu tượng nào bạn đã gắn vào Dock sẽ tự động xuất hiện lại trong các lần đăng nhập tiếp theo.

**Cấu hình hiển thị**

Bạn có thể thiết lập để Dock luôn nằm trên các cửa sổ đã phóng to. Để thực hiện, nhấp chuột phải vào biểu tượng chính của Dock hoặc bất kỳ biểu tượng ứng dụng nào trên đó, sau đó chọn tùy chọn phù hợp từ menu con Dock position. ([Xem thêm phần Menu biểu tượng ứng dụng để biết chi tiết](https://github.com/slimulv1/huong-dan-wmaker/blob/main/#application-icon-menu)).

**Di chuyển và ẩn Dock**
- Đổi bên màn hình: Biểu tượng WMDock (mặc định có logo GNUstep) có thể được kéo sang ngang để chuyển toàn bộ Dock từ cạnh này sang cạnh kia của màn hình.
- Thu gọn Dock: Kéo biểu tượng WMDock xuống dưới sẽ đẩy toàn bộ Dock ra khỏi màn hình, ngoại trừ chính biểu tượng WMDock đó vẫn hiển thị.
- Khôi phục: Để hiển thị lại Dock, chỉ cần nhấp chuột trái và kéo biểu tượng đó trở lại màn hình.

💠 **Lưu ý:** Biểu tượng WMDock chính là "mỏ neo" của toàn bộ hệ thống Dock. Nếu bạn lỡ tay kéo nó đi quá xa, đừng lo lắng, chỉ cần tìm biểu tượng có hình logo GNUstep và kéo nó trở lại vị trí cũ là được!

<a name="#starting-an-application"></a>
Starting an application
----------------------
Việc nhấp đúp vào biểu tượng của một ứng dụng đã được gắn trên Dock sẽ khởi chạy ứng dụng đó.

**Nhận biết trạng thái qua biểu tượng**
Trạng thái của ứng dụng được thể hiện qua các dấu hiệu trực quan trên biểu tượng (icon):
- <p align="left"> <img src="/img/unlaunched_app.png" alt=""> </p> Ứng dụng chưa chạy: Một dấu ba chấm (...) sẽ xuất hiện ở góc dưới bên trái của biểu tượng và hình ảnh hiển thị đầy đủ màu sắc.
- <p align="left"> <img src="/img/launched_app.png" alt=""> </p> Ứng dụng đang chạy: Dấu ba chấm sẽ biến mất và biểu tượng sẽ được làm nổi bật (highlighted).
- <p align="left"> <img src="/img/grayed_out_icon.png" alt=""> </p> Biểu tượng bị mờ (Greyed out): Đôi khi, khi ứng dụng đang chạy, biểu tượng sẽ mờ đi thay vì nổi bật. Đây là tín hiệu cho biết ứng dụng đã mở và không thể khởi chạy thêm một bản sao (instance) nào nữa.

**Tùy chỉnh chạy nhiều bản sao**
Nếu một biểu tượng vẫn giữ nguyên dấu ba chấm và đầy đủ màu sắc ngay cả khi ứng dụng đã chạy, điều đó có nghĩa là cài đặt đã được thay đổi để cho phép chạy nhiều bản sao từ cùng một biểu tượng. Để thiết lập điều này, bạn mở ứng dụng, vào phần "Application specific" trong menu lệnh (commands menu) và chọn "Shared application icons".

Ngoài việc nhấp đúp, bạn cũng có thể sử dụng lệnh "Launch" trong menu biểu tượng ứng dụng để khởi động chương trình.

**Tính năng "Chiếm" biểu tượng (Icon Stealing)**
Kể từ phiên bản 0.80.0, Dock có tính năng "chiếm" (steal) các biểu tượng ứng dụng (appicons). Tính năng này khác với tính năng tự động thu hút biểu tượng (Autoattract Icons):
- hi bạn khởi chạy một ứng dụng từ bất kỳ đâu (như từ menu hoặc cửa sổ lệnh terminal) mà không phải từ Clip hay Dock, nếu biểu tượng của ứng dụng đó đã tồn tại sẵn trong Clip hoặc Dock, thì biểu tượng mới sẽ không xuất hiện ở dưới đáy màn hình nữa.
- Thay vào đó, biểu tượng đã có sẵn trong Clip hoặc Dock sẽ "chiếm" lấy tiến trình đó và hiển thị trạng thái đang chạy ngay tại vị trí của nó.

💠 **Có thể bạn chưa biết:** Tính năng "Icon Stealing" giúp màn hình của bạn cực kỳ sạch sẽ. Thay vì có hai biểu tượng giống hệt nhau (một cái cố định trên Dock và một cái tạm thời ở đáy màn hình), Window Maker sẽ gom chúng lại làm một để bạn dễ dàng quản lý!

<a name="#customizing"></a>
Customizing
----------------------
Việc nhấp chuột trái và kéo một biểu tượng ứng dụng (appicon) vào Dock sẽ thêm ứng dụng đó vào danh sách các ứng dụng được gắn cố định. Tất nhiên, điều này đồng nghĩa với việc ứng dụng đó hiện đang phải chạy thì bạn mới có biểu tượng để kéo!
- Lưu ý quan trọng: Các cửa sổ thu nhỏ (miniwindows - là cửa sổ của ứng dụng đã bị thu nhỏ xuống đáy màn hình) không thể được gắn vào Dock. Bạn có thể phân biệt chúng qua thanh tiêu đề nhỏ xuất hiện phía trên biểu tượng; các biểu tượng ứng dụng chuẩn (appicons) sẽ không có thanh tiêu đề này.
- Gỡ bỏ: Để xóa một ứng dụng khỏi Dock, bạn chỉ cần nhấp chuột trái và kéo biểu tượng đó ra khỏi phạm vi của Dock rồi thả tay ra.

💠 **Mẹo nhỏ:** Nếu bạn muốn đưa một ứng dụng vào Dock mà không muốn phải mở nó lên trước, bạn có thể kéo biểu tượng của nó từ một "Drawer" (ngăn kéo) khác hoặc cấu hình trực tiếp thông qua WPrefs.app. Hãy nhớ rằng Dock chỉ chấp nhận các biểu tượng ứng dụng thực thụ, không phải các cửa sổ đang chạy được thu nhỏ lại đâu nhé!

<a name="#configuring"></a>
Configuring
----------------------
Mỗi biểu tượng trên Dock đều có một menu riêng. Bạn nhấp chuột phải vào biểu tượng đó để hiển thị "menu biểu tượng ứng dụng" (Application icon menu), sau đó chọn mục "Settings..." để bắt đầu cấu hình.
<p align="left"> <img src="/img/docked_application_settings.png" alt=""> </p>

**Các tùy chỉnh trong bảng cài đặt:**
- Đường dẫn và Tham số: Bạn có thể thay đổi đường dẫn thực thi của ứng dụng, các tham số đi kèm, lệnh thực thi khi nhấp chuột giữa và biểu tượng hiển thị.
- Lưu ý về lệnh: Các lệnh Shell phức tạp (như điều hướng dòng lệnh >) không thể sử dụng trực tiếp trong trường nhập lệnh này.
- Thay đổi biểu tượng: Biểu tượng bạn muốn dùng phải nằm trong các thư mục được hiển thị trong bảng chọn khi duyệt tìm. Bạn có thể thêm các thư mục mới vào danh sách này thông qua phần [Search path](https://github.com/slimulv1/huong-dan-wmaker#search-path) trong bảng tùy chỉnh hệ thống.
- Tự động khởi chạy (Auto-launch): Có một ô đánh dấu cho phép ứng dụng tự động khởi động cùng lúc với Window Maker.
  - Lưu ý: Hãy cẩn thận với tính năng này! Nếu bạn đặt trình giả lập terminal, trình quản lý tệp và trình duyệt web tự khởi động, chúng sẽ đồng loạt mở ra mỗi khi bạn đăng nhập. Thông thường, bạn chỉ nên dùng tính năng này cho các dockapps (như đồng hồ hay trình theo dõi hệ thống).
- Chống gỡ bỏ: Từ phiên bản 0.62.0, một ô đánh dấu mới đã được thêm vào để giúp ngăn chặn việc vô tình kéo biểu tượng ra khỏi Dock (khóa biểu tượng).
- Nhấp chuột giữa (Middle-click launch): Từ phiên bản 0.70.0, một trường mới đã được thêm vào cho phép gán lệnh khi nhấp chuột giữa. Ví dụ, nếu bạn nhập "firefox" vào trường này của một biểu tượng bất kỳ, trình duyệt Firefox sẽ khởi chạy khi bạn nhấp chuột giữa vào biểu tượng đó.

💠 **Mẹo nhỏ:** Việc tận dụng trường Middle-click launch là một cách tuyệt vời để "giấu" một ứng dụng thứ hai vào cùng một biểu tượng trên Dock, giúp tiết kiệm không gian màn hình tối đa!

<a name="#clip"></a>
CLIP
----------------------
Theo mặc định, Clip được đại diện bởi một biểu tượng ở góc trên cùng bên trái của màn hình với hình ảnh một chiếc kẹp giấy.
<p align="left"> <img src="/img/clip.png" alt=""> </p>

Clip có hai chức năng chính sau đây:

**1. Dock riêng cho từng không gian làm việc**
Chức năng chính của Clip là đóng vai trò như một chiếc Dock dành riêng cho từng không gian làm việc cụ thể. Nói cách khác, bạn có thể gắn các ứng dụng vào Clip giống hệt như cách làm với Dock, nhưng Clip và các ứng dụng đi kèm với nó chỉ xuất hiện trên không gian làm việc đó — chúng không hiển thị trên tất cả các màn hình ảo như Dock chính.

**2. Bộ chuyển đổi không gian làm việc (Pager)**
Chức năng thứ hai của Clip là hoạt động như một "pager" — một tiện ích để chuyển đổi qua lại giữa các không gian làm việc.
- Mũi tên góc trên bên phải: Chuyển sang không gian làm việc tiếp theo.
- Mũi tên góc dưới bên trái: Quay lại không gian làm việc trước đó.

Tên của không gian làm việc hiện tại (nếu có) và số thứ tự của nó sẽ được hiển thị ngay trên biểu tượng Clip.

Ngoài ra, Clip còn sở hữu một loạt các tính năng khác được điều khiển thông qua menu (menu) khi bạn nhấp chuột phải vào nó.

💠 **Bạn có biết?** Sự khác biệt lớn nhất giữa Dock và Clip là tính "toàn cục":
- Dock: Giữ các ứng dụng bạn muốn dùng ở mọi nơi (như Trình duyệt, Terminal).
- Clip: Giữ các ứng dụng phục vụ cho tác vụ cụ thể trên không gian đó (ví dụ: Workspace "Đồ họa" sẽ có Clip chứa GIMP và Inkscape, trong khi Workspace "Lập trình" sẽ có Clip chứa IDE và Debugger).

### Clip Menu
<p align="left"> <img src="/img/menu_clip.png" alt=""> </p>

Khi bạn nhấp chuột phải vào biểu tượng Clip, một menu sẽ hiện ra với các tùy chọn quản lý mạnh mẽ. menu này bao gồm các mục sau:
- Workspace (Không gian làm việc): menu con này cho phép bạn quản lý các không gian làm việc (thêm mới, xóa hoặc chuyển đổi), tương tự như menu không gian làm việc chính.
- Rename (Đổi tên): Cho phép bạn đặt lại tên cho không gian làm việc hiện tại ngay trên biểu tượng Clip.
- Selected (Lựa chọn): Các tùy chọn áp dụng cho các biểu tượng ứng dụng đang được chọn trong Clip.
- Keep on top (Luôn ở trên cùng): Thiết lập để Clip luôn nổi trên các cửa sổ ứng dụng, giúp bạn dễ dàng chuyển đổi không gian làm việc.
- Collapsed (Thu gọn): Thu nhỏ Clip lại chỉ còn biểu tượng chính để tiết kiệm diện tích màn hình.
- Autocollapse (Tự động thu gọn): Clip sẽ tự động thu gọn khi bạn không sử dụng và chỉ mở ra khi bạn di chuột qua.
- Autoattract Icons (Tự động thu hút biểu tượng): Đây là một tính năng cực kỳ thú vị. Khi được kích hoạt, bất kỳ ứng dụng nào bạn khởi chạy trong không gian làm việc này (mà chưa được gắn vào Dock) sẽ tự động được "hút" và gắn vào Clip. Điều này giúp bạn gom nhóm các ứng dụng đang làm việc theo từng dự án một cách tự động.

💠 **Sự kết hợp hoàn hảo:** Tính năng Autocollapse kết hợp với Autoattract Icons biến Clip thành một "ngăn chứa thông minh". Nó tự động thu thập các công cụ bạn đang dùng và ẩn mình đi khi bạn cần tập trung vào cửa sổ chính, giúp không gian làm việc luôn ngăn nắp nhưng vẫn cực kỳ tiện lợi!

### Clip Option
Mục đầu tiên trong menu cho phép bạn thiết lập các tùy chọn cho Clip. Các tùy chọn cụ thể bao gồm:
- Luôn nổi trên cùng (Keep on top): Không cho phép các cửa sổ khác che khuất biểu tượng Clip.
- Thu gọn (Collapsed): Các biểu tượng ứng dụng được gắn vào Clip sẽ bị ẩn đi cho đến khi bạn nhấp chuột trái vào Clip để hiển thị chúng.
- Tự động thu gọn (Autocollapse): Tương tự như tùy chọn trên, nhưng các biểu tượng ứng dụng sẽ tự động hiện ra khi bạn di chuột qua Clip.
- Tự động đưa lên trên (Autoraise): Khi bạn nhấp vào biểu tượng đại diện cho một cửa sổ đang bị che khuất bởi một cửa sổ lớn hơn, cửa sổ đó sẽ ngay lập tức được đưa lên phía trước.
- Tự động thu hút biểu tượng (Autoattract icons): Khi tùy chọn này được chọn, biểu tượng của bất kỳ ứng dụng nào được khởi chạy trên không gian làm việc hiện tại sẽ tự động được "hút" vào Clip. Khi ứng dụng đó đóng lại, biểu tượng của nó cũng sẽ tự động bị xóa khỏi Clip.

💠 **Mẹo nhỏ:** Tùy chọn Autoattract icons cực kỳ hữu ích khi bạn muốn biến mỗi không gian làm việc thành một "ngăn chứa" tạm thời cho các dự án khác nhau. Kết hợp với Autocollapse, bạn sẽ có một màn hình cực kỳ tối giản nhưng vẫn đầy đủ các phím tắt cho mọi ứng dụng đang mở!

### Rename Workspace
Mục này cho phép bạn đặt tên (hoặc đổi tên) cho không gian làm việc hiện tại.

Nhiều người dùng có thói quen nhóm các ứng dụng nhất định theo từng không gian làm việc và muốn đặt tên cho chúng để thể hiện tính chất của các ứng dụng đang được gắn trên Clip.

**Ví dụ:**
- Một người dùng có thể gắn trình duyệt web, phần mềm chat (IRC) và ứng dụng truyền tệp lên Clip của một không gian làm việc, sau đó đặt tên là "internet" để biểu thị chức năng chính của không gian đó.
- Người dùng đó cũng có thể có một không gian làm việc riêng biệt khác với các ứng dụng đồ họa vector, chỉnh sửa ảnh và trình xem ảnh trên Clip, và đặt tên không gian này là "graphics".

💠 **Cách thực hiện nhanh:** Ngoài việc dùng menu, bạn có thể nhấp chuột trái vào thanh tiêu đề của Clip (nếu nó đang được ghim) hoặc sử dụng tổ hợp phím Ctrl + Nhấp chuột vào tên không gian làm việc trên menu để chỉnh sửa trực tiếp.
Việc cá nhân hóa tên gọi này giúp bạn không còn phải nhớ máy móc "Workspace 1", "Workspace 2" mà có thể chuyển đổi thẳng tới môi trường làm việc mình cần đấy!

### Other Options
Khi bạn nhấp chuột phải vào một biểu tượng ứng dụng đã được gắn trên Clip, một menu chứa các tùy chọn dành riêng cho ứng dụng đó sẽ xuất hiện:
- Biểu tượng hiện diện khắp nơi (Omnipresent): Bạn có thể thiết lập để biểu tượng của ứng dụng đó xuất hiện trên Clip của tất cả các không gian làm việc
- Chọn biểu tượng: Bạn có thể chọn một hoặc tất cả các biểu tượng đang có trên Clip.
- Di chuyển: Cho phép bạn di chuyển một hoặc toàn bộ biểu tượng từ Clip này sang một không gian làm việc khác.
- Gỡ bỏ (Remove): Xóa biểu tượng ứng dụng khỏi Clip.
- Tự động thu hút (Autoattract): Bạn có thể chỉ thị cho Window Maker tự động thu hút tất cả các biểu tượng vào Clip ngay khi ứng dụng được khởi chạy, thay vì để chúng xuất hiện tại vị trí mặc định dưới đáy màn hình như ban đầu.

**Các tính năng tương tự Dock**
Các mục còn lại trong menu Clip tương tự như [menu biểu tượng ứng dụng của Dock](https://github.com/slimulv1/huong-dan-wmaker#dock). Giống như với Dock, các ứng dụng trên Clip có thể được:
- Khởi chạy (Launched), Ẩn (Hidden), hoặc Buộc dừng (Killed).
- Thay đổi các Cài đặt (Settings) như: hình ảnh biểu tượng, đường dẫn/tham số khởi chạy, và lệnh thực thi khi nhấp chuột giữa.

**Tính năng "Chiếm" biểu tượng (Icon Stealing)***
Kể từ phiên bản 0.80.0, Clip cũng có khả năng "chiếm" các biểu tượng ứng dụng. Tính năng này hoàn toàn độc lập với tính năng tự động thu hút biểu tượng:
- Khi bạn khởi chạy một ứng dụng từ một nguồn khác (như từ menu ứng dụng hoặc terminal) mà ứng dụng đó đã được gắn sẵn vào Clip hoặc Dock, một biểu tượng mới sẽ không xuất hiện ở dưới đáy màn hình.
- Biểu tượng đã tồn tại trên Clip hoặc Dock sẽ "chiếm" lấy vai trò quản lý ứng dụng đó. Kết quả là, biểu tượng cho ứng dụng vừa chạy chính là biểu tượng đã có sẵn trên Clip hoặc Dock của bạn.
- 
💠 **Mẹo nhỏ:** Việc sử dụng tính năng "Omnipresent" cho các ứng dụng như trình phát nhạc hay trình theo dõi tài nguyên hệ thống giúp bạn có thể điều khiển chúng từ bất kỳ không gian làm việc nào mà không cần phải chuyển màn hình ảo liên tục!

<a name="#backgrounds-and-themes"></a>
BACKGROUNDS AND THEMES
----------------------
### Nội Dung
- [Hình nền (Backgrounds)](#backgrounds)
- [Kiểu dáng (Styles)](#styles)
- [Chủ đề (Themes)](#themes)

Trong phạm vi của chuyến tham quan hướng dẫn này, chúng ta sẽ chỉ xem xét các tùy chọn diện mạo có sẵn (built-in) của Window Maker. Việc tự tay thiết kế các Kiểu dáng (Styles) và Chủ đề (Themes) tùy chỉnh không quá khó và cũng không đòi hỏi kiến thức lập trình hay kỹ năng chuyên môn đặc biệt, nhưng nội dung đó nằm ngoài phạm vi của bài hướng dẫn này.

Bạn có thể dễ dàng tùy biến giao diện đồ họa (GUI) của Window Maker thông qua mục "Appearance" trong menu ứng dụng.

**Cài đặt và sử dụng**
Các Chủ đề, Kiểu dáng, Bộ biểu tượng và Hình nền có thể được lựa chọn ngay khi chúng được cài đặt vào đúng thư mục quy định:
- Chủ đề (Themes): Cài đặt tại thư mục ```~/GNUstep/Library/WindowMaker/Themes/```
- Kiểu dáng (Styles): Cài đặt tại thư mục ```~/GNUstep/Library/WindowMaker/Styles/```
- Hình nền (Backgrounds): Cài đặt tại thư mục ```~/GNUstep/Library/WindowMaker/Backgrounds/```

**Các tài nguyên mặc định**
Nếu bạn đang sử dụng một phiên bản Window Maker mới cài đặt, bản phân phối Linux của bạn thường đã cung cấp sẵn một số chủ đề, kiểu dáng và hình nền mặc định. Trong một số trường hợp hiếm hoi, có những bản phân phối không cung cấp thêm bất kỳ tài nguyên nào và mong muốn người dùng tự bổ sung theo ý thích.

💠 **Mẹo nhỏ:** Nếu bạn không tìm thấy các thư mục trên trong thư mục cá nhân của mình, bạn có thể tự tạo chúng! Window Maker sẽ tự động nhận diện các tệp tin mới ngay khi bạn thêm chúng vào mà không cần phải khởi động lại hệ thống.

Dưới đây là hình ảnh minh họa cho menu "Appearance" cùng các menu con liên quan như chủ đề, kiểu dáng và hình nền:

<p align="left"> <img src="/img/appearancemenu.png" alt=""> </p>

Trong ảnh chụp màn hình phía trên, hầu hết các Kiểu dáng (Styles) đều là mặc định của bản phân phối Debian GNU/Linux, trong khi phần lớn các Chủ đề (Themes) là do người dùng tự cài đặt thêm. Hiện nay, có rất nhiều chủ đề đa dạng mà bạn có thể dễ dàng tải xuống từ Internet.

💠 **Thông tin thêm cho bạn:** Vì bạn đang sử dụng hệ thống Linux, các bản phân phối như Debian thường lưu trữ các tài nguyên mặc định của Window Maker trong thư mục hệ thống ```/usr/share/WindowMaker/```. Nếu bạn muốn cài đặt các chủ đề mới tải về để sử dụng cá nhân mà không cần quyền quản trị (root), hãy ưu tiên đưa chúng vào thư mục ```~/GNUstep/Library/WindowMaker/Themes/``` trong thư mục Home của mình nhé!

<a name="#backgrounds"></a>
BACKGROUNDS 
----------------------
Hình nền có thể là các màu đơn sắc hoặc màu chuyển sắc (gradient) do hệ thống tạo ra, hoặc có thể là các tệp hình ảnh do người dùng hoặc bản phân phối cung cấp.
**Cách thay đổi nhanh:**
- Màu sắc & Chuyển sắc: Cách dễ nhất để thay đổi màu nền đơn sắc hoặc hiệu ứng chuyển màu của hệ thống là chọn một mẫu từ menu:
```Appearance -> Background -> <Solid | Gradient>```
Trong hầu hết các cấu hình mặc định, sẽ có khoảng sáu đến tám lựa chọn sẵn có cho mỗi danh mục này.
- Hình ảnh: Tương tự, cách đơn giản nhất để đổi sang một hình nền phong cảnh hoặc ảnh nghệ thuật là chọn từ menu:
```Appearance -> Background -> Images```

**Sử dụng hình ảnh cá nhân:**
Nếu bạn muốn cài đặt các hình ảnh của riêng mình để làm hình nền, hãy đặt tệp hình ảnh đó vào thư mục:
```~/GNUstep/Library/WindowMaker/Backgrounds/```

Ngay sau khi bạn chép tệp vào đây, chúng sẽ xuất hiện trong menu để bạn lựa chọn mà không cần thực hiện thêm thao tác cấu hình phức tạp nào.

💠 **Gợi ý:** Nếu bạn có một bộ sưu tập ảnh độ phân giải cao, hãy thử định dạng .png hoặc .jpg để có chất lượng hiển thị tốt nhất trên màn hình của mình.

<a name="#styles"></a>
STYLES
----------------------

**Kiểu dáng (Styles)**
Một "Kiểu dáng" xác định diện mạo của các thành phần then chốt trên môi trường máy tính Window Maker. Các thành phần này bao gồm thanh tiêu đề (titlebar) và thanh thay đổi kích thước (resizebar) của cửa sổ, tiêu đề và phần văn bản của menu (menu), cũng như nền của các biểu tượng (icons).

**Đặc điểm của Style**
Các đặc tính được xác định trong một Style (hoặc Theme) bao gồm màu sắc và "kết cấu" (texture) của các yếu tố giao diện chính. "Kết cấu" trong ngữ cảnh này có nghĩa là việc sử dụng kết hợp nhiều màu sắc theo các hiệu ứng chuyển màu (gradients) khác nhau — bạn không bị giới hạn chỉ trong các màu đơn sắc.

**Cách thay đổi và tạo mới**
- Thay đổi nhanh: Cách đơn giản nhất để thay đổi là chọn một kiểu dáng có sẵn từ menu:
```Appearance -> Style```
- Tạo kiểu dáng riêng: Bạn có thể tạo một Style theo ý muốn bằng công cụ Appearance Preferences trong WPrefs.app. Với công cụ này, bạn có thể cấu hình:
  - Màu sắc và kết cấu của các thành phần cửa sổ (thanh tiêu đề, thanh thay đổi kích thước).
  - Các thành phần của menu (thanh tiêu đề menu, màu chữ của các mục, "kiểu" menu).
  - Màu sắc và kết cấu nền của biểu tượng.
  - Vị trí văn bản trên thanh tiêu đề, cũng như phông chữ và màu chữ cho cả cửa sổ và menu.

💠 **Mẹo nhỏ:** Nếu bạn đang tùy chỉnh trong WPrefs.app, hãy chú ý đến phần Texture. Bạn có thể chọn các kiểu như Symmetric Gradient, Diagonal Gradient, hoặc Interlaced để tạo ra vẻ ngoài bóng bẩy và hiện đại hơn cho các thanh tiêu đề cửa sổ đấy!

<p align="left"> <img src="/img/prefs13.png" alt=""> </p>

<a name="#themes"></a>
THEMES
----------------------
Ở dạng cơ bản nhất, một "Chủ đề" đơn giản là một Kiểu dáng (Style) có bao gồm cả hình nền. Một số bản phân phối Linux cung cấp sẵn một hoặc nhiều chủ đề mặc định để sử dụng trên toàn hệ thống. Bạn có thể tự cài đặt các chủ đề của riêng mình vào thư mục ```~/GNUstep/Library/WindowMaker/Themes/```. Các chủ đề được đặt đúng thư mục sẽ xuất hiện trong menu``` Appearance -> Themes.```

Khi bạn chọn một Chủ đề từ menu này, hệ thống sẽ chạy chương trình ```setstyle``` để thiết lập giao diện và ghi lại cấu hình đó vào tệp ```~/GNUstep/Defaults/WindowMaker```.
**Tìm kiếm và Cài đặt**
- Có rất nhiều chủ đề được cấu hình sẵn trên Internet. Bạn có thể tìm kiếm với từ khóa "Window Maker themes" để có thêm nhiều kết quả.
- Hãy kiểm tra kho lưu trữ (repositories) của bản phân phối Linux bạn đang dùng — một số nơi cung cấp sẵn các gói chủ đề để cài đặt thông qua trình quản lý gói (như ```apt```, ```pacman```, ```dnf```...).

**Cấu trúc của một Chủ đề**
Các chủ đề có thể bao gồm hình ảnh định dạng ```.png```, .```jpg```, ```.xpm``` và các định dạng hỗ trợ khác cho các thành phần chính của giao diện như thanh tiêu đề, nền biểu tượng và hình nền không gian làm việc.
- Thư mục chủ đề: Vì bao gồm các tệp hình ảnh, một chủ đề không thể được lưu trữ chỉ dưới dạng một tệp văn bản đơn lẻ mà phải nằm trong một thư mục.
- Tệp "style": Bên trong thư mục chủ đề bắt buộc phải có một tệp tên là ```style```. Tệp này sẽ chỉ định tất cả các thành phần GUI, bao gồm cả việc sử dụng tệp hình ảnh nào thay vì dùng mã màu RGB.
- Hậu tố: Thư mục chứa chủ đề phải sử dụng hậu tố ```.themed``` sau tên của chủ đề đó (Ví dụ: ```MyFavorite.themed```).

💠 **Lưu ý kỹ thuật**: Nếu bạn tải về một chủ đề có dạng thư mục .themed, hãy đảm bảo rằng bên trong nó có tệp style. Nếu thiếu tệp này, Window Maker sẽ không thể nhận diện được đó là một gói chủ đề hợp lệ.

<a name="#miscellaneous"></a>
MISCELLANEOUS
----------------------
Các thiết lập khác (Miscellaneous)
Nội dung
- [Bản địa hóa (Localization)](#localization)
- [Phông chữ (Fonts)](#fonts)
- [Tiện ích (Utilities)](#utilities)

<a name="#localization"></a>
Localization
----------------------
**Bản địa hóa (Localization)**
Chỉ cần Window Maker được biên dịch với các tùy chọn phù hợp và có cài đặt ```gettext```, nó sẽ hoàn toàn có khả năng bản địa hóa (chuyển đổi ngôn ngữ giao diện). Bạn có thể kiểm tra chi tiết trong tệp ```INSTALL```.

**Bản địa hóa menu không cần biến môi trường**
Thông thường, việc chuyển đổi ngôn ngữ phụ thuộc vào biến môi trường ```$LANG```. Tuy nhiên, bạn vẫn có thể bản địa hóa các menu mà không cần thiết lập biến này. Bằng cách sử dụng pl menu (property list menu), bạn có thể hiển thị menu bằng bất kỳ ngôn ngữ nào có sẵn.

**Tại sao lại dùng cách này thay vì thiết lập "đúng chuẩn"?**
Có một vài lý do khiến người dùng muốn giữ ngôn ngữ mặc định của hệ thống thay vì định nghĩa một bản địa hóa mới toàn diện. Một trong những lý do chính là phần lớn các phần mềm khác không tồn tại đầy đủ ở tất cả các ngôn ngữ.

Việc chỉ bản địa hóa menu giúp bạn có một giao diện điều hướng thân thiện bằng tiếng mẹ đẻ, trong khi vẫn giữ hệ thống ổn định với ngôn ngữ mặc định để tránh các lỗi hiển thị hoặc thiếu hụt ngôn ngữ trong các ứng dụng chuyên sâu khác.

💠 **Giải thích thêm:** Nói một cách đơn giản, nếu bạn đặt ```$LANG``` hệ thống sang một ngôn ngữ ít phổ biến, một số ứng dụng có thể bị lỗi font hoặc hiển thị "loằng ngoằng". Cách tiếp cận của Window Maker cho phép bạn "lai" giữa việc dùng menu tiếng Việt (chẳng hạn) nhưng vẫn giữ các thông báo hệ thống bằng tiếng Anh để dễ tra cứu lỗi khi cần thiết.

<a name="#fonts"></a>
Fonts
----------------------
Bạn hoàn toàn có thể thay đổi các phông chữ trong Window Maker bằng cách chỉnh sửa tệp ```WindowMaker``` hoặc tệp ```WMGLOBAL``` trong thư mục ```~/GNUstep/Defaults```.

Một lần nữa, tệp ```INSTALL``` đi kèm trong bộ mã nguồn sẽ cung cấp các hướng dẫn chi tiết về cách thực hiện việc này. Tệp cụ thể mà bạn cần chỉnh sửa sẽ tùy thuộc vào việc bạn muốn thay đổi loại phông chữ nào (ví dụ: phông chữ cho thanh tiêu đề cửa sổ khác với phông chữ trong menu).

Để đơn giản hóa công việc này, Window Maker cung cấp sẵn một kịch bản (script) có tên là ```wsetfont``` để giúp bạn thực hiện các thay đổi một cách thuận tiện hơn.

💠 **Mẹo nhỏ cho người dùng Linux:** Thay vì chỉnh sửa thủ công các tệp cấu hình phức tạp, bạn nên sử dụng công cụ đồ họa WPrefs.app.
- Mở WPrefs.app.
- Tìm đến biểu tượng có chữ "A" lớn (Font Configuration).
- Tại đây, bạn có thể chọn trực quan phông chữ cho từng thành phần như Window Title, Menu Title, Menu Text, và Icon Title.

Việc sử dụng các phông chữ hiện đại (như font dạng Xft nếu phiên bản Window Maker của bạn hỗ trợ) sẽ giúp giao diện trông sắc nét hơn rất nhiều trên các màn hình đời mới!

<a name="#utilities"></a>
Utilities
----------------------
Window Maker cung cấp cho người dùng một số công cụ hỗ trợ rất hữu ích. Bạn có thể tìm thấy tệp ```README``` liên quan đến các kịch bản (scripts) này trong thư mục ```util```. Hầu hết mỗi kịch bản đều có trang hướng dẫn (```man page```) riêng mà bạn nên tham khảo.

Các tiện ích này chủ yếu tập trung vào việc quản lý giao diện đồ họa (GUI) như: biểu tượng, kiểu dáng, phông chữ, menu và hình nền.

**Một số công cụ đáng chú ý:**
- wdwrite: Dùng để ghi dữ liệu trực tiếp vào các tệp cấu hình.
- setstyle và getstyle: Bộ đôi công cụ dùng để quản lý và áp dụng các chủ đề (themes).
- wxcopy và wxpaste: Cho phép sao chép và dán văn bản bằng cách sử dụng bộ đệm cắt (cutbuffer) của hệ thống X. Trong đó, ```wxcopy``` thường được tích hợp sẵn trong menu ứng dụng mặc định (mục Selection).
- wkdemenu.pl: Một công cụ cực kỳ hữu ích cho những người dùng cài đặt song song môi trường KDE, giúp tích hợp menu ứng dụng của KDE vào Window Maker.
- wmagnify (Từ phiên bản 0.63.0): Công cụ kính lúp, cho phép phóng to vùng màn hình ngay tại vị trí con trỏ chuột.

💠 **Mẹo nhỏ cho bạn:** Nếu bạn đang tùy chỉnh màu sắc qua Pywal như bạn đã tìm hiểu trước đó, lệnh ```setstyle``` chính là "chìa khóa" để bạn áp dụng các thay đổi về màu sắc lên toàn bộ giao diện Window Maker một cách đồng bộ mà không cần khởi động lại.

<a name="#screensot"></a>
SCREENSHOT
----------------------
<p align="left"> <img src="/img/screenshot0.jpg" alt=""> </p> 
<p align="left"> <img src="/img/screenshot1.jpg" alt=""> </p>