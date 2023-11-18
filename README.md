# Sprint_TutorialProject

1. Java framework dev to make enterprise java dev easier!
2. Spring enables us to write better java code.
3. Example:
4. Tightly coupled code is hard to maintain, diff. to write unit tests.
5. classes should be Loosely coupled
6. Spring frameworks provides us 2 interfaces: BeanFactoryInterface and **ApplicationContextInterface**

**Dependency Injection**

<img src="https://user-images.githubusercontent.com/66110984/283212532-c571d85d-c152-4ec7-a7dc-94fa554c1139.png" width="700">

--------------------------------------
<img src="https://user-images.githubusercontent.com/66110984/283212668-80f19131-bd49-43f5-9404-3b161d1e3f1f.png" width="700">

**IOC Container: Using XML Configuration**

<img src="https://github.com/Vaibhavwani11/Sprint_TutorialProject/raw/main/Screenshot%202023-11-17%20173027.png" width="700">

Creates objects automatically using xml file

**IOC Container: Using Spring Java Configuration**

<img src="https://user-images.githubusercontent.com/66110984/283983919-772359c5-3480-47ce-a388-b969baf6492f.png" width="700">

**Dependency Injection types**
#_Setter Injection_: Inject dependencies through a Setter Method
#_Constructor Injection_ Inject dependencies through a Contructor
#_Field Injection_

**Component Scanning and Autowiring**

Automatically creates @beans using @ComponentScan annotation
@Autowired annotation for injecting the beans into our class.
@Qualifier Annotation: 
