








mi primera pagina
🔧 El hardware es el conjunto de componentes físicos de un sistema informático. Es todo lo que puedes ver y tocar en una computadora, teléfono, consola de videojuegos, etc.

🧩 ¿Qué incluye el hardware?
Se divide en varias categorías:
1. Hardware interno
- Placa base (motherboard): conecta todos los componentes.
- Procesador (CPU): ejecuta instrucciones y cálculos.
- Memoria RAM: almacena datos temporales mientras se ejecutan programas.
- Disco duro o SSD: guarda datos de forma permanente.
- Tarjeta gráfica: procesa imágenes y video.
2. Hardware externo (periféricos)
- Entrada: teclado, ratón, escáner, micrófono.
- Salida: monitor, impresora, altavoces.
- Entrada/salida: pantallas táctiles, memorias USB.

🔄 Diferencia entre hardware y software
|  |  |  | 
|  |  |  | 
|  |  |  | 
|  |  |  | 



🕹️ Ejemplo práctico
Cuando escribes en Word:
- El teclado (hardware) envía señales.
- El software interpreta esas señales y muestra texto.
- El monitor (hardware) muestra el resultado.
¿Quieres que te muestre imágenes de los componentes principales del hardware o que te explique cómo se ensamblan en una computadora?
💾 El software es el conjunto de programas, instrucciones y datos que permiten que una computadora o dispositivo electrónico realice tareas específicas. Es la parte intangible de la tecnología: no puedes tocarlo, pero es esencial para que el hardware funcione.
Los lenguajes de programación son sistemas formales que permiten escribir instrucciones para que una computadora realice tareas específicas. Son esenciales para crear software, aplicaciones, sitios web, videojuegos y mucho más.
Variables, Valores y Operadores
Una variable es un nombre que usamos para hacer referencia a un valor que guardamos en la memoria del computador.

Un valor es una unidad de información que puede ser almacenada y manipulada por un programa.
Los valores pueden ser de distintos tipos de datos, como:

Números enteros (int): 3, -12, 250
Números decimales (float): 3.14, -0.001, 2.5
Cadenas de texto (str): "Hola", 'Python'
Valores lógicos (bool): True, False
Cada valor ocupa un espacio físico en la memoria del computador, y las variables sirven como etiquetas que nos permiten acceder a esos espacios fácilmente.
Operadores
Hemos introducido el concepto de variable, y al mismo tiempo vimos cómo guardar valores en ellas.
En el proceso, sin notarlo, usamos el símbolo =, que es un operador llamado operador de asignación.

Un operador es un símbolo o palabra reservada que indica una operación que el intérprete debe realizar sobre uno o más valores.
Por ejemplo, los operadores +, -, * y / realizan operaciones aritméticas, mientras que = asigna un valor a una variable.

El operador de asignación = no compara igualdad, sino que toma el valor que está a la derecha y lo guarda en la variable de la izquierda.


Código
Salida

a = 5
b = a + 2
print(a, b)
Orden de las Operaciones
Cuando en una expresión aparecen varios operadores, el orden en que se evalúan depende de las reglas de precedencia.
Python sigue una jerarquía muy similar a la de las matemáticas: primero las operaciones con mayor prioridad y, en caso de igual precedencia, evalúa de izquierda a derecha (salvo en algunos casos específicos como la potenciación).
Precedencia de operadores en Python (de mayor a menor prioridad)
Prioridad	Operador(es)	Descripción
1	()	Paréntesis: se evalúan primero
2	**	Potenciación
3	+x, -x, ~x	Unarios: positivo, negativo, negación bit a bit
4	*, /, //, %	Multiplicación, división, división entera y módulo
5	+, -	Suma y resta
6	<<, >>	Desplazamientos de bits
7	&	AND bit a bit
8	^	XOR bit a bit
9	|	OR bit a bit
10	<, <=, >, >=, ==, !=	Comparaciones
11	not	Negación lógica
12	and	Conjunción lógica
REFLEXION: En etas tres semanas que llevamos en el curso de pensamiento algoritmico hemos aprendido como funciona el hardware, como funciona una memoria SSD, nos estamos empezando a adentrar en el mundo de la programacion. con esta herramienta git hub estamos aprendiendo como darle instrucciones a un computador atraves de los lenguajes de programacion. 
# Ejemplo básico de uso de variables, valores y operadores en Python

# Definimos variables con valores numéricos
a = 10
b = 5

# Operaciones aritméticas
suma = a + b
resta = a - b
multiplicacion = a * b
division = a / b
modulo = a % b
potencia = a ** b

# Mostramos los resultados
print("Suma:", suma)
print("Resta:", resta)
print("Multiplicación:", multiplicacion)
print("División:", division)
print("Módulo:", modulo)
print("Potencia:", potencia)

En programación, una variable es un espacio de almacenamiento con nombre que se utiliza para guardar datos que pueden cambiar durante la ejecución de un programa. Es como una caja etiquetada donde puedes guardar y recuperar información cuando la necesites.
nombre = "Carlos"
edad = 30
activo = True
En programación, un valor es el dato concreto que se almacena en una variable o se utiliza en una operación. Es el contenido real que representa algo en el programa.
🔍 ¿Qué tipos de valores existen?
Los valores pueden ser de distintos tipos de datos, dependiendo del lenguaje de programación:
- Números enteros (int): como 5, -12, 1000
- Números decimales (float o double): como 3.14, -0.5, 2.718
- Cadenas de texto (string): como "Hola", "Carlos", "123"
- Booleanos (bool): True o False (verdadero o falso)
- Listas o arreglos (list, array): como [1, 2, 3] o ["a", "b", "c"]
- Objetos: estructuras más complejas que agrupan varios valores bajo una misma entidad
nombre = "Lucía"       # valor: "Lucía"
edad = 28              # valor: 28
activo = True          # valor: True
En programación, los operadores son símbolos o palabras clave que permiten realizar operaciones sobre datos y variables. Son esenciales para construir la lógica de cualquier programa.
 Tipos principales de operadores
1. Operadores aritméticos
Realizan cálculos matemáticos.
|  |  | a = 5b = 2 | 
| + |  | a + b7 | 
| - |  | a - b3 | 
| * |  | a * b10 | 
| / |  | a / b2.5 | 
| % |  | a % b1 | 
| ** |  | a ** b25 | 
. Operadores de comparación
Comparan valores y devuelven True o False.
|  |  | a = 5b = 2 | 
| == |  | a == bFalse | 
| != |  | a != bTrue | 
| > |  | a > bTrue | 
| < |  | a < bFalse | 
| >= |  | a >= bTrue | 
| <= |  | a <= bFalse | 

. Operadores de comparación
Comparan valores y devuelven True o False.
|  |  | a = 5b = 2 | 
| == |  | a == bFalse | 
| != |  | a != bTrue | 
| > |  | a > bTrue | 
| < |  | a < bFalse | 
| >= |  | a >= bTrue | 
| <= |  | a <= bFalse | 
 Variables
base = 10         # valor: 10
altura = 5        # valor: 5

# Operador aritmético (*)
area = base * altura

# Mostrar el resultado
La precedencia aritmética es el conjunto de reglas que determina el orden en que se deben realizar las operaciones matemáticas en una expresión.
Cuando una expresión contiene múltiples operaciones (como suma, resta, multiplicación, división, potencias o paréntesis), el resultado puede variar dependiendo del orden en que se ejecuten. Para evitar ambigüedades, se establece una jerarquía que todos deben seguir.
📌 Ejemplo práctico
Supón que tienes la expresión:
3+4\cdot 2
Si haces la suma primero:
(3+4)\cdot 2=7\cdot 2=14
Pero según la precedencia correcta, primero va la multiplicación:
3+(4\cdot 2)=3+8=11
resultado = (2 + 3) * 4  # Se suma primero, luego se multiplica
Los paréntesis se usan para invocar funciones y pasarles argumentos.
print("Hola mundo")  # 'print' es la función, "Hola mundo" es el argumen





BLOG/TAREA 2 UNIDAD 1. MD
Tarea 2 Ejercicios unidad 1


mi_tortuga.py
import turtle

t = turtle.Turtle()   # Crea una tortuga
t.forward(100)        # Avanza 100 unidades
turtle.done()         # Mantiene la ventana abierta

Reto1: simula el comportamiento de la tortuga usando solo print() e input().

Intenta recrear el movimiento de la tortuga únicamente con texto, usando funciones, print() y input() para pedir valores al usuario.
# Programa que avanza "-"
# Pedimos al usuario cuántas casillas quiere avanzar
'''phyton'''
casillas = int(input("¿Cuántas casillas quieres avanzar? "))

# Creamos una línea vacía con "_" para representar casillas
tablero = ["_"] * (casillas + 1)

# Recorremos cada casilla y dejamos un "-"
for i in range(casillas + 1):
    tablero[i] = "-"
  
# Mostramos el tablero completo en una sola línea
print("".join(tablero))
''''
ejemplo en phyton
¿Cuántas casillas quieres avanzar? 5
------
<img width="1115" height="628" alt="Captura de pantalla 2025-12-13 191927" src="https://github.com/user-attachments/assets/c324e2c3-7262-430f-9a17-61e806f1c97b" />



   

    
        
Reto 2: Tortuga bajando

Crea el rastro de una tortuga moviéndose hacia abajo usando únicamente print() e input().
'''phyton

posicion = 0      # posición inicial
meta = 10         # número de casillas (puedes cambiarlo)

while posicion < meta:
    pasos = int(input("¿Cuántas posiciones quieres que baje la barra? "))
    posicion += pasos
    if posicion > meta:
        posicion = meta
    
    # Dibujar todas las casillas desde arriba hasta la posición actual
    for i in range(posicion):
        print("|")
        '''

ejemplo en phyton   

<img width="1115" height="628" alt="Captura de pantalla 2025-12-14 114304" src="https://github.com/user-attachments/assets/7cdc55d4-418c-43ca-a65e-3e614ac7f592" />


¿Cuántas posiciones quieres que baje la barra? 2
|
|

Reto 3: Girar y dibujar usando solo print() e input()

Ahora la tortuga no solo avanza: también gira.
Observa cómo lo hace la versión gráfica:


import turtle
t = turtle.Turtle()
t.forward(100)
t.right(90)          # Gira 90 grados a la derecha
t.forward(100)
turtle.done()
Salida (versión gráfica): se dibuja una “L”.

Reto 4: Encapsula los comportamientos anteriores usando funciones

Reescribe los retos anteriores creando funciones que representen los movimientos de la tortuga solo con texto.
# Movimiento con "-" hacia adelante y "|" hacia abajo
# Solo usa print e input

# Pedimos valores al usuario
´´´phyton

adelante = int(input("¿Cuántas casillas quieres avanzar hacia adelante? "))
abajo = int(input("¿Cuántas casillas quieres avanzar hacia abajo? "))

# Dibujamos el avance hacia adelante en la primera fila
print("-" * adelante)

# Dibujamos el avance hacia abajo con "|"
for i in range(abajo):
    print(" " * (adelante - 1) + "|")
    ´´´

    ejemplo en phyton
    <img width="1115" height="612" alt="Captura de pantalla 2025-12-14 120210" src="https://github.com/user-attachments/assets/e95ada57-d14b-4b33-b85a-397ec7529623" />

    
    


¿Cuántas casillas quieres avanzar hacia adelante? 5
¿Cuántas casillas quieres avanzar hacia abajo? 2
-----
    |
    |
Reto 5: La tortuga baja las escalas

Ajusta tus funciones para que la tortuga pueda bajar escalones.
Cada escalón debe conservar la posición horizontal acumulada y dibujar correctamente tanto el tramo horizontal como el vertical.
# Programa para dibujar una escalera personalizada

# Pedimos al usuario cuántos escalones quiere

´´´phyton
escalones = int(input("¿Cuántos escalones quieres dibujar? "))

# Pedimos el número de guiones (-) por escalón
num_guiones = int(input("¿Cuántos '-' quieres por escalón? "))

# Pedimos el número de barras (|) por escalón
num_barras = int(input("¿Cuántos '|' quieres por escalón? "))

# Dibujamos la escalera
for i in range(escalones):
    # Línea horizontal con guiones y al final las barras
    print(" " * i + "-" * num_guiones + "|")
    # Si hay más de una barra, se dibujan debajo alineadas
    for j in range(num_barras - 1):
        print(" " * i + " " * (num_guiones - 1) + "|")
        ´´´

 ejemplo en phyton 
 <img width="1115" height="628" alt="Captura de pantalla 2025-12-14 114841" src="https://github.com/user-attachments/assets/9ce79235-a20f-44c0-94a9-d1b483be1bfc" />

 
¿Cuántos escalones quieres dibujar? 3
¿Cuántos '-' quieres por escalón? 5
¿Cuántos '|' quieres por escalón? 2
-----|
    |
 -----|
     |
  -----|
      |
Al ejecutar el programa pregunta cuantos escalones quiere dibujar luego cuantos pasos hacia adelante y cuantos pasos hacia abajo y finalmente ejecuta la funcion.






























































































































































































































































































