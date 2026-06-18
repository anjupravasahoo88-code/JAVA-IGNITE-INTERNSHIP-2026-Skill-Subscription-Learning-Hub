# Viva / Interview Questions

##  Basic

- What is Spring Boot?
- >Spring Boot is a Java framework used to build backend applications quickly. It reduces configuration time by providing default settings and embedded servers like Tomcat.

- What is MVC architecture?
- >MVC (Model–View–Controller) is a design pattern used to separate an application into three parts:
Model: Data and database logic
View: UI (JSP pages)
Controller: Handles user requests and controls flow


---

##  Intermediate

- What is Service layer?
- > Service layer contains business logic of the application. It acts as a bridge between Controller and Repository.
  
- What is Repository in Spring Data JPA?
- > Repository is used to interact with the database. It provides ready-made methods like save(), findAll(), deleteById() without writing SQL queries.

- Difference between GET and POST?
- > GET:
Used to fetch data
Data visible in URL
Less secure
POST:
Used to send data
Data hidden in request body
More secure

---

##  Advanced (Project Based)

- How does subscription flow work?
- > In the project, the user selects a subscription pack, submits the request, and the controller processes it through service layer, saves it in database, and shows confirmation using JSP.
  
- How do you link User and SkillPack?
- > User and SkillPack are linked using relationships like One-to-Many or Many-to-Many in JPA. This allows one user to subscribe to multiple skill packs.

- Why do we use Service layer?
- > Service layer is used to keep business logic separate from controller. It makes the code clean, reusable, and easy to maintain.
  
- How does JSP get data from Controller?
- > Controller sends data using Model object. JSP accesses this data using Expression Language (EL) like ${data}.
