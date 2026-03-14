# Auth Callback (Reset Password)

Trang này xử lý redirect sau khi user đặt mật khẩu mới qua email:

- **Desktop**: Hiển thị thông báo "Đặt mật khẩu thành công. Mở app trên điện thoại để đăng nhập."
- **Mobile**: Redirect về `officereader://auth-callback` để mở app.

## Cấu hình Supabase

Thêm URL này vào **Supabase Dashboard** → **Authentication** → **URL Configuration** → **Redirect URLs**:

```
https://FinAITechnology.github.io/office-reader-legal/auth-callback/
```

## Deploy

Deploy thư mục `auth-callback/` lên GitHub Pages (cùng repo với privacy-policy, terms).
