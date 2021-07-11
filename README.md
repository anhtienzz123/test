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
- `[POST] /login`: đăng nhập.
  - body: {username: String, password: String}.

### Course
- `[GET] /courses/topics`: lấy danh sách topic.
- `[GET] /courses`: lấy danh sách khóa học từ vựng.
  - params: name: String, topicSlug: String, page: int, size: int.
- `[GET] /courses/:slug`: lấy chi tiết khóa học từ vựng
  
