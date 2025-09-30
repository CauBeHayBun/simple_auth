simple_auth
# Simple Authentication

Dự án này minh họa cách sử dụng **Basic Auth** và **Cookie Auth** trong Node.js để xác thực người dùng.

---

## Cách chạy
```bash
cd simple_auth
npm install
node basic_auth.js     # chạy Basic Auth
node cookie_auth.js    # chạy Cookie Auth


Server chạy tại http://localhost:3000

Test bằng Postman
1. Basic Auth

Method: GET

URL: http://localhost:3000

Tab Auth → chọn Basic Auth

Username: admin

Password: 12345

2. Cookie Auth

Method: GET

URL: http://localhost:3000

Khi gửi request, server trả về Set-Cookie trong response headers

Cookie được lưu để quản lý session

cd simple_auth
npm install
node basic_auth.js     # chạy Basic Auth
node cookie_auth.js    # chạy Cookie Auth


Server chạy tại http://localhost:3000

Test bằng Postman
1. Basic Auth

Method: GET

URL: http://localhost:3000

Tab Auth → chọn Basic Auth

Username: admin

Password: 12345

2. Cookie Auth

Method: GET

URL: http://localhost:3000

Khi gửi request, server trả về Set-Cookie trong response headers

Cookie được lưu để quản lý session

<img width="959" height="607" alt="image" src="https://github.com/user-attachments/assets/5d190004-19f9-470f-8a5f-a1e975fb1e0e" />
<img width="767" height="494" alt="image" src="https://github.com/user-attachments/assets/ea38f28b-7540-4cb2-8ee0-e2a66734bb10" />
<img width="1004" height="620" alt="image" src="https://github.com/user-attachments/assets/b6eac41c-3e1b-498f-addd-1e6e1b2ed68c" />




