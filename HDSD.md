CÁCH 1 : XAMPP
------------------------------------------------------
1. Copy thư mục code `vendor-management` vào `C:\xampp\htdocs\`.
2. Mở XAMPP Control Panel, nhấn [Start] cho Apache và MySQL.
3. Import Database:
   - Truy cập: http://localhost/phpmyadmin
   - Bấm [Import], chọn file `database_export.sql` (ở trong thư mục code) và bấm Go.
4. Mở trình duyệt web và truy cập: http://localhost/vendor-management/public


------------------------------------------------------
CÁCH 2: LARAGON 
------------------------------------------------------
1. Copy thư mục `vendor-management` vào `C:\laragon\www\`.
2. Mở Laragon, bấm [Start All].
3. Import Database (Giống hệt bước 3 của XAMPP ở trên).
4. Mở trình duyệt web và truy cập thẳng tên miền ảo cực xịn:
   http://vendor-management.test/public
   
THÔNG TIN ĐĂNG NHẬP 

Admin:
 - Tài khoản: admin
 - Mật khẩu:  123456

Quyền Quản Lý :
 - Tài khoản: manager_minh
 - Mật khẩu:  123456

Quyền Nhân Viên :
 - Tài khoản: staff_tuan
 - Mật khẩu:  123456
