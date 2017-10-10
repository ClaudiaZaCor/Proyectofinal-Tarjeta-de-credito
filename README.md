*/
Crea una web que pida, por medio de un prompt(), el número de una tarjeta de crédito y confirme su validez según el algoritmo de Luhn.

Consideraciones Específicas
Tu código debe estar compuesto por 1 función: isValidCard
El usuario no debe poder ingresar un campo vacío.
/*

array.prompt  ( Inserte su numero de tarjeta de credito)
array.longitud = 16 //El numero de una TC tiene 16 digitos//

var numberOfCreditCard = array []

*/ Segun el algoritmo de Luhn, tenemos que multiplicar por 2 a los digitos que ocupan las posiciones pares empezando por el final, por eso aplicare un reverse /*
var invertedNumber = numberOfCreditCard.reverse ();
var invertedNumber = i

//Aplicando el algoritmo de Luhn//

      variable digito = parseInt(invertedNumber.charAt(i), 10); */aplico parseInt para asegurarme que el typeof sea number y charAt para localizar*/
        si (digito % 2 == 0 && digito <9 ) { //Definiendo la multiplicacion por 2 a los digitos pares menores que 9//
            (digito * 2) ;
            
      } de otro modo {
          (digito + (digito * 2)) // Ejecutando la suma de los digitos impares con el resultado anterior//
      
//Aplicando la funcion//
      var resultado = funcion esUnaTarjetaValida (digito, (digito * 2));
       retorna ((digito + (digito * 2)) % 10) == 0;
      }
  
  esUnaTarjetaValida (70) /*Llamando a la funcion, en este caso, que la suma resulte 70, la tarjeta seria valida, ya que 70 modulo de 10 es 0*/
fin
