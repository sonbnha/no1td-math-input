# no1td Math — gõ công thức toán cho Word trên Mac

**no1td Math** là app soạn công thức toán kiểu MathType cho **Word trên Mac**. Công thức lưu trong Word dưới dạng **object MathType** (`Equation.DSMT4`), nên:
- máy có MathType mở và sửa được;
- gửi tệp Word cho người khác như bình thường.

## Tính năng

**Trong Word (tab "no1td Math" trên Ribbon)**
- Chèn công thức trong dòng, Chèn riêng dòng, Đánh số công thức (kèm Cập nhật số).
- Sửa công thức: click đúp vào công thức, hoặc bấm nút **Sửa công thức** có trên mọi tab. Ribbon không nhảy tab.
- Sửa được cả công thức MathType có sẵn trong tài liệu cũ.
- TeX → MathType: đổi đoạn `$…$`, `\(…\)`, `$$…$$`, `\[…\]` thành công thức.
- Sang Word Equation: đổi công thức MathType thành công thức Word (cả tài liệu hoặc vùng chọn).
- Công thức trước / sau: nhảy giữa các công thức.

**Trình soạn công thức**
- Thanh ký hiệu và thanh mẫu như MathType: phân số, căn, chỉ số, tổng, tích phân, giới hạn, hệ phương trình, ma trận...
- Các tab biểu thức có sẵn: Đại số, Hình học, Giải tích, Xác suất, Lượng giác, Tập hợp, Ma trận. Thêm tab Gần đây và Của tôi.
- Phím tắt MathType (Ctrl+F phân số, Ctrl+H mũ, Ctrl+L chỉ số dưới, ...).
- Font toán **STIX Two Math**. Chỉnh kiểu chữ, font và cỡ (Định nghĩa kiểu và cỡ) như MathType.
- Hộp Ma trận, Chèn ký hiệu, thu phóng, kiểm tra công thức ngay khi gõ.
- **⌘↩ hoặc ⌘S**: đưa ngay công thức vào Word khi đang chèn hoặc sửa.
- **Sao chép / ⌘C** trong app rồi **⌘V** trong Word: ra công thức MathType. Dán vào app khác thì ra mã TeX.

**App**
- App macOS gốc, giao diện màu xanh lá no1td.
- Tự vẽ công thức ngay trong app: không cần cài thêm Node hay TeX Live.
- Tự đề nghị cài add-in Word khi mở lần đầu; có Cài / Gỡ add-in trong menu.

## Cài đặt

1. Tải **no1td-Math-0.1.1.dmg** ở trang [Releases](https://github.com/sonbnha/no1td-math-input/releases/latest), mở ra và kéo **no1td Math** vào Applications.
2. Lần đầu mở: bấm chuột phải vào app → **Mở** → **Mở**. Bản này chưa được Apple xác minh.
3. Chọn **Cài** khi app hỏi cài add-in cho Word. Thoát Word rồi mở lại: Ribbon có tab "no1td Math".
4. Để click đúp mở công thức: vào System Settings → Quyền riêng tư & Bảo mật → Trợ năng, bật "no1td Math".

Chi tiết xem tệp "Hướng dẫn cài đặt.txt" trong DMG.

## Yêu cầu

- Mac chip Apple (M1 trở lên). Bản này chưa chạy trên Mac Intel.
- Microsoft Word for Mac (đã thử với bản 16.113).

## Giới hạn đã biết

- Chưa ký Developer ID và chưa notarize, nên lần đầu phải mở bằng chuột phải.
- Chưa thử với MathType 7 thật. Các công cụ đọc MathType đều nhận đúng object.
- Chưa thử cài trên máy sạch.

## Phản hồi

Gặp lỗi hoặc cần thêm tính năng: mở mục [Issues](https://github.com/sonbnha/no1td-math-input/issues).

Repo này chỉ chứa gói cài đặt và ghi chú phát hành.
