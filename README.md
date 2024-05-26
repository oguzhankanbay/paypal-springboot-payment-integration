# PayPal Spring Boot Payment Integration

This project demonstrates how to integrate PayPal payment processing into a Spring Boot application.

**Features:** PayPal REST API integration, secure payment processing, Spring Boot framework, MVC architecture.

**Requirements:** Java 11 or higher, Maven, Spring Boot 2.5.4, PayPal SDK.

**Setup:**
\```bash
1. Clone the repository:
   git clone https://github.com/oguzhankanbay/paypal-springboot-payment-integration.git

2. Navigate to the project directory:
   cd paypal-springboot-payment-integration

3. Update PayPal credentials in `application.properties`:
   paypal.client.id=YOUR_CLIENT_ID
   paypal.client.secret=YOUR_CLIENT_SECRET

4. Build the project using Maven:
   mvn clean install

5. Run the application:
   mvn spring-boot:run
\```

**Usage:** Open your browser and go to `http://localhost:8080`. Follow the instructions to complete a payment.

**Acknowledgements:** [Spring Boot](https://spring.io/projects/spring-boot), [PayPal SDK](https://developer.paypal.com/docs/api/overview/)
