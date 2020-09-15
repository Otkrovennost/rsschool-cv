# Anastasiya Ivanova

## Contacts
* email: Otkrovennost@mail.ru
* skype: stasya1043

## My goal
My goal is striving for new knowledge and improving myself as a professional. 

## Skills
* HTML, CSS
* JS
* React
* Git, GitHub, Webpack, Node

## Code examples

```

function solution(str){
  if(str.length === 0) {
    return [];
  } else {
    if(str.length % 2 !== 0) {
      str = str + '_';
    }
    return str.match(/.{1,2}/g);
  }
}
```

```

function solution(str){
  if(str.length === 0) {
    return [];
  } else if(str.length % 2 !== 0) {
    str = str + '_';
    return str.match(/.{1,2}/g);
  } else if(str.length % 2 === 0) {
      return str.match(/.{1,2}/g);
  }
}
```

```

function sumOfMinimums(arr) {
let newArr = [];
  for(let i = 0; i < arr.length; i++) {
    let j = Math.min.apply(null, arr[i]);
    newArr.push(j);
  }
  console.log(newArr);
  return newArr.reduce((a, b) => a + b, 0);
}
```

## My projects

* [Cat-energy](https://otkrovennost.github.io/cat-energy/)
* [Ligabank](https://otkrovennost.github.io/ligabank-project/)
* [SmartDevice](https://otkrovennost.github.io/SmartDevice/)
* [Keksoboking](https://otkrovennost.github.io/keksobuking-project/)
* [Kekstagram](https://otkrovennost.github.io/kekstagram-project/)
* [Big-trip](https://otkrovennost.github.io/big-trip/)
* [Six-cities](https://github.com/Otkrovennost/986345-six-cities-4)

## Education

HTML Academy, Coursera

## English level

Intermediate. I can read and understand a technical documentation.