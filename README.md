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
| **API Gateway** | Maneja el enrutamiento de peticiones | [api-gateway](https://github.com/KevinEcommerce/api-gateway) |
| **Discovery Server** | Servicio de descubrimiento (Eureka) | [discovery-server](https://github.com/KevinEcommerce/discovery-server) |
| **Config Server** | Centraliza configuraciones | [config-server](https://github.com/KevinEcommerce/config-server) |
| **Catálogo** | Gestión de productos y categorías | [catalog-service](https://github.com/KevinEcommerce/catalog-service) |
| **Usuarios/Auth** | Autenticación y gestión de usuarios | [user-service](https://github.com/KevinEcommerce/user-service) |
| **Pedidos y Carrito** | Manejo de órdenes y carritos | [order-service](https://github.com/KevinEcommerce/order-service) |
| **Pagos** | Procesamiento de pagos | [payment-service](https://github.com/KevinEcommerce/payment-service) |
| **Notificaciones** | Envío de correos y mensajes | [notification-service](https://github.com/KevinEcommerce/notification-service) |

## 🚀 Instalación y Ejecución
1. Clona este repositorio:
   ```bash
   git clone https://github.com/KevinEcommerce/ecommerce-project.git
