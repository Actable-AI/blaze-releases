# Blaze Note — phiên bản tối thiểu (mobile)

`version.json` là phiên bản **tối thiểu** được phép chạy. App Blaze Note (iOS / Android) đọc file này lúc mở; thấp hơn ⇒ màn bắt buộc cập nhật.

- Chỉ nâng `ios.version` / `android.version` **sau khi** bản đó đã duyệt xong và tải được trên App Store / Google Play. Nâng sớm ⇒ người dùng bấm Cập nhật, store còn bản cũ, kẹt ở màn chặn.
- Hai nền tảng nâng riêng.
- So `major.minor.patch` theo số; không ghi build number.
- `notes`: ghi chú hiện trên màn cập nhật (`vi`, `en`, `zh`, `km`; thiếu thì `en`, rồi `vi`).
- Có hiệu lực sau tối đa ~5 phút (cache CDN của raw.githubusercontent).
