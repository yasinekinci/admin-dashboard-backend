# admin-dashboard-backend

Architectural : 
    API Gateway & BFF (Backend for Frontend)(Orion)
    Micro Service    
    NLayer/Clear Architecture
    Repository
    Domain-Driven Design (DDD)
    Event-Driven Architecture / Message Driven Architecture   
    Transaction Management
    Saga Pattern (özellikle dağıtık transaction yönetimi için)    
    CQRS (Command Query Responsibility Segregation)

ORM : 
    Entity framework    
    Migrations / Database Seeding

Caching : 
    Redis/In-Memory

Queue : 
    RabbitMq 
    MassTransit
    Azure Service Bus4

Authentication :
    OAuth, JWT
    Role/Policy-Based Authorization

Test : 
    Xunit
    Moq / NSubstitute
    FluentAssertions
    Test Pyramid (Unit, Integration, E2E)
    Integration Tests with TestContainers

WebSocket : 
    Signalr

Logging & Monitoring :
    Serilog / NLog / ILogger
    Application Insights / ELK / Grafana
    Structured Logging
    Health Checks (AspNetCore.Diagnostics.HealthChecks)

Security :
    OWASP Top 10
    Data Protection API (DPAPI)
    Rate Limiting / Brute Force Prevention
    HTTPS / HSTS / CORS yönetimi

API :
    Swagger / Swashbuckle
    Versioning
    Rate Limiting / Throttling

CI/CD : 
    Docker Build/Push
    Azure
    SonarQube on Azure (SonarQube Rules & Clean Code Metrics)
    Release Pipelines (Environments / Approvals)

Githup :
    Action
    Project
    Branching Strategy (Git Flow / Trunk Based Dev)
    Conventional Commits / Commitlint
    GitHub Packages / Container Registry
    Mono Repo