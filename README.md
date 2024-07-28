# Section-1
# 1. Intro
Section Name Repo URL
## Introduction to Spring Boot
- https://github.com/shabbirdwd53/spring-bootmicroservices
## Restful Web Services with Spring Boot 
- https://github.com/shabbirdwd53/spring-bootmicroservices
## Spring Data JPA with Spring Boot 
- https://github.com/shabbirdwd53/spring-bootmicroservices
## Microservices Implementation 
- https://github.com/shabbirdwd53/spring-bootmicroservices
## Docker with Microservices 
- https://github.com/shabbirdwd53/spring-bootmicroservices/
tree/docker
## Kubernetes with Microservices 
- https://github.com/shabbirdwd53/spring-bootmicroservices/
tree/kubernetes
## Kubernetes without Service Registry
-  https://github.com/shabbirdwd53/spring-bootmicroservices/

## OrderService 
- https://github.com/shabbirdwd53/OrderServic
e
## PaymentService 
- https://github.com/shabbirdwd53/PaymentSer
vice
## ProductService
-  https://github.com/shabbirdwd53/ProductServ
ice
## CloudGateway 
- https://github.com/shabbirdwd53/CloudGatew
ay
## ConfigServer
-  https://github.com/shabbirdwd53/ConfigServe
r
## ms-initial-setup 
- https://github.com/shabbirdwd53/ms-initial-set
up
# Section-2
# 3 Intro to Spring boot?
- jab java introduced hua to log java EE edition like jsp, servelet concept use karke app banane lage.
- uske upar kayi sare framework aaye like Struts, live Free, Spring
- Spring famous tha but ismee lot of configuration karna padta tha.
- So spring boot introduced to reduce the headache.
# 4 What is dependency injection?
![alt text](image.png)![alt text](image-1.png)![alt text](image-2.png)
# 5. Spring Intializer
![alt text](image-3.png)![alt text](image-4.png)![alt text](image-5.png)
# 6. Setting up ide for the spring boot project
![alt text](image-6.png)![alt text](image-7.png)![alt text](image-8.png)
# 7. Creating First HelloWorld Api
### We are creating Rest endpoint to serve the request.
- we are going to create a controller which handle http request 

![alt text](image-9.png)![alt text](image-10.png)![alt text](image-11.png)
# 8. Spring boot Starters Project
![alt text](image-12.png)
# 9. Understanding Spring Boot Magic
### How Spring-boot works internally?
![alt text](image-13.png)![alt text](image-14.png)![alt text](image-15.png)
### Agar aapko apne project mein jpa use karna hai so kya karna honga?
![alt text](image-16.png)![alt text](image-17.png)
### Q)Spring ko pata kaise chal rha hai ki property provide karni hai?
![alt text](image-18.png)
### Q)  How about running your application?
![alt text](image-19.png)
### About @SpringBootConfiguration annotation
![alt text](image-20.png)![alt text](image-21.png)
### About run() method
#### This run method help you to start your application.
![alt text](image-22.png)
# 10. Embedded Server
### ***Normal flow***
![alt text](image-23.png)![alt text](image-24.png)![alt text](image-25.png)
### ***Inside pom.xml***
![alt text](image-26.png)![alt text](image-27.png)
### ***Agar hume Jetty  server use karna ho tab?***
![alt text](image-28.png)
#### Remember:
![alt text](image-29.png)
### ***Remove Manually***
![alt text](image-30.png)
### ***Add jetty server dependency***
![alt text](image-31.png)![alt text](image-32.png)![alt text](image-33.png)
### ***Change port:***
![alt text](image-34.png)![alt text](image-35.png)![alt text](image-36.png)
### ***Exculsion automatically kaise kare***
#### Add plugin
![alt text](image-37.png)![alt text](image-38.png)
#### After removing all tomcat exclusion
####  Hum automatically exclusion karenge
![alt text](image-39.png)![alt text](image-40.png)![alt text](image-41.png)
# 11. Exploring Spring boot actuator
![alt text](image-42.png)![alt text](image-43.png)![alt text](image-44.png)
# 12. Exploring Spring Boot dev tools.
![alt text](image-45.png)![alt text](image-46.png)
![alt text](image-47.png)![alt text](image-48.png)![alt text](image-49.png)
# Section-3
![alt text](image-50.png)![alt text](image-51.png)![alt text](image-52.png)![alt text](image-53.png)![alt text](image-54.png)![alt text](image-55.png)
![alt text](image-56.png)![alt text](image-57.png)![alt text](image-60.png)![alt text](image-58.png)![alt text](image-59.png)
# Section-4
# 16. What is rest?
![alt text](image-61.png)![alt text](image-62.png)![alt text](image-63.png)![alt text](image-64.png)
# 17. Creating a hello world service?
![alt text](image-65.png)![alt text](image-66.png)
![alt text](image-67.png)
# 18. Enhancing Hello World Servie to return an Object?
## Target:Create a new endpoint where we can handle the object.
### Create a User class which have some fields and return that user
![alt text](image-68.png)![alt text](image-69.png)
![alt text](image-70.png)![alt text](image-71.png)![alt text](image-72.png)
### Varaition-1
#### by default it's always Get method
![alt text](image-73.png)
### What happen if you define this method as post.
![alt text](image-74.png)![alt text](image-75.png)![alt text](image-76.png)
### Var-2
![alt text](image-77.png)![alt text](image-78.png)
# 19. Working with Path variables?
## Path variable is a path that you define in Uri.
![alt text](image-79.png)![alt text](image-80.png)
## U can also define multiple path variables.
![alt text](image-81.png)![alt text](image-82.png)
## Hume name pasand nhi hai varible ka path parameter wale.. hum change karenge
![alt text](image-83.png)![alt text](image-84.png)
# 20. Working with Request Params?
```
When data is mandatory u take it using Path variable
When data is not mandatory u take it using Request Parameter
Request Parameter is defined with ? ie. query parameter
and multiple query parameter are separated by &
````
![alt text](image-85.png)![alt text](image-86.png)![alt text](image-87.png)
## Var-2
![alt text](image-88.png)![alt text](image-89.png)
## Var-3 ab hume sirf email chaiye na ki emailId
![alt text](image-90.png)![alt text](image-91.png)
## Var-4 if i don't want email as a mandatory thing, agar hum nahi bhi de to kaam chal jave
![alt text](image-92.png)![alt text](image-93.png)
## Var-5 i don't wont to pass email id and also don't wont null retrun
![alt text](image-94.png)![alt text](image-95.png)
# 21. Impelementing Post method to create Employee Resource.
![alt text](image-96.png)![alt text](image-97.png)![alt text](image-98.png)![alt text](image-99.png)
![alt text](image-100.png)![alt text](image-101.png)![alt text](image-102.png)![alt text](image-103.png)![alt text](image-104.png)![alt text](image-105.png)![alt text](image-106.png)
![alt text](image-107.png)
### Employee class
```java
package com.radhaCodeBuffer.springbootdemo.model;

public class Employee {

    private String employeeId;
    private String firstName;
    private String lastName;
    private String emailId;
    private String department;

    public String getFirstName() {
        return firstName;
    }

    public void setFirstName(String firstName) {
        this.firstName = firstName;
    }

    public String getLastName() {
        return lastName;
    }

    public void setLastName(String lastName) {
        this.lastName = lastName;
    }

    public String getEmailId() {
        return emailId;
    }

    public void setEmailId(String emailId) {
        this.emailId = emailId;
    }

    public String getDepartment() {
        return department;
    }

    public void setDepartment(String department) {
        this.department = department;
    }

    public String getEmployeeId() {
        return employeeId;
    }

    public void setEmployeeId(String employeeId) {
        this.employeeId = employeeId;
    }
}
```
### Employee Controller
```java
package com.radhaCodeBuffer.springbootdemo.controller;

import com.radhaCodeBuffer.springbootdemo.model.Employee;
import com.radhaCodeBuffer.springbootdemo.service.EmployeeService;
import org.springframework.beans.factory.annotation.Autowired;
import org.springframework.web.bind.annotation.PostMapping;
import org.springframework.web.bind.annotation.RequestBody;
import org.springframework.web.bind.annotation.RequestMapping;
import org.springframework.web.bind.annotation.RestController;

@RestController
@RequestMapping("/employees")
public class EmployeeController {

    @Autowired
    private EmployeeService employeeService;

    @PostMapping
    public Employee save(@RequestBody Employee employee){

        return  employeeService.save(employee);
    }
}
```
### EmployeeService
```java
package com.radhaCodeBuffer.springbootdemo.service;

import com.radhaCodeBuffer.springbootdemo.model.Employee;

public interface EmployeeService {

    Employee save(Employee employee);
}
```
### EmployeeServiceImpl
```java
package com.radhaCodeBuffer.springbootdemo.service;

import com.radhaCodeBuffer.springbootdemo.model.Employee;
import org.springframework.stereotype.Service;

import java.util.ArrayList;
import java.util.List;
import java.util.UUID;

@Service
public class EmployeeServiceImpl implements EmployeeService{

    //I will store here in List
    List<Employee> employees = new ArrayList<>();

    @Override
    public Employee save(Employee employee) {

        //check for employeeId if null or empty then generate employeeId
        if(employee.getEmployeeId() == null ||
            employee.getEmployeeId().isEmpty()){

            employee.setEmployeeId(UUID.randomUUID().toString());
        }
        employees.add(employee);

        return employee;
    }
}
```
# 22. Implementing get method for employee resource.
![alt text](image-108.png)![alt text](image-109.png)![alt text](image-110.png)
# 23. Implementing get method for employee by id.
![alt text](image-111.png)![alt text](image-112.png)![alt text](image-113.png)
# 24. Implementing exception handling- 404 resourece not found.
![alt text](image-114.png)![alt text](image-115.png)![alt text](image-116.png)![alt text](image-117.png)![alt text](image-118.png)![alt text](image-119.png)![alt text](image-120.png)![alt text](image-121.png)![alt text](image-122.png)![alt text](image-123.png)
# 25. Implementing Generic Exception for all resource.
![alt text](image-124.png)![alt text](image-125.png)![alt text](image-126.png)
# 26. Implementing delete method to delete a Employee resource.
![alt text](image-127.png)![alt text](image-128.png)![alt text](image-129.png)![alt text](image-130.png)
# 27. Content Negotiation: Impelmenting support for xml and json.
![alt text](image-131.png)![alt text](image-132.png)![alt text](image-133.png)![alt text](image-134.png)![alt text](image-135.png)![alt text](image-136.png)![alt text](image-137.png)![alt text](image-138.png)![alt text](image-139.png)
## 28. Implementing Data filtering for restful services.
![alt text](image-140.png)![alt text](image-141.png)![alt text](image-142.png)![alt text](image-143.png)![alt text](image-144.png)![alt text](image-145.png)
# 29. API Versioning
![alt text](image-146.png)![alt text](image-147.png)![alt text](image-148.png)![alt text](image-149.png)![alt text](image-150.png)![alt text](image-151.png)![alt text](image-152.png)
# Section-5 JPA with boot
# 30. What is JPA with Rest API?
![alt text](image-153.png)![alt text](image-154.png)![alt text](image-155.png)![alt text](image-156.png)
# 31. Setting up JPA and different classes?
![alt text](image-157.png)![alt text](image-158.png)![alt text](image-159.png)![alt text](image-160.png)![alt text](image-161.png)![alt text](image-162.png)
# 32. Create Employee Post method with JPA.
![alt text](image-163.png)![alt text](image-164.png)![alt text](image-165.png)![alt text](image-166.png)![alt text](image-167.png)![alt text](image-168.png)![alt text](image-169.png)![alt text](image-170.png)![alt text](image-171.png)
# 33. Get Employee Data from DB with JPA.
![alt text](image-172.png)![alt text](image-173.png)![alt text](image-174.png)![alt text](image-175.png)![alt text](image-176.png)![alt text](image-177.png)
# 34. Delete Employee Data with JPA.
![alt text](image-178.png)![alt text](image-179.png)![alt text](image-180.png)![alt text](image-181.png)
# 35. Converting h2 db to mysql db.
![alt text](image-182.png)![alt text](image-183.png)![alt text](image-184.png)![alt text](image-185.png)![alt text](image-186.png)
# Section -6 Microservice Intro
# 36. All About the microservices.
![alt text](image-187.png)![alt text](image-188.png)![alt text](image-189.png)![alt text](image-190.png)![alt text](image-191.png)![alt text](image-192.png)![alt text](image-193.png)![alt text](image-194.png)![alt text](image-195.png)![alt text](image-196.png)![alt text](image-197.png)![alt text](image-198.png)![alt text](image-199.png)
# Section-7 Microservices Implementation
# 37. Overview of implementing microservice architecture.
![alt text](image-200.png)![alt text](image-201.png)![alt text](image-202.png)
# 38. What is Service Registry?
![alt text](image-203.png)![alt text](image-204.png)![alt text](image-205.png)![alt text](image-206.png)
# 39. Creating Product Service?
![alt text](image-207.png)![alt text](image-208.png)![alt text](image-209.png)![alt text](image-210.png)![alt text](image-211.png)![alt text](image-212.png)![alt text](image-213.png)![alt text](image-214.png)![alt text](image-215.png)
# 40. IMplementing Create Product API?
![alt text](image-216.png)![alt text](image-217.png)![alt text](image-218.png)![alt text](image-219.png)![alt text](image-220.png)![alt text](image-221.png)![alt text](image-222.png)![alt text](image-223.png)![alt text](image-224.png)![alt text](image-225.png)![alt text](image-226.png)
# 41. Implementing Get Product API.
![alt text](image-227.png)![alt text](image-229.png)![alt text](image-228.png)![alt text](image-230.png)![alt text](image-231.png)![alt text](image-232.png)![alt text](image-233.png)![alt text](image-234.png)
# 42. Exception Handling in product Service.
![alt text](image-235.png)![alt text](image-236.png)![alt text](image-237.png)![alt text](image-238.png)![alt text](image-239.png)![alt text](image-240.png)![alt text](image-241.png)![alt text](image-242.png)
- So whenever the product is not found, we will send this error message and this status would be not found and we will send a particular error code as well.
# 43. Creating Service Registry
![alt text](image-243.png)![alt text](image-244.png)![alt text](image-245.png)![alt text](image-246.png)
## Now we need to add configuration for this as well
### 2)	Convert app.prop to app.yaml
![alt text](image-247.png)![alt text](image-248.png)![alt text](image-249.png)
# 44. Implementing Service Registry Client in ProductService.
![alt text](image-250.png)![alt text](image-251.png)![alt text](image-252.png)
# 45. Creating Order Service application with package and classes.
![alt text](image-253.png)![alt text](image-254.png)![alt text](image-255.png)
## Now Create classes
### Controller
![alt text](image-256.png)
### Service
![alt text](image-257.png)![alt text](image-258.png)
### Entity
![alt text](image-259.png)
### Repository
![alt text](image-260.png)
# 46. Creating Place Order API with Basic Data Saving
## Create an API to place an Order
![alt text](image-261.png)
## OrderRequest
![alt text](image-262.png)![alt text](image-263.png)
### Go back to OrederController
![alt text](image-264.png)
### Go to Service
![alt text](image-265.png)![alt text](image-266.png)![alt text](image-267.png)![alt text](image-268.png)
### Output
![alt text](image-269.png)![alt text](image-270.png)![alt text](image-271.png)
# 47. Implement Service Registry Client in OrderService.
![alt text](image-272.png)![alt text](image-273.png)
# 48. How to handle repitative configuration
![alt text](image-274.png)![alt text](image-275.png)
# 50. Creating Config Server.
![alt text](image-276.png)![alt text](image-277.png)
### Create a Github repository
![alt text](image-278.png)![alt text](image-279.png)
### Git hub repo Create a file
![alt text](image-280.png)![alt text](image-281.png)
### Now go to order-service and product-service and comment this configuration
![alt text](image-282.png)![alt text](image-283.png)
# 51. Adding Config Client in Order and Product Service.
![alt text](image-284.png)
### Now I tell both service where to connect
![alt text](image-285.png)
### Start configserver app
![alt text](image-286.png)
### Restarting Order and Product Services
![alt text](image-287.png)
# 52. Implementing Reduce quantity API in Product Service.
![alt text](image-288.png)![alt text](image-289.png)
## Service layer
![alt text](image-290.png)![alt text](image-291.png)
## Testing
### Always restart the server while testing
![alt text](image-292.png)![alt text](image-293.png)![alt text](image-294.png)![alt text](image-295.png)
# 54. Feign Client Intro & 55. Calling reduce quantity API from place order service via Feign Client. 
![alt text](image-296.png)![alt text](image-297.png)![alt text](image-298.png)
## Target:
![alt text](image-299.png)
### Step-1: Add dependency of Feign client
![alt text](image-300.png)
### Go to Order-Service pom.xml add this depenedency
![alt text](image-301.png)
### Go to Order-Service Application and Enable Feign-Client
![alt text](image-302.png)
## Create an external pkg and here we create our Feign Client.
- In external pkg create another pkg as Client, since we have to create client
### Create an ProductService as Interface.
![alt text](image-303.png)
## Kaha kaha se kya kya liya
### 1)PRODUCT-SERVICE ye name Product ke application.yaml file se uthaya. AAp eureka server se bhi fetch kar sakte ho.
![alt text](image-304.png)![alt text](image-305.png)
### 2)/product ye  ProductController se uthaya
![alt text](image-306.png)
### 3)	Method declaration ye bhi Product Controller se uthaya
![alt text](image-307.png)
## Ab hume is feign client ko call karna hai .. apne order microserve se
![alt text](image-308.png)
## Test: Place an order
![alt text](image-309.png)![alt text](image-310.png)
# 56. Implementing error Decoder to handle exception

