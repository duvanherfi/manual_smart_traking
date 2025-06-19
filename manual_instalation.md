
---

## 🛠️ Manual de Instalación – *Smart Tracking*

### 🔧 Requisitos previos

#### Backend (Ruby on Rails)

* Ruby (versión recomendada: 3.x)
* Rails (versión recomendada: 7.x)
* PostgreSQL o SQLite
* Node.js y Yarn (para compilar assets)
* Git

#### Frontend (Flutter)

* Flutter SDK (versión estable)
* Android Studio o VS Code con Flutter & Dart plugins
* Dispositivo físico o emulador

---

### 1. **Clonar el repositorio**

```bash
git clone https://github.com/usuario/smart-tracking.git
cd smart-tracking
```

---

### 2. **Instalación del backend**

```bash
cd backend
bundle install
yarn install
rails db:create
rails db:migrate
rails s
```

---

### 3. **Instalación del frontend**

```bash
cd ../frontend
flutter pub get
flutter run
```

---

### 4. **Variables de entorno (opcional)**

Crear un archivo `.env` en ambos entornos para configurar claves y endpoints si se requiere.

---

### 5. **Acceso a la app**

* Backend en: `http://localhost:3000`
* App móvil/web desde Flutter en el emulador o navegador según plataforma

---

Si tu aplicación tiene despliegue en producción (por ejemplo, en Heroku o Vercel), puedo ayudarte a incluir esa parte también. ¿Lo deseas?
