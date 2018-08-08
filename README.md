# demo
#### Backend: Spring, Spring Security 
#### Frontend: React

##### Steps to setup back and front parts

1. Clone the application <br>
```
git clone https://github.com/kdmts/demo.git
cd demo
```

2. Create MySQL database
```
create database application
```
3. Update src/resources/application.properties file with your actual username and password
4. Run the application 
```
mvn spring-boot:run
```
5. Add roles
```
INSERT INTO roles(name) VALUES('ROLE_USER');
INSERT INTO roles(name) VALUES('ROLE_ADMIN');
```
6. Run Front part
```
cd client
npm install
npm start
```
7. Open localhost:3000


