---
difficulty:
  - newbie
OAs:
  - booleans
  - conditionals
projects:
  - cipher
  - card validation
---

# Icy-hot

[https://the-winter.github.io/codingjs/exercise.html?name=icyHot&title=Warmup-1](https://the-winter.github.io/codingjs/exercise.html?name=icyHot&title=Warmup-1)

Dadas dos temperaturas, devuelve true si una es menor que 0 y la otra es mayor
que 100.

__Ejemplos:__

```js
  icyHot(120, -1) → true
  icyHot(-1, 120) → true
  icyHot(2, 120) → false
```



function icyHot(temp1, temp2){

  if((temp1<0 || temp2<0) && (temp1>100 || temp2>100)){
    return true;
  }else{
    return false;
  }
  
}
