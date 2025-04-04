# scmxpert-backend

scmxpert/
├── build.gradle                    # Root build file for common dependencies/config
├── settings.gradle                 # Includes all subprojects
├── README.md
├── .gitignore
│
├── common-libs/                        # Shared modules
│   ├── build.gradle
│   ├── src/
│   │   └── main/java/com/scmxpert/common/
│   │       ├── dto/                    # Shared DTOs across services
│   │       ├── exceptions/            # Custom exceptions
│   │       ├── util/                  # Utilities (JWT, PDF generator, converters, etc.)
│   │       └── config/                # Shared config (e.g., Mongo config, constants)
│   └── src/test/java/
│
├── user-service/
│   ├── build.gradle
│   ├── src/
│   │   ├── main/java/com/scmxpert/user/
│   │   │   ├── controller/
│   │   │   ├── service/
│   │   │   ├── repository/
│   │   │   ├── model/
│   │   │   └── UserServiceApplication.java
│   │   └── resources/
│   │       └── application.yml
│   └── src/test/java/
│
├── shipment-service/
│   ├── build.gradle
│   ├── src/
│   │   ├── main/java/com/scmxpert/shipment/
│   │   │   ├── controller/
│   │   │   ├── service/
│   │   │   ├── repository/
│   │   │   ├── model/
│   │   │   └── ShipmentServiceApplication.java
│   │   └── resources/
│   │       └── application.yml
│   └── src/test/java/
│
├── device-service/
│   ├── build.gradle
│   ├── src/
│   │   ├── main/java/com/scmxpert/device/
│   │   │   ├── controller/
│   │   │   ├── service/
│   │   │   ├── repository/
│   │   │   ├── model/
│   │   │   └── DeviceServiceApplication.java
│   │   └── resources/
│   │       └── application.yml
│   └── src/test/java/
│
├── alert-service/
│   ├── build.gradle
│   ├── src/
│   │   ├── main/java/com/scmxpert/alert/
│   │   │   ├── controller/
│   │   │   ├── service/
│   │   │   ├── repository/
│   │   │   ├── model/
│   │   │   └── AlertServiceApplication.java
│   │   └── resources/
│   │       └── application.yml
│   └── src/test/java/
│
├── business-partner-service/
│   ├── build.gradle
│   ├── src/
│   │   ├── main/java/com/scmxpert/partner/
│   │   │   ├── controller/
│   │   │   ├── service/
│   │   │   ├── repository/
│   │   │   ├── model/
│   │   │   └── PartnerServiceApplication.java
│   │   └── resources/
│   │       └── application.yml
│   └── src/test/java/
|
├── customer-service/
│   ├── build.gradle
│   ├── src/
│   │   ├── main/java/com/scmxpert/partner/
│   │   │   ├── controller/
│   │   │   ├── service/
│   │   │   ├── repository/
│   │   │   ├── model/
│   │   │   └── PartnerServiceApplication.java
│   │   └── resources/
│   │       └── application.yml
│   └── src/test/java/
│
├── gateway-service/                 
│   ├── build.gradle
│   ├── src/
│   │   ├── main/java/com/scmxpert/gateway/
│   │   │   └── GatewayApplication.java
│   │   └── resources/
│   │       └── application.yml
│   └── src/test/java/
│
└── config-server/                      
    ├── build.gradle
    ├── src/
    │   ├── main/java/com/scmxpert/config/
    │   │   └── ConfigServerApplication.java
    │   └── resources/
    │       └── application.yml
    └── src/test/java/
