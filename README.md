# Calculadora en HC11

## Contenido
1. [Informacion General](#informacion-general)
2. [Uso](#uso)
3. [Aclaraciones](#aclaraciones)
### Informacion General
***
Se realizo una calculadora la cual realiza opereaciones de Suma, Resta y Mutiplicacion de numeros enteros de dos digitos. Los mismos son ingresados a traves del teclado que provee el Software Wookie
El resultado admite una longitud de 4 digitos para numero positivos y 3 digitos para aquellos numero que son negativos.

## Uso
***
Para su utilizacion el usuario una vez que ya haya cargado el codigo en el correspondiente Software le debera de dar Inicio al codigo. Una vez inicializado despliega el de los menus el "Puerto C" el cual contiene un teclado que con el mismo se cargaran los numero, as u vez para su visulizacion se requeiere el uso del Display para ver el resultado de forma digital
***
A continuacion se definen los diferentes caracteres que actuan como operadores:
* Suma: "A"
* Resta: "B"
* Multiplicacion: "E"
* Resolver: "F" (dicha infromacion se dara en el display)
* Clear: "E"

# Aclaraciones
***
A continuacion se definen las diferentes causas que llevan la calculadora a Error
1. **Exceder digitos permitidos:**
El maximo de digitos permitido por numero es de dos, el cual en caso de sobrepasarse se mostraria un Error en el diplay 
2. **Operador Erroneo:** 
En caso de no se haya precionado algun operador o se hayan precionado mas de dos operadores la calculadora mostrara un Error en la pantalla
Solo se puede ingresar una operación 
3. **Exceso de digitos en la Respuesta**
El maximo de digitos permitidos en la respuesta es de:
* 3 digitos: para numeros signados
* 4 digitos: para numeros no signados
4. **Como ingresar correctamente un valor**
Se deberá colocar un "0" en la decena en los valores menores a "10".

> En caso de ERROR se debe de precionar la tecla CLEAR para reiniciar la Calculadora