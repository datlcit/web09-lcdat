RULES CHUNG KHI SỬ DỤNG GIT
Quy tắc đặt tên nhánh khi thi công chức năng:
feature/[Mô tả ngắn gọn về chức năng]
Ví dụ: Thực hiện thi công: Yêu cầu nhập mã captcha khi đăng nhập không thành công nhiều lần.

Tên nhánh sẽ là: feature/login-captcha

Quy tắc đặt tên nhánh khi fix bug:
bugfix/[Mô tả ngắng gọn về bug]
Ví dụ: Thực hiện fix bug: Lỗi không biển thị đủ thông tin trên file báo cáo thuế.

Tên nhánh sẽ là: bugfix/miss-data-report-tax

Quy tắc viết comment khi commit:
type: subject (Bắt buộc)
body (Tùy chọn)
1. Type:

feat - Một tính năng mới (feature)
fix - Fix một bug
docs - Thay đổi tài liệu
style - Mọi thứ liên quan tới style
refactor - Refactor code
test - Mọi thứ liên quan tới test
chore - Cập nhật các cấu hình build, cấu hình ứng dụng,...
2. Subject:

Không được dài quá 50 ký tự, bắt đầu bằng chữ hoa và không được kết thúc bằng dấu chấm.
Sử dụng câu mệnh lệnh để mô tả những gì commit thực hiện thay vì những gì nó đã làm. Ví dụ: sử dụng "thay đổi" thay vì "đã thay đổi"
3. Body:

Sử dụng khi commit cần giải thích thêm. Sử dụng để giải thích những gì (What), tại sao (Why) của commit này, không sử dụng làm thế nào (How).
Cần một dòng trống giữa type: subject, mỗi dòng không quá 72 ký tự.
Ví dụ

feat: Hiển thị captcha khi người dùng đăng nhập nhiều lần
Captcha sẽ được thị sau khi người dùng đăng nhập sai n lần. Ngăn không cho phép người dùng viết các công cụ tự động dò mật khẩu.
Số lần đăng nhập sai được cấu hình tại file confile với khóa là: MaxLoginFail.
