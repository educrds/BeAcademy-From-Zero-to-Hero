# Praticando

### 1. Declare uma variável de nome person

```js
let person;
```

### 2. Que tipo de dado é a variável acima?

Indefinido.

### 3. Declare uma variável e atribua valores para cada um dos dados:

```js
let name = "Eduardo";
let age = 21;
let weight = 65;
let isAdmin = true;
let isAMan = true;
```

### 4. A variável `human` abaixo é de que tipo de dados?

Objeto

### 4.1 Atribua a ela as mesmas propriedades e valores do exercício 3

```js
let human = {
	name: "Eduardo";
	age: 21;
	weight: 65;
	isAdmin: true;
	isAMan: true;
};
```

### 4.2 Mostre no console a seguinte mensagem

```js
console.log(`O humano ${human.name} tem o peso ${human.weight} kg.`)
```

### 5. Declare uma variável do tipo `Array`, de nome humans e atribua a ela nenhum valor, ou seja, somente o Array vazio

```js
let humans = [];
```

### 6. Reatribua valor para a variável acima, colocando dentro dela o objeto human da questão 4

```js
humans.push(human);
```

### 7. Coloque no console o valor da posição zero do array acima

```js
console.log(humans[0]);
```

### 8. Crie um novo objeto student e coloque na posiçao 1 do `Array` students

```js
let student = {
  name: "Eduardo",
  id: 109898,
  course: "Engenharia de Software",
};

let students = [];

students.push(student);
```

### 9. Sem rodar o código responda o resultado da saída abaixo

### a)

```jsx
console.log(a);
var a = 1 
```

Retornará `indefinido`, pois a variável está sendo atribuída depois do `log`.

### b)

```jsx
let a;
console.log(a);
{
    let a = 2;
    console.log(a);
}
console.log(a);
```

Imprimirá apenas o `log` dentro das chaves, pois está utilizando `let` que é privada ao bloco que está inserida. O resto retornará `indefinido`.

### c)

```jsx
console.log(b);
{
    let b = 3;
    console.log(b);
}
console.log(b);
```

Retornará erro.

### d)

```jsx
const c = 10;
{
    console.log(c);
    const c = 20;
    console.log(c);
}
```

Retornará erro.
