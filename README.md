# JWT_STARTER
Starter for a jwt spring boot project.

# SETUP
Under "resources" in the application properties, on the second line, change the IP in spring.datasource.url=jdbc:mysql://111.111.111.11:8080/test
to the SQL server's IP and port. Then, update spring.datasource.username= and spring.datasource.password= with the appropriate username and password.
Next, under Biscuit_corpo.app.jwtSecret=, add a JWT secret. It must be 256 bits long and contain no special characters.

Then, test run to see if you're connected. Once you've connected successfully, Spring Boot will generate your tables in the database.
All you have to do is manually add this into the roles table.

![image](https://github.com/KevinKohutek04/JWT_STARTER/assets/144548080/3747dbde-d243-499e-9cca-cfb7d189b969)

# HOW TO USE
Open up Postman, then send a POST request to signup like this.

![image](https://github.com/KevinKohutek04/JWT_STARTER/assets/144548080/6fac0af1-b8a8-471b-811d-ede988e83226)

To log in, you do this, and you'll receive back this information.

![image](https://github.com/KevinKohutek04/JWT_STARTER/assets/144548080/04e42127-c8a2-48f1-bff8-d79abf41d9ae)
