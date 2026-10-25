# Mini Planilla

Planilla de cálculo personal para iPhone: 10 filas y 4 columnas, con Suma y Promedio, un teclado numérico propio con tecla Intro y el teclado de texto del iPhone.

Abrir en Safari en https://pablocarvallo.github.io/miniexcel/ y elegir Compartir → «Agregar a inicio».

La planilla no se guarda: al cerrar la app vuelve a quedar vacía.

## Uso

- Toca una celda para escribir. **Intro** confirma y baja a la celda siguiente; **Listo** cierra el teclado.
- **123** abre el teclado numérico y **ABC** el de texto.
- **Suma** y **Promedio** insertan la fórmula con las cifras de arriba. Mientras editas una fórmula, toca o arrastra sobre celdas para cambiar el rango.
- Arrastra sobre la planilla, o toca una letra o número de encabezado, para ver la suma y el promedio de esa selección.
- La papelera borra la selección, con unos segundos para deshacer.

## Fórmulas

- `=SUMA(B2:B9)` y `=PROMEDIO(B2:B9)` (también `SUM` y `AVERAGE`).
- Operaciones `+ - * / ^` y paréntesis, por ejemplo `=B2*1,19`.
- Los argumentos se separan con punto y coma: `=SUMA(B2:B5;D2)`.
- Cifras con punto de miles y coma decimal.
