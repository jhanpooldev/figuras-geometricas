# Figuras Geométricas


## Propósito del Repositorio

El propósito de este repositorio es demostrar cómo implementar clases abstractas en Python para representar figuras geométricas y cómo aplicar buenas prácticas de codificación según las convenciones de estilo **PEP 8**. Además, se ha incorporado Pylint para identificar y corregir posibles errores en el código, garantizando que siga las mejores prácticas.


 ## Desarrollador 
| Apellidos y Nombres |
|---------------------|
|Flores Torres Jhanpool|


**Errores que han aparecido**: 
1.
- FiguraGeometrica.py:1:0: C0114: Missing module docstring (missing-module-docstring)
- FiguraGeometrica.py:1:0: C0103: Module name "FiguraGeometrica" doesn't conform to snake_case naming style (invalid-name)
- FiguraGeometrica.py:12:8: W0107: Unnecessary pass statement (unnecessary-pass)
- FiguraGeometrica.py:6:0: R0903: Too few public methods (1/2) (too-few-public-methods)
- FiguraGeometrica.py:15:0: C0115: Missing class docstring (missing-class-docstring)
- FiguraGeometrica.py:15:0: R0903: Too few public methods (1/2) (too-few-public-methods)
- FiguraGeometrica.py:26:0: C0115: Missing class docstring (missing-class-docstring)
- FiguraGeometrica.py:26:0: R0903: Too few public methods (1/2) (too-few-public-methods)
- FiguraGeometrica.py:37:0: C0115: Missing class docstring (missing-class-docstring)
- FiguraGeometrica.py:37:0: R0903: Too few public methods (1/2) (too-few-public-methods)

## Cambios Realizados

A continuación se detallan los cambios realizados en el código para cumplir con las recomendaciones de PEP 8 y mejorar la funcionalidad:

1. **Nombres de clases y métodos**: 
   - Se siguió la convención de nombres en **CamelCase** para las clases (ej. `FiguraGeometrica`, `Rectangulo`, `Triangulo`, `Circulo`).
   - Los métodos y variables siguen la convención de **snake_case**.

2. **Métodos adicionales en cada clase**:
   - **`obtener_nombre`**: Agregado a cada clase para devolver el nombre de la figura geométrica.
   - **`obtener_perimetro`**: Calcula el perímetro de la figura.
   - Se implementaron métodos adicionales como `obtener_perimetro` en las clases de figuras, proporcionando una funcionalidad más completa.

3. **Corrección de la longitud de líneas**: 
   - Se corrigieron líneas largas que excedían los 100 caracteres, dividiendo cadenas y expresiones en múltiples líneas para cumplir con la convención de PEP 8.

4. **Mejora de la legibilidad**:
   - Se organizaron los comentarios en el código, explicando el propósito de cada clase y método.
   - Se mejoró la claridad de los comentarios para asegurar que cada parte del código fuera comprensible.

5. **Uso de `@abstractmethod`**:
   - Se utilizaron métodos abstractos en la clase `FiguraGeometrica` para definir la interfaz que las clases concretas deben implementar.

6. **Pylint**:
   - Se ejecutó **Pylint** para identificar y corregir errores de estilo según PEP 8.
   - Se resolvieron advertencias relacionadas con "demasiados pocos métodos públicos" (R0903) agregando métodos adicionales como `obtener_nombre` y `obtener_perimetro`.

![Figuras](https://cdn.euroinnova.com/img/subidasEditor/figuras-geometricas_1736848938.webp)



