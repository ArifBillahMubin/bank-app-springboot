# Bank Application using Java Spring Boot 🚀

## Project Overview 🏦
This is a simple bank application built using Java Spring Boot with MySQL integration. It allows users to register, log in, check their balance, deposit, withdraw, transfer money, and view transaction history. The frontend is built using HTML and CSS.

## Features ✨
- **User Registration & Login**: Users can register with a username and password, then log in with the same credentials.
- **Dashboard**: Displays the user's current balance and account details.
- **Deposit & Withdraw**: Users can deposit and withdraw money from their accounts.
- **Money Transfer**: Users can transfer money to another account.
- **Transaction History**: Users can view their past transactions.
- **Navigation Bar**: Contains options for Dashboard, Transactions, and Logout.
- **Logout**: Users can securely log out of their accounts.

## Technologies Used 🛠️
- **Backend**: Java Spring Boot
- **Database**: MySQL
- **Frontend**: HTML, CSS

## Installation & Setup ⚙️
### Prerequisites 📌
- Java (JDK 11 or later)
- MySQL Server
- Spring Boot
- Maven

### Steps to Run the Project 🚀
1. **Clone the repository**:
   ```sh
   git clone https://github.com/ArifBillahMubin/bank-application.git
   cd bank-application
   ```

2. **Configure MySQL Database**:
   - Create a database in MySQL named `bank_db`.
   - Update `application.properties` with your MySQL credentials.

3. **Build & Run the Spring Boot Application**:
   ```sh
   mvn spring-boot:run
   ```

4. **Access the Application**:
   - Open your browser and go to `http://localhost:8080`

## API Endpoints 🌐
| Endpoint             | Method | Description               |
|----------------------|--------|---------------------------|
| `/register`         | POST   | User registration        |
| `/login`            | POST   | User login               |
| `/dashboard`        | GET    | View account details     |
| `/deposit`          | POST   | Deposit money            |
| `/withdraw`         | POST   | Withdraw money           |
| `/transfer`         | POST   | Transfer money           |
| `/transactions`     | GET    | View transaction history |
| `/logout`          | GET    | Logout user              |


## Author 👨‍💻
**Md. Arif Billah Mubin**  
🎓 **University**: Green University of Bangladesh  
📧 **Email**: arifbillahmubin@gmail.com  
🔗 **GitHub**: [ArifBillahMubin](https://github.com/ArifBillahMubin)
