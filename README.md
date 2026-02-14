# Actividad 1 - Backend 2 (Miércoles)
**Nombre Completo:** Roque Julio Aldana Rincon
**Institución:** Cesde

---

## 1. Instancia de Base de Datos
* **Enlace a la instancia:** [Prisma Studio - Base de Datos](https://console.prisma.io/cmlirw20s0b4212eeyaw1a8jw/cmlmia3co04g2yhebjapq42xn/cmlmia3co04g0yhebckegrwoz/studio)

* **Configuración de Base de Datos en Prisma.io:**
![Configuración Base de Datos - URL y Usuario (sin contraseña)](datos-prisma.png)

* **Cadena de Conexión:**
```
postgresql://usuario:****@db.prisma.io:5432/postgres?sslmode=require
```
*(URL y usuario visibles, contraseña oculta por seguridad)*

---

## 2. Conexión desde Spring Boot
![Log de Conexión Exitosa en Spring Boot](![alt text](conexion-spring.png))

---

## 3. Pruebas de la API (CRUD)

### [POST] Crear Registro
*Captura de la solicitud (Request) y la respuesta (Response) en Postman/Insomnia:*
![POST Request](post-request.png)
![POST Response](post-response.png)

### [GET] Obtener Todos (All)
![GET All Request](get-all-request.png)
![GET All Response](get-all-response.png)

###  Obtener por ID
![GET by ID Request](get-by-id-request.png)
![GET by ID Response](get-by-id-response.png)

### [GET] Obtener por Email
![GET by Email Request](get-by-email-request.png)
![GET by Email Response](get-by-email-response.png)

### [PUT] Actualizar Registro
![PUT Request](put-request.png)
![PUT Response](put-response.png)

### [DELETE] Eliminar Registro
![DELETE Request](delete-request.png)
![DELETE Response](delete-response.png)
---

## 4. Pruebas Internas del Proyecto
![Resultados de Pruebas Internas](image.png)

> **Estado final:** Todas las pruebas pasaron exitosamente.

---
*Este repositorio es un fork del proyecto original para la asignatura de Backend 2.*
