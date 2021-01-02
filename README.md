# Django Angular MySQL CRUD Example

https://loizenai.com/django-angular-mysql-crud-example/

![Django Angular MySQL CRUD Example](https://loizenai.com/wp-content/uploads/2020/12/Angular-Django-CRUD-MySQL-Example.png)

” Tutorial: Django Angular MySQL CRUD Example – Fullstack: Angular + Django Rest Framework + MySQL. ”

Django is a Python-based free and open-source web framework that follows the model-template-view architectural pattern. Angular is a TypeScript-based open-source web application framework led by the Angular Team at Google. In the tutorial, I introduce how to build a Angular Django CRUD RestAPIs Fullstack Project with POST/GET/PUT/DELETE requests using Django Rest Framework and MySQL database with step by step coding examples.

## Architecture – Django Angular CRUD Example

Here is an overview of Architecture Design for Django Angular CRUD Example with Django Rest Framework and MySQL:

![Overall Architecture – Angular Django RestAPIs FullStack Integration](https://loizenai.com/wp-content/uploads/2020/07/Overall-Architecture-Angular-Django-RestAPIs-FullStack-Integration.png)

- We build the backend Python Django Application that provides RestAPIs for POST/GET/PUT/DELETE Customer entities and store them in MySQL/PostgreSQL database.
- We implement the Angular CRUD Application that uses Angular HTTPClient to interact (call/receive requests) with Django backend’s RestAPIs and display corresponding page views in Browser

## Django RestAPIs CRUD MySQL Workflow – Django Angular MySQL CRUD Example

- Django Application interacts with MySQL/PostgreSQL database via Model layers.
- The Views are simply Python functions that take web requests and return web responses.
- URLs are used to mapping each request with the corresponding views.

![Django RestAPIs Workflow Architecture](https://loizenai.com/wp-content/uploads/2020/07/Django-RestAPIs-Workflow-Architecture.png)

## Django RestAPI CRUD Project Structure – Django Angular MySQL CRUD Example

![Django Project Structure](https://loizenai.com/wp-content/uploads/2020/07/Django-Project-Structure.png)

The Django RestAPIs project includes 2 folders:

- djangoLoiZenAiRestAPIs is a main project folder
- customers is an application folder

## Angular Frontend Architecture – Django Angular MySQL CRUD Example

![Angular Frontend Architecture – Django Angular MySQL CRUD Example](https://loizenai.com/wp-content/uploads/2020/07/Angular-Application-Architecture.png)

Angular CRUD Application is designed with 3 main layers:

- Service Layer is used to define Angular Common Services and HttpClient Services to interact with RestAPIs
- Component Layer is used to define Angular Components to show views in Browser for interacting with Users
- Router Layer is used to route URLs mapping with the corresponding Angular Components

## Angular CRUD Project Structure – Django Angular MySQL CRUD Example
![Angular Project Structure](https://loizenai.com/wp-content/uploads/2020/07/Angular-Project-Structure-1.png)

Angular CRUD Application defines 3 components, 2 services, 1 routers, and 2 data models:

– Components:

add-customer component is used to add a new customer to system
list-customer component is used to show all customers on view pages, delete a customer and update a customer
message component is used to define a view to show logging message on browser
– Services:

customer.service.ts defines POST/GET/PUT/DELETE HTTP requests to Django RestAPIs with the built-in Angular HttpClient.
message.service.ts defines an array storage to log all messages when Angular CRUD App running
– Router: app-routing.module.ts defines how to map a corresponding Angular component with an URL.

– Models:

customer.ts defines the main data model of our application.
message.ts defines the response data model between Django RestAPIs and Angular application.


## Angular Django MySQL Example – Project Goal – Django Angular MySQL CRUD Example

Here is a list of goals for Angular Django CRUD Example with Django Rest Framework and MySQL database:

– Add a Customer Entities from Angular Client:

![Goal 1 – Add a Customer Entity](https://loizenai.com/wp-content/uploads/2020/07/Goal-1-Add-a-Customer-Entity.png)

– List All Customer’s entities:

![Goal 2 – List All Customer’s entities from Angular Client](https://loizenai.com/wp-content/uploads/2020/07/List-All-Customers-entities-from-Angular-Client.png)

– Details a Customer:

![Goal 3 – Angular shows details of a Customer entity](https://loizenai.com/wp-content/uploads/2020/07/Angular-shows-details-of-a-Customer-entity.png)

– Update a Customer:

![Goal 4 – Angular update a Customer Entity](https://loizenai.com/wp-content/uploads/2020/07/Angular-Client-Update-a-Customer-Entity.png)

– Delete a Customer:

![Goal 5 – Angular Client delete a Customer entity](https://loizenai.com/wp-content/uploads/2020/07/Goal-5-Angular-Client-delete-a-Customer-entity.png)

## Tutorial

[Angular Django MySQL CRUD EXampple](https://loizenai.com/django-angular-mysql-crud-example/)

## Related posts

- [Angular Nodejs PostgreSQL CRUD Example](https://loizenai.com/angular-10-nodejs-postgresql-crud-example-using-express-restapis-sequelize-tutorial/)
- [SpringBoot + Angular + PostgreSQL CRUD Example](https://loizenai.com/angular-10-nodejs-postgresql-crud-example-using-express-restapis-sequelize-tutorial/)
- [Django Angular 10 CRUD Example – MySQL](https://loizenai.com/angular-10-django-mysql-rest-crud-api-example/)
- [Django Angular 8 MySQL CRUD Example](https://loizenai.com/angular-10-django-mysql-rest-crud-api-example/)
- [Django Angular 9 PostgreSQL CRUD Example](https://loizenai.com/django-angular-9-postgresql-crud-example/)
- [Django Angular 9 MySQL CRUD Example](https://loizenai.com/django-angular-9-postgresql-crud-example/)
- [Django Angular PostgreSQL CRUD Example](https://loizenai.com/django-angular-9-postgresql-crud-example/)
- [Django Angular 11 MySQL CRUD Example](https://loizenai.com/django-angular-11-mysql-crud-example/)
- [Django Angular 11 PostgreSQL CRUD Example](https://loizenai.com/django-angular-11-mysql-crud-example/)
- [Angular Springboot Jwt Authentication Example](https://loizenai.com/angular-10-spring-boot-jwt-authentication-example/)
- [SpringBoot Jwt authentication Example](https://dev.to/loizenai/angular-11-springboot-jwt-authentication-example-1h9f)

## Youtube
- https://www.youtube.com/watch?v=dTR-41_jMvc&t=46s
- https://www.youtube.com/watch?v=lb5LVzJbquI&t=476s
- https://www.youtube.com/watch?v=DoV8xfA8WBo&t=30s
- https://www.youtube.com/watch?v=rYmf_MthobU&t=376s
- https://www.youtube.com/watch?v=7ZfInOvFsz0&t=1308s

