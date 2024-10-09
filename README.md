# OWASP Juice Shop Ethical Hacking

## Login as administrator using SQL injection
Intercepted the login request and injected a SQL payload in place of the email address to log in as the administrator without a password.
<img width="982" alt="1" src="https://github.com/user-attachments/assets/02df04d7-f217-4df5-9fbc-1cac7c4abf5c">

<img width="1310" alt="2" src="https://github.com/user-attachments/assets/04497bc1-bf15-4a3f-9bf0-3993b84fd7aa">

<img width="982" alt="3" src="https://github.com/user-attachments/assets/e8dbd84a-5be3-4e89-9450-f9d5c9b2616c">

## Brute-force administrator password
Used a common password list from SecLists as the payload to perform a brute-force attack on the administrator login password.
<img width="1342" alt="4" src="https://github.com/user-attachments/assets/9323bd9a-5dfb-486c-ba4d-44f0e0752fc7">

<img width="1407" alt="5" src="https://github.com/user-attachments/assets/519d35fb-ff26-4b38-b639-e4a0bf07551a">

## Database schema exfiltration
Used the UNION keyword to combine the Products and sqlite_master tables, allowing the extraction of the database schema.
<img width="1703" alt="6" src="https://github.com/user-attachments/assets/e0d883c8-d110-41f4-96c8-4be25ac32924">
