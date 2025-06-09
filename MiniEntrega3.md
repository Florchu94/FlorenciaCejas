# 📄 Tercera Pre-entrega – Versión con Array en JavaScript

## 🎯 Objetivo General

Crear una aplicación web con HTML, CSS y JavaScript que:
1. Simule una base de datos de usuarios utilizando un array en el código,
2. Permita agregar nuevos usuarios desde un formulario,
3. Guarde información del usuario en el navegador (`localStorage` o `sessionStorage`),
4. Muestre toda la información en pantalla.

---

## ✅ Requisitos Obligatorios

### 1️⃣ Crear un array de usuarios directamente en `app.js`

```js
let usuarios = [
  { id: 1, nombre: "Juan", edad: 25, email: "juan@mail.com" },
  { id: 2, nombre: "Ana", edad: 30, email: "ana@mail.com" }
];
```

- Este array será tu “base de datos”.
- No necesitás ningún archivo .json.

### 2️⃣ Mostrar los usuarios en pantalla

Usar innerHTML o createElement() para mostrar los usuarios dentro de un ```<div>``` o ```<ul>```

### 3️⃣ Agregar nuevos usuarios desde un formulario

Crear un formulario con inputs (nombre, edad, email).

Al hacer clic en el botón “Agregar usuario”:

  - Crear un nuevo objeto usuario con los datos del formulario.

  - Agregarlo al array usuarios.

  - Volver a mostrar la lista completa en pantalla.

### 4️⃣ Guardar información en Storage
1. Pedir un dato extra al usuario (por ejemplo, su nombre o color favorito).
2. Guardarlo con localStorage.setItem("clave", "valor").
3. Al cargar la página, leerlo con getItem() y mostrarlo en pantalla.

---

### 📁 Estructura del Proyecto

```
/proyecto-array
├── index.html
├── style.css
└── app.js
```

---

### 🧪 Resultado Esperado
Cuando el usuario abre la página:
  - Se ve un saludo personalizado con el dato del Storage.
  - Se lista el contenido inicial del array de usuarios.
  - Al agregar un usuario con el formulario, se actualiza la lista.

