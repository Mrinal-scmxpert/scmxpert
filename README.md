scmxpert/
├── build.gradle                    # Root build file for shared dependencies and plugins
├── settings.gradle                 # Gradle settings for multi-module setup
├── README.md
├── .gitignore
│
├── common-libs/                   # Shared libraries used across microservices
│   ├── build.gradle
│   └── src/
│       ├── main/java/com/scmxpert/common/
│       │   ├── dto/               # Shared DTOs
│       │   ├── exceptions/        # Custom exception classes
│       │   ├── util/              # Utilities (JWT, PDF, etc.)
│       │   └── config/            # Common configurations
│       └── test/java/
│
├── user-service/                  # User management microservice
│   ├── build.gradle
│   └── src/
│       ├── main/java/com/scmxpert/user/
│       │   ├── controller/
│       │   ├── service/
│       │   ├── repository/
│       │   ├── model/
│       │   └── UserServiceApplication.java
│       └── resources/application.yml
│
├── shipment-service/              # Shipment handling microservice
│   ├── build.gradle
│   └── src/
│       ├── main/java/com/scmxpert/shipment/
│       │   ├── controller/
│       │   ├── service/
│       │   ├── repository/
│       │   ├── model/
│       │   └── ShipmentServiceApplication.java
│       └── resources/application.yml
│
├── device-service/                # IoT device management service
│   ├── build.gradle
│   └── src/
│       ├── main/java/com/scmxpert/device/
│       │   ├── controller/
│       │   ├── service/
│       │   ├── repository/
│       │   ├── model/
│       │   └── DeviceServiceApplication.java
│       └── resources/application.yml
│
├── alert-service/                 # Alert and notification microservice
│   ├── build.gradle
│   └── src/
│       ├── main/java/com/scmxpert/alert/
│       │   ├── controller/
│       │   ├── service/
│       │   ├── repository/
│       │   ├── model/
│       │   └── AlertServiceApplication.java
│       └── resources/application.yml
│
├── business-partner-service/      # Business partner management service
│   ├── build.gradle
│   └── src/
│       ├── main/java/com/scmxpert/partner/
│       │   ├── controller/
│       │   ├── service/
│       │   ├── repository/
│       │   ├── model/
│       │   └── PartnerServiceApplication.java
│       └── resources/application.yml
│
├── customer-service/              # Customer-related operations (duplicate path - verify)
│   ├── build.gradle
│   └── src/
│       ├── main/java/com/scmxpert/partner/
│       │   ├── controller/
│       │   ├── service/
│       │   ├── repository/
│       │   ├── model/
│       │   └── PartnerServiceApplication.java
│       └── resources/application.yml
│
├── gateway-service/               # API Gateway using Spring Cloud Gateway
│   ├── build.gradle
│   └── src/
│       ├── main/java/com/scmxpert/gateway/
│       │   └── GatewayApplication.java
│       └── resources/application.yml
│
└── config-server/                 # Centralized Spring Cloud Config Server
    ├── build.gradle
    └── src/
        ├── main/java/com/scmxpert/config/
        │   └── ConfigServerApplication.java
        └── resources/application.yml
