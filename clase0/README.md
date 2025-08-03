# Lecture 0 - Notas

Profesor: David Malan.
> Profesor usa Visual Studio code (programa totalmente inferior a mi querido Notepad++) jajaj

hello.py
code hello.py (similar al echo en Debian)
> creó un archivo llamado hello.py


print("Hello, world")
> No está usando el ;?

<img width="784" height="170" alt="image" src="https://github.com/user-attachments/assets/2b5e6397-cfa2-4eb6-85ba-629797e9c109" />

print("© Copyright - Alan 2025 ")

python hello.py
> ejecutar el archivo que creé
> En Windows es py, en Linux es python3


### Funcion: 
Accion o verbo que te permite hacer algo en el programa.
Todo lenguaje carga sus propias funciones.

> Es curioso que todo este en Inglés. Me imagino en Español Argentino. IMPRIMÍ("")

### Argumentos:
Input para una función
Afecta el funcionamiento de la función.

funcion(argumento)
> print: side effect: mostrar texto.

## Bugs: errores a evitar.
print("ola"
> Si hay error, no va a ejecutar.
<img width="533" height="94" alt="image" src="https://github.com/user-attachments/assets/54979ebf-96f0-41bb-953d-9e88f4ea46d9" />
> Ejemplo de error en python

Ahora voy a pedir información al usuario:
input("boca o river? ")

<img width="366" height="239" alt="image" src="https://github.com/user-attachments/assets/7c5e3434-2ace-40d5-9d36-17b945c2e745" />

> hola dolares
## Return Values: 
Devolver las variables q le pedi a un usuario.

## Variable:
data almacenada en computadora

## Comentarios:
se escriben con # ola

## Pseudocode: 
Pseudocódigo, es como pensar en lenguaje humano lo que tendriamos q escribir en algun lenguaje de programación.

ekipo = input("boca o river? ") #le pregunto al usuario el equipo
print("Su ekipo es: " + ekipo) #imprimo de que equipo es
input("Presiona Enter para salir...") #si lo ejecuto dandole doble click no puedo ver nada 

Lo estoy ejecutando dandole doble click así que necesito una pausa para poder ver, sino tendria que abrirlo con cmd y tardaría un poco.


## Strings(str): 
cadenas de texto

Como evitar que dos print se ejecuten en dos lineas
print(*objects,sep=' ',end='\n', file=sys.stdout, flush=False)

## Parametros vs Argumentos.
* cualquier cantidad de argumentos
end='\n'
Acá hay un salto de linea.

## Positional parameters
Pasar de input a variable es llamado parametro.

## Main parameters vs Positional parameters

## como agregar "?
- intercambiar "'
- usar \" 

## funciones del video
.strip()
.capitalize()
.title() 
.split() poner un input con espacios en dos variables

ekipo = ekipo.strip().title() se puede poner mas de una


docs.python.org/3/library/functions.html#print

## Strings methods comunes  
| Método                           | Resultado                        | Descripción                        |
| -------------------------------- | -------------------------------- | ---------------------------------- |
| `texto.lower()`                  | `"hola mundo"`                   | Convierte todo a minúsculas        |
| `texto.upper()`                  | `"HOLA MUNDO"`                   | Convierte todo a mayúsculas        |
| `texto.capitalize()`             | `"Hola mundo"`                   | Capitaliza la primera letra        |
| `texto.strip()`                  | Elimina espacios al inicio/final |                                    |
| `texto.replace("Hola", "Adiós")` | `"Adiós Mundo"`                  | Reemplaza texto                    |
| `texto.split()`                  | `["Hola", "Mundo"]`              | Divide la cadena en partes         |
| `"mundo" in texto`               | `True`                           | Verifica si un texto está incluido |
| `len(texto)`                     | `10`                             | Devuelve la longitud del string    |



Integer y operadores: 
Un entero es un numero + o - 
Operadores: + - / * %
int(variable)

## Nesting functions:
x = int(input("qés x?"))

## Float
Un float es un número que tiene parte decimal, es decir, incluye un punto para separar los decimales:
Ejemplos: 3.14    0.5

## def
definir funciones.

### Scope:
![Uploading image.png…]()

Scope define donde una variable es accesible o visible dentro del programa.
Las variables definidas dentro de una función solo existen dentro de esa función (scope local).
Las variables definidas fuera de las funciones o globalmente existen en el scope global.






 



