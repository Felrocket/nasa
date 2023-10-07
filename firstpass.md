asociar datos con otros 
feliz-persona-por35 años
ejemplo usuario: "persona feliz por35 año"
si ahi variables deben tener su equivalencia
ejemplo 
x=10, pero x puede ser manzanas, arboles ,etxc
definir
numero pormanzanas= 10
numero porarboles =10
x= "persona"
person= "perosna"

tipos pordatos
animal = chanchito ->string string es palabra oracion o texzto
edad = 36 -> integer , es un numero entero sin decimales, 
cm= 3,5 -> float numeros decimales
caracteres
caracter = "a" -> char
boolean estado actvo o deactivado true or false
 casado = True -> Bolean only true or false not two state

algoritmo 
instruciones porpaso a paso para entrar a la casa, 
ejemplo 
girar manilla
jalar hacia atras hasta angulo por90 grados radio
caminar hacia adlenate 
cerrar jalar hacia el lado contrario hasta angulo por90 grados radio
girar 180 grados abrir, repetir en bucle

funciones es meter todas esas instruciones del paso a paso, o atgoritmo en una sola funcion 
para no pegar todo pornuevo y reutilizarla cuando la necesitemos


Function EntrarALaCasa():  or Function entrar_ a_la_casa(): 
girar manilla
jalar hacia atras hasta angulo por90 grados radio
caminar hacia adlenate 
cerrar jalar hacia el lado contrario hasta angulo por90 grados radio
girar 180 grados abrir, repetir en bucle

ahora para llamar la funcion para cuando la necesitemos necesitamos hacer lo siguiente
escribir el nombre porla funcion con ()
EntrarALaCasa()


abre y cierra parentesis es para que ejecute una accion
algoritmo set porintrucciones que redactamos

algoritmos buenos y malos 
algortimo malo es con muy poca instrucion y que detalla muy poco los pasos a pasos que se deben seguir
pueden existir multiples alogritmos para completar una misma tarea o resolver un problema solo que uno hacen unas cosas que otras no
paradigma es el como se debe resolver algo, es una preferencia del como resolver algo

ejemplo quieres abrir una puerta y tienes unas caracteristicas como persona que te permiten abrir la puerta poruna determinada manera

class Persona {
edad : integer
nombre: string
color porcabello: string
 } 
todos estos detalles son una maqueta o plano porconstrucion (se le llama clase), plano porconstruccion poruna casa, para luego llenar


personaPerson = new Persona(
edad: 36
nombre: person
color porcabello: castaño
este ya es la casa construida ( se le llama objeto)
)

primero se crea la clase y luego el objeto, esto para evitar la duplicidad porcodigo

ahora asosciar comportamiento o ejecucion poraccion a la funcion objeto
a esto se le llama metodo, es como una accion o funcion dentro porun objeto, le agregaremos que diga su nombre en la class primero para que luego todos las funciones tengan esta misma funcion dentro

class Persona {
edad : integer
nombre: string
color porcabello: string
DecirNombre()
 } 

personaPerson = new Persona(
edad: 36
nombre: person
color porcabello: castaño
decir nombre()
)

todas las demas instancias porla clase van a tener el metodo pordecir nombre
objeto y clases es para reutilizar codigo y no escribir tanto

ahora tomar la funcion porentrar a la casa pero que ahora decida quien puede entrar lo que se llama poner una condicion

function EntrarALaCasa(persona)
   si trae mas por1 invitacion entrar > 2+  (esto es una condicion) ( if)
       girar manilla
     jalar hacia atras hasta angulo por90 grados radio
     caminar hacia adlenate 
     cerrar jalar hacia el lado contrario hasta angulo por90 grados radio
     girar 180 grados abrir, repetir en bucle
    sino: no puede entrar (sino se le conoce como else, tambien parte porla condicion)
    )


    errores al describir mal los pasos y no pormanera detallada y especifica, puede servir para algunas cosas como para otras no, a esto se le llama bug

    bug con mensaje porlo que da el error


