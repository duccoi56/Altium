# AltiumLab — Ứng dụng Web Học Thiết Kế Mạch PCB với Altium Designer

**AltiumLab** là ứng dụng web tương tác (single-file HTML/CSS/JS, không cần build) giúp kỹ sư điện – điện tử nhập môn học từ nền tảng linh kiện, đọc sơ đồ nguyên lý đến thực hành đi dây PCB, kiểm tra DRC và xuất Gerber trên Altium Designer.

## Tính năng chính
- **Lộ trình 6 giai đoạn chuẩn kỹ sư**: Từ tạo Project (`.PrjPcb`), vẽ Schematic, đồng bộ ECO, sắp xếp linh kiện, đi dây đến kiểm tra DRC và xuất file Gerber.
- **Đọc Nguyên lý & Lý thuyết nhập môn toàn diện**:
  - Sơ đồ nguyên lý tương tác hỗ trợ soi Net kiểu `Alt + Click`, xem phân tích linh kiện và bài tập truy vết.
  - Lý thuyết nhập môn (`VCC`, `GND`, `R`, `C`, `L`, `Diode`, `MOSFET`, `IC`) kèm mô phỏng mạch MCU bật/tắt quạt 12V.
  - Từ điển Thuật ngữ A–Z (38 mục có tìm kiếm & lọc), bảng so sánh 5 họ MCU (`ATmega`, `ESP32`, `STM32`, `RP2040`, `nRF52`) và bản đồ chân ngoại vi.
- **Phòng Lab PCB 2D/3D tương tác**: Kéo thả, xoay (`Space`), lật lớp (`L`), đi dây (`Ctrl+W`), thả Via (`*`), Single Layer Mode (`Shift+S`), xem 3D và kiểm tra lỗi DRC trực tiếp.
- **Luyện Phím tắt & Công cụ Tính toán PCB**: Luyện phản xạ phím tắt (Cơ bản / Toàn bộ), tính độ rộng đường đồng chuẩn IPC-2221 kèm cảnh báo giới hạn gia công 6 mil, và khám phá cấu trúc bo 4 lớp.
- **Giao diện Sáng / Tối** tự động lưu trạng thái và tiến độ học tập trên trình duyệt.

## Cách đưa lên GitHub & chạy trực tiếp bằng GitHub Pages
1. Tạo một repository mới trên GitHub (ví dụ: `altiumlab`).
2. Giải nén tệp `altiumlab-github.zip` và tải toàn bộ 3 tệp (`index.html`, `README.md`, `LICENSE`) lên nhánh `main`.
3. Vào **Settings → Pages → Build and deployment → Source: Deploy from a branch**, chọn nhánh `main` và thư mục `/ (root)`, sau đó bấm **Save**.
4. Sau khoảng 1–2 phút, ứng dụng sẽ hoạt động công khai tại địa chỉ `https://<ten-github-cua-ban>.github.io/altiumlab/`.

## Chạy cục bộ (Offline)
Chỉ cần mở trực tiếp tệp `index.html` bằng trình duyệt Chrome, Edge, Firefox hoặc Safari.
