# Comunicación de portafolio — Restaurante

## Publicación para LinkedIn (español)

Desarrollé **Restaurante**, una aplicación de gestión de pedidos construida con **Java 17, Spring Boot, MySQL y Thymeleaf**.

El proyecto comenzó como un ejercicio de lógica y estructuras de datos. Lo fui ampliando hasta convertirlo en una aplicación web con dashboard operativo, administración de platillos, flujo de pedidos, historial, API REST y control de acceso por roles.

Lo que más destaco del desarrollo:

- Separación entre dominio Java, repositorio JDBC y capa web.
- Persistencia transaccional y conservación del precio histórico de los pedidos.
- Autenticación con Spring Security y BCrypt, protección CSRF y permisos `ADMIN` / `EMPLEADO`.
- Bitácora operativa y pruebas automatizadas con JUnit, MockMvc, MySQL y GitHub Actions.

Es una **demo funcional local** para mi portafolio, no un producto comercial desplegado. Me permitió practicar tanto la implementación de funcionalidades como la seguridad, las pruebas y la documentación técnica.

Código y documentación:
https://github.com/HenryGonzalezAlguera/Restaurante

#Java #SpringBoot #MySQL #BackendDevelopment #SoftwareEngineering #GitHub

## English version (for international recruiters)

I developed **Restaurante**, a local restaurant order-management demo built with **Java 17, Spring Boot, MySQL, and Thymeleaf**.

What started as a Java data structures exercise evolved into a multi-module web application featuring order workflows, a dashboard, menu administration, REST endpoints, role-based access control, and operational audit events.

I focused on separating business logic from HTTP controllers, using JDBC transactions to preserve order consistency and historical prices, implementing Spring Security and BCrypt, and validating the application with JUnit, MockMvc, MySQL integration tests, and GitHub Actions.

This is a **working local portfolio demo**, not a deployed production service.

Repository: https://github.com/HenryGonzalezAlguera/Restaurante

#Java #SpringBoot #MySQL #BackendDevelopment #SoftwareEngineering

## Información para el campo de proyecto de LinkedIn

**Nombre:** Restaurante | Sistema de gestión de pedidos

**Descripción corta:** Aplicación web local en Java y Spring Boot para pedidos y catálogo, con MySQL/JDBC, API REST, seguridad por roles, bitácora operativa y pruebas automatizadas.

**Tecnologías:** Java, Spring Boot, Spring MVC, Spring Security, JDBC, MySQL, Thymeleaf, Maven, JUnit, MockMvc, GitHub Actions.

**Enlace:** https://github.com/HenryGonzalezAlguera/Restaurante

**Capturas:** adjuntar únicamente las fotos sanitizadas de [CAPTURAS.md](CAPTURAS.md) cuando estén disponibles.

## GitHub — texto recomendado para la descripción del repositorio

`Java + Spring Boot restaurant order management demo | MySQL/JDBC, REST API, Spring Security, Thymeleaf and CI tests`

**Topics sugeridos:** `java`, `spring-boot`, `mysql`, `jdbc`, `thymeleaf`, `spring-security`, `rest-api`, `junit`, `github-actions`, `portfolio-project`.

La descripción y los topics deben configurarse desde GitHub cuando el dueño del repositorio decida publicarlos. No se deben presentar como ya cambiados hasta comprobarlos.

## Material visual y control de publicación

**Capturas de pantalla:** todavía no existen PNG funcionales en el repositorio. El proceso para producirlas a partir de una sesión local con datos sintéticos se encuentra en [CAPTURAS.md](CAPTURAS.md) y la carpeta [screenshots](screenshots/README.md).

Mientras no existan esas imágenes, la publicación puede incluir **solo el enlace del repositorio** o un gráfico de portada expresamente rotulado «ilustración de proyecto». Una imagen generada no debe presentarse como evidencia del funcionamiento real.

### Checklist

- [ ] Revisar que el enlace real sea https://github.com/HenryGonzalezAlguera/Restaurante (el repositorio cambió de nombre).
- [ ] Comprobar el último resultado de [Java Maven CI](https://github.com/HenryGonzalezAlguera/Restaurante/actions/workflows/java-maven.yml).
- [ ] No anunciar demo pública: esta aplicación **solo se ejecuta localmente**.
- [ ] No atribuir pagos, reservas, inventario ni facturación: son funcionalidades **fuera del alcance**.
- [ ] Usar únicamente capturas reales y sanitizadas, cuando estén disponibles.
- [ ] Elegir versión en español o inglés, publicar el texto desde LinkedIn y verificar la vista previa del enlace.

**Texto para Destacados:** Java / Spring Boot restaurant order management system featuring transactional JDBC persistence, MySQL, REST API, Spring Security and automated tests. Local portfolio demo (no public hosting).
