# 📱 Deber Splash Screen - Aplicaciones Móviles

## 📌 Sistema de Captura y Gestión de Imágenes

---

## 📖 Descripción del proyecto

Este proyecto consiste en el desarrollo de una aplicación móvil híbrida utilizando Ionic Framework junto con Angular.
La aplicación permite al usuario interactuar con diferentes funcionalidades como la generación de alertas, captura de fotografías mediante la cámara del dispositivo y visualización de imágenes en formato de galería.

Además, se integró Capacitor para ejecutar la aplicación en dispositivos Android, permitiendo el acceso a funcionalidades nativas como la cámara y el almacenamiento.

En ausencia de un dispositivo físico Android, se utilizó el emulador proporcionado por Android Studio para ejecutar y probar la aplicación.

---

## 🎯 Objetivo

Desarrollar una aplicación móvil funcional que permita aplicar los conocimientos adquiridos sobre Ionic y Angular, incluyendo interacción con el usuario, uso de hardware del dispositivo y despliegue en entorno móvil.

---

## 👨‍💻 Estudiante

* Gabriel Escobar

---

## 🎨 Personalización de la Aplicación

### 🔹 Icono de la App

![Icono de la app](https://github.com/GabrielEsc23/Splash-Screen/blob/raw/Capturas_APP/LOGO.png)

**Descripción:**
Se realizó la personalización del icono de la aplicación, el cual es visible tanto en el dispositivo móvil como en el menú de aplicaciones.
Este cambio permite identificar de manera visual la aplicación desarrollada, mejorando su presentación y experiencia de usuario.

---

### 🔹 Splash Screen

![Splash Screen](./splash.png)

**Descripción:**
Se implementó un splash screen personalizado que se muestra al iniciar la aplicación.
Esta pantalla de carga inicial brinda una mejor experiencia visual al usuario mientras la aplicación se inicia.

---

## 📸 Evidencias de funcionamiento

### 🏠 Pantalla principal (Tab1 - Alerta)

![Pantalla principal](./tab1.jpeg)

**Descripción:**
Esta pantalla corresponde a la pestaña Tab1.
En esta sección se muestra un botón llamado "Mostrar Alerta", el cual al ser presionado despliega una alerta en pantalla.
Esta funcionalidad permite demostrar la interacción básica con el usuario mediante eventos y componentes de Ionic.

---

### 📷 Captura de imágenes (Tab2 - Cámara)

![Tab2 Cámara](./tab2.jpeg)

**Descripción:**
La pestaña Tab2 contiene un botón con ícono de cámara, el cual permite acceder a la cámara del dispositivo.
Al presionar el botón, se abre la cámara para capturar imágenes en tiempo real.
Esta funcionalidad utiliza Capacitor para interactuar con el hardware del dispositivo.

---

### 🖼️ Galería de imágenes (Tab3)

![Galería](./tab3.jpeg)

**Descripción:**
En la pestaña Tab3 se visualizan las fotografías que han sido tomadas previamente.
Las imágenes se muestran en forma de galería, permitiendo al usuario ver todas las fotos capturadas dentro de la aplicación.

---

### 📱 Ejecución en Android

![Android](./android.jpeg)

**Descripción:**
En esta imagen se muestra la aplicación ejecutándose en un dispositivo Android.
Se puede observar que las fotografías capturadas se almacenan automáticamente en la galería del dispositivo, demostrando la correcta integración con Capacitor y el acceso al almacenamiento del sistema.
