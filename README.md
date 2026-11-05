# FitBox Web

Dự án React/Vite dựng từ `FitBox.jsx`, đã kèm Tailwind CSS và lucide-react.

## Chạy trên máy

Cài Node.js, mở terminal tại thư mục dự án, rồi chạy:

```bash
npm install
npm run dev
```

Mở đường dẫn local do Vite hiển thị trong terminal.

## Đưa lên mạng bằng Vercel

1. Đẩy toàn bộ thư mục này lên một repository GitHub.
2. Vào Vercel và chọn **Add New → Project**, rồi import repository vừa tạo.
3. Giữ Build Command là `npm run build`, Output Directory là `dist`, nhấn **Deploy**.
4. Vercel sẽ cung cấp đường link công khai dạng `ten-du-an.vercel.app`.

Không tải riêng `FitBox.jsx` lên Vercel; cần đưa cả thư mục dự án.
