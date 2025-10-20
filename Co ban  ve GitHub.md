# Làm việc cùng GitHub

## Bạn có biết GitHub không?

GitHub là một nền tảng trực tuyến dùng để lưu trữ, quản lý và chia sẻ tài liệu, mã nguồn hoặc bất kỳ tệp tin nào. Khi sử dụng GitHub, bạn có thể:

- Lưu trữ tài liệu, file dự án dễ dàng trên “đám mây” (cloud), an toàn và truy cập mọi lúc mọi nơi.
- Theo dõi lịch sử chỉnh sửa, giúp bạn kiểm soát các thay đổi trong tài liệu.
- Chia sẻ tài liệu với bạn bè, đồng nghiệp hoặc công khai cho cộng đồng cùng đọc hoặc đóng góp.
- Làm việc nhóm hiệu quả: nhiều người có thể cùng sửa đổi, cập nhật tài liệu và kết hợp thay đổi lại với nhau.
- Tạo các bản sao lưu (backup) tự động cho tài liệu của bạn.

Tóm lại, GitHub không chỉ dành cho lập trình viên mà còn cực kỳ hữu ích trong việc lưu trữ, quản lý và phối hợp làm việc trên các loại tài liệu số khác nhau.

## Cách sử dụng GitHub

Để sử dụng GitHub, bạn có thể làm theo các bước cơ bản sau:

1. **Tạo tài khoản GitHub**
   - Truy cập https://github.com và đăng ký một tài khoản miễn phí.
2. **Cài đặt Git trên máy tính**
   - Tải và cài đặt Git từ https://git-scm.com nếu chưa có.
3. **Tạo kho lưu trữ (repository) mới**
   - Đăng nhập vào GitHub, nhấn "New" để tạo một repository mới cho dự án/tài liệu của bạn.
4. **Kết nối dự án trên máy với repository GitHub**
   - Mở Terminal (hoặc Git Bash), chuyển đến thư mục dự án của bạn và sử dụng các lệnh:
     - `git init` (khởi tạo dự án)
     - `git remote add origin <link-repo-GitHub>` (kết nối với repo trên GitHub)
5. **Đưa (commit) và đẩy (push) dữ liệu lên GitHub**
   - Lưu các thay đổi: `git add .` rồi `git commit -m "Mô tả thay đổi"`
   - Đẩy lên GitHub: `git push -u origin main` (hoặc `master` tùy repo)
6. **Làm việc nhóm**
   - Mời bạn bè/cộng sự tham gia bằng cách thêm họ vào repository (Settings → Collaborators).
   - Sử dụng nhánh (branch), fork, và pull request để phối hợp chỉnh sửa và tổng hợp thay đổi.
7. **Theo dõi và cập nhật**
   - Sử dụng `git pull` để nhận các cập nhật mới nhất từ repository.
   - Theo dõi lịch sử thay đổi, kiểm tra và khôi phục các phiên bản cũ khi cần.

**Lưu ý:** Ngoài giao diện dòng lệnh, bạn cũng có thể thao tác với GitHub qua giao diện web hoặc app GitHub Desktop.

## Sử dụng GitHub Desktop để làm việc dễ dàng hơn với GitHub

Nếu bạn không quen với dòng lệnh hoặc muốn thao tác trực quan hơn khi làm việc với GitHub (như các bước ở trên), bạn có thể sử dụng phần mềm **GitHub Desktop**. Đây là ứng dụng hỗ trợ bạn quản lý, đồng bộ dự án với GitHub chỉ bằng vài thao tác chuột.

**Các bước liên hệ với quy trình sử dụng GitHub đã nêu phía trên:**
1. **Tải và cài đặt GitHub Desktop:** 
   - Truy cập https://desktop.github.com và tải về cài đặt như phần mềm thông thường.
2. **Đăng nhập tài khoản GitHub** để đồng bộ các kho lưu trữ (repository) của bạn.
3. **Clone (tải về) repository từ GitHub:** Thay vì dùng lệnh `git clone`, bạn chỉ cần chọn repository và nhấn "Clone" để tải về máy.
4. **Quản lý, chỉnh sửa và commit/push dễ dàng:**
   - Giao diện hiển thị các file, thay đổi và lịch sử commit rõ ràng. 
   - Chọn file, ghi chú thay đổi và nhấn "Commit", sau đó nhấn "Push" để gửi dữ liệu lên GitHub, hoàn toàn không cần dùng câu lệnh.
5. **Hỗ trợ làm việc nhóm:** Dễ dàng nhận các bản cập nhật mới nhất (Pull), tạo branch mới, tạo Pull Request và xem lịch sử thay đổi trên giao diện.

**Tóm lại:** GitHub Desktop là một cách tiện lợi, trực quan để thao tác với GitHub — phù hợp với cả người mới bắt đầu lẫn các thành viên muốn tiết kiệm thời gian, và mọi chức năng nền tảng (commit, push, pull, tạo branch, làm việc nhóm...) đều liên kết chặt chẽ với những gì bạn đã học về GitHub phía trên.