# Buổi 1:

## 1. Các lệnh của git

### 1.1 Khởi tạo:

+ `git init`: khởi tạo 1 **Git repository** mới trong thư mục

+ `git remote add origin <URL>`: liên kết repository (có địa chỉ URL) từ xa 
với repository Git local của mình 

+ `git clone <URL>`: sao chép 1 repository từ xa về máy

### 1.2 Tương tác:

+ `git status`: kiểm tra trạng thái (xem các thay đổi) của repository

+ `git add <tên tệp>`: thêm tệp cụ thể vào vùng chuẩn bị trước khi commit 
(**git add .** thêm tất cả các tệp)

+ `git rm <tên_tệp>`: xóa tệp 

+ `git commit -m "message"`: lưu những thay đổi 

+ `git log`: xem lịch sử thay đổi 

+ `git push origin main`: đẩy các thay đổi của nhánh main lên repository từ xa 

+ `git pull origin main`: lấy các thay đổi của repository từ xa và hợp nhất với nhánh main repository local

### 1.3 Nhánh:

+ `git branch`: kiếm tra vị trí hiện tại đang ở nhánh nào

+ `git branch <tên_nhánh>`: tạo nhánh mới

+ `git branch -d <tên_nhánh>`: xóa nhánh

+ `git merge <tên_nhánh>`: gộp nhánh khác vào nhánh hiện tại

+ `git checkout <tên_nhánh>`: chuyển sang tương tác với nhánh khác

+ `git push -u origin <branch>`: đẩy thay đổi nhánh lên và thiết lập theo dõi nhánh 
(các lệnh git push và git pull sẽ mặc định tương tác với nhánh này)


## 2. Các tương tác với file README.md

### 2.1 Định dạng văn bản:

+ `#`: tạo các heading

+ `+` `-` `*`: tạo gạch đầu dòng các ý 

+ `* *`: in nghiêng văn bản

+ `** **`: in đậm văn bản

+ `*** ***`: vừa in đậm, vừa in nghiêng văn bản

+ `~ ~`: gạch ngang văn bản

+ dùng 2 dấu ` để nhấn mạnh

### 2.2 Chèn link: `[tên link](link)` 


 