# Unit 2 – Grade 5

Ứng dụng React + Vite học tiếng Anh lớp 5. Không cần Gemini API key.

## Chạy trên máy

Yêu cầu Node.js 24 và npm.

```sh
npm ci
npm run dev
```

## Đưa lên GitHub Pages

1. Trong repository, chọn **Settings → Pages → Source → GitHub Actions**.
2. Đẩy các thay đổi lên nhánh `main`. Workflow **Deploy to GitHub Pages** tự kiểm tra TypeScript, build và xuất bản thư mục `dist`.
3. Chờ workflow thành công, rồi mở https://minee382.github.io/Unit-2---Grade-5/.

Không xuất bản trực tiếp mã nguồn `src/main.tsx`: trình duyệt cần JavaScript đã được build. Cấu hình `base: './'` giúp tải đúng tài nguyên khi trang nằm trong đường dẫn repository.

```sh
npm run lint
npm run build
npm run preview
```
