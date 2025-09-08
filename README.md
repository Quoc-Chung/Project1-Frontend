# 🚀 Monorepo E-Commerce Platform

Monorepo này chứa **2 dự án Next.js** tách biệt: **Client** (giao diện chính của website thương mại điện tử) và **Admin** (bảng điều khiển quản trị).  
Cấu trúc monorepo giúp quản lý đồng thời cả hai ứng dụng trong cùng một repo, thuận tiện cho việc phát triển, bảo trì và triển khai.

---

## 🛠️ Cấu trúc dự án

📂 Admin/           
  ├── package.json  
  └── ...            
📂 Client/          
  ├── package.json   
  └── ...           
📜 package.json      

 
---

## 🛠️ Chức năng chính

### 🌐 Client (Front-end chính của website)
- Đăng nhập / Đăng ký người dùng
- Trang chủ hiển thị sản phẩm
- Tìm kiếm và lọc sản phẩm
- Giao diện giỏ hàng và đặt hàng
- Trải nghiệm UI/UX thân thiện cho khách hàng

### 🛡️ Admin (Hệ thống quản trị)
- Quản lý người dùng (User Management)
- Quản lý sản phẩm / dịch vụ (Product & Service Management)
- Quản lý đơn hàng
- Thống kê và báo cáo
- Quản lý các cấu hình hệ thống khác

---

## 🚀 Cách chạy dự án

B2: Chạy ứng dụng

Chạy cả Client và Admin cùng lúc:

npm run dev

B3: Truy cập trên trình duyệt

Client: http://localhost:3001

Admin: http://localhost:3000
