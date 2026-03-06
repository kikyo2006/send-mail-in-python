# Send Mail in Python (SMTP with String Templates)

[![GitHub stars](https://img.shields.io/github/stars/kikyo2006/send-mail-in-python.svg)](https://github.com/kikyo2006/send-mail-in-python/stargazers)
[![GitHub license](https://img.shields.io/github/license/kikyo2006/send-mail-in-python.svg)](https://github.com/kikyo2006/send-mail-in-python/blob/master/LICENSE)

**EN:** A simple and efficient Python script to send bulk emails using SMTP and Python's built-in string templates. Perfect for automated notifications or simple newsletters.

**VN:** Script Python đơn giản và hiệu quả để gửi email hàng loạt qua SMTP, sử dụng string templates có sẵn của Python. Phù hợp cho việc gửi thông báo tự động hoặc bản tin đơn giản.

---

## 🚀 Features (Tính năng)

- **Template Support:** Use external `.txt` or `.html` files for email content. (Sử dụng tệp bên ngoài cho nội dung email).
- **Bulk Sending:** Send emails to multiple recipients from a list. (Gửi email cho nhiều người từ danh sách).
- **SMTP Integration:** Works with Gmail, Outlook, and other SMTP providers. (Tương thích với Gmail, Outlook và các nhà cung cấp SMTP khác).

## 🛠️ Setup (Cài đặt)

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/kikyo2006/send-mail-in-python.git](https://github.com/kikyo2006/send-mail-in-python.git)
   cd send-mail-in-python
   ```
2. **Configure your credentials:**
Open app.py and update your SMTP settings (server, port, email, and password).
Note: For Gmail, use an App Password.

3. **Prepare your recipient list:**
Add email addresses to listmails.txt, one per line.

📖 Usage (Cách dùng)
Simply run the script with:
   ```bash
python app.py
   ```
