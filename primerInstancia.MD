# Programación 1

### Parcial 2 - Primer Instancia

#### Tecnicatura Superior en Análsis de Sistemas - 2018

## 1

Escribir una función que calcule si un número es primo. defina la mejor manera de hacerlo según sus criterios.

## 2

Dado el siguiente fragmento de código:

``` javascript
function esPar(num) {
    if (isNaN(num)) {
        return 'error';
    }
    else if (num % 2 === 0) {
        return true;
    } else {
        return false;
    }
}

const n1 = 'e';
const n2 = 5;
const n3 = process.argv[2];

```

Completar el código para que calcule si un número es par e imprima por pantalla los 3 resultados posibles:

* No es número
* Es par
* No es par

## 3

Escriba un programa que dibuje el triángulo del tamaño indicado por el usuario de acuerdo al ejemplo:

Número recibido: `5`

```
*****
****
***
**
*
```

## 4

Escriba un programa que pida al usuario dos números enteros, y luego entregue la suma de todos los números primos que están entre ellos. 

* Ejemplo 1: Si los números son 1 y 7, debe entregar como resultado 3 + 5 + 7 = 15.

* Ejemplo 2: Si los números son 14 y 25, debe entregar como resultado 17 + 19 + 23 = 59