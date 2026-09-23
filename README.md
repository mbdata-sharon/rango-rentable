# Rango Rentable

Aplicación web interactiva del proyecto final de **Cálculo Diferencial** (Fundación Universitaria Compensar, 2026).

El dueño de un negocio escribe sus costos fijos, su costo por unidad, su precio de venta y un factor de encarecimiento. La app calcula al instante el **rango de producción** donde el negocio gana más, y muestra paso a paso cómo se llegó al resultado con límites y derivadas.

## Qué calcula

- **Producción mínima conveniente:** mínimo del costo medio, $Cme'(x)=0$.
- **Producción óptima:** máximo de la utilidad, $U'(x)=0$ con $U''(x)<0$.
- **Punto de equilibrio y precio piso:** a partir de $U(x)=0$ y su discriminante.
- **Meta de ganancia, margen de seguridad y día del mes en que se cubren los costos fijos.**
- **Simulador "¿Y si…?":** compara la predicción hecha con derivadas contra el resultado exacto.
- **Tabla de verificación:** comprueba el máximo con el criterio de la primera derivada.

Modelo: $C(x)=CF+vx+ax^2$, $I(x)=px$, $U(x)=I(x)-C(x)$, con $x \ge 0$.

## Cómo verla

Abre `index.html` en el navegador, o entra al enlace de GitHub Pages del repositorio.

Los ejemplos usan cifras supuestas con fines académicos.
