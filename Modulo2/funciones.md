# 📄 Uso de `console.log()` en JavaScript

## ¿Qué sintaxis usamos para imprimir algo en la consola?

```js
console.log('Hola mundo');
```

### 🟢 Explicación para principiantes

La palabra console es como una herramienta que ya viene incluida en JavaScript. Dentro de esa herramienta, hay una función llamada log que sirve para mostrar mensajes.

Cuando escribimos:

```js
console.log('Hola mundo');
```

Le estamos diciendo al programa: “Imprime este mensaje en la consola”.

Esto se usa mucho mientras estamos aprendiendo o desarrollando, para ver si nuestro código está funcionando como queremos, o para encontrar errores.

### 🔧 Explicación técnica
En JavaScript, console es un objeto global que proporciona varios métodos para interactuar con la consola del navegador o del entorno (como Node.js). Uno de esos métodos es log().

```js
console.log('Hola mundo');
```

- console → objeto global.

- log() → método que imprime uno o más valores.

- 'Hola mundo' → argumento que se imprime.

El método console.log() se utiliza principalmente para depuración (debugging), ya que permite ver el estado del programa en diferentes momentos de la ejecución.


### 📌 ¿Es una instrucción?

Sí, console.log('Hola mundo'); es una instrucción en JavaScript.

Una instrucción (en inglés statement) es cualquier línea de código que indica una acción a ejecutar. En este caso:

Se invoca un método (log) del objeto console.

Se pasa un argumento (la cadena 'Hola mundo').

Y se finaliza con un punto y coma (;), como toda instrucción válida.