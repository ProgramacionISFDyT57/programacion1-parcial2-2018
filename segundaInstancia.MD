# Programación 1

### Parcial 2 - Segunda Instancia

#### Tecnicatura Superior en Análsis de Sistemas - 2018

## 1

Escribir una función que calcule si un número es par. Defina la mejor manera de hacerlo según sus criterios.

## 2

Dado el siguiente fragmento de código:

``` javascript
function esPrimo(num) {
    if (isNaN(num)) {
        return 'error';
    }
    let divisible = 0;
    for(let i = num; i > 0; i--) {
        if (num % i === 0) {
            divisible++;
        }
    }
    return divisible === 2;
}

const n1 = process.argv[2];

```

Completar el código para que calcule si `n1` es primo e imprima por pantalla los 3 resultados posibles:

* No es número
* Es primo
* No es primo

## 3

Escriba un programa que dibuje el triángulo del tamaño indicado por el usuario de acuerdo al ejemplo:

Número recibido: `5`

```
*
**
***
****
*****
```

## 4

Escriba un programa que pida al usuario dos números enteros, y luego entregue la multiplicación de todos los números pares que están entre ellos. 

* Ejemplo 1: Si los números son 1 y 7, debe entregar como resultado 2 * 4 * 6 = 48.

* Ejemplo 2: Si los números son 14 y 25, debe entregar como resultado 14 * 16 * 18 * 20 * 22 * 24 = 42577920