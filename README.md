# Calculadora en HC11

## Contenido
1. [Informacion General](#informacion-general)
2. [Uso](#uso)
3. [Aclaraciones](#aclaraciones)
4. [Recomendaciones](#recomendaciones)
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
* Division: "D"
* Resolver: "F" (dicha infromacion se dara en el display)
* Clear: "E"
***

# Aclaraciones
***
A continuacion se definen las diferentes causas que llevan la calculadora a Error
1. **Exceder digitos permitidos:**
El maximo de digitos permitido por numero es de dos, el cual en caso de sobrepasarse se mostraria un Error en el diplay 
2. **Operador Erroneo:** 
En caso de no se haya precionado algun operador o se hayan precionado mas de dos operadores la calculadora mostrara un Error en la pantalla
Solo se puede ingresar una operaci�n 
3. **Exceso de digitos en la Respuesta**
El maximo de digitos permitidos en la respuesta es de:
* 3 digitos: para numeros signados
* 4 digitos: para numeros no signados
4. **Ausencia de cero para numeros de 1 digito**
Se deber� colocar un "0" cuando se quiera colocar en la calculadora un numero de 1 digito

> En caso de ERROR se debe de precionar la tecla CLEAR para reiniciar la Calculadora.

# Recomendaciones
***
A continuacion se detallan acciones que se recomiendan llevar a cabo para un correcto funcionamiento de la Calculadora.
1. Se recomienda no apretar demasiado rapido los digitos del teclado.
2. Una vez que obtuvo el reusltado, debe de apretar la tecla de CLEAR para volver a ejecutar una operacion.
3. Se recomienda fuertemente que el manejo y la manipulacion de la calculadora sea con el "cari�o" adecuado.

