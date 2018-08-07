# demo
<p>Backend: Spring, Spring Security 
<p>Frontend: React

1. Clone the application <br>
<code>
  git clone https://github.com/kdmts/demo.git
  cd demo
</code>

2. Create MySQL database
3. Change application.properties file (set your username and password)
4. Run the application mvn spring-boot:run
5. Add roles
INSERT INTO roles(name) VALUES('ROLE_USER');
INSERT INTO roles(name) VALUES('ROLE_ADMIN');
6. cd client 
npm install
npm start
