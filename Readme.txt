Các bước đầu tiên khi mới tạo file

// b1 tạo tệp .git trong folder
    git init
// b2 add file, có 2 cách add file
    //thêm tất cả file  
    git add .
    //thêm file theo chỉ định
    git add README.md
// b3 viết lại ghi chú đầu tiên
    git commit -m "nội dung ghi chú"
// b4 Đổi tên nhánh hiện tại thành main
    git branch -M main
        // note: Git branch là một câu lệnh để quản lý các nhánh trong kho lưu trữ của bạn. Tùy chọn -M là viết tắt của --move --force, nghĩa là di chuyển nhánh hiện tại đến một nhánh mới và ghi đè lên nếu nhánh mới đã tồn tại. Main là tên của nhánh mới mà bạn muốn đổi.
// b5 thêm một kho lưu trữ từ xa
    git remote add origin https://github.com/truonghuynhcan/github_demo.git
// b6 đẩy các commit từ nhánh main cụ bộ của bạn lên nhánh main từ xa của bạn trên github
    git push -u origin main
// hoàn tất ----------------------------------------------------------

