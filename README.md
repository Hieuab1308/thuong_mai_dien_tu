# Ecommerce-FULL-stack

## Giới Thiệu

Dự án **Ecommerce-FULL-stack** là một ứng dụng thương mại điện tử được phát triển bởi nhóm sinh viên Trường Đại học Phenikaa, Khoa Công nghệ Thông tin. Mục tiêu của dự án là cung cấp một nền tảng mua sắm trực tuyến tiện lợi, an toàn, kết nối hiệu quả giữa người mua và người bán.

## Mục Tiêu

- Xây dựng một nền tảng thương mại điện tử thân thiện, hiệu quả và an toàn.
- Kết nối người tiêu dùng với các nhà cung cấp và thương hiệu uy tín.
- Đảm bảo giao dịch nhanh chóng, minh bạch và mang lại trải nghiệm tốt cho người dùng.

## Tầm Quan Trọng

- Đáp ứng nhu cầu mua sắm trực tuyến ngày càng tăng.
- Hỗ trợ người tiêu dùng mua sắm dễ dàng và an toàn.
- Giúp các nhà bán hàng tiếp cận khách hàng nhanh chóng và hiệu quả.

## Tính Năng Chính

### Dành cho Người dùng (User)

- **Đăng ký/Đăng nhập**: Quản lý tài khoản cá nhân.
- **Tìm kiếm sản phẩm**: Tìm kiếm theo từ khóa (tên, loại, thương hiệu).
- **Đặt hàng**: Thêm sản phẩm vào giỏ hàng và thanh toán.
- **Quản lý giỏ hàng**: Xem, chỉnh sửa, xóa sản phẩm trong giỏ hàng.
- **Danh sách yêu thích**: Lưu sản phẩm yêu thích.
- **Quản lý profile**: Theo dõi đơn hàng, cập nhật thông tin cá nhân.
- **Chatbox**: Hỗ trợ tự động qua chatbot.

### Dành cho Admin

- **Quản lý sản phẩm**: Thêm, cập nhật, xóa sản phẩm.
- **Quản lý đơn hàng**: Theo dõi và cập nhật trạng thái đơn hàng.
- **Thống kê doanh thu**: Xem báo cáo doanh số.
- **Gửi thông báo**: Hiển thị thông báo đến người dùng.

## Công Nghệ Sử Dụng

### Front-end

- **Flutter**: Xây dựng giao diện đa nền tảng.
- **Dart**: Ngôn ngữ lập trình chính.

### Back-end

- **Node.js (Express.js)**: Xử lý logic phía server.

### Database

- **MongoDB**: Lưu trữ dữ liệu dưới dạng JSON.

### Quản lý dự án

- **GitHub**: Quản lý mã nguồn và cộng tác nhóm.

## Cấu Trúc Thư Mục

```
Ecommerce-FULL-stack/
├── client/              # Mã nguồn Front-end (Flutter)
├── server/              # Mã nguồn Back-end (Node.js)
├── .env                 # Biến môi trường (API keys, database URL, v.v.)
└── README.md            # Tài liệu hướng dẫn dự án
```

## Yêu Cầu Hệ Thống

- **Flutter**: Phiên bản 3.x trở lên.
- **Node.js**: Phiên bản 14.x trở lên.
- **MongoDB**: Chạy local hoặc sử dụng MongoDB Atlas.
- **Git**: Để clone repository.
- **Trình duyệt**: Chrome (khuyến nghị).

## Hướng Dẫn Cài Đặt

### Bước 1: Clone Repository

```bash
git clone https://github.com/HieuaB1308/thuong_mai_dien_tu.git
cd Ecommerce-FULL-stack
```

### Bước 2: Cài Đặt Back-end

Di chuyển vào thư mục `server`:

```bash
cd server
```

Cài đặt các dependency:

```bash
npm install
```

Tạo file `.env` trong thư mục `server` và thêm các biến môi trường:

```
PORT=3000
MONGODB_URI=mongodb://localhost:27017/ecommerce
STRIPE_SECRET_KEY=your_stripe_secret_key
```

Chạy server:

```bash
node index.js
```

Server sẽ chạy tại `http://localhost:3000`.

### Bước 3: Cài Đặt Front-end

Di chuyển vào thư mục `client`:

```bash
cd client
```

Cài đặt các dependency:

```bash
flutter pub get
```

Chạy ứng dụng:

```bash
flutter run -d chrome
```

Ứng dụng sẽ chạy trên trình duyệt Chrome.

## Lưu Ý

- Đảm bảo MongoDB đang chạy trước khi khởi động server.


## Hướng Dẫn Sử Dụng

### Đối Với Người Dùng

1. Mở ứng dụng trên trình duyệt hoặc thiết bị di động.
2. Đăng ký tài khoản hoặc đăng nhập.
3. Sử dụng thanh tìm kiếm để tìm sản phẩm.
4. Thêm sản phẩm vào giỏ hàng và tiến hành đặt hàng.
5. Theo dõi đơn hàng trong phần **Profile**.
6. Sử dụng **Chatbox** để nhận hỗ trợ tự động.

### Đối Với Admin

1. Đăng nhập bằng tài khoản Admin.
2. Quản lý sản phẩm: Thêm, cập nhật, xóa sản phẩm.
3. Xem thống kê doanh thu trong mục **Thống kê**.
4. Quản lý đơn hàng và gửi thông báo cho người dùng.

## Tác Giả

Dự án được thực hiện bởi nhóm sinh viên Trường Đại học Phenikaa:

- **Nguyễn Danh Hiếu** – 22010104
- **Phạm Văn Thân** – 22010093
- **Vũ Minh Hiếu** – 22010080
- **Giảng viên hướng dẫn**: TS. Trịnh Thanh Bình

## Giấy Phép

Dự án hiện chưa có giấy phép cụ thể. Vui lòng liên hệ nhóm tác giả nếu bạn muốn sử dụng mã nguồn cho mục đích thương mại.

---

Cảm ơn bạn đã quan tâm đến dự án của chúng tôi!



