# E-commerce Distribuido con Microservicios 🚀

Este es un proyecto de e-commerce distribuido desarrollado con **Spring Boot, Spring Cloud y Docker**.

## 📌 Tecnologías Utilizadas
- **Java 21 + Spring Boot**
- **Spring Cloud (Eureka, Config Server, Gateway)**
- **RabbitMQ / Kafka**
- **Docker + Kubernetes**
- **CI/CD con GitHub Actions**
- **PostgreSQL**

## 🛠️ Arquitectura del Proyecto
Este sistema está dividido en los siguientes microservicios:

| Microservicio        | Descripción | Repositorio |
|----------------------|-------------|--------------|
| **API Gateway** | Maneja el enrutamiento de peticiones | [ecommerce-api-gateway](https://github.com/KevinEcommerce/api-gateway) |
| **Discovery Server** | Servicio de descubrimiento (Eureka) | [ecommerce-discovery-server](https://github.com/KevinEcommerce/discovery-server) |
| **Config Server** | Centraliza configuraciones | [ecommerce-config-server](https://github.com/KevinEcommerce/config-server) |
| **Catálogo** | Gestión de productos y categorías | [ecommerce-catalog-service](https://github.com/KevinEcommerce/catalog-service) |
| **Usuarios/Auth** | Autenticación y gestión de usuarios | [ecommerce-user-service](https://github.com/KevinEcommerce/user-service) |
| **Pedidos y Carrito** | Manejo de órdenes y carritos | [ecommerce-order-service](https://github.com/KevinEcommerce/order-service) |
| **Pagos** | Procesamiento de pagos | [ecommerce-payment-service](https://github.com/KevinEcommerce/payment-service) |
| **Notificaciones** | Envío de correos y mensajes | [ecommerce-notification-service](https://github.com/KevinEcommerce/notification-service) |

## 🚀 Instalación y Ejecución
1. Clona este repositorio:
   ```bash
   git clone https://github.com/KevinEcommerce/ecommerce-project.git
