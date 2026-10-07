# ARAM Supporter

Công cụ hỗ trợ chơi **ARAM** cho League of Legends trên Windows: tự lấy tướng bạn thích từ bench, tự xin đổi tướng với đồng đội, tự chấp nhận trận, gợi ý Lõi Nâng Cấp ngay trong game và nhiều tiện ích khác.

> Repo này chỉ chứa **bản cài đặt** để tải. Mã nguồn không công khai.

## Tải về

1. Vào trang **[Releases](../../releases/latest)** và tải file **`ARAM Supporter_..._x64-setup.exe`**.
2. Chạy file vừa tải để cài (chỉ cần file `.exe`, bỏ qua `latest.json`).
3. Mở **League of Legends**, sau đó mở ARAM Supporter. App tự nhận League Client khi bạn đăng nhập.

Windows có thể hiện cảnh báo SmartScreen khi chạy bộ cài lần đầu vì app chưa có chứng chỉ ký số của nhà phát hành. Bấm **Thông tin thêm → Vẫn chạy** nếu bạn tin tưởng nguồn tải.

Lần sau có bản mới, app sẽ tự đề nghị cập nhật, bạn không cần tải lại thủ công.

**Yêu cầu:** Windows 10/11 (cần WebView2, Windows 11 có sẵn), League of Legends đã cài.

## Tính năng chính

### Tự lấy tướng theo Danh Sách Ưu Tiên
Bạn tự xếp danh sách tướng yêu thích (`#1` là ưu tiên nhất) bằng cách kéo thả.
- **Tự Lấy Bench:** tướng ưu tiên cao hơn tướng đang cầm vừa lên bench là app lấy ngay, không bao giờ đổi xuống tướng kém hơn.
- **Tự Trade Đồng Đội:** tự xin đổi với đồng đội đang cầm tướng ưu tiên cao hơn. App theo dõi trạng thái đổi thật, xin lại khi tướng quay về tay họ, và bỏ qua người bạn đã đưa vào danh sách chặn trade.
- **Tự trả lời lời xin đổi:** nhận lời đổi sang tướng ưu tiên hơn, từ chối tướng kém hơn (đi cùng Tự Trade).
- **Ưu tiên lấy ở game này:** chuột phải một tướng trên bench hoặc đội hình để ưu tiên nó hơn mọi thứ hạng, chỉ trong ván hiện tại.

### Tự động hoá phòng chờ và cuối trận
- **Auto Chấp Nhận** trận khi tìm được.
- **Auto Start:** tự bấm tìm trận khi bạn là chủ phòng (chọn khi 1 mình hoặc từ 2 người), có ô nhập số giây chờ trước khi bấm. Tự tắt khi có người từ chối hoặc huỷ tìm trận.
- **Auto Skip End Game:** tự bỏ qua màn vinh danh, về lại phòng và đóng popup thông thạo tướng.
- **Auto Flash:** tự đặt Tốc Biến đúng phím D hoặc F theo ý bạn.
- **Auto Import Build:** khi chốt tướng, tự tạo bộ trang bị trong game và đổi sang cặp phép bổ trợ tốt nhất.

### Gợi ý Lõi Nâng Cấp (ARAM: Hỗn Loạn)
- Bảng lõi của tướng đang cầm theo từng bậc (Kim Cương / Vàng / Bạc), kèm bậc S+…D và tỉ lệ thắng.
- **Overlay trong game:** hiện huy hiệu bậc và tỉ lệ thắng ngay dưới mỗi thẻ lõi khi bạn chọn lõi. Overlay là cửa sổ riêng, không can thiệp vào tiến trình game. Cần để game ở chế độ **Borderless** hoặc **Windowed**, tỉ lệ 16:9.

### Giao diện chọn tướng và phòng chờ
- Bench 10 ô bấm để swap, thẻ bài tướng đầu ván, đội hình 5 người với phép bổ trợ, thứ hạng ưu tiên và trạng thái trade.
- Splash theo skin đang chọn, dải trang phục chỉ gồm skin bạn sở hữu.
- Phòng chờ: mời bạn bè (có thể kéo thả), đổi mode ARAM, tìm trận, Ready Check.
- **Lịch Sử Đấu:** xem chi tiết 2 đội (lõi, đồ, sát thương, vàng) và tra lịch sử người chơi khác.

### Setting theo tài khoản
Setting, Danh Sách Ưu Tiên và danh sách chặn trade được lưu theo tài khoản LoL trên máy chủ. Đổi máy, đăng nhập lại là có đủ. Các công tắc có tác dụng ngay khi bật hoặc tắt và tự lưu sau khoảng 1,5 giây.

## Bản Free và bản VIP

| | Free | VIP |
|---|---|---|
| Tất cả tính năng ở trên | Có | Có |
| Tự lấy tướng theo Danh Sách Ưu Tiên | Sau **2,5 giây** | **Lấy ngay lập tức** |

Free chờ 2,5 giây trước khi lấy bench hoặc xin đổi tướng (giống độ trễ của giao diện client), còn VIP lấy ngay. Nhập key VIP ở tab **Tướng Ưu Tiên** hoặc trong **Cài Đặt**. Mỗi key gắn với một tài khoản LoL, có thể có hạn theo ngày hoặc vĩnh viễn. Muốn mua key, bấm nút **MUA KEY VIP** trong app.

## Dữ liệu và quyền riêng tư

- App giao tiếp với League Client qua API nội bộ trên máy bạn và chỉ hoạt động khi client đang mở.
- Để kiểm tra quyền dùng và đồng bộ setting, app gửi lên máy chủ: mã tài khoản (puuid), Riot ID, phiên bản app, setting, Danh Sách Ưu Tiên và danh sách chặn trade. App không đọc hay gửi mật khẩu Riot của bạn.
- App cần kết nối mạng để dùng. Mất kết nối máy chủ thì các tính năng tự động tạm dừng cho tới khi kết nối lại.

## Lưu ý

ARAM Supporter là sản phẩm độc lập, **không được Riot Games xác nhận hay bảo trợ** và không liên kết với Riot Games. League of Legends là thương hiệu của Riot Games, Inc. Công cụ sử dụng API nội bộ của League Client, hãy tự cân nhắc khi sử dụng. Quản trị viên có thể chặn tài khoản hoặc tạm khoá app khi cần.

## Hỗ trợ

Mọi chi tiết và hỗ trợ liên hệ: **gnad.dev97@gmail.com**

© DangTH. Vui lòng không sao chép dưới mọi hình thức.
