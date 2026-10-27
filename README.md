# Mini Planilla

Planilla de cálculo personal para iPhone: 10 filas y 4 columnas, con Suma y Promedio, un teclado numérico propio con tecla Intro y el teclado de texto del iPhone.

Abrir en Safari en https://pablocarvallo.github.io/miniexcel/ y elegir Compartir → «Agregar a inicio».

La planilla se guarda sola en el iPhone cada vez que cambia algo, como la Calculadora de iOS: sigue ahí al cerrar la app o apagar el teléfono, hasta que la borres. Para vaciarla, toca la esquina superior izquierda de la planilla (selecciona todo) y luego la papelera.

## Uso

- Toca una celda para escribir. **Intro** confirma y baja a la celda siguiente; **Listo** cierra el teclado.
- **123** abre el teclado numérico (con = + − × ÷) y **ABC** el de texto.
- Para una fórmula, toca **=** y arma la cuenta tocando celdas y operaciones, por ejemplo `=A1/A2*B3+C1-A4-5`.
- **Suma** y **Promedio** insertan la fórmula con las cifras de arriba. Mientras editas una fórmula, toca o arrastra sobre celdas para cambiar el rango.
- Arrastra sobre la planilla, o toca una letra o número de encabezado, para ver la suma y el promedio de esa selección.
- La papelera borra la selección, con unos segundos para deshacer.

## Fórmulas

- Empiezan con `=` y admiten las cuatro operaciones: `+ - * /`, con paréntesis si hace falta.
- Se multiplica y divide antes de sumar y restar: `=A1/A2*B3+C1-A4-5`.
- `=SUMA(B2:B9)` y `=PROMEDIO(B2:B9)` (también `SUM` y `AVERAGE`).
- Los argumentos se separan con punto y coma: `=SUMA(B2:B5;D2)`.
- Cifras con punto de miles y coma decimal.
