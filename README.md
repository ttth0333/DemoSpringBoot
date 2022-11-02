# DemoSpringBoot
Viết chương trình chuyển tiền online với yêu cầu như sau:
Thông tin user:
- Mã người dùng (kiểu số)
- Tên người dùng (kiểu chuỗi)
- Số tiền trong tài khoản (kiểu số)
Chức năng:
- Thêm mới user.
- Cập nhật thông tin user.
- Tìm kiếm user theo id.
 Chức năng chính: Chuyển tiền giữa hai tài khoản

 POJO bean Account : 
- id : (kiểu số)
- ownerName: Tên tài khoản (Kiểu chuỗi).
- balance: Số dư (kiểu số thực).
 Lớp AccountDao bao gồm list chứa danh 
sách Account và 3 phương thức:
- insert : Thêm mới account.
- update: Cập nhật account.
- find: Tìm account theo id.
 Lớp AccountService gồm 2 phương 
thức:
- transferMoney: Chuyển tiền.
- getAccount: Lấy thông tin account 
theo id.
Cấu hình Bean theo cả 2 cách XML 
Config và Java Cofig.
Áp dụng Denpendency Injection và 
thực hiện test các chức năn
