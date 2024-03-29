Hotel reservation system using spring boot and thymeleaf.

[![Youtube demo](https://github.com/softfantasy/hotel-reservation-springmvc/blob/master/hotel_thumb.png)](https://www.youtube.com/watch?v=A9QIAvK-aGc "Youtube demo")


This project implements a complex domain model powering a session based wizard form flow to book
a hotel room. The flow simulates a real world application in terms of having a variety
of booking options and business rules. 

Key features include

- Thymeleaf ajax fragments + javascript
- Google maps API integration
- Responsive CSS with semantic-ui
- Extensive spring mvc tests + mockito
- Hibernate
- Query DSL

This project provided the inspiration and use cases to create a thymeleaf extension for manipulating query strings.
https://github.com/softfantasy/thymeleaf-querystring contains a video tutorial using this project to demonstrate the
integration with spring data `PagingAndSortingRepository`.

# Getting started

This project has a dependency on https://github.com/softfantasy/thymeleaf-querystring.
Its currently added as a static jar in the pom for convenience. 

This is the standard spring boot entry point, you can run this from within intellij if you dont want to run the created jar generated by mvn. 
https://github.com/softfantasy/hotel-reservation-springmvc/blob/master/src/main/java/com/demo/HotelApplication.java.

To play around in the IDE, run `mvn clean compile` to generate any QueryDsl auto generated classes.


TODO:

I don't have time right now to fix issues that are to do with new thymeleaf versions so you will see these errors.
https://stackoverflow.com/questions/55707941/thymeleaf-only-variable-expressions-returning-numbers-or-booleans-are-allowed-i/55765317

