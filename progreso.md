# Progreso de Aprendizaje en Python

> **Nota para Antigravity (en cualquier computadora):** Cuando el usuario diga *"Lee progreso.md y seguimos desde ahí"*, revisa la sección **Estado actual** y continúa la lección o el ejercicio desde ese punto, respetando los temas ya dominados.

---

## Estado actual

- **Tema en curso:** Semana 4 — Listas a fondo (métodos, *slicing*, modificación y bucles)
- **Subtemas recién vistos:**
  - Acceso por índice positivo (`0`) y negativo (`-1`)
  - *Slicing* (`lista[inicio:fin:paso]`)
  - Mutabilidad y métodos básicos: `.append()`, `.insert()`, `.remove()`, `.pop()`
  - Tamaño con `len()` y pertenencia con `in`
  - Llenado dinámico de listas con `while` y `for`
- **Ejercicio pendiente:** Completar [semana_4_listas/01_reto_listas.py](semana_4_listas/01_reto_listas.py)
  1. Partir de `pendientes = ["estudiar python", "hacer ejercicio", "leer"]`.
  2. Pedir una nueva tarea con `input().strip().lower()`.
  3. Solo si no está ya en la lista (usando `in`), agregarla con `.append()`; si ya existe, mostrar un aviso.
  4. Mostrar cuántas tareas hay en total e imprimirlas una por una.
- **Siguientes temas por ver:**
  - Listas (continuación): ordenamiento (`sort()`, `sorted()`), `enumerate()`, listas anidadas y *list comprehensions*
  - Funciones (`def`): parámetros, `return`, valores por defecto y alcance (*scope*)

---

## Temario completado

### 1. Fundamentos y Datos (Semana 1)
- Variables y tipos básicos: `int`, `float`, `str`, `bool` (`True`/`False`), e introducción a colecciones (`list`, `tuple`, `dict`).
- Inspección y conversión (*casting*): `type()`, `int()`, `float()`, `str()`.
- Entrada y salida: `input()`, `print()`, *f-strings*.
- Matemáticas básicas: operadores aritméticos y `round()`.
- Buenas prácticas: nombres en `snake_case` (PEP 8) y lectura básica de errores (`SyntaxError`, `NameError`, `AttributeError`).

### 2. Lógica y Control de Flujo (Semana 2 — hasta el Día 28)
- Operadores de comparación: `==`, `!=`, `>`, `<`, `>=`, `<=` (y diferencia entre asignar `=` y comparar `==`).
- Condicionales: `if`, `elif`, `else`, dos puntos (`:`), indentación y condicionales anidados.
- Limpieza de texto: `.strip()`, `.lower()`, `.upper()` y encadenamiento en `input()`.
- Evaluación implícita: valores *Truthy* y *Falsy* (cadenas vacías, ceros, `None`).
- Operador ternario en una línea.

### 3. Bucles e Iteración (Semana 3 — Días 29 a 34)
- Bucle `while`: inicialización, condición de parada y actualización.
- Validación de entradas con bucles.
- Control de flujo en bucles: condiciones con `and`, `break`, `continue`.
- Patrón `while True:` para menús interactivos.
- Contadores (`intentos += 1`) vs. acumuladores (`total += precio`).
- Bucle `for` y `range()` (1, 2 y 3 argumentos, incluyendo conteo regresivo).
- Recorrido de `str` y `list`, y criterios para elegir entre `for` y `while`.

---

## Prácticas y material acumulado

- **Scripts construidos (sesiones previas):**
  - Conversor de Monedas (con validaciones)
  - Validador de Contraseña con límite de intentos
  - Cajero Automático
  - Caja Registradora
  - Generador de Tablas de Multiplicar
  - Ejercicios de condicionales
- **Material de repaso:**
  - Flashcards de Tipos de datos, Operadores de comparación y Condicionales
  - Quiz interactivo de Bucles `for` y `while`
