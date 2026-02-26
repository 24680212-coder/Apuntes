# 🖥️ Unidad I: Interfaz Gráfica de Usuario (GUI)

Esta unidad se centra en el diseño y desarrollo de interfaces que permitan una interacción intuitiva entre el usuario y el sistema, así como la lógica detrás de la respuesta a estímulos externos (eventos).

---

## 1.1 Creación de Interfaz Gráfica para Usuarios
Una **GUI** (Graphical User Interface) es el conjunto de elementos visuales que permiten la comunicación con el computador sin necesidad de usar comandos de texto. Su objetivo principal es facilitar la usabilidad mediante metáforas visuales.

### Conceptos Fundamentales:
* **Contenedores:** Son los elementos base que sostienen a los demás componentes (Ej: `Frame` en Java, `Page` en Flet, `Div` en HTML).
* **Layouts (Gestores de diseño):** Algoritmos que deciden la posición y el tamaño de los componentes de forma automática (Columnas, Filas, Grillas).
* **Componentes (Widgets):** Elementos individuales con los que el usuario interactúa.



---

## 1.2 Tipos de Eventos
Un **evento** es una señal que envía el sistema operativo al programa cuando sucede algo relevante. Se clasifican principalmente por el periférico que los origina:

1.  **Eventos de Ratón (Mouse Events):** Acciones como clic, doble clic, mover el puntero (`mouseMove`) o arrastrar (`drag`).
2.  **Eventos de Teclado (Key Events):** Ocurren al presionar (`keyDown`), soltar (`keyUp`) o mantener una tecla.
3.  **Eventos de Acción (Action Events):** Eventos de alto nivel, como presionar un botón de confirmación o seleccionar una opción de una lista.
4.  **Eventos de Estado:** Cambios en el ciclo de vida de la aplicación, como minimizar la ventana o perder el foco de escritura.

---

## 1.3 Manejo de Eventos
El manejo de eventos se basa comúnmente en el modelo de **Delegación de Eventos**. Para que el programa responda, se necesitan tres elementos:

* **Fuente (Source):** El componente que genera el evento (Ej: un Botón).
* **Objeto del Evento (Event Object):** Contiene la información técnica (coordenadas, tiempo, tecla pulsada).
* **Oyente/Manejador (Listener/Handler):** El bloque de código (función o método) que se ejecuta como respuesta.

En programación moderna, esto se logra vinculando una función al componente:
`boton.on_click = mi_funcion_manejadora`



---

## 1.4 Manejo de Componentes Gráficos de Control
Los componentes de control permiten capturar datos y ejecutar comandos. Se clasifican según su propósito:

| Categoría | Ejemplos | Función Principal |
| :--- | :--- | :--- |
| **Entrada** | TextField, TextArea | Captura de texto y datos alfanuméricos. |
| **Selección** | CheckBox, RadioButton | Selección de opciones booleanas o excluyentes. |
| **Listas** | Dropdown, ComboBox | Selección de elementos desde un conjunto definido. |
| **Acción** | Button, FloatingActionButton | Disparadores de procesos o lógicas de negocio. |

### Flujo de Implementación:
1.  **Instanciación:** Crear el objeto del componente en memoria.
2.  **Propiedades:** Definir atributos visuales (color, texto, tamaño, icono).
3.  **Posicionamiento:** Agregar el componente al árbol visual (Layout).
4.  **Interactividad:** Asignar el manejador de eventos correspondiente.

---

## 📚 Bibliografía (Recursos Digitales)

Unknown. (s. f.). 1.1 Creación de interfaz gráfica para usuarios. https://topicosavanzadosdprogramacion.blogspot.com/p/la-interfaz-grafica-de-usuario-conocida.html

Perla_ValGar. (s. f.). TÓPICOS AVANZADOS DE PROGRAMACIÓN. https://perlavalgar.blogspot.com/2017/02/topicos-avanzados-de-programacion.html

Unknown. (2017, 14 febrero). 1.4 Manejo de componentes gráficos de Control. https://erickprogrmacion.blogspot.com/2017/02/14-manejo-de-componentes-graficos-de.html

---
