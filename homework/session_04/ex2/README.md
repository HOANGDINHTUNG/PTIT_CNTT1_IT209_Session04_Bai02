# Bài 2: Quản lý nhánh và Giải quyết xung đột (Merge Conflict)

Dòng code 1: Nội dung ban đầu (Đã gộp và giải quyết xung đột từ 2 nhánh).

## Báo cáo các bước giải quyết xung đột thủ công:
1. Tạo nhánh `feature-update` và chỉnh sửa dòng 1 của file README.md, sau đó commit.
2. Quay lại nhánh `main`, chỉnh sửa chính dòng 1 của file README.md và commit.
3. Thực hiện lệnh `git merge feature-update` khi đang ở nhánh `main`, dẫn đến xung đột (Merge Conflict).
4. Mở file README.md, tìm và xóa các ký hiệu đánh dấu xung đột (`<<<<<<< HEAD`, `=======`, `>>>>>>> feature-update`).
5. Chỉnh sửa lại đoạn text bị xung đột thành nội dung cuối cùng thống nhất.
6. Lưu file, chạy lệnh `git add homework/session_04/ex2/README.md` và `git commit -m "Merge branch 'feature-update' into main"` để hoàn tất gộp nhánh.

## Ảnh minh chứng git log --graph --oneline
*(Học viên chèn ảnh chụp kết quả lệnh `git log --graph --oneline` vào đây)*
