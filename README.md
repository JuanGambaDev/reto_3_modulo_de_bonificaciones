# reto_3-modulo_de_bonificaciones
Reto 3 - Ciclo 1 - Fundamentos de programación - Universidad de Caldas - MisionTIC 

## Descripción del Reto
La empresa llamada “Market cicle” se dedica a la fabricación y comercialización de bicicletas todo terreno y sus respectivos accesorios, para la empresa, uno de sus principales objetivos es mantener contentos y bien remunerados a todos sus empleados, en especial al departamento de ventas y por ello ha diseñado un plan de incentivos para ellos, de esta manera pretende mantener felices a sus empleados y sobre todo incrementar las ventas en esta época de pandemia.

## Aspectos a tener en cuenta
Los trabajadores cuentan con un código interno el cual deberán ingresar cada que se registre una venta, este código debe cumplir con las siguientes características:
Nota: Recordar que es es para una sola venta a un solo cliente por un solo vendedor con todas las posibles combinaciones.

- Es un código de 8 caracteres
- En el tercer carácter del código siempre ponen un asterisco (*)
- No utilizan el símbolo “@”
- El primero y el ultimo carácter debe ser el mismo
- Nunca utilizan uno de los siguientes símbolos (‘+’, ‘=’, ‘&’)

NOTA: Si el código es invalido mostrar un mensaje de error y no se podrá realizar el registro de la venta
Una vez se ha validado que el vendedor si pertenece a la empresa “Market cicle” debe llenar un formulario para registrar la venta
Campos del formulario: (al ser formulario, se debe pensar en una interfaz amigable para el usuario, aplicar lo visto con el robot Arturito y los print)

- Marca de la bicicleta Specialized [1] treck [2] BMC [3]
- Color de la bicicleta roja [1] negra [2] roja-negra [3]
- Tamaño de la bicicleta (S-M-L-XL)
- Precio de la bicicleta
- Nombre del cliente
- Cantidad de bicicletas vendidas (se asumirá que siempre la venta es sobre la
misma clase de bicicleta (cantidad * precio)
- Precio total de la venta
- IVA (20% nacionales y 30% para importadas)
- Fecha de la venta (en formato DD/MM/AAAA)

Una vez se tengan esos datos se deberá indicar el valor de la comisión que ganará por dicho empleado

- Bonificación tipo A: se dará una bonificación del 5% si la venta está entre $200.000 y $800.000
- Bonificación tipo B: se dará una bonificación del 10% si la venta está entre $800.000 y $1’500.000
- Bonificación tipo C: se dará una bonificación del 15% si la venta es superior a $1’500.000

Al finalizar el registro se deberán mostrar la siguiente información:
- Nombre completo del empleado
- Fecha de la venta
- Precio de la bicicleta vendida
- Tipo de bonificación ganada por dicha venta
- Valor de la bonificación ganada

## ¿Qué debes hacer?
Aplicar el proceso IDEAL completamente, es decir. 
1. Identificar el problema
2. Definir el problema
3. Estrategias que dividan el problema 
4. Algoritmos condicionales

Implementar la aplicación en Python
1. Utilizando instrucciones condicionales
2. Utilizando funciones para cadenas de caracteres(str) c. Definiendo funciones con parámetros
3. Invocando funciones correctamente
4. Documentando el código
5. Probando la aplicación

# Solución

### I: Identificacion del problema 

La empresa “Market cicle” desea incrementar sus ventas en esta época de pandemia. Por ello ha diseñado un plan de incentivos con el cual busca mantener a sus empleados motivados y bien remunerados.

**¿Quiénes son los interesados?**
Cliente = La empresa “Market cicle”
Usuarios = Empleados y clientes de la empresa Market cile.

**¿Cuál es el objetivo?**
Realizar un programa con expresiones lógicas que pueda implementar el plan de incentivos diseñado por la empresa market place.

**Se tienen restricciones?**
- Los empleados cuentan con un codigo interno que deben ingresar al programa cada vez que realicen una venta, este codigo y registro se debe realicar por una sola venta.

### D: Definir el problema

**¿Qué conozco?**
- Cada empleado cuenta con un codigo interno propio que debe ser ingresado en cada registro de venta.
- El plan de incentivos diseñado por la empresa.

**¿Que debo conocer?**
- Fomulas para calcular impuestos IVA.
- Condicionales logicas para el desarrollo del programa.

### E: Estrategias

**Ejemplos particulares**
1. Un empleado ingresa su codigo interno al programa.
2. El programa valida si el codigo es correcto o no para permitirle continuar con el proceso.
3. el empleado llenara el formulario para registrar la venta:
4. El software validara la marca de la biblicleta , el color y el tamaño.
5. El software validara precios, impuestos y valor total de la venta.
6. El software calculara la comision que le corresponde al vendedor.
7. El software le mostrara al vendedor datos de la venta realizada.

**Estrategia de solución**  
De acuerdo a lo visto en el ejemplo anterior podemos decir que para implementar el software es necesario:
- Obtener valores de la situacion iniciar. Es decir, codigo del vendedor, datos del producto vendido
- Realizar validaciones logicas condicionales, conversiones y cálculos intermedios para poder usar de forma adecuada las datos brindados.

### A: Algoritmos

**Requerimientos de software a cada subproblema**
- El software solicitar el codigo interno de cada empleado
- El software validara si el codigo ingresado es correcto segun las condicionales brindadas.
- El software imprimira un formulario el cual debe ser lleno por el vendedor.
- El software realizara validaciones logigas y operaciones intermedias con los datos ingresados.
- El software mostrara al vendedor y al cliente datos correspondondientes  de la venta realizada.

**Algortitmo**
1. Solicitar codigo interno del empleado.
2. Validar si el codigo ingresado es el correcto.
3. Imprimir formulario.
4. Capturar datos del formulario.
5. Validar cual es la marca de la bicicleta.
6. Validar color de la biblicleta.
7. Calcular impuesto IVA.
8. Calcular precio total de venta.
9. Imprimir datos de venta a empleado y cliente.





