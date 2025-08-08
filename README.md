# Face Scanner Angular

> 🧠 Frontend demo for facial recognition and biometric workflows  
> Angular-based UI for interacting with FaceScanner API and OpenBR biometric system.

---

## 🧭 Overview

**Face Scanner Angular** is the official frontend demo for the Face Scanner platform.  
It provides a user interface for capturing face images, submitting them for enrollment or matching, and visualizing biometric responses from the backend.

Built with **Angular**, it communicates with a Java-based server that integrates [OpenBR](https://github.com/biometrics/openbr) for facial recognition.

---

## ✨ Features

- 📷 Webcam-based face capture (HTML5 Media)
- 🧠 Biometric enrollment and matching
- 🔐 Secure API communication
- 🧾 Realtime response display (JSON)
- 🌐 Responsive and cross-browser UI
- ⚙️ Configurable endpoints

---

## ⚙️ Requirements

- Node.js 18+
- Angular CLI 16+
- API access to `facescanner-server` backend
- Modern browser with camera permissions

---

## 🚀 Getting Started

1. **Clone the repository**

```bash
git clone https://github.com/your-org/facescanner-angular.git
cd facescanner-angular
```

2. **Install dependencies**

```bash
npm install
```

3. **Run the development server**

```bash
ng serve
```

Visit `http://localhost:4200` in your browser.

---

## 🔧 Configuration

Edit the API base URL in:

```ts
src/environments/environment.ts
```

```ts
export const environment = {
  production: false,
  apiBaseUrl: 'http://localhost:8080'
};
```

---

## 🗂️ Project Structure

```plaintext
src/
├── app/
│   ├── services/       → API communication
│   ├── components/     → UI components
│   ├── pages/          → Enrollment, Match, Home
│   └── app.module.ts
├── assets/
├── environments/
└── index.html
```

---

## 🧪 Testing

Run Angular unit tests:

```bash
ng test
```

Run end-to-end tests:

```bash
ng e2e
```

---

## 🧾 License

This project is for demonstration and internal use only.  
© Gaming Innovators — Do not redistribute without permission.

---

## 🤝 Credits

- Angular
- OpenBR (backend integration)
- ngx-webcam
- Gaming Innovators UI/UX team
