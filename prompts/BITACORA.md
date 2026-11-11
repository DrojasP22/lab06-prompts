# Bitacora de prompts
Laboratorio 06: Fundamentos de Ingenieria de Prompts Herramienta de IA usada: (escribe aqui cual usaste) 

## Ejercicio 2: Tokens y ventana de contexto

| Texto | Caracteres | Tokens |
|---------|----------------|-----------|
| Los estudiantes programan en Java. | 37 | 7 |
| The students program in Java. | 29 | 6 |
| desafortunadamente | 18 | 4 |

resultado esperado, tras crear un nuevo chat la ia me dio como respuesta que no contaba con los datos y no podia responder.

## Ejercicio 3: Temperatura
| Temperatura | % de BiblioTec | Nombres en los 5 intentos |
|-------------|----------------|---------------------------|
| 0 | 100% | BiblioTec |
| 0.5 |65.3% | BiblioTec, LibroYa, PrestaLibro,LectoGo, Paginalibre, NubeDeTinta |
| 1 | 44.5% | BiblioTec, LibroYa, PrestaLibro,LectoGo, Paginalibre, NubeDeTinta|
| 1.8 |32.2% |BiblioTec, LibroYa, PrestaLibro,LectoGo, Paginalibre, NubeDeTinta |

## Ejercicio 4: Prompt vago vs estructurado 

| Criterio | Prompt vago | Prompt estructurado |
| --- | --- | --- |
| Menciona el objetivo del sistema | SI | SI |
| Menciona a los usuarios principales | SI | SI |
| Tiene exactamente 3 funcionalidades | SI | SI |
| Esta en 3 parrafos | NO  | SI |
| Lo usaria en un informe real | NO | SI |

## Ejercicio 5: Anatomia de un prompt

| Componente | Texto de mi prompt |
| --- | --- |
| Rol | Java Senior Developer|
| Instruccion | Create a Java Program |
| Contexto | Managing products on a virtual store|
| Ejemplo | Using a product class with the attributes code, name, price, stock |
| Formato | Methods: getprice(), setprice|

Nivel 1: Programa genérico en Java sin un propósito claro.

Nivel 2: Adopta un tono técnico más profesiona

Nivel 3: Define la temática (gestión de productos)

Nivel 4: Especifica la clase Producto y sus 4 atributos exactos

Nivel 5: explicación previa y el código ejecutable al final.