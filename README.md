# PW-Manager
This project is command-line interface project for a password management system enabling users to create accounts and log in using a username and password.

How It Works
<div></div>
    Account Creation: Users can create an account by providing a username and password. The password is securely hashed using SHA-256 before it is stored. This ensures that even if the data is compromised, the actual passwords are not easily retrievable.
    <div></div>
    Login: Users can log in by entering their username and the password they set up. The system hashes the provided password and compares it to the stored hash. If they match, the login is successful; otherwise, it denies access, ensuring that only users with valid credentials can log in.
    <div></div>
    Secure Password Handling: To enhance security, the script uses the getpass library to hide password input, preventing it from being visible or easily intercepted during entry.
    <div></div>
    SHA-256 Hashing: The use of SHA-256 for password hashing adds a layer of security, making it computationally infeasible to reverse-engineer the original password from the hash.
    <img width="796" alt="Screenshot 2024-03-06 at 4 55 07 PM" src="https://github.com/XVI-Adam/PW-Manager/assets/102603088/e24ce40b-5fe8-428f-a789-c0a0ee0b42ff">
