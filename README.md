# 📚 Libretea 🇬🇧

> 🌐 [Versión en español abajo](#-libretea-)

---

A personal collection manager for books and comics. Organize your library, keep track of what you own, and create wishlists for your next acquisitions.

---

## 🛠️ Tech Stack

| Layer | Technology |
|---|---|
| Frontend | Vue 3 + Tailwind CSS |
| Backend | Java 17 + Spring Boot |

---

## ✅ Prerequisites

### Frontend
- Node.js >= 18.x
- npm >= 9.x

### Backend
- Java >= 17
- Maven >= 3.8

---

## 📥 Installation

### Clone the repository

```bash
git clone https://github.com/your-username/libretea.git
cd libretea
```

### Frontend

```bash
cd frontend
npm install
```

### Backend

```bash
cd backend
mvn install
```

---

## 🚀 Running the project

### Frontend

```bash
cd frontend
npm run dev
```
Available at: `http://localhost:5173`

### Backend

```bash
cd backend
mvn spring-boot:run
```
Available at: `http://localhost:8080`

---

## 📁 Folder structure

```
libretea/
├── frontend/                 # Vue 3 + Tailwind CSS
│   ├── src/
│   │   ├── assets/           # Images, fonts, global styles
│   │   ├── components/       # Reusable components
│   │   ├── views/            # Main pages/views
│   │   ├── router/           # Route configuration
│   │   ├── stores/           # Global state (Pinia)
│   │   └── services/         # API calls
│   └── ...
│
├── backend/                  # Java + Spring Boot
│   └── src/main/java/
│       └── com/libretea/
│           ├── controller/   # REST endpoints
│           ├── service/      # Business logic
│           ├── repository/   # Data access
│           └── model/        # Entities
│
├── .gitignore
└── README.md
```

---

## 📝 Commit convention

This project follows [Conventional Commits](https://www.conventionalcommits.org/):

```
feat:      new feature
fix:       bug fix
chore:     configs, dependencies, project files
docs:      documentation changes
style:     formatting/UI changes without logic
refactor:  code improvement without behavior change
test:      add or modify tests
```

**Examples:**
```
feat: add book collection view
feat: create wishlist endpoint
fix: correct pagination in comic list
chore: update dependencies
docs: update README setup instructions
```

---

## 🌿 Contributing & branches

### Workflow

```
master        ← protected branch, only via Pull Request
  └── develop ← main integration branch
        └── feature/feature-name
```

### Steps to contribute

1. Create your branch from `develop`:
```bash
git checkout -b feature/feature-name develop
```

2. Make your changes and commit following the convention
3. Push your branch:
```bash
git push origin feature/feature-name
```
4. Open a **Pull Request** targeting `develop`
5. Once approved, it gets merged into `develop` and eventually into `master`

---

## 📄 License

Distributed under the terms of the license included in this repository.

---
---

# 📚 Libretea 🇪🇸

> 🌐 [English version above](#-libretea-)

---

Gestor de colecciones personales de libros y cómics. Organiza tu biblioteca, lleva el control de lo que tienes y crea listas de deseos para tus próximas adquisiciones.

---

## 🛠️ Tecnologías

| Capa | Tecnología |
|---|---|
| Frontend | Vue 3 + Tailwind CSS |
| Backend | Java 17 + Spring Boot |

---

## ✅ Requisitos previos

### Frontend
- Node.js >= 18.x
- npm >= 9.x

### Backend
- Java >= 17
- Maven >= 3.8

---

## 📥 Instalación

### Clonar el repositorio

```bash
git clone https://github.com/tu-usuario/libretea.git
cd libretea
```

### Frontend

```bash
cd frontend
npm install
```

### Backend

```bash
cd backend
mvn install
```

---

## 🚀 Cómo correr el proyecto

### Frontend

```bash
cd frontend
npm run dev
```
Disponible en: `http://localhost:5173`

### Backend

```bash
cd backend
mvn spring-boot:run
```
Disponible en: `http://localhost:8080`

---

## 📁 Estructura de carpetas

```
libretea/
├── frontend/                 # Vue 3 + Tailwind CSS
│   ├── src/
│   │   ├── assets/           # Imágenes, fuentes, estilos globales
│   │   ├── components/       # Componentes reutilizables
│   │   ├── views/            # Páginas/vistas principales
│   │   ├── router/           # Configuración de rutas
│   │   ├── stores/           # Estado global (Pinia)
│   │   └── services/         # Llamadas a la API
│   └── ...
│
├── backend/                  # Java + Spring Boot
│   └── src/main/java/
│       └── com/libretea/
│           ├── controller/   # Endpoints REST
│           ├── service/      # Lógica de negocio
│           ├── repository/   # Acceso a datos
│           └── model/        # Entidades
│
├── .gitignore
└── README.md
```

---

## 📝 Convención de commits

Este proyecto usa [Conventional Commits](https://www.conventionalcommits.org/):

```
feat:      nueva funcionalidad
fix:       corrección de un bug
chore:     configs, dependencias, archivos del proyecto
docs:      cambios en documentación
style:     cambios de formato/UI sin lógica
refactor:  mejora de código sin cambiar comportamiento
test:      agregar o modificar tests
```

**Ejemplos:**
```
feat: add book collection view
feat: create wishlist endpoint
fix: correct pagination in comic list
chore: update dependencies
docs: update README setup instructions
```

---

## 🌿 Contribución y ramas

### Flujo de trabajo

```
master        ← rama protegida, solo via Pull Request
  └── develop ← rama de integración principal
        └── feature/nombre-de-la-funcionalidad
```

### Pasos para contribuir

1. Crea tu rama desde `develop`:
```bash
git checkout -b feature/nombre-funcionalidad develop
```

2. Haz tus cambios y commitea siguiendo la convención
3. Sube tu rama:
```bash
git push origin feature/nombre-funcionalidad
```
4. Abre un **Pull Request** hacia `develop`
5. Una vez aprobado, se mergea a `develop` y eventualmente a `master`

---

## 📄 Licencia

Distribuido bajo los términos de la licencia incluida en este repositorio.