# Apuntes por 3lisa Araya para Frontend ✨

## 📌 Estaba practicando y se me va armando esta estructura de tabulación. la pregunta es: ¿Eso modifica en algo la pag en HTML?

La estructura de tabulación (indentación) en HTML no afecta directamente cómo se muestra la página, pero sí impacta la legibilidad del código.

- Visualmente en el navegador: No cambia nada. El navegador ignora los espacios, tabs y saltos de línea extras entre etiquetas HTML.

- Para ti (y developers): Una buena indentación hace el código más legible y mantenible.

- Excepciones menores: Dentro de elementos como <pre>, los espacios y tabs sí se respetan.

Ejemplo:

```js
<!-- Sin buena indentación -->
<div><h1>Hola</h1><p>Bienvenido</p></div>

<!-- Con buena indentación -->
<div>
  <h1>Hola</h1>
  <p>Bienvenido</p>
</div>
```

El navegador los renderiza *idéntico*.

##  Los saltos de línea se hacen con <br>? o hay algún otro método?

Sí, en HTML los saltos de línea se hacen con <br>, pero hay otros métodos dependiendo del contexto.

Usos comunes para saltos de línea en HTML:

- <br> (line break): Para insertar un salto de línea dentro de un mismo párrafo o bloque de texto sin cortar el flujo del contenido.

- <p> (paragraph): Se usa para separar bloques de texto. Cada <p> crea un salto de línea automático y un margen arriba y abajo.

- CSS con margin o padding: Puedes espaciar elementos usando CSS sin necesidad de usar <br> (que todavia no vimos)

### ❌ Cuándo evitar <br>:

- No se recomienda usar muchos <br> seguidos para crear espacios (mejor usar CSS).

- En estructuras más complejas o diseño responsivo, <br> puede romper el flujo.