
# Pay Application

Overview:
The Pay Application is a Spring Boot application designed to manage transactions and users. It provides functionalities to add transactions, delete failed transactions, add users, and retrieve information about users' transactions.


## Features

Transaction Management

- Add a new transaction.
- Delete all failed transactions.
 User Management

- Add a new user.
- Retrieve the total number of successful transactions for a -specific user.
- Get the user with the maximum refunds.



## Tech Stack

- **Spring Boot:** Framework used to create the application.
- **Spring Data JPA:** For data persistence.
- **MySQL:** Database used to store user and transaction data.
- **Springdoc OpenAPI:** For API documentation.


## Installation
- Clone the repository: git clone https://github.com/your-repo/pay-application.git
- Navigate to the project directory: cd pay-application
- Configure the MySQL database in the application.properties file:spring.datasource.url=jdbc:mysql://localhost:3306/pay?createTableIfNotExists=true
spring.datasource.username=root
spring.datasource.password=yourpassword
spring.jpa.hibernate.ddl-auto=update
spring.datasource.driver-class-name=com.mysql.cj.jdbc.Driver
springdoc.swagger-ui.path=/swagger-ui-custom.html
spring.mvc.pathmatch.matching-strategy=ANT_PATH_MATCHER
- Build and run the application: mvn spring-boot:run
## License

This project is licensed under the MIT License. See the [LICENSE](https://choosealicense.com/licenses/mit/) file for details.


## Contribution
Contributions are welcome! Please create a pull request or open an issue to discuss any changes.