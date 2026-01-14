# API REST de Series | Java Spring Boot + PostgreSQL

Proyecto **backend** desarrollado en **Java con Spring Boot**, enfocado en el diseño de una **API REST**, la persistencia de datos en **PostgreSQL** y la integración con un frontend de demostración para validar la comunicación cliente-servidor.

---

## 👋 Sobre el proyecto

Este proyecto fue desarrollado como parte de mi formación en **Java Spring Boot con Alura Latam** y tiene como objetivo demostrar habilidades en:

- Desarrollo de APIs REST
- Arquitectura backend
- Conexión con bases de datos relacionales
- Consumo de la API desde un cliente frontend

El frontend **no es el foco del proyecto**, sino una herramienta para probar el correcto funcionamiento del backend.

---

## 🧑‍💻 Mi rol en el proyecto

- Diseño y desarrollo completo del **backend**
- Implementación de **API REST** con Spring Boot
- Modelado y persistencia de datos con **PostgreSQL**
- Creación de servicios y DTOs
- Integración backend–frontend

---

## 🛠️ Stack tecnológico

### Backend
- Java
- Spring Boot
- Spring Data JPA
- Hibernate
- Maven
- PostgreSQL

### Frontend (uso demostrativo)
- Frontend desarrollado por **Monica Hillman**
- Utilizado únicamente para consumo y prueba de la API

---

## 👤 Créditos

- **Backend, API REST y base de datos:** desarrollados por mí  
- **Frontend:** Monica Hillman (uso demostrativo)  
- **Formación:** Alura Latam – Java Spring Boot

---

## ▶️ Cómo ejecutar el proyecto

### Backend
```bash
cd backend
mvn spring-boot:run
La API quedará disponible en:
  http://localhost:8080

🔗 Endpoints de la API
Base URL
  http://localhost:8080/series

GET /series
  Obtiene el listado completo de series.

GET /series/top5
  Obtiene las 5 series mejor valoradas.

GET /series/lanzamientos
  Obtiene las series con lanzamientos más recientes.

GET /series/{id}
  Obtiene la información de una serie por su identificador.

GET /series/{id}/temporadas/todas
  Obtiene todas las temporadas y episodios de una serie.

GET /series/{id}/temporadas/{numeroTemporada}
  Obtiene los episodios de una temporada específica.

GET /series/categoria/{genero}
  Obtiene series filtradas por género.

🎯 Objetivos técnicos
Implementar una API REST siguiendo buenas prácticas

Separar responsabilidades mediante controladores, servicios y DTOs

Manejar datos relacionales con JPA / Hibernate

Exponer endpoints claros y reutilizables

🚀 Lo que aprendí
Diseño de endpoints REST

Manejo de relaciones entre entidades

Uso de DTOs para desacoplar la API del modelo

Integración backend–frontend

Buenas prácticas en proyectos Spring Boot

