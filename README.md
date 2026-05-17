<div align="center">

<img width="220" src="https://cdn-icons-png.flaticon.com/512/3097/3097144.png" />

# 🚗 Car Rental Management System

### Plataforma web de administración y renta de vehículos 🚀

<p align="center">
  <b>Car Rental Management System</b> es una aplicación web desarrollada como proyecto académico enfocada en la gestión de alquiler de automóviles, administración de clientes, reservas y operaciones vehiculares mediante una arquitectura basada en Django.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/CarRental-WebPlatform-blue?style=for-the-badge">
  <img src="https://img.shields.io/badge/Django-PythonFramework-092E20?style=for-the-badge&logo=django&logoColor=white">
  <img src="https://img.shields.io/badge/SQLite-Database-003B57?style=for-the-badge&logo=sqlite&logoColor=white">
  <img src="https://img.shields.io/badge/OpenSource-Academic-success?style=for-the-badge">
</p>

<p align="center">
  <a href="#-acerca-del-proyecto">Acerca</a> •
  <a href="#-módulos-del-sistema">Módulos</a> •
  <a href="#-características">Características</a> •
  <a href="#-tecnologías-utilizadas">Tecnologías</a> •
  <a href="#-vista-previa">Vista previa</a>
</p>

</div>

---

# 🌌 Acerca del proyecto

**Car Rental Management System** es una plataforma web orientada a la administración de alquiler de automóviles y reservas vehiculares.

El sistema fue desarrollado utilizando Django y arquitectura LAMP, permitiendo administrar clientes, vehículos y procesos de renta desde una interfaz moderna y centralizada.

El sistema fue diseñado para:

- 🚗 Gestionar vehículos
- 👥 Administrar clientes
- 📅 Gestionar reservas
- 📋 Supervisar alquileres
- 💳 Gestionar pagos
- 📊 Visualizar información
- 🔐 Administrar accesos
- 🌐 Centralizar operaciones

---

# ✨ Características

## 🚘 Gestión de vehículos

- 🚗 Registro de automóviles
- 📍 Control de disponibilidad
- 💰 Configuración de precios
- 📋 Información detallada
- ⚡ Gestión dinámica

---

## 👥 Gestión de usuarios

- 👤 Registro de clientes
- 🔐 Inicio de sesión
- 📄 Gestión de perfiles
- 📊 Historial de reservas
- ⚡ Administración centralizada

---

## 📅 Sistema de reservas

- 📆 Reservas vehiculares
- 🚘 Asignación de automóviles
- 📋 Gestión de alquileres
- ⚡ Confirmaciones rápidas
- 📄 Historial de operaciones

---

## 📊 Panel administrativo

- 📈 Dashboard administrativo
- 👥 Gestión de usuarios
- 🚗 Supervisión vehicular
- 📅 Control de reservas
- 🔐 Gestión de permisos

---

# 👨‍💼 Módulos del sistema

## 🚗 Vehicle Module

Este módulo administra toda la información de vehículos disponibles.

### Funcionalidades:

- ➕ Registro de automóviles
- 📍 Gestión de disponibilidad
- 💰 Tarifas de alquiler
- 📋 Información técnica
- ⚡ Administración dinámica

---

## 👥 Customer Module

Este módulo es utilizado por los clientes del sistema.

### Funcionalidades:

- 🔍 Buscar vehículos
- 📅 Reservar automóviles
- 📄 Visualizar historial
- 💳 Gestionar alquileres
- 🚘 Consultar disponibilidad

---

## 📊 Reservation Module

Este módulo administra las reservas realizadas.

### Funcionalidades:

- 📆 Gestión de reservas
- 🚗 Asignación vehicular
- 📋 Confirmaciones
- 💰 Gestión de pagos
- ⚡ Seguimiento administrativo

---

## 🛠️ Admin Module

Este módulo funciona como administrador principal.

### Funcionalidades:

- 👥 Gestión de usuarios
- 🚗 Supervisión vehicular
- 📊 Dashboard administrativo
- 📅 Administración de reservas
- 🔐 Gestión del sistema

---

# 🛠️ Tecnologías utilizadas

## 🎨 Frontend

<p>
  <img src="https://skillicons.dev/icons?i=html,css,js" />
</p>

- HTML5
- CSS3
- JavaScript

---

## ⚙️ Backend

<p>
  <img src="https://skillicons.dev/icons?i=python,django" />
</p>

- Python
- Django 1.96
- Arquitectura MVC
- API Web

---

## 🗄️ Base de datos

<p>
  <img src="https://skillicons.dev/icons?i=sqlite" />
</p>

- SQLite
- Persistencia de datos
- Relaciones SQL
- Gestión vehicular

---

## 🧰 Infraestructura y herramientas

<p>
  <img src="https://skillicons.dev/icons?i=linux,apache,nginx,git,github,vscode" />
</p>

- Linux
- Apache
- Nginx
- Git
- GitHub
- Visual Studio Code
- StarUML

---

# 📂 Estructura del proyecto

```bash
CarRentalManagementSystem/
│
├── api/                      # API principal
├── templates/                # Plantillas HTML
├── static/                   # Recursos frontend
├── doc/                      # Documentación e imágenes
├── models/                   # Modelos Django
├── views/                    # Vistas del sistema
├── manage.py                 # Administrador principal
├── requirements.txt
├── README.md
└── LICENSE
```

---

# ⚡ Instalación

## 📋 Requisitos

- Python 3+
- Django 1.96
- SQLite
- Linux / Windows
- Apache o Nginx

---

# 🚀 Configuración del proyecto

## 1️⃣ Clonar repositorio

```bash
git clone https://github.com/isairey/CarRentalManagementSystem.git
```

---

## 2️⃣ Instalar dependencias

```bash
pip install -r requirements.txt
```

---

## 3️⃣ Ejecutar migraciones

```bash
python manage.py migrate
```

---

## 4️⃣ Iniciar servidor

```bash
python manage.py runserver
```

---

## 5️⃣ Abrir aplicación

```bash
http://localhost:8000
```

---

## 6️⃣ Acceder al modelo API

```bash
http://localhost:8000/api/
```

---

# 📊 Funcionalidades principales

## 🚗 Administración vehicular

- Gestión de automóviles
- Disponibilidad en tiempo real
- Tarifas de alquiler
- Información detallada

---

## 👥 Administración de clientes

- Registro y autenticación
- Gestión de perfiles
- Historial de reservas
- Gestión de alquileres

---

## 📅 Gestión de reservas

- Reservas dinámicas
- Confirmaciones rápidas
- Seguimiento administrativo
- Historial financiero

---

# 📸 Vista previa

## 🖥️ Interfaces del sistema

<div align="center">

### 🚗 Logo del sistema
<img src="/doc/img/logo.png" width="300">

### 🏠 Página principal
![Home](https://images.unsplash.com/photo-1503376780353-7e6692767b70?q=80&w=1200&auto=format&fit=crop)

### 🚘 Gestión de vehículos
![Vehicles](https://images.unsplash.com/photo-1492144534655-ae79c964c9d7?q=80&w=1200&auto=format&fit=crop)

### 📅 Sistema de reservas
![Reservations](https://images.unsplash.com/photo-1485291571150-772bcfc10da5?q=80&w=1200&auto=format&fit=crop)

### 📊 Dashboard administrativo
![Dashboard](https://images.unsplash.com/photo-1556740749-887f6717d7e4?q=80&w=1200&auto=format&fit=crop)

</div>

---

# 🧠 Objetivos del proyecto

## 🎯 Aprendizaje y administración

- Desarrollo web con Django
- Arquitectura LAMP
- Gestión de reservas
- Bases de datos SQL
- Diseño UML
- Sistemas administrativos
- Automatización de procesos

---

# 🚧 Roadmap

## 🔮 Próximas mejoras

- 📱 Aplicación móvil
- ☁️ Infraestructura cloud
- 💳 Integración de pagos
- 🤖 Reportes inteligentes
- 🌐 API REST moderna
- 🔔 Notificaciones en tiempo real
- 📍 Seguimiento GPS

---

# 🤝 Contribuciones

Las contribuciones son bienvenidas ❤️

## Cómo contribuir

1. Fork del proyecto

```bash
git checkout -b feature/nueva-funcionalidad
```

2. Commit

```bash
git commit -m "✨ Nueva funcionalidad"
```

3. Push

```bash
git push origin feature/nueva-funcionalidad
```

4. Pull Request 🚀

---

# 👨‍💻 Desarrollador

<div align="center">

## Isai Reyes — Python & Django Developer

Desarrollador apasionado por plataformas web, sistemas administrativos y arquitectura backend moderna 🚀

</div>

---

# 🌟 Apoya el proyecto

⭐ Dale una estrella  
🍴 Haz fork  
📢 Comparte el proyecto

---

# 📜 Licencia

Proyecto open source orientado al aprendizaje de Django, arquitectura LAMP y sistemas de renta vehicular.

---

<div align="center">

### 🚗 Car Rental Management System — administración inteligente de vehículos y reservas 🚀

</div>
