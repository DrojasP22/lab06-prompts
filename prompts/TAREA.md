# Tarea: Diseño Iterativo de Prompts - Registro de Clientes

En este documento se documenta el proceso iterativo de diseño de un prompt para generar un módulo de **Registro de Clientes en Java**.

---

## 1. Proceso de Iteración

### Versión 1 (Prompt Básico)

```text
Crea un programa en Java para registrar clientes.
```

## Version 2

```text
Actúa como un desarrollador Java Senior. Crea un programa en Java orientado a objetos para registrar clientes de una tienda comercial, usando una clase Cliente con los campos id, nombre, correo y telefono. 
```

## Version 3: prompt final
```
Actúa como un desarrollador Java Senior experto en buenas prácticas.

Necesitamos un módulo de gestión de clientes para el sistema de ventas de una tienda minorista.

Instrucción: Diseña una clase `Cliente` y una clase `GestionClientes` que permita agregar clientes a una lista en memoria y listar los clientes registrados. Incluye una validación sencilla para asegurar que el correo contenga un '@'.

Restricciones:
- No uses librerías externas (utiliza únicamente Java Standard Library SE).
- No uses bases de datos ni frameworks como Spring.

Ejemplo de entrada/salida esperada:
Cliente agregado: ID 1 - Juan Pérez - juan@mail.com - 987654321

Formato: Explica brevemente la estructura de las clases en 2 párrafos y luego presenta el código Java completo y ejecutable dentro de un único bloque de código.
```
## Componentes del prompt final

| Componente | Texto de mi prompt final |
| --- | --- |
| **Rol** | Actúa como un desarrollador Java Senior experto en buenas prácticas. |
| **Contexto** | Necesitamos un módulo de gestión de clientes para el sistema de ventas de una tienda minorista. |
| **Instrucción** | Diseña una clase `Cliente` y una clase `GestionClientes` que permita agregar clientes a una lista en memoria y listar los clientes registrados. Incluye una validación sencilla para asegurar que el correo contenga un '@'. *(Restricción: No uses librerías externas ni bases de datos)* |
| **Ejemplo** | Cliente agregado: ID 1 - Juan Pérez - juan@mail.com - 987654321 |
| **Formato** | Explica brevemente la estructura de las clases en 2 párrafos y luego presenta el código Java completo y ejecutable dentro de un único bloque de código. |

## Evaluacion del resultado

| Criterio de Evaluación | Cumple (Sí / No) |
| --- | --- |
| ¿El código generado es ejecutable sin librerías externas? | Sí |
| ¿Incluye las clases requeridas (`Cliente` y `GestionClientes`) con sus atributos? | Sí |
| ¿Aplica la validación solicitada para el correo electrónico? | Sí |
| ¿Respeta el formato de respuesta (explicación de 2 párrafos y luego código)? | Sí |

## Errores que evite

1. **Ser demasiado general:** En la primera versión solo pedí "un programa para registrar clientes", lo que producía respuestas impredecibles. Lo evité especificando exactamente las clases (`Cliente` y `GestionClientes`), sus atributos y las funciones requeridas.
2. **No indicar el formato:** Al no especificar el formato inicial, la IA tendía a entregar fragmentos de código desordenados con explicaciones dispersas. Lo evité definiendo explícitamente una estructura de 2 párrafos explicativos seguidos por un único bloque de código ejecutable.



