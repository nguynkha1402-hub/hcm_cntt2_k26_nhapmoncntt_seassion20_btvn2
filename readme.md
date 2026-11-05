### Hiệu ứng Domino (Credential Stuffing)
Hacker lấy cắp mật khẩu "123456" từ web nhỏ, sau đó dùng bot tự động thử đăng nhập hàng loạt vào Facebook, Gmail, GitHub. Do bạn dùng chung một mật khẩu, hacker dễ dàng mở khóa hàng loạt tài khoản, đặc biệt là Gmail - "chìa khóa" để khôi phục mọi dịch vụ khác.

### Mật khẩu cảm tính vs. Máy tính sinh ra

- Mật khẩu cảm tính ("123456"): Tuân theo quy luật ngôn ngữ hoặc thói quen. Hacker dùng Tấn công từ điển để bẻ khóa trong chưa tới 1 mili-giây.
- Mật khẩu máy tính sinh ra: Hoàn toàn ngẫu nhiên. Hacker buộc phải dùng Brute-force, siêu máy tính cũng mất hàng tỷ năm để giải mã.

### Password Manager (AES-256) vs. Ghi chép thủ công

- Sổ tay thủ công: Dữ liệu thô, ai nhìn thấy cũng đọc được, kèm theo rủi ro vật lý.

- Password Manager: Lưu trữ dưới dạng văn bản mã hóa bằng chuẩn AES-256. Số lượng khóa mã hóa của AES-256 lớn hơn số nguyên tử trong vũ trụ. Nếu không có "mật khẩu chủ", bất kỳ ai đánh cắp được dữ liệu cũng chỉ thu về một chuỗi ký tự rác vô nghĩa.