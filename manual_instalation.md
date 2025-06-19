
---

## 🛠️ Manual de Instalación – *Smart Tracking*

### 🔧 Requisitos previos

#### Backend (Ruby on Rails)

* Ruby (versión recomendada: 3.x)
* Rails (versión recomendada: 7.x)
* MongoDB
* Node.js y Yarn (para compilar assets)
* Git

#### Frontend (Flutter)

* Flutter SDK (versión estable)
* Android Studio o VS Code con Flutter & Dart plugins
* Dispositivo físico o emulador

---

### 1. **Clonar repositorios**

```bash
git clone https://github.com/duvanherfi/smart-tracking-back
git clone https://github.com/duvanherfi/smartTracking-flutter
```

---

### 2. **Instalación del backend**

```bash
cd smart-tracking-back
bundle install
yarn install
rails s
```

---

### 3. **Instalación del frontend**
cd smartTracking-flutter
```bash
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
