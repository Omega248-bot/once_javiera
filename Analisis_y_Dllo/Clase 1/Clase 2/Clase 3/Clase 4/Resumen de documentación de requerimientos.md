# Clase 4: Documentación de Requerimientos

Proceso de formalización que convierte los hallazgos de la elicitación en especificaciones técnicas oficiales y contratos legales.

- # 1. Importancia de la Documentación**
  - Riesgos de no documentar: Pérdida de conocimiento por salida de personal, malentendidos de alcance con clientes y multas regulatorias por falta de evidencia.
  - Funciones esenciales: Sirve como acuerdo (contrato), guía de desarrollo, base para pruebas (testers), memoria del proyecto y evidencia legal.
  - Criterio de volumen: A mayor riesgo del software (banca, medicina), mayor nivel de rigurosidad y extensión documental.

- # 2. El Estándar IEEE 830 (SRS)**
  - Definición: Práctica recomendada internacional para la Especificación de Requerimientos de Software (Master Document).
  - Estructura base: 
    - Sección 1 (Introducción): Propósito, alcance, glosario y referencias.
    - Sección 2 (Descripción General): Perspectiva, funciones de alto nivel, usuarios y restricciones.
    - Sección 3 (Requisitos Específicos): Detalle numerado de requerimientos funcionales, no funcionales e interfaces.
  - Atributos de calidad según la norma: Correcto, no ambiguo, completo, consistente, priorizado, verificable, modificable y trazable.

- # 3. Casos de Uso (UML)**
  - Concepto: Descripción narrativa de la interacción paso a paso entre un actor y el sistema para lograr un objetivo específico.
  - Diferencia con Requerimiento: El requerimiento dicta el "qué" en una frase, el caso de uso narra el "cómo" cronológicamente.
  - Componentes del Diagrama UML: Actores (figuras humanas), Casos de uso (óvalos) y Límites del sistema (rectángulo).
  - Relaciones: Include (un caso requiere obligatoriamente de otro) y Extend (comportamiento opcional bajo condición).

- # 4. Plantilla y Estructura de un Caso de Uso**
  - Metadatos: ID único, Nombre (Verbo + Objeto), Actores, Descripción breve, Prioridad y Frecuencia de uso.
  - Reglas del Flujo: Precondiciones (estado previo necesario) y Postcondiciones (estado final tras el éxito).
  - Escenarios: Flujo principal (secuencia donde todo sale bien / camino feliz), Flujos alternos (variaciones exitosas) y Excepciones (gestión de fallas y errores).

- # 5. Revisión Cruzada y Práctica**
  - Control de Calidad: Inspección técnica para detectar fallas comunes antes del desarrollo, principalmente términos subjetivos que invalidan la verificabilidad de la especificación.
  - Reto Final: Redacción de una Especificación de Requerimientos de Software formal con su respectivo diagrama de casos de uso basado en un caso de estudio real.