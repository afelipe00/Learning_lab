# Sistemas de diseño
Un **Sistema de diseño** es un conjunto de reglas, componentes y guías que se utilizan para crear una experiencia visual y de usuarios coherente y consistente en un producto digital. Es una combinación de estilo, código y documentación que ayuda a los equipos a crear interfaces de usuario de manera escalable. En pocas palabras un sistema de diseño es un conjunto de elementos estandarizados que se pueden reutilizar en diferentes combinaciones para dar como resultado un producto final.

Existe una herramienta que nos permite ir haciendo un check-list sobre todos los conceptos que tiene un sistema de diseño. [check-list](https://www.designsystemchecklist.com/).

## Elementos de un sistema de diseño
1. **Principios del diseño:** Son las guías que establecen cómo debe ser la experiencia de usuario.
2. **Guías de estilos:** Define colores, tipografía, espaciados, iconografía y otros aspectos visuales.
3. **Componentes reutilizables:** Son los elementos reutilizables con los que puede interactuar el usuario; Botones, tarjetas, formularios, modales, etc.
4. **Tokens de diseño:** Son las variables que almacenan colores, tamaños, espaciados y otras propiedades reutilizables.
5. **Documentación:** Explicaciones sobre cómo y cuándo usar cada elemento para garantizar una consistencia entre los diferentes productos.

## Principios de un sistema de diseño
Son las reglas fundamentales que guían cómo se crean, organizan y usan los componentes visuales y de interacción en un producto digital, estos son los principios más comunes y útiles de un sistema de diseño moderno:

1. **Consistencia:** Un sistema de diseño busca que todos los elementos visuales y de interfaz se usen de manera uniforme, por ejemplo: un botón debe comportarse y verse igual en todas partes. Esto reduce la curva de aprendizaje del usuario y evita errores.
2. **Modularidad y reutilización:** _"construye piezas que se ensamblen como LEGO."_ Los componentes debe ser reutilizables, Diseñas un botón, un input, una tarjeta y luego los usas en todo el sistema de diseño. Esto acelera el desarrollo, evita el código duplicado y mantiene la estética coherente.
3. **Claridad:** _"Si el usuario tiene que adivinar, algo falló."_ Cada elemento del sistema debe tener una intención clara y un propósito definido. Nada debe estar "porque se ve bonito". Claridad visual, claridad funcional.
4. **Accesibilidad:** _"Diseñar para todos no es una opción, es un compromiso."_ Los sistemas de diseño deben garantizar que sus componentes funcionen bien con los lectores de pantalla, teclados y tengan un buen contraste para personas con discapacidades visuales. Esto también incluye internacionalización y adaptación a distintos dispositivos.
5. **Escalabilidad:** _"Lo que funciona para uno, debe escalar para miles."_ Los principios deben permitir que el sistema crezca sin romperse. Desde una landing page hasta un dashboard complejo, el sistema debe mantenerse coherente y robusto.
6. **Flexibilidad controlada:** _"Creatividad sí, caos no."_ Un buen sistema permite adaptar componentes sin romper sus reglas. Por ejemplo, un botón puede tener variantes (primario, secundario, danger) pero todos deben compartir el mismo ADN visual y de interacción.
7. **Intuición:** _"Diseña pensando en cómo las personas ya esperan que funcione."_ El sistema debe apoyarse en patrones comunes y buenas prácticas de UX/UI. Lo intuitivo requiere menos explicación.
8. **Documentación clara:** _"El sistema no vive en la cabeza de nadie, vive en su documentación."_ Los principios no sirven si nadie los entiende o usa. Documentar con ejemplos claros, reglas y casos de uso es fundamental.
9. **Colaboración:** _"Diseño, desarrollo y producto hablando el mismo idioma."_ Un sistema de diseño bien pensado une a equipos multidisciplinarios con un lenguaje en común. Esto reduce fricción, acelera entregas y mejora la calidad.
10. **Iteración continua:** _"Un sistema no estático, evoluciona."_ Los principios deben revisarse y adaptarse a medida que el producto crece, el equipo cambia y surgen nuevas necesidades tecnológicas o de negocio.

### Ejemplos de sistemas de diseño:
- [Lightning design system 2, Salesforce](https://www.lightningdesignsystem.com/2e1ef8501/p/85bd85-lightning-design-system-2)
- [Ant design](https://ant.design/docs/spec/introduce/)
- [Material design](https://m3.material.io/)
- [Human Interface](https://developer.apple.com/design/human-interface-guidelines)

## Foundations y Design Tokens
Los fundamentos son los elementos básicos que van a formar parte de nuestro sistema de diseño. Son esos elementos **primitivos visuales**, esas decisiones de estilo mas básicas y "fundamentales" que, cuando se combinan, crean todos los componentes visuales y finalmente permiten crear las pantalla e interfaces de la plataforma.

> No son "un botón"; son el color del botón, la tipografía del botón, el radio de las esquinas del botón y la sombra que tiene debajo.

### ¿Que objetivo cumplen?
Si no se definen los **foundations** en un sistema de diseño cada diseñador del equipo usará valores arbitrario y diferentes para crear sus propias interfaces, utilizará de forma diferente los principios lo que no generará consistencia en la plataforma. Los **foundations** logran:
  1.  **Consistencia Visual:** Asegura que el producto se vea como una unidad, cono como un collage de ideas sueltas.
  2.  **Escalabilidad:** Cada decisión sobre el sistema de diseño puede ser replicado y aplicado de forma escalable y sencilla. "tomas la decision de cambiar el tono de un color" solo cambias el foundation y esto se aplica a toda la interface.
  3.  **Lenguaje Común:** permite crear un puente entre el sistema de diseño y el desarrollo. En lugar de decir "usa el hex #0055FF", decimos "usa el color Primary-500".

### Los 4 pilares de los foundations
Aunque un sistema de diseño puede tener muchos **foundations** estos son los 4 principales (necesarios) **foundations** que todo sistema de diseño debe de tener:
  1.  **Color (La paleta de colores):** No basta con elegir "colores bonitos" cada color debe ser estructurado por función.
      1.  Primario/secundario: identidad de la marca
      2.  Neutros: Escalas de grises para textos, fondos, y bordes (se suele necesitar más de lo que se cree).
      3.  Semánticos (Feedback): Colores con significado universal.
          - Success (verde)
          - Error (rojo)
          - Warning (amarillo)
          - Info (azul)
  2.  **Tipografía (Type Scale):** No permitir que la tipografía tenga tamaños y fuentes aleatorias es fundamental. Define una escala limitada y estricta. Un set básico incluye:
      1.  Headings (Para títulos): 

