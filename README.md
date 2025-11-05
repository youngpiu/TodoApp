# Ứng Dụng Todo Web

Một ứng dụng quản lý công việc hiện đại, đáp ứng trên web được xây dựng với React và Vite. Ứng dụng này cho phép người dùng quản lý các nhiệm vụ với các tính năng như phân loại, lọc, tìm kiếm và đánh dấu ưu tiên.

## 🚀 Tính Năng

- ✅ Thêm, chỉnh sửa và xóa nhiệm vụ
- 📂 Tổ chức nhiệm vụ theo danh mục
- 🔍 Tìm kiếm và lọc nhiệm vụ
- ⭐ Đánh dấu nhiệm vụ quan trọng
- 📊 Theo dõi trạng thái hoàn thành
- 🎨 Giao diện hiện đại với Tailwind CSS
- 📱 Thiết kế đáp ứng
- ⚡ Phát triển nhanh với Vite HMR

## 🛠️ Công Nghệ Sử Dụng

- **Framework Frontend:** React 18
- **Công Cụ Build:** Vite
- **Styling:** Tailwind CSS
- **Icons:** FontAwesome
- **Ngôn Ngữ:** JavaScript (ES6+)
- **Linting:** ESLint
- **Định Dạng Code:** Prettier

## 📦 Cài Đặt

1. Clone repository:
```bash
git clone <repository-url>
cd web-todo-app
```

2. Cài đặt dependencies:
```bash
pnpm install
```

3. Khởi động server phát triển:
```bash
pnpm dev
```

4. Mở [http://localhost:5173](http://localhost:5173) trong trình duyệt.

## 🏗️ Các Lệnh Có Sẵn

- `pnpm dev` - Khởi động server phát triển
- `pnpm build` - Build cho production
- `pnpm preview` - Xem trước build production
- `pnpm lint` - Chạy ESLint

## 📁 Cấu Trúc Dự Án

```
src/
├── components/          # Các component UI có thể tái sử dụng
│   ├── Categories.jsx   # Quản lý danh mục
│   ├── TodoItem.jsx     # Item todo cá nhân
│   ├── TodoList.jsx     # Container danh sách todo
│   ├── TaskInput.jsx    # Form nhập nhiệm vụ mới
│   ├── FilterPanel.jsx  # Điều khiển lọc
│   └── ...
├── contexts/            # React contexts cho quản lý state
├── constant.js          # Hằng số của ứng dụng
├── App.jsx             # Component chính của ứng dụng
└── main.jsx            # Điểm vào của ứng dụng
```

## 🎯 Cách Sử Dụng

1. **Thêm Nhiệm Vụ:** Sử dụng trường nhập ở trên cùng để thêm nhiệm vụ mới
2. **Phân Loại:** Gán nhiệm vụ vào các danh mục khác nhau
3. **Lọc:** Sử dụng bảng điều khiển lọc để xem nhiệm vụ theo trạng thái hoặc danh mục
4. **Tìm Kiếm:** Sử dụng thanh tìm kiếm để tìm nhiệm vụ cụ thể
5. **Đánh Dấu Quan Trọng:** Nhấp vào biểu tượng ngôi sao để đánh dấu nhiệm vụ quan trọng
6. **Hoàn Thành Nhiệm Vụ:** Đánh dấu vào checkbox để đánh dấu nhiệm vụ đã hoàn thành
