Hướng dẫn cấu hình gửi email - Wordpress 
========================================

**Cấu hình gửi email** 

| Tại giao diện quản trị website, truy cập vào menu **Settings -> WP
  SMTP** như hình sau: |wp smtp|

| Các bạn có thể sử dụng tài khoản
  yahoo, google, hotmail,..để miễn phí gửi email cho website của mình.
   Tuy nhiên, chúng tôi đề nghị các bạn sử dụng tài khoản yahoo, ngày
  nay google đã bảo mật đăng nhập sử dụng cho bên thứ ba do vậy cách đơn
  giản và dễ nhất là sử dụng Yahoo SMTP.
| Tiếp theo, chúng ta điền thông tin Yahoo SMTP vào form: |image1| 

Giải thích:

-  From: địa chỉ yahoo mail của bạn.
-  From Name: tên người gửi.
-  SMTP Host: smtp.mail.yahoo.com
-  SMTP Secure: SSL
-  SMTP Port: 465
-  SMTP Authentication: Yes
-  Username: yahoo mail của bạn
-  Password: mật khẩu đăng nhập yahoo

| Nhấn nút **Save Changes** khi hoàn thành.
| **Kiểm tra hoạt động**\ Giờ đến lúc bạn kiểm tra chức năng gửi mail có
  hoạt động hay không, bằng cách kéo xuống phía dưới bạn nhìn thấy form:
  |image2|
| Điền địa chỉ email đến (To:), chủ đề (Subject:) và nội dung
  (Message:). Sau đó nhấn nút **Send Test** để bắt đầu gửi email, nếu
  thành công bạn sẽ nhận được thông báo: "Message sent!" xuất hiện ở bên
  trên.
| Câu trả lời này có giúp ích cho bạn không? Yes NoSend feedback Sorry
  we couldn't be helpful. Help us improve this article with your
  feedback.

.. |wp smtp| image:: https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/5009176628/original/smtp-wp.jpg?1425354111
   :class: inline-image
.. |image1| image:: https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/5009176781/original/screenshot-2.png?1425354397
   :class: inline-image
.. |image2| image:: https://s3.amazonaws.com/cdn.freshdesk.com/data/helpdesk/attachments/production/5009176891/original/test-wp-smtp.jpg?1425354706
   :class: inline-image
