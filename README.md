# ✈️ Sistema de Reserva de Boletos de Avión  
### Proyecto académico – Tecnológico de Monterrey  
**Lenguaje:** C++  
**Materia:** Programación Orientada a Objetos (POO)

---

## 📘 Descripción del Proyecto

Este proyecto consiste en un **Sistema de Reserva de Boletos de Avión** desarrollado en **C++**, diseñado para simular el proceso real de compra de boletos mediante programación orientada a objetos.  

La aplicación permite gestionar usuarios, reservas, administración, autenticación y manejo de datos a través de una estructura clara y modular.  

Este sistema fue creado como parte del curso de POO del **Tecnológico de Monterrey**, implementando los principios de:

- Abstracción  
- Encapsulamiento  
- Herencia  
- Modularidad  
- Manejo de archivos  
- Gestión de sesiones  

---

## 🧩 Funcionalidades Principales

- 🔑 **Inicio de sesión** para usuarios y administradores.  
- 👤 **Registro de clientes** con almacenamiento persistente.  
- 🛫 **Reserva de vuelos** mediante un módulo dinámico.  
- 📄 **Generación de tickets** en archivos de texto.  
- 👨‍✈️ **Módulo de administrador** para revisar usuarios y reservas.  
- 🗂️ **Lectura y escritura de datos** usando archivos `.txt`.  
- 📦 Arquitectura basada en clases, totalmente escalable.  

---
## ⚙️ Funcionamiento General del Sistema

El archivo **Main.cpp** es el punto de entrada del programa y controla el flujo principal de la aplicación.  
Al ejecutarse, realiza lo siguiente:

---

### 🔹 1. Menú Principal

Al iniciar el programa, se muestra un menú inicial que permite:

- **Iniciar sesión**
- **Salir del sistema**

No se puede acceder a ninguna otra funcionalidad sin autenticarse.

---

### 🔹 2. Inicio de Sesión

Cuando un usuario ingresa sus credenciales, el sistema identifica su tipo basándose en su **ID**, siguiendo estas reglas:

- 🧑‍💼 **Administrador:** su ID siempre comienza con **2**  
  Ejemplos: `201`, `250`, `298`

- 👤 **Cliente:** su ID siempre comienza con **1**  
  Ejemplos: `101`, `145`, `180`

De esta forma, el sistema distingue automáticamente el rol del usuario sin pedir información extra.

---

### 🔹 3. Menús Dependiendo del Tipo de Usuario

Una vez validada la cuenta, el sistema redirige al usuario al menú correspondiente:

#### 👑 Menú de Administrador
Incluye funciones como:

- Registrar Usuarios
- Registrar Vuelos
- Salr

#### 🧍 Menú de Cliente
Incluye funciones como:

- Reservar vuelos  
- Pagar boleto 
- Salir

---

### 🔹 4. Finalización del Programa

Si el usuario selecciona la opción **Salir**, el sistema termina la sesión activa y finaliza la ejecución de manera segura.

---



