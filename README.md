# **HODO Interview**

### I. API

https://jsonplaceholder.typicode.com/posts

### II. Playground

https://stackblitz.com/edit/vue2-hodo-fe-interview?file=README.md

### III. Yêu cầu

#### 1. Các packages cần dùng: axios, vuex@3.6.2, vue-router@3.6.5

- Call API: Axios
- Store: Vuex
- Router: Vue-router

#### 2. Yêu cầu chính (Thời gian 40 ~ 50 phút)

- Sử dụng Vuex để lưu store tất cả dữ liệu posts lấy về từ API
- Hiển thị lên màn hình 5 posts (bao gồm: title, body) theo thứ tự ID **[100, 99, 98, 97, 96]**
- Hiển thị chi tiết post theo ID thông qua router (sử dụng vue-router)

#### 3. Yêu cầu thêm (Optional)

- Build 1 layout hiển thị trang blog post.
- Do API không trả về hình ảnh, sử dụng link sau làm ảnh thumbnail demo cho các posts:
  **https://picsum.photos/id/<id_post>/500/300**
- Sử dụng 5 posts hiển thị dạng lưới (Grid) bao gồm:
  - Tiêu đề mục: Latest posts
  - Image
  - Title
  - Body
- Với 95 posts còn lại [95, 94, 93, …, 1] hiển thị dạng danh sách (List) bao gồm:
  - Image
  - Title
  - Body
- Danh sách có phân trang với limit **10 posts/page**. Danh sách này được đặt bên dưới Latest posts

#### 4. Kết quả đạt được cho phần yêu cầu thêm (Optional)

- Trang Blog posts có:
  - Latest posts (5 posts có ID mới nhất (lớn nhất)
  - List 95 posts còn lại, có phân trang với limit: **10 posts/page**
- Trang Detail post: hiển thị nội dung của 1 bài post khi được click từ trang Blog post bên trên
