# WeatherApp



## Description

The project involves developing a Spring Boot server in Java integrated with the Weather API from Rapid API. It will expose RESTful APIs for retrieving weather forecast summaries and hourly details of any city. Header-based authentication using randomly generated keys will secure access to the APIs. The goal is to create a secure and efficient platform for accessing real-time weather data.

## Key Features:

1. **Secure Authentication:** Header-based authentication.
2. **Rapid API Integration:**  Seamless integration with Rapid API for accurate weather data.
3. **RESTful Endpoint:** Expose endpoints for summary and hourly weather forecasts.
4. **JSON Respons:** Deliver weather forecast information in JSON format for easy consumption.

## Tech-Stacks:
    - Backend: Java, Spring-Boot, Feign Client

## Prerequisites
- Node JS
- npm or yarn
- Java 8 or higher

  
## Backend Setup 
### Dependency:
    - spring-boot-starter-web
    - spring-cloud-starter-openfeign
    - lombok

##### Run the Spring Boot Application


## Backend Directory Structure
<pre> 
Weather-Api-1-backend/ 
   ├─ src/
       ├─ com.parking/ 
          ├─ controllers
          ├─ exceptions
          ├─ externalapis
          ├─ service (interface) 
                    ├─ impl (implemented classes)
          ├─ repositories
          ├─ service
      ├─ WeatherApiApplication
</pre>





