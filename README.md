Đây là dự án Fleet Tracking sử dụng công nghệ OpenStreetMap để theo dõi vị trí của các phương tiện trong một khu vực nhất định.
Để đảm bảo có thể chạy được code trên laptop, bạn có thể làm theo các bước sau:

###  **Chuẩn bị dự án**
Trước khi gửi dự án, hãy đảm bảo rằng tất cả các thư viện và gói cần thiết được liệt kê trong file `package.json` và bạn có file `README.md` với hướng dẫn cài đặt và chạy dự án.

## Yêu cầu tài và cài đặt
- Node.js
- npm (Node Package Manager) ( sẽ tự động cài kèm theo khi cài node.js )

## Cài đặt và chạy dự án

### Bước 1: Clone repository hoặc tải về dự án
```bash
git clone <repository-url>
```
Hoặc tải file ZIP của dự án và giải nén.

### Bước 2: Cài đặt các gói cần thiết
```bash
cd <tên-thư-mục-dự-án>
npm install
```

### Bước 3: Chạy server
```bash
node server.js
```

### Bước 4: Truy cập vào ứng dụng
Mở trình duyệt và truy cập vào địa chỉ:
```
http://localhost:3000
```

## Cấu trúc thư mục
- `server.js`: File khởi động server.
- `public`: Chứa các file HTML, CSS, và JS.

1. **Giải nén file ZIP**: Giải nén file ZIP vào một thư mục trên máy tính.
2. **Cài đặt Node.js và npm**: 
3. **Mở terminal hoặc command prompt**: Điều hướng đến thư mục chứa dự án.
4. **Cài đặt các gói cần thiết**:
   ```bash
   npm install
   ```
5. **Chạy server**:
   ```bash
   node server.js
   ```
6. **Truy cập ứng dụng**: Mở trình duyệt và truy cập vào địa chỉ `http://localhost:3000`.
