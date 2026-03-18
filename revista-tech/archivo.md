# Documentación Técnica - Sebastian Alexis Moreno Jaramillo 11-3

## Estructura del Árbol DOM

El Modelo de Objetos del Documento (DOM) de la tarjeta personal presenta una organización jerárquica clara, que facilita la comprensión de cómo se distribuyen los elementos dentro de la página.

- **html** (Elemento raíz del documento)  
  Contiene toda la estructura de la página web.

  - **head** (Sección de configuración)  
    Aquí se incluyen los metadatos, el título y otros elementos que no son visibles directamente para el usuario.

  - **body** (Contenido visible)  
    En esta parte se encuentra toda la información que el usuario puede ver en la página.

    - **main** (Contenedor principal)  
      Agrupa el contenido más importante del sitio.

      - **article** (Tarjeta de presentación)  
        Representa la información principal del perfil.

        - **header**  
          Incluye el nombre del estudiante en un **h1** y el grado en un **p**.

        - **section**  
          Contiene la descripción personal o biografía.

        - **aside**  
          Presenta la información de contacto usando la etiqueta **address**.

    - **footer** (Sección final)  
      Contiene la información de cierre o datos adicionales del sitio.