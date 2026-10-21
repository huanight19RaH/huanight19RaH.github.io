# 🌐 Personal Web Portfolio — Nguyễn Thái Hưng

Trang Web Portfolio cá nhân với thiết kế tông màu **FC Barcelona (Blaugrana 🔴🔵🟡)** hiện đại, đồng bộ phong cách và dữ liệu xác thực 100% với GitHub Profile.

---

## ✨ Tính Năng Nổi Bật

- 🎨 **Giao diện Blaugrana Độc Quyền:** Tông nền Midnight Stadium (`#080E1E`), điểm nhấn Royal Blue (`#004D98`), Garnet (`#A50044`) và Gold (`#EDBB00`) cùng hiệu ứng Glassmorphism & Ambient Glow sang trọng.
- ⚡ **Hiệu ứng gõ chữ (Typing Animation):** Hiển thị các chức danh chuyên môn, vị trí Phó Chủ nhiệm CLB FU-DEVER và định hướng nghiên cứu mượt mà.
- 🏆 **Phân mục Thành tích & Giải thưởng riêng biệt:** Vinh danh Giải Khuyến Khích Research Festival 2026, Giải Nhì Code Mosaic Hackathon 2025, Giải Khuyến Khích HSG Toán Đà Nẵng 2024 và 2 bài báo khoa học đã accepted.
- 🎯 **Bộ lọc dự án thông minh (4 dự án thực tế):** Lọc theo từng nhóm lĩnh vực: *AI Research (2 Papers)*, *ML Systems*.
- 📊 **Tích hợp thống kê trực quan:** Embed đầy đủ thẻ GitHub Stats, Top Languages, Streak Stats Blaugrana, LeetCode Stats và Snake Game Contribution Activity.
- 📱 **Responsive 100%:** Hiển thị tối ưu và mượt mà trên cả Mobile, Tablet và Desktop.
- 🚀 **Zero Dependency (Chạy ngay không cần cài đặt):** Mở trực tiếp file `index.html` trên bất kỳ trình duyệt nào.

---

## 💻 Cách Xem Thử (Local Preview)

### Cách 1: Mở trực tiếp (Nhanh nhất)
Nhấp đúp chuột vào file `index.html` trong thư mục này để mở ngay trên trình duyệt (Chrome, Edge, Brave, Firefox...).

### Cách 2: Chạy Local Server (Khuyên dùng)
Nếu máy đã cài Node.js, bạn có thể chạy trong terminal:
```bash
npx serve .
# Hoặc
npm run dev
```
Sau đó truy cập địa chỉ hiển thị trên terminal (thường là `http://localhost:3000`).

---

## 🚀 Hướng Dẫn Deploy Lên Vercel / GitHub Pages

### Cách 1: Deploy lên Vercel (Miễn phí & Tự động có domain đẹp)
1. Tạo một repository mới trên GitHub cá nhân (Ví dụ: `portfolio` hoặc `web-portfolio`).
2. Đẩy toàn bộ nội dung thư mục `web-portfolio/` này lên repository đó:
   ```bash
   cd D:\THStudy\personal\web-portfolio
   git init
   git add .
   git commit -m "feat: initial portfolio website"
   git branch -M main
   git remote add origin https://github.com/huanight19RaH/<ten-repo>.git
   git push -u origin main
   ```
3. Truy cập [Vercel.com](https://vercel.com/) và đăng nhập bằng GitHub.
4. Chọn **Add New...** -> **Project** -> Chọn repo vừa tạo và nhấn **Deploy** (File `vercel.json` đã được thiết lập sẵn, không cần cấu hình thêm gì).
5. Vercel sẽ tự động cấp một domain miễn phí dạng `ten-ban.vercel.app` bảo mật HTTPS.

### Cách 2: Deploy lên GitHub Pages
1. Tạo repository tên `<username>.github.io` trên GitHub (hoặc bất kỳ tên repo nào).
2. Đẩy code lên nhánh `main`.
3. Vào **Settings** -> **Pages** -> Tại mục **Branch**, chọn `main` / `root` -> Nhấn **Save**.
4. Website sẽ xuất hiện trực tiếp tại `https://huanight19RaH.github.io/`.
