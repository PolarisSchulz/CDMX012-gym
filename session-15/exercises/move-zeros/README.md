---
difficulty:
  - beginner
OAs:
  - arrays
projects:
  - data lovers
  - memory match
  - emergency room
---

# Moving Zeros To The End

[https://www.codewars.com/kata/52597aa56021e91c93000cb0/train/javascript](https://www.codewars.com/kata/52597aa56021e91c93000cb0/train/javascript)

Escribe un algoritmo que recibe un arreglo con elementos y mueva todos los ceros
al final, preservando el orden de los otros elementos que no sean cero.

__Ejemplo__

```js
Entrada: [false,1,0,1,2,0,1,3,"a"]
Salida: [false,1,1,2,1,3,"a",0,0]
```

> __Importante__ ❗
>
> - Considera el tipo de dato
> - ¡No olvides retornar el  arreglo con los ceros al final!


```js
function moveZeros(arr) {
	
  let zeros = [], nonZeros=[], result=[];

//Iterar -> Recorrer los elementos de un arreglo u objeto por medio de un ciclo
//Estructuras de control --> for, forEach, forOf, while, do-while 
// == es que sea el mismo valor y === que sea el mismo valor y tipo de dato
  for(let i=0; i<arr.length; i++){
  if(arr[i]===0){
    zeros.push(arr[i]);
  }else{
    nonZeros.push(arr[i]);
   }
 }
  result = nonZeros.concat(zeros);
  return result

}
```
