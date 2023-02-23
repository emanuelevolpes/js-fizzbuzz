Scrivi un programma che stampi in console i numeri da 1 a 100, ma che per i multipli di 3 stampi “Fizz” al posto del numero e per i multipli di 5 stampi “Buzz”. Per i numeri che sono sia multipli di 3 che di 5 stampi “FizzBuzz”.


//ultilizzo un ciclo for in questo modo;
⬇️
//nel contatore imposto una variabile a cui assegno il valore iniziale 1;
//la condizione da verificare per poter eseguire il codice sarà "variabile <= 100";
//infine incremento il valore utilizzando "variabile++";


//all'interno del ciclo for mi servono delle condizioni per stampare "fizz" al posto dei multipli di 3, "buzz" al posto dei multipli di 5 e "fizzbuzz" al posto dei multipli di 3 e di 5;
//per verificare che un numero sia divisibile per un altro numero posso utilizzare l'operatore modulo "%" all'interno della condizione;
// se il numero è multiplo di 3 stampo "fizz" utilizzando "replace";
// se il numero è multiplo di 5 stampo "buzz" utilizzando "replace";
// se il numero è multiplo sia di 3 che di 5 stampo "fizzbuzz";