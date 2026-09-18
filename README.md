# 🌍 Vtours - Tour Booking Management System

Vtours là một hệ thống quản lý và đặt tour du lịch trực tuyến. Dự án được chia làm 2 phần chính: **Frontend (UI)** xây dựng giao diện người dùng và **Backend** cung cấp API xử lý dữ liệu.

## 🚀 Công nghệ sử dụng

### 🎨 Frontend (Thư mục `/ui`)
- **Framework:** React.js (với Vite)
- **Styling:** Tailwind CSS, Material UI, Radix UI, Emotion
- **Routing:** React Router DOM
- **Animation & UI Components:** Framer Motion, Embla Carousel, Lucide React
- **Fetching:** Axios
- **Khác:** React Hook Form, Recharts, Date-fns

### ⚙️ Backend (Thư mục `/backend`)
- **Môi trường:** Node.js
- **Framework:** Express.js (dựa trên cấu trúc routes, controllers, middlewares)
- **Cơ sở dữ liệu:** MongoDB (với Mongoose models)
- **Tính năng nổi bật:** Authentication, xử lý logic đặt tour, APIs quản lý dữ liệu.

---

## 📂 Cấu trúc thư mục dự án

```text
Website-tour-booking-Vtours/
├── backend/                # Source code của Server (Node.js/Express)
│   ├── controllers/        # Xử lý logic của các API
│   ├── models/             # Định nghĩa schema cho MongoDB
│   ├── routes/             # Khai báo các đường dẫn API
│   ├── middlewares/        # Các hàm trung gian (Auth, Error handling...)
│   ├── services/           # Các service xử lý nghiệp vụ
│   ├── server.js           # File khởi chạy server chính
│   └── .env                # File biến môi trường (Database URI, JWT Secret...)
│
└── ui/                     # Source code của Frontend (React/Vite)
    ├── package.json        # Chứa danh sách các thư viện UI
    └── ...                 # Code React components & pages
