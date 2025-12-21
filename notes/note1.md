### What is springboot?

> spring boot makes it easy for creating webapp is java programming languages.


the core spring framework already reduces the boilerplate code and provides many helpful features out of the box.

the **springboot** framework does this at a more bigger level. more boilerplate code reduced.

---

spring helps a lot in
1. creating a web app
2. connecting databases
3. managing transactions

**but** still requires a lot of manual configurations.

this is solved by **spring-boot**

---

#### springboot helps in creating java apps
- which are standalone, no tomcat servers
- which are auto-configured.

---
In spring 
- To set up an api,you have to manually set spring application context.
In springboot
- It is replaced by an annotation `@SpringBootApplication` on the main class.
> just run `SpringApplication.run()` to start an application, and springboot takes care of the configurations.
> these configurations are embedded web server setup and other necessary steps.

1. automatic component scanning.
2. embedded server configuration.
3. 