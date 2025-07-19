# 🧠 Analizador Léxico Personalizado – Proyecto de Lenguajes y Compiladores
Este proyecto es un analizador léxico desarrollado en Java como parte del curso de Lenguajes y Compiladores. Permite identificar y clasificar tokens a partir de un texto fuente, aplicando las reglas definidas en un lenguaje personalizado creado por el estudiante.

---

## 🔍 ¿Qué hace este proyecto?
Analiza un texto de entrada e identifica palabras clave, operadores, identificadores, números, delimitadores y otros componentes léxicos.

Muestra los tokens reconocidos en una interfaz gráfica (GUI) desarrollada con Swing y AbsoluteLayout.

Informa si se encontraron errores léxicos y en qué línea del texto se ubican.

---

## 🧩 Estructura del Proyecto
El sistema está dividido en las siguientes clases principales:

### ✅ Token.java
Define los tipos de token reconocidos.

Incluye una enumeración con categorías como:

PALABRA_RESERVADA

OPERADOR

IDENTIFICADOR

NUMERO

PUNTUACION

DESCONOCIDO

### ⚙️ Analizador.java
Contiene la lógica principal de análisis léxico.

Procesa el texto línea por línea y palabra por palabra.

Usa expresiones regulares para reconocer tokens válidos.

Crea objetos Token y los almacena en una lista para ser visualizados.

### 🖥️ Vista_Principal.java
Es la interfaz gráfica que el usuario utiliza.

Permite ingresar el texto fuente a analizar.

Muestra los tokens detectados en una tabla.

Reporta errores léxicos si se encuentran.

---

## 🚀 Cómo ejecutar el proyecto
Abre el proyecto en NetBeans.

Asegúrate de haber agregado el paquete AbsoluteLayout si es necesario (AbsoluteLayout.jar).

Ejecuta el archivo Vista_Principal.java.

Escribe o carga el texto a analizar.

Presiona el botón para iniciar el análisis.

---

## 🛠️ Requisitos
JDK 8 o superior

NetBeans IDE (preferiblemente 17)

Librería AbsoluteLayout.jar agregada al proyecto

---

## 📂 Estructura de carpetas típica
````css
analizador_lexico/
├── src/
│   └── analizador_lexico2/
│       ├── Token.java
│       ├── Analizador.java
│       └── Vista_Principal.java
├── build/
│   └── ...
├── nbproject/
│   └── ...
````

---

## 📚 Autor
Carlos Jesús Ocaña Huamán 

