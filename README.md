# To-Do List Interactiva

¡Bienvenido al proyecto **To-Do List Interactiva**! Este proyecto tiene como objetivo ayudarte a aprender cómo manejar eventos en JavaScript vanilla mediante la creación de una lista de tareas dinámica e interactiva.

---

## **Descripción**

Este proyecto te permitirá:
- Agregar tareas a una lista.
- Marcar tareas como completadas.
- Eliminar tareas de la lista.

Al mismo tiempo, aprenderás conceptos clave como:
1. **Event Delegation** para manejar eventos dinámicos en los elementos de la lista.
2. **Uso de `event.preventDefault()`** para evitar comportamientos por defecto en formularios.
3. **Manipulación del DOM** para crear, modificar y eliminar elementos.

---

## **Requisitos**

### **1. Funcionalidades Principales**
1. **Agregar tareas dinámicamente**:
   - Los usuarios pueden escribir una tarea en un campo de texto y añadirla a la lista.
2. **Marcar tareas como completadas**:
   - Los usuarios pueden hacer clic en una tarea para marcarla como completada, lo que aplicará un estilo diferente (e.g., tachado).
3. **Eliminar tareas específicas**:
   - Los usuarios pueden eliminar tareas individuales de la lista al hacer clic en un botón correspondiente.

---

### **2. Flujo de Trabajo**
1. **Capturar datos del formulario**:
   - Al enviar el formulario, la nueva tarea debe aparecer en la lista.
2. **Manejo de eventos dinámicos**:
   - Usa `event.target` para identificar qué elemento fue clickeado.
3. **Prevención del comportamiento predeterminado del formulario**:
   - Implementa `event.preventDefault()` para evitar que la página se recargue.

---

## **Especificaciones Técnicas**

1. **HTML Estructura Básica**
   - Un campo de entrada para la nueva tarea.
   - Un botón para enviar (agregar la tarea).
   - Un contenedor `<ul>` donde aparecerán las tareas.

2. **CSS Opcional**
   - Usa estilos básicos para diferenciar las tareas completadas (e.g., una clase `.completed` para tachar texto).

3. **JavaScript Funcionalidad**
   - Escucha el evento `submit` del formulario.
   - Usa `document.createElement` para agregar nuevos ítems a la lista.
   - Aplica `classList.toggle` para alternar la clase de completado.
   - Implementa `remove()` para eliminar un elemento específico de la lista.

---

## **Estructura del Proyecto**

```plaintext
📂 TodoList
├── 📄 index.html      # Archivo HTML principal
├── 📄 style.css       # (Opcional) Estilos para el diseño de la lista
└── 📄 script.js       # Lógica principal en JavaScript
