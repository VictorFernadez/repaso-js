### Tipos de Datos Primitivos

1. **String** (Cadena de texto):
   - Representa texto.
   - Se definen entre comillas simples o dobles.

   ```javascript
   let saludo = "Hola, ¿cómo estás?";
   console.log(saludo); // "Hola, ¿cómo estás?"
   ```

2. **Number** (Número):
   - Representa tanto números enteros como decimales.

   ```javascript
   let edad = 25;
   let altura = 1.75;
   console.log(edad);    // 25
   console.log(altura);  // 1.75
   ```

3. **Boolean** (Booleano):
   - Representa un valor de verdadero (`true`) o falso (`false`).

   ```javascript
   let esAdulto = true;
   let esEstudiante = false;
   console.log(esAdulto);   // true
   console.log(esEstudiante); // false
   ```

4. **Undefined**:
   - Representa una variable que ha sido declarada, pero no se le ha asignado un valor.

   ```javascript
   let nombre;
   console.log(nombre);  // undefined
   ```

5. **Null**:
   - Representa la ausencia intencional de un valor.

   ```javascript
   let respuesta = null;
   console.log(respuesta); // null
   ```

6. **Symbol**:
   - Introducido en ES6, es un tipo de dato único e inmutable, generalmente usado para identificadores privados.

   ```javascript
   let simbolo = Symbol('descripcion');
   console.log(simbolo); // Symbol(descripcion)
   ```

7. **BigInt**:
   - Introducido en ES11, permite representar números enteros muy grandes que no pueden ser representados con el tipo `Number`.

   ```javascript
   let numeroGrande = 1234567890123456789012345678901234567890n;
   console.log(numeroGrande); // 1234567890123456789012345678901234567890n
   ```

---

### Tipos de Datos No Primitivos (Referenciados)

1. **Object** (Objeto):
   - Es un tipo de dato compuesto que almacena colecciones de datos y funcionalidades mediante pares clave-valor.

   ```javascript
   let persona = {
     nombre: "Juan",
     edad: 30,
     saludar: function() { console.log("Hola"); }
   };
   console.log(persona.nombre);  // Juan
   persona.saludar();            // Hola
   ```

2. **Array** (Arreglo):
   - Un tipo especial de objeto que almacena elementos en orden.

   ```javascript
   let numeros = [1, 2, 3, 4];
   console.log(numeros[0]);  // 1
   ```

3. **Function** (Función):
   - Las funciones también son objetos en JavaScript.

   ```javascript
   function sumar(a, b) {
     return a + b;
   }
   console.log(sumar(2, 3));  // 5
   ```

---

### Resumen de los Tipos de Datos:

| **Tipo de Dato** | **Descripción**                  | **Ejemplo**                               |
|------------------|----------------------------------|-------------------------------------------|
| **String**       | Texto.                           | `"Hola, Mundo"`                          |
| **Number**       | Números enteros o decimales.     | `42`, `3.14`                              |
| **Boolean**      | `true` o `false`.                | `true`, `false`                           |
| **Undefined**    | Variable declarada pero sin valor. | `let x; console.log(x); // undefined`     |
| **Null**         | Ausencia intencional de valor.   | `let y = null;`                           |
| **Symbol**       | Valor único e inmutable.         | `Symbol('identificador')`                 |
| **BigInt**       | Números enteros muy grandes.     | `1234567890123456789012345678901234567890n` |
| **Object**       | Colección de propiedades y valores. | `{ nombre: "Juan", edad: 30 }`            |
| **Array**        | Colección ordenada de elementos. | `[1, 2, 3, 4]`                            |
| **Function**     | Bloque de código reutilizable.   | `function sumar(a, b) { return a + b; }`  |

---