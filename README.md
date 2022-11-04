# Ejersicio de programacion en javascript

en esto momento estoy resolviendo algunos problema basico en javascrit para poder entender la logica de programacion es  muy basico esto consepto de programacion .

- Analizar el problema 
- escribir el codogo
- test del codigo que corra bn

**Se seguira agragando atualisaciones de proyecto**

##Esto es un de los ejersico que he resuelto..
...
 /* 7) Programa una funci�n que valide si una palabra o frase dada, es un pal�ndromo (que se lee igual en un sentido que en otro), pe. mifuncion("Salas") devolver� true */

      const palindromo = (palabra = "") => {
        if (!palabra) {
          return console.error("no ha introducido la palabra");
        }

        if (typeof palabra !== "string") {
          return console.error(
            "el tipo de dato es incorrecto" + " " + typeof palabra
          );
        }

        let newCadena = palabra.split("").reverse().join("");

        if (newCadena === palabra) {
          return console.log(
            "la palabra que escridio es palindromo" + " " + newCadena
          );
        } else {
          console.error(
            "la palabra que escridio no es palindromo" + " " + newCadena
          );
        }
      };

      palindromo("salas");

...

## Soy un persona apreder js en 2022

:tw-1f60e:

