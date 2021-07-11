# API Web Tiếng Anh - NodeJs

## Cách sử dụng

Clone project về và chạy 2 câu lệnh sau, project chạy trên [http://localhost:3001](http://localhost:3001)

### `npm i`

### `npm start`

## API

### Word

- `/word/:name`: lấy thông tin từ vựng.
  - params: name: String, topic: String, page: int, size: int.
  - body: {}.

# API Web Tiếng Anh - Spring Boot

## API

### Login
- `/login [POST]`: đăng nhập.
  - body: {username: String, password: String}.

### Course
- `/courses [GET]`: lấy danh sách khóa học từ vựng.
  - params: name: String, topicSlug: String, page: int, size: int.
- `/courses/topics [GET]`: lấy danh sách topic
- `/courses/:slug [GET]`: lấy chi tiết khóa học từ vựng
  
