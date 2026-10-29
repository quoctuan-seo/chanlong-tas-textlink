# Chan Long · Mô hình TAS & Textlink

Trang xem chung hai mô hình được cung cấp ngày 09/10/2026.

- `index.html`: trang chính, chuyển giữa hai mô hình bằng tab.
- `tas.html`: bản hiển thị độc lập từ file “Design – Mô hình TAS · Chan Long Pickleball.html”. Giữ nội dung và bố cục, bỏ lớp runtime không cần thiết của bản xuất thiết kế.
- `textlink.html`: giữ nguyên nội dung file “Sơ đồ textlink Chan Long (2).html”; đồng bộ nền trắng, bảng màu, phông Google Sans Flex và cỡ chữ với tab TAS.

Trang mặc định mở TAS; `#textlink` mở tab Textlink. Nút “Mở riêng” xem từng mô hình ở cửa sổ riêng. Nút “Vừa màn hình” điều chỉnh tỷ lệ sơ đồ TAS.

Để xem trên máy: `python3 -m http.server 8767`, sau đó mở `http://localhost:8767/`.

GitHub Pages: dùng nhánh `main`, thư mục `/ (root)`.

## Cập nhật 29/10/2026

Tab TAS được thay bằng mẫu “Mô hình TAS-html/Main.dc.html” người dùng cung cấp: Cloudflare, Odoo, GitHub, GitLab Pages và Netlify. Giữ nguyên nội dung, tọa độ, đường nối và bảng màu của mẫu; dùng HTML/SVG tĩnh với phông sẵn có, không cần runtime xuất thiết kế. Textlink giữ nguyên.
