# Blog-Style GitHub Repository: Distributed Systems with Spring Boot

A comprehensive educational resource designed as a blog-like repository for developers interested in learning distributed systems concepts through practical examples.

## Repository Structure

```
distributed-systems-blog/
├── README.md                          # Main landing page/blog index
├── docs/
│   ├── 01-introduction/
│   │   ├── README.md                  # What are Distributed Systems?
│   │   └── code-snippets/
│   │       ├── basic-rest-controller.java
│   │       └── simple-config.yml
│   ├── 02-microservices-basics/
│   │   ├── README.md                  # Microservices Architecture
│   │   └── code-snippets/
│   │       ├── user-service-structure/
│   │       ├── service-discovery.java
│   │       └── application.yml
│   ├── 03-service-discovery/
│   │   ├── README.md                  # Service Discovery with Eureka
│   │   └── code-snippets/
│   │       ├── eureka-server/
│   │       ├── eureka-client.java
│   │       └── configuration/
│   ├── 04-api-gateway/
│   │   ├── README.md                  # API Gateway Pattern
│   │   └── code-snippets/
│   │       ├── gateway-config.java
│   │       ├── routing-rules.yml
│   │       └── filters/
│   ├── 05-data-persistence/
│   │   ├── README.md                  # JPA, Hibernate & PostgreSQL
│   │   └── code-snippets/
│   │       ├── entities/
│   │       ├── repositories/
│   │       ├── database-config.java
│   │       └── schema.sql
│   ├── 06-inter-service-communication/
│   │   ├── README.md                  # Service-to-Service Communication
│   │   └── code-snippets/
│   │       ├── rest-template.java
│   │       ├── webclient.java
│   │       └── feign-client.java
│   ├── 07-fault-tolerance/
│   │   ├── README.md                  # Circuit Breaker & Resilience
│   │   └── code-snippets/
│   │       ├── circuit-breaker.java
│   │       ├── retry-mechanism.java
│   │       └── fallback-methods.java
│   ├── 08-monitoring-observability/
│   │   ├── README.md                  # Monitoring & Health Checks
│   │   └── code-snippets/
│   │       ├── actuator-config.java
│   │       ├── custom-metrics.java
│   │       └── health-indicators.java
│   ├── 09-containerization/
│   │   ├── README.md                  # Docker & Deployment
│   │   └── code-snippets/
│   │       ├── Dockerfile
│   │       ├── docker-compose.yml
│   │       └── kubernetes/
│   └── 10-best-practices/
│       ├── README.md                  # Best Practices & Patterns
│       └── code-snippets/
│           ├── error-handling.java
│           ├── configuration-management.java
│           └── testing-strategies.java
├── examples/
│   ├── complete-user-service/         # Full working example
│   ├── complete-product-service/      # Full working example
│   └── complete-order-service/        # Full working example
├── resources/
│   ├── diagrams/
│   │   ├── architecture-overview.png
│   │   ├── service-communication.png
│   │   └── data-flow.png
│   └── references/
│       ├── useful-links.md
│       └── recommended-reading.md
└── CONTRIBUTING.md
```

## Main README.md (Blog Index)

```markdown
# 🚀 Distributed Systems with Spring Boot: A Learning Journey

> A comprehensive blog-style guide to understanding and implementing distributed systems using Java Spring Boot, JPA/Hibernate, and PostgreSQL.

<div align="center">
  <img src="resources/diagrams/architecture-overview.png" alt="Distributed Systems Architecture" width="700"/>
</div>

## 📚 Table of Contents (Blog Posts)

### 🎯 **Part 1: Foundations**
1. [**Introduction to Distributed Systems**](docs/01-introduction/) 
   - What are distributed systems and why do we need them?
   - Key challenges and benefits
   - *Code*: Basic Spring Boot setup

2. [**Microservices Architecture Basics**](docs/02-microservices-basics/)
   - Monolith vs Microservices
   - Service boundaries and design principles
   - *Code*: Creating your first microservice

### 🔗 **Part 2: Service Communication**
3. [**Service Discovery with Eureka**](docs/03-service-discovery/)
   - Why service discovery matters
   - Implementing Netflix Eureka
   - *Code*: Eureka server and client setup

4. [**API Gateway Pattern**](docs/04-api-gateway/)
   - Centralized routing and cross-cutting concerns
   - Spring Cloud Gateway implementation
   - *Code*: Gateway configuration and filters

### 💾 **Part 3: Data Management**
5. [**Data Persistence with JPA & PostgreSQL**](docs/05-data-persistence/)
   - Database per service pattern
   - JPA/Hibernate configuration
   - *Code*: Entity mapping and repository patterns

6. [**Inter-Service Communication**](docs/06-inter-service-communication/)
   - REST APIs between services
   - Synchronous vs Asynchronous communication
   - *Code*: RestTemplate, WebClient, and Feign examples

### 🛡️ **Part 4: Reliability**
7. [**Fault Tolerance & Circuit Breakers**](docs/07-fault-tolerance/)
   - Handling service failures gracefully
   - Circuit breaker pattern with Resilience4j
   - *Code*: Implementing circuit breakers and fallbacks

8. [**Monitoring & Observability**](docs/08-monitoring-observability/)
   - Health checks and metrics
   - Distributed tracing
   - *Code*: Spring Actuator and custom metrics

### 🚀 **Part 5: Deployment**
9. [**Containerization with Docker**](docs/09-containerization/)
   - Dockerizing microservices
   - Container orchestration basics
   - *Code*: Dockerfile and Docker Compose examples

10. [**Best Practices & Patterns**](docs/10-best-practices/)
    - Common pitfalls and solutions
    - Production-ready considerations
    - *Code*: Error handling and configuration management

---

## 🎓 **Learning Path**

**Beginner**: Start with Parts 1-2 to understand the basics
**Intermediate**: Continue with Parts 3-4 for practical implementation
**Advanced**: Complete Parts 5 for production deployment

## 💡 **How to Use This Repository**

1. **Read Sequentially**: Each blog post builds upon the previous ones
2. **Try the Code**: Every concept includes runnable code snippets
3. **Experiment**: Use the complete examples in `/examples` to practice
4. **Reference**: Use this as a handbook for distributed systems concepts

## 🔧 **Complete Working Examples**

- [User Service](examples/complete-user-service/) - Full microservice with CRUD operations
- [Product Service](examples/complete-product-service/) - Inventory management service
- [Order Service](examples/complete-order-service/) - Order processing with inter-service calls

## 🌟 **What You'll Learn**

- ✅ Microservices architecture principles
- ✅ Service discovery and communication
- ✅ Database design for distributed systems
- ✅ Fault tolerance and resilience patterns
- ✅ Monitoring and observability
- ✅ Container deployment strategies
- ✅ Production best practices

## 🤝 **Contributing**

Found a mistake or want to improve content? See [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines.

---

*Happy learning! 🚀*
```

## Sample Blog Post Structure

### docs/03-service-discovery/README.md

```markdown
# Service Discovery with Netflix Eureka

*Part 3 of the Distributed Systems with Spring Boot series*

## 🎯 What You'll Learn

By the end of this post, you'll understand:
- Why service discovery is crucial in microservices
- How Netflix Eureka works
- How to implement service registration and discovery
- Best practices for service discovery

## 🤔 The Problem: Finding Services in a Dynamic Environment

Imagine you have multiple microservices running across different servers and ports. How does the User Service know where to find the Product Service? What happens when services scale up or down?

```java
// ❌ Hard-coded approach - brittle and inflexible
@Service
public class OrderService {
    
    public User getUser(Long userId) {
        // What if user-service moves to a different port?
        String url = "http://localhost:8081/users/" + userId;
        return restTemplate.getForObject(url, User.class);
    }
}
```

## ✅ The Solution: Service Discovery

Service discovery allows services to find each other dynamically without hard-coded URLs.

## 🏗️ Architecture Overview

```
┌─────────────────┐    ┌─────────────────┐
│   User Service  │    │ Product Service │
│   Port: 8081    │    │   Port: 8082    │
└─────────┬───────┘    └─────────┬───────┘
          │                      │
          │ Register/Discover    │ Register/Discover
          │                      │
          └──────────┬───────────┘
                     │
          ┌─────────────────┐
          │ Eureka Server   │
          │   Port: 8761    │
          └─────────────────┘
```

## 🛠️ Implementation

### Step 1: Setting Up Eureka Server

First, let's create the service registry:

```java
// EurekaServerApplication.java
@SpringBootApplication
@EnableEurekaServer
public class EurekaServerApplication {
    public static void main(String[] args) {
        SpringApplication.run(EurekaServerApplication.class, args);
    }
}
```

```yaml
# application.yml for Eureka Server
server:
  port: 8761

eureka:
  client:
    register-with-eureka: false
    fetch-registry: false
  server:
    enable-self-preservation: false
```

### Step 2: Registering Services (Eureka Clients)

```java
// UserServiceApplication.java
@SpringBootApplication
@EnableEurekaClient  // or @EnableDiscoveryClient
public class UserServiceApplication {
    public static void main(String[] args) {
        SpringApplication.run(UserServiceApplication.class, args);
    }
}
```

```yaml
# application.yml for User Service
spring:
  application:
    name: user-service  # This is how other services will find this service

server:
  port: 8081

eureka:
  client:
    service-url:
      defaultZone: http://localhost:8761/eureka/
  instance:
    prefer-ip-address: true
    lease-renewal-interval-in-seconds: 10
    lease-expiration-duration-in-seconds: 30
```

### Step 3: Service Discovery in Action

Now services can find each other using their logical names:

```java
// OrderService.java - Using service discovery
@Service
public class OrderService {
    
    @Autowired
    @LoadBalanced  // Enable client-side load balancing
    private RestTemplate restTemplate;
    
    public User getUser(Long userId) {
        // ✅ Using service name instead of hard-coded URL
        String url = "http://user-service/users/" + userId;
        return restTemplate.getForObject(url, User.class);
    }
}
```

```java
// Configuration for RestTemplate with Load Balancing
@Configuration
public class RestTemplateConfig {
    
    @Bean
    @LoadBalanced
    public RestTemplate restTemplate() {
        return new RestTemplate();
    }
}
```

## 🎯 Key Benefits

1. **Dynamic Discovery**: Services find each other automatically
2. **Load Balancing**: Built-in client-side load balancing
3. **Health Monitoring**: Eureka tracks service health
4. **Fault Tolerance**: Failed services are removed from registry

## 🔍 Monitoring Your Services

Access the Eureka Dashboard at `http://localhost:8761`:

```
Application         AMIs        Availability Zones    Status
USER-SERVICE        n/a (1)     (1)                  UP (1) - localhost:user-service:8081
PRODUCT-SERVICE     n/a (1)     (1)                  UP (1) - localhost:product-service:8082
ORDER-SERVICE       n/a (1)     (1)                  UP (1) - localhost:order-service:8083
```

## 🚀 Advanced Features

### Custom Instance Metadata

```yaml
eureka:
  instance:
    metadata-map:
      version: 1.0.0
      region: us-east-1
      team: backend
```

### Health Check URL

```yaml
eureka:
  instance:
    health-check-url-path: /actuator/health
    status-page-url-path: /actuator/info
```

## 🧪 Testing Service Discovery

```java
@SpringBootTest
@TestPropertySource(properties = {
    "eureka.client.enabled=false"  // Disable Eureka for tests
})
class OrderServiceTest {
    
    @MockBean
    private RestTemplate restTemplate;
    
    @Test
    void shouldGetUser() {
        // Test your service logic without Eureka dependency
        when(restTemplate.getForObject(anyString(), eq(User.class)))
            .thenReturn(new User(1L, "testuser"));
            
        User user = orderService.getUser(1L);
        
        assertThat(user.getUsername()).isEqualTo("testuser");
    }
}
```

## 💡 Best Practices

1. **Service Names**: Use meaningful, consistent naming conventions
2. **Health Checks**: Always implement proper health endpoints
3. **Graceful Shutdown**: Handle service deregistration properly
4. **Environment Isolation**: Use different Eureka servers for dev/prod
5. **Security**: Secure your Eureka server in production

## 🐛 Common Issues & Solutions

### Issue: Service not appearing in Eureka
```yaml
# Solution: Check your configuration
eureka:
  client:
    fetch-registry: true      # Make sure this is true
    register-with-eureka: true # Make sure this is true
```

### Issue: Service discovery not working
```java
// Solution: Don't forget @LoadBalanced annotation
@Bean
@LoadBalanced  // This is crucial!
public RestTemplate restTemplate() {
    return new RestTemplate();
}
```

## 🎯 Next Steps

In the next post, we'll explore **API Gateway Pattern** - creating a single entry point for all client requests while leveraging our service discovery setup.

---

## 📁 Complete Code Examples

- [Eureka Server Setup](code-snippets/eureka-server/)
- [Service Registration](code-snippets/eureka-client.java)
- [Service Discovery Usage](code-snippets/service-communication.java)

**Continue to**: [API Gateway Pattern →](../04-api-gateway/)
```

## Code Snippets Structure

### docs/03-service-discovery/code-snippets/eureka-server/

```
eureka-server/
├── EurekaServerApplication.java
├── application.yml
└── pom.xml
```

**EurekaServerApplication.java**:
```java
package com.example.eurekaserver;

import org.springframework.boot.SpringApplication;
import org.springframework.boot.autoconfigure.SpringBootApplication;
import org.springframework.cloud.netflix.eureka.server.EnableEurekaServer;

@SpringBootApplication
@EnableEurekaServer
public class EurekaServerApplication {
    public static void main(String[] args) {
        SpringApplication.run(EurekaServerApplication.class, args);
    }
}
```

## Navigation Structure

Each blog post should include:

```markdown
## Navigation
- **Previous**: [Microservices Basics ←](../02-microservices-basics/)
- **Next**: [API Gateway Pattern →](../04-api-gateway/)
- **Home**: [Back to Index](../../)

## Quick Links
- 📁 [Complete Code Examples](code-snippets/)
- 🎯 [Working Example](../../examples/complete-user-service/)
- 📖 [Additional Resources](../../resources/references/)
```

## GitHub Features for Blog-Style Repo

### Enable GitHub Pages
1. Go to repository Settings
2. Enable GitHub Pages from `docs/` folder
3. Your blog will be available at `https://username.github.io/repo-name`

### Add Topics
```
distributed-systems, microservices, spring-boot, tutorial, 
educational, java, postgresql, blog, learning-resource
```

### Repository Description
```
📚 A comprehensive blog-style tutorial on building distributed systems with Spring Boot, JPA/Hibernate & PostgreSQL. Learn through practical examples and code snippets.
```

This structure creates an educational, blog-like experience where readers can:
- Learn concepts step-by-step
- See practical code examples for each concept
- Access complete working examples
- Navigate easily between related topics
- Use it as a reference guide

The focus is on education and practical learning rather than a production codebase.