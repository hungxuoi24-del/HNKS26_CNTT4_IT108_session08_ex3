# Bài 3: Onboarding Lập Trình Viên Mới

## 1. Báo cáo phân tích (I/O)

- **Input (Văn bản thô):** Là tập hợp các ký tự văn bản thuần túy (Plain Text) chứa các cú pháp Markdown chưa qua biên dịch như `#`, `**`, `` ` ``, `|`, `\`,...
- **Output (Giao diện Render):** Là kết quả hiển thị trực quan, đẹp mắt trên trình đọc Markdown, nơi các cú pháp thô đã được biên dịch thành tiêu đề, văn bản định dạng, khối code có tô màu cú pháp, bảng biểu chia cột và ô kiểm tra tiến độ.

---

## 2. Tài liệu hướng dẫn Onboarding & Cài đặt VS Code

### Tổng quan & Ràng buộc Escape Character
Tài liệu này hướng dẫn lập trình viên mới cấu hình môi trường phát triển trên **VS Code**.

> **Lưu ý về bẫy dữ liệu:** Khi viết tài liệu kỹ thuật, nếu muốn hiển thị các ký tự đặc biệt của Markdown như \* hoặc \# dưới dạng văn bản thuần túy mà không muốn hệ thống tự động render thành định dạng, bạn bắt buộc phải thêm dấu gạch chéo ngược `\` ngay phía trước (Ví dụ: `\*ký tự\*` hoặc `\# tiêu đề`).

---

### Đoạn mã Python kiểm 

Sử dụng lệnh `python main.py` trong Terminal để chạy đoạn script Python cơ bản dưới đây (chú ý cách dùng Inline Code cho các tên biến ngắn như `app_name`, `version`, `status`):

```python
app_name = "VS Code"
status = "Ready"

print("Ung dung:", app_name)
print("Trang thai:", status) 
```

### Bảng so sánh
Tiêu chí | StackEditVisual | Studio Code (VS Code)
| :--: | :--: | :--: |
| Nền tảng | Chạy trực tiếp trên trình duyệt Web | Phần mềm cài đặt độc lập trên máy tính |
| Mục đích chính | Soạn thảo & Xem trước Markdown siêu nhanh | Trình soạn thảo mã nguồn đa năng (IDE/Editor) |
| Ưu điểm nổi bật | Không cần cài đặt, đồng bộ Google Drive tốt |Hệ sinh thái Extension phong phú, tích hợp Terminal & Git |
| Chạy code | Không hỗ trợ (chỉ xử lý văn bản .md) | Hỗ trợ biên dịch và chạy trực tiếp Python, JS, C++,... |

### Danh sách công việc (Task List) 
- [x] Tải xuống và cài đặt VS Code từ trang chủ.

- [x] Cài đặt Extension Python và Pylance.

- [ ] Chạy thử file Python đầu tiên.

- [ ] Push bài tập lên GitHub Repository theo đúng quy định.