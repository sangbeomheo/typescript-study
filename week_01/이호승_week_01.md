</br>

# πλ€μ΄κ°κΈ°μ μμ

</br>

> ν΄λΉ ν¬μ€νΈλ νμμ€ν¬λ¦½νΈλ₯Ό νμ΅ν λ΄μ©μ μ£Όκ΄μ μΈ κΈ°μ€μ λ°λΌ μ λ¦¬ν λ΄μ©μλλ€.

</br>

---

</br>

# π νμ

</br>

## 2.1 νμμ μ’λ₯

`νμ`μ΄λ `Javascript`μμ λ€λ£¨λ κ°μ <strong style="color:skyblue"> νν</strong>μ λν μ€λͺμ΄λ€.

</br>

#### π ννλ?

κ°μ μ‘΄μ¬νλ μμ±κ³Ό λ©μλ κ·Έλκ³  λ΄μ₯λμ΄ μλ `typeOf` μ°μ°μκ° μ€λͺνλ κ²μ μλ―Έ

- μΌκ³± κ°μ§ κΈ°λ³Έ μμ νμ

  1. `null`

  2. `undefined`
  3. `boolean`
  4. `string`
  5. `number`
  6. `BingInt`
  7. `symbol`

</br>

### 2.1.1 νμ μμ€ν

νμ μμ€ν(type system)μ νλ‘κ·Έλλ° μΈμ΄κ° νλ‘κ·Έλ¨μμ κ°μ§ μ μλ νμμ μ΄ν΄νλ λ°©λ²μ λν κ·μΉ μ§ν©.

- κΈ°λ³Έμ μΈ νμμ€ν¬λ¦½νΈμ νμ μμ€ν λμ

  1. μ½λλ₯Ό μ½κ³  μ‘΄μ¬νλ λͺ¨λ  νμμ μ΄ν΄
  2. κ° κ°μ΄ μ΄κΈ° μ μΈμμ κ°μ§ μ μλ νμμ νμΈ
  3. κ° κ°μ΄ μΆν μ½λμμ μ΄λ»κ² μ¬μ©λ  μ μλμ§ λͺ¨λ  λ°©λ² νμΈ
  4. κ°μ μ¬μ©λ²μ΄ νμκ³Ό μΌμΉνμ§ μμΌλ©΄ μ¬μ©μμκ² μ€λ₯ νμ

</br>

### 2.1.2 μ€λ₯ μ’λ₯

μμ£Ό μ νκ² λλ λ κ°μ§ μ€λ₯

- <strong>κ΅¬λ¬Έ μ€λ₯</strong> :

  - νμμ€ν¬λ¦½νΈκ° μλ°μ€ν¬λ¦½νΈλ‘ λ³νλλ κ²μ μ°¨λ¨ν κ²½μ°

- <strong>νμ μ€λ₯</strong> :
  - νμ κ²μ¬κΈ°μ λ°λΌ μΌμΉνμ§ μλ κ²μ΄ κ°μ§λ κ²½μ°

</br>

#### κ΅¬λ¬Έ μ€λ₯

- `Typescript`κ° μ½λλ‘ μ΄ν΄ν  μ μλ μλͺ»λ κ΅¬λ¬Έμ κ°μ§ν λ λ°μ

- κ³ λ¬Έ μ€λ₯κ° λ°μνλ κ²½μ° μ»΄νμΌμ μ°¨λ¨
  (`javascript` νμΌμ μ»μ§ λͺ»νκ±°λ μ»λλΌλ μμκ³Ό λ€λ₯Ό μ μμ)

</br>

```ts
let let someting;
// Error : ',' expected
```

> π νμμ€ν¬λ¦½νΈλ κ΅¬λ¬Έ μ€λ₯μλ μκ΄μμ΄ μλ°μ€ν¬λ¦½νΈ μ½λλ₯Ό μΆλ ₯νκΈ° μν΄μ μ΅μ μ λ€ν¨. νμ§λ§ μνλ μΆλ ₯ κ²°κ³Όκ° μλ μ μμ. λ°λΌμ μ»΄νμΌ λ `Javascript`λ₯Ό μ€ννκΈ° μ μ κ΅¬λ¬Έ μ€λ₯λ₯Ό μμ νλ κ²μ΄ μ’μ

</br>

#### νμ μ€λ₯

`Typescript`μ `inference`λ‘ μ€λ₯λ₯Ό κ°μ§νμ λ λ°μ
μ€λ₯κ° λ°μνλ€κ³  μ»΄νμΌμ μ°¨λ¨νμ§ μμ

> π `Javascript` μ½λκ° μνλ λλ‘ μ€νλμ§ μμ κ°λ₯μ±μ΄ μλ€λ μ νΈλ₯Ό νμ μ€λ₯λ‘ μλ €μ€λ€. `Javascript`λ₯Ό μ€ννκΈ° μ μ νμ μ€λ₯λ₯Ό νμΈνκ³  λ°κ²¬λ λ¬Έμ λ₯Ό λ¨Όμ  ν΄κ²°νλ κ²μ΄ κ°μ₯ μ’λ€.

</br>

---

</br>

## 2.2 ν λΉ κ°λ₯μ±

`Typescript`λ λ³μμ μ΄κΉκ°μ μ½κ³  ν΄λΉ λ³μκ° νμ©λλ νμμ κ²°μ 

`Typescript`μμ ν¨μ νΈμΆμ΄λ λ³μμ κ°μ μ κ³΅ν  μ μλμ§ νμΈνλ κ²μ <strong style="color:skyblue"> ν λΉ κ°λ₯μ±(assignability)</strong>λΌκ³  νλ€.

μ¦, μ λ¬λ κ°μ΄ μμλ νμμΌλ‘ ν λΉ κ°λ₯νμ§ νμΈ

</br>

## 2.3 annotation

μ΄κΈ° νμμ μ μΆν  μ μλ λ³μλ <strong style="color:tomato"> μ§ννλ any</strong> λΌκ³  λΆλ₯Έλ€.

```ts
let rocker; // type : any
rocker = 'Joan Jett'; // type : string

rocker.toUpperCase(); //OK

rocker = 19.58; // type : number
rocker.toPrecision(1); //OK

rocker.toUpperCase();
//Property 'toUpperCase' does not exist on type 'number'.
```

</br>

`typescript`λ μ΄κΉκ°μ ν λΉνμ§ μκ³  λ³μμ νμμ μ μΈν  μ μλ κ΅¬λ¬ΈμΈ `type annotation` μ΄ μ‘΄μ¬νλ€.

`type annotation`μ λ³μ μ΄λ¦ λ€μ λ°°μΉλλ©° μ½λ‘ (:)κ³Ό νμμ΄λ¦μ μ°¨λ‘λλ‘ κΈ°μ¬νλ€.

```ts
let rocker: string;
rocker = 'Joan Jett';
```

</br>

μ΄λ¬ν `Type annotation`μ `Typescript`μλ§ μ‘΄μ¬νλ©° λ°νμ μ½λμ μν₯μ μ£Όμ§λ μκ³ , μ»΄νμΌ μ μ κ±°λλ€.

> π μ΄κΈ° ν λΉμΌλ‘ `TypeChecker`μ μν΄μ `inference`κ° κ°λ₯ν  κ²½μ° `anntation`κΉμ§ μ€λ³΅ν΄μ μ¬μ©νμ§ μλ κ²μ΄ μ’λ€.

     (κ²½μ°μ λ°λΌ λ€λ¦)

</br>

## 2.4 νμ νν

νμμ ννκ° μ ν΄μ‘λ€λ©΄ `Typescript`λ κ°μ²΄μμ μ΄λ€ λ©€λ² μμ±μ΄ μ‘΄μ¬νλμ§ μκ³  μκΈ° λλ¬Έμ ν΄λΉ νμμμ μ¬μ©κ°λ₯ν μμ±μ μλμμ±ν  μ μκ³ , μ λͺ»λ λΆλΆμ΄ μλμ§λ νμΈ κ°λ₯νλ€.

```ts
// Type AnnotationμΌλ‘ κ΅¬μ²΄μ μΌλ‘ λͺμκ°λ₯
// νμ§λ§ Inferenceκ° κ°λ₯ν κ²½μ° μ€νλ € ν¨μ¨κ³Ό κ°λμ±μ΄ λ¨μ΄μ§ μ μμ
const user: { firstName: string; age: number } = {
  firstName: 'hoseung',
  age: 33,
};
//Property 'middleName' does not exist on type '{ firstName: string; age: number; }'.
user.middleName;
```

`Typescript`λ κ°μ²΄μ ννμ λν μ΄ν΄λ₯Ό λ°νμΌλ‘ ν λΉ κ°λ₯μ±λΏλ§ μλλΌ κ°μ²΄ μ¬μ©κ³Ό κ΄λ ¨λ λ¬Έμ λ μλ €μ€λλ€.

</br>

## 2.5 Module

ν λͺ¨λμμ λ€λ₯Έ νμΌμ μ μΈλ λ³μμ λμΌν μ΄λ¦μΌλ‘ μ μΈλ λ³μλ λ€λ₯Έ νμΌμ λ³μλ₯Ό κ°μ Έμ€μ§ μλ μ΄μ μ΄λ¦ μΆ©λμ΄ λ°μνμ§ μλλ€.
(`export`λ‘ λ΄λ³΄λ΄μ§ μμΌλ©΄ λ€λ₯Έ νμΌμμ μ¬μ©ν  μ μλ€)

```ts
// a.ts
export const shared = 'koby';

// b.ts
export const shared = 'koby';

// index.ts
import { shared } from './a';
// Error: Import declaration confilcts with local declaration of 'shared'

export const shared = 'koby';
//Error : Individual declarations in merged declaration
//'shared' must be all exported or all local.
```

κ·Έλ¬λ νμΌμ΄ `script`μΌ κ²½μ° `Typescript`λ ν΄λΉ νμΌμ `global scope`λ‘ κ°μ£Όνλ―λ‘ λͺ¨λ  `script`κ° νμΌμ λ΄μ©μ μ κ·Όν  μ μλ€.

# π λ νΌλ°μ€

> Goldberg, et al. λ¬λ νμμ€ν¬λ¦½νΈ / μ‘°μ κ³¨λλ²κ·Έ μ§μ ; κ³ μΉμ μ?κΉ, 2023.

> <a href="https://inpa.tistory.com/entry/TS-%F0%9F%93%98-%ED%83%80%EC%9E%85%EC%8A%A4%ED%81%AC%EB%A6%BD%ED%8A%B8-%EB%AA%A8%EB%93%88-%EB%84%A4%EC%9E%84%EC%8A%A4%ED%8E%98%EC%9D%B4%EC%8A%A4-%EC%8B%9C%EC%8A%A4%ED%85%9C-%EC%9D%B4%ED%95%B4%ED%95%98%EA%B8%B0" target="_blank"> λͺ¨λ & λ€μμ€νμ΄μ€ μμ€ν μ΄ν΄νκΈ° | Inpa Dev </a>

> <a href="https://www.typescriptlang.org/ko/docs/handbook/modules.html" target="_blank"> Modules | Typescript κ³΅μλ¬Έμ </a>

</br>

---

- μ λμΈ(union): κ°μ νμ©λ νμμ λ κ° μ΄μμ κ°λ₯ν νμμΌλ‘ νμ₯νλ κ²

- λ΄λ‘μ(narrowing): κ°μ νμ©λ νμμ΄ νλ μ΄μμ κ°λ₯ν νμμ΄ λμ§ μλλ‘ μ’νλ κ²

</br>

## π 3.1 μ λμΈ(Union)

</br>

κ°μ΄ μ νν μ΄λ€ νμ μΈμ§ λͺ¨λ₯΄μ§λ§ λ κ° μ΄μμ μ΅μ μ€νλλΌλ κ²μ μκ³  μλ κ²½μ° μ¬μ©ν  μ μλ€.

νμμ€ν¬λ¦½νΈλ κ°λ₯ν κ° λλ κ΅¬μ± μμ μ¬μ΄μ `|` μ°μ°μλ₯Ό μ¬μ©ν΄ μ λμΈ νμμμ λνλΈλ€.

```js
// // something: string | number
let something: string | number;

// something: string | number
let something2 = Math.random() > 0.5 ? 'leekoby' : 1;

// "string"κ³Ό "number" λͺ¨λ κ°κ³  μλ λ©μλ
something2.toString();

// β Error : Property 'toFixed' does not exist on type 'string'.
something2.toFixed(); // "number"λ§ κ°κ³  μλ λ©μλ

// β Error : Property 'toUpperCase' does not exist on type 'number'.
something2.toUpperCase(); //"string" λ§ κ°κ³  μλ λ©μλ
```

</br>

---

</br>

## π 3.2 λ΄λ‘μ(narrowing)

</br>

<strong style="color:skyblue">λ΄λ‘μ(narrowing)</strong>

- γ±κ°μ νμ(union)μ λ²μλ₯Ό μ’νλ κ³Όμ 
- κ°μ΄ μ΄μ μ μ μΆλ κ²λ³΄λ€ λ κ΅¬μ²΄μ μΈ νμμμ μ μΆνλ κ²

<strong style="color:skyblue">νμκ°λ(type guard)</strong>

- νμμ μ’νλ λ° μ¬μ©ν  μ μλ λΌλ¦¬μ  κ²μ¬

</br>

### 3.2.1 κ° ν λΉμ ν΅ν λ΄λ‘μ

νμμ€ν¬λ¦½νΈλ λ³μμ νμμ ν λΉλ κ°μ νμμΌλ‘ μ’νλ€.

```js
let admiral: number | string;
admiral = 'leekoby';

admiral.toUpperCase(); //OK : string

// β Error : Property 'toFixed' does not exist on type 'string'. Did you mean 'fixed'?
admiral.toFixed();
```

```js
let admiral: number | string = 'leekoby';

admiral.toUpperCase(); //OK : string

// β Error : Property 'toFixed' does not exist on type 'string'. Did you mean 'fixed'?
admiral.toFixed();
```

</br>

### 3.2.2 μ‘°κ±΄ κ²μ¬λ₯Ό ν΅ν λ΄λ‘μ

μ‘°κ±΄λ¬ΈμΌλ‘ μ λμΈ νμμ μ’ν μ μλ€.

```ts
let something = Math.random() > 0.5 ? 'leekoby' : 1;

// typeμ΄ number μΌ λλ‘ νμ μ’νκΈ°
if (something === 2) {
  // something: 2
  something.toFixed();
}
// typeμ΄ string μΌ λλ‘ νμ μ’νκΈ°
if (something === 'leekoby') {
  // something: "leekoby"
  something.toUpperCase();
}

// β Error : Property 'toUpperCase' does not exist on type 'number'.
something.toUpperCase();
```

</br>

### 3.2.3 typeof κ²μ¬λ₯Ό ν΅ν λ΄λ‘μ

`typeof` μ°μ°μλ₯Ό μ¬μ©νμ¬ νμμ μ’ν μ μμ.

`typeof` κ²μ¬λ μμ£Ό μ¬μ©νλ μ€μ©μ μΈ λ°©λ²

```js
let something = Math.random() > 0.5 ? 'leekoby' : 1;

// typeμ΄ number μΌ λλ‘ νμ μ’νκΈ°
if (typeof something === 'number') {
  something.toFixed();
}
// typeμ΄ string μΌ λλ‘ νμ μ’νκΈ°
if (typeof something === 'string') {
  something.toUpperCase();
}

// ! λ₯Ό μ¬μ©ν λΌλ¦¬ λΆμ κ³Ό else λ¬Έλ κ°λ₯
// typeμ΄ number μΌ λλ‘ νμ μ’νκΈ°
if (!(typeof something === 'number')) {
  something.toUpperCase();
} else something.toFixed();
// typeμ΄ string μΌ λλ‘ νμ μ’νκΈ°

// μΌν­μ°μ°μλ μ¬μ©κ°λ₯
typeof something === 'string' ? something.toUpperCase() : something.toFixed();

// β Error : Property 'toUpperCase' does not exist on type 'number'.
something.toUpperCase();
```

</br>

---

</br>

## π 3.3 λ¦¬ν°λ΄ νμ(literal type)

μ’ λ κ΅¬μ²΄μ μΈ λ²μ μ μμ νμ

μμ νμ κ° μ€μ νλκ° μλ <strong style="color:tomato">νΉμ  μμ―κ°</strong>μΌλ‘ μλ €μ§ νμμ μλ―Ένλ€.

- `string` μ΄ μλ "leekoby"λΌλ κ΅¬μ²΄μ μΈ νμμ λ¦¬ν°λ΄ νμμ΄λΌκ³  νλ€.

```ts
// const something:"leekoby"
const something = 'leekoby';
```

</br>

### 3.3.1 λ¦¬ν°λ΄ ν λΉ κ°λ₯μ±

λμΌν μμ νμμ΄λΌκ³  ν΄λ μλ‘ λ€λ₯Έ λ¦¬ν°λ΄ νμμ΄λ©΄ ν λΉν  μ μλ€.

```ts
let something: 'leekoby' = 'leekoby';
something = 'Byron'; // β Error: Type '"Byron"' is not assignable to type '"leekoby"'.
```

</br>

β λ¦¬ν°λ΄ νμμ μμ κ°μ ν λΉ κ°λ₯
β μμ κ°μ λ¦¬ν°λ΄ νμμ ν λΉ λΆκ°

```ts
let sayHi: 'Hi';
sayHi = 'Bye'; //β μ€λ₯λ°μ

sayHi = 'Hi';
let something = '';
something = sayHi; // βκ°λ₯
```

</br>

## 3.4 μκ²©ν null κ²μ¬(strict null checking)

νμμ΄ νμν μμΉμμ null κ°μ νμ©νλ λ§μ νμ μμ€ν
const something: string = null;

νμμ€ν¬λ¦½νΈλ, `strictNullChecks` μ΅μμ ν΅νμ¬ μκ²©ν `null` κ²μ¬ μ€μ μ ν  μ μλ€.
μΌλ°μ μΌλ‘ μκ²©ν `null` μ²΄ν¬λ₯Ό νμ±νν΄μΌλ§ `null` λλ `undefined` κ°μΌλ‘ μΈν μ€λ₯λ‘ λΆν° μμ νμ§ μ½κ² νμκ°λ₯

```ts
let something: string;

// strictNullChecks: true
something = null; // β Error: Type 'null' is not assignable to type 'string'.

// strictNullChecks: false
something = null; // λ¬Έμ  μμ
```

> π μκ²©ν `null`κ²μ¬λ₯Ό νμ±ννλ κ²μ κΆμ₯

</br>

### 3.4.2 μ°Έ κ²μ¬λ₯Ό ν΅ν λ΄λ‘μ

`Javascript`μμλ `falsy`(`0, -0, 0n, "", false, null, undefined, NaN`) κ°μ `falsy` κ°μ μ μΈνκ³  λͺ¨λ μ°Έμ΄λ€. μ΄λ₯Ό μ΄μ©νμ¬ νμ μΆλ‘ μ ν  μ μλ€.

```ts
let sth = Math.random() > 0.5 ? 'leekoby' : undefined;

if (sth) {
  sth.toUpperCase(); //β
}
sth.toUpperCase();
// β Error : sth' is possibly 'undefined'.
```

> π’ λΌλ¦¬ μ°μ°μμ λΆμ‘±ν μ  :

- μ°Έ μ¬λΆ νμΈ μΈμ λ€λ₯Έ κΈ°λ₯μ μ κ³΅νμ§ μμ.
- `falsy` κ°μ΄λΌλ©΄ `""` κ°μ λΉ λ¬Έμμ΄μΈμ§ `undefined`μΈμ§ μμ μμ

```ts
let sth = Math.random() > 0.5 && 'hello';
if (sth) {
  // sth: string
  sth;
} else {
  // sth : string | false
  sth;
}
```

</br>

### 3.4.3 μ΄κΉκ°μ΄ μλ λ³μ

</br>

`javascript`μμλ μ΄κΉκ°μ΄ μλ λ³μλ κΈ°λ³Έμ μΌλ‘ `undefined`κ° λλ€.

`Typescript` μμλ κ°μ΄ ν λΉλ  λκΉμ§ λ³μκ° `undefined`μμ μ΄ν΄νκ³ , λ³μμ μμ±μ μ¬μ©νλ €κ³  μλνλ©΄ μ€λ₯λ₯Ό λ°μμν¨λ€.

```ts
let sth: string;
sth.length;
// β Error : Variable 'sth' is used before being assigned.

let someth: string | undefined;

someth?.length; //β

someth = 'leekoby';
someth.length; // β
```

</br>

## 3.5 νμ λ³μΉ­

<strong style="color:skyblue">νμ λ³μΉ­(type alias)</strong> :

- μ¬μ¬μ©νλ νμμ λ μ¬μ΄ μ΄λ¦μ ν λΉνλ κ²
- `type` μλ‘μ΄μ΄λ¦ = `type` ννμ΄λ©° `pascalCase`λ‘ μμ±

```ts
type sth = string | number;
let something: sth = 'leekoby';

type sth2 = boolean | number | string | null | undefined;
let first: sth2;
let second: sth2;
let third: sth2;
```

</br>

### 3.5.1 νμ λ³μΉ­μ `Javascript`μ μλ€

νμ λ³μΉ­μ `annotion`μ²λΌ μλ°μ€ν¬λ¦½νΈλ‘ μ»΄νμΌλμ§ μλλ€. (λ°νμμ μ‘΄μ¬νμ§ μμ)

μμ μ½λλ₯Ό μ»΄νμΌν κ²°κ³Ό

```ts
'use strict';
let something = 'leekoby';
let first;
let second;
let third;
```

λν νμ λ³μΉ­μ νμ μμ€νμλ§ μ‘΄μ¬νλ―λ‘ λ°νμ μ½λμμ μ°Έμ‘°ν  μ μλ€.

```ts
console.log(sth, sth2);
// β Error : 'sth' only refers to a type,
// but is being used as a value here.

// β Error : 'sth2' only refers to a type,
// but is being used as a value here.
```

</br>

### 3.5.2 νμ λ³μΉ­ κ²°ν©

νμ λ³μΉ­μ λ€λ₯Έ νμ λ³μΉ­μ μ°Έμ‘°ν  μ μλ€.

```ts
type Id = number | string;
type Idmaybe = Id | undefined | null;
// IdMaybeμ νμμ number | string | undefined | null
```

```ts
type Idmaybe = Id | undefined | null;
type Id = number | string;
```

---

</br>

</br>

# π λ νΌλ°μ€

> Goldberg, et al. λ¬λ νμμ€ν¬λ¦½νΈ / μ‘°μ κ³¨λλ²κ·Έ μ§μ ; κ³ μΉμ μ?κΉ, 2023.

> <a href="https://typescript-kr.github.io/pages/unions-and-intersections.html" target="_blank"> Typescript νΈλλΆ </a>

</br>

---

</br>

# π 4.1 κ°μ²΄ νμ

- `{...}` κ΅¬λ¬Έμ μ¬μ©ν΄μ κ°μ²΄ λ¦¬ν°λ΄μ μμ±νλ©΄, TSλ ν΄λΉ μμ±μ κΈ°λ°μΌλ‘ μλ‘μ΄ κ°μ²΄ νμ λλ νμ ννλ₯Ό κ³ λ €νλ€.

- ν΄λΉ κ°μ²΄ νμμ κ°μ²΄μ κ°κ³Ό λμΌν μμ±λͺκ³Ό μμ νμμ κ°λλ€.
- κ°μ μμ±μ μ κ·Όνλ €λ©΄ value.λ©€λ²λλvalue["λ©€λ²"]λ₯Ό κ΅¬λ¬Έμ μ¬μ©νλ€.

```ts
const someone = {
  born: 1990,
  name: 'leekoby',
};
someone['born']; // νμ : number
someone.name; // νμ : string

someone.hello;
// β Error : Property 'hello' does not exist on type '{ born: number; name: string; }'.
```

- κ°μ²΄ νμμ `Typescript`κ° `Javascript`λ₯Ό μ΄ν΄νλ λ°©λ²μ λν ν΅μ¬ κ°λ

- `null`κ³Ό `undefined`λ₯Ό μ μΈν λͺ¨λ  κ°μ κ·Έ κ°μ λν μ€μ  νμμ λ©€λ² μ§ν©μ κ°μ§.
- κ·Έλ κΈ° λλ¬Έμ `Typescript`λ λͺ¨λ  κ°μ νμμ νμΈνκΈ° μν΄μ κ°μ²΄ νμμ μ΄ν΄ν΄μΌνλ€.

</br>

## 4.1.1 κ°μ²΄ νμ μ μΈ

- κΈ°μ‘΄ κ°μ²΄μμ μ§μ  νμμ μ μΆνλ λ°©λ²λ κ΅μ₯ν μ’μ§λ§, κ°μ²΄μ νμμ λͺμμ μΌλ‘ μ μΈνκ³  μΆμ

- λͺμμ μΌλ‘ νμμ΄ μ μΈλ κ°μ²΄μλ λ³λλ‘ κ°μ²΄μ ννλ₯Ό μ€λͺνλ λ°©λ² νμ
- κ°μ²΄ νμμ κ°μ²΄ λ¦¬ν°λ΄κ³Ό μ μ¬νκ² λ³΄μ΄μ§λ§ νλ κ° λμ  νμμ μ¬μ©ν΄ μ€λͺ

```
let someone = {
    born: 1990,
    name: "leekoby"
};

someone = {
    born: 1333,
    name: "kobykoby"
};
someone["born"] // νμ : number
someone.name // νμ : string

someone = "cube"
// β Error : Type 'string' is not assignable to type '{ born: number; name: string; }'.
```

</br>

## 4.1.2 λ³μΉ­ κ°μ²΄ νμ

- κ°μ²΄ νμμ κ³μ μ₯μ±νλ μΌμ ν¨μ¨μ±μ΄ λ¨μ΄μ§λ€.

- κ°μ²΄μ νμμ νμ λ³μΉ­μ ν λΉν΄ μ¬μ©νλ λ°©λ²μ΄ λ μΌλ°μ μ΄λ€.
- β λλΆλΆμ νμμ€ν¬λ¦½νΈ νλ‘μ νΈλ κ°μ²΄ νμμ μ€λͺν  λ interface ν€μλ μ¬μ©μ μ μΈνλ€.

```ts
type koby = {
  born: number;
  name: string;
};

let someone: koby;
someone = {
  born: 1990,
  name: 'leekoby',
};

someone = {
  born: 1333,
  name: 'kobykoby',
};
someone['born']; // νμ : number
someone.name; // νμ : string

someone = 'cube';
// β Error : Type 'string' is not assignable to type 'koby'.
```

</br>

> λλΆλΆμ `Typescript` νλ‘μ νΈλ κ°μ²΄ νμμ μ€λͺν  λ `interface`

# π¦ 4.2 κ΅¬μ‘°μ  νμ΄ν

- νμμ€ν¬λ¦½νΈμ νμ μμ€νμ κ΅¬μ‘°μ μΌλ‘ νμν λμ΄ μλ€.
  - μ¦, νμμ μΆ©μ‘±νλ λͺ¨λ  κ°μ ν΄λΉ νμμ κ°μΌλ‘ μ¬μ©ν  μ μλ€.
  - λ§€κ°λ³μλ λ³μκ° νΉμ  κ°μ²΄ νμμΌλ‘ μ μΈλλ©΄ νμμ€ν¬λ¦½νΈμ μ΄λ€ κ°μ²΄λ₯Ό μ¬μ©νλ  ν΄λΉ μμ±μ΄ μμ΄μΌ νλ€

```ts
type WithFirstName = {
  firstName: string;
};

type WithLastName = {
  lastName: string;
};

const hasBoth = {
  firstName: 'Koby',
  lastName: 'Lee',
};

// β hasBothλ string νμμ "firstName"μ ν¬ν¨ν¨
let WithFirstName: WithFirstName = hasBoth;

// β hasBothλ string νμμ "lastName"μ ν¬ν¨ν¨
let WithLastName: WithLastName = hasBoth;
```

- <strong style="color:skyblue">λ νμ΄ν ( `JavaScript` )</strong>:

  - λ°νμμμ μ¬μ©λ  λκΉμ§ κ°μ²΄ νμμ κ²μ¬νμ§ μλ κ²

- <strong style="color:skyblue">κ΅¬μ‘°μ  νμ΄ν ( `TypeScript` )</strong>:
  - μ μ  μμ€νμ΄ νμμ κ²μ¬νλ κ²

</br>

## 4.2.1 μ¬μ©κ²μ¬

κ°μ²΄ νμμ μ μν κ°μ νμμ μΌλ‘ μ μΈν΄μΌ νκ³ , νμμ μ λ³΄μλ μΌμΉν΄μΌνλ€.

```ts
type Sth = {
  name: string;
  age: number;
};

//  Error: Property 'age' is missing in type '{ name: string; }' but required in type 'Sth'
const sth: Sth = {
  name: 'Aatrox',
};

// Error: Type 'string' is not assignable to type 'number'
const sthBoth: Sth = {
  name: 'Aatrox',
  age: '10',
};
```

</br>

## 4.2.2 μ΄κ³Ό μμ± κ²μ¬

μ΄κΈ°μ μ ν νμλ³΄λ€ λ λ§μ μμ±μ μ¬μ©νλ €νλ©΄ νμ μ€λ₯κ° λ°μ

κ°μ²΄ λ¦¬ν°λ΄μ΄ μλ κ²½μ°μλ κ΅¬μ‘°μ  νμ΄νμ μν΄μ μ€λ₯κ° λ°μνμ§ μμ

```ts
type Sth = {
  name: string;
  age: number;
};

// (3)
const Sth1: Sth = {
  name: 'leekoby',
  age: 33,
  activity: 'working',
  // β Error : Type '{ name: string; age: number; activity: string; }' is not assignable to type 'Sth'.
  // Object literal may only specify known properties, and 'activity' does not exist in type 'Sth'.
};

// (4)
const Sth = {
  name: 'kobykoby',
  age: 22,
  activity: 'working',
};
// (4)
const Sth2: Sth = Sth;

// β Error : Property 'activity' does not exist on type 'Sth'.
Sth2.activity;
```

</br>

## 4.2.3 μ€μ²©λ κ°μ²΄ νμ

`Javascript` κ°μ²΄λ λ€λ₯Έ κ°μ²΄μ λ©€λ²λ‘ μ€μ²©λ  μ μμΌλ―λ‘ νμμ€ν¬λ¦½νΈμ κ°μ²΄ νμλ νμ μμ€νμμ μ€μ²©λ κ°μ²΄ νμμ λνλΌ μ μμ΄μΌνλ€

- μ€μ²© κ°μ²΄μ μμ±μ ννλ₯Ό μμ²΄ λ³μΉ­ κ°μ²΄ νμμΌλ‘ μΆμΆνλ©΄ μ€λ₯ λ©μμ§μ λ λ§μ μ λ³΄λ₯Ό λ΄μ μ μλ€

```ts
type Someone = {
  author: {
    firstName: string;
    lastName: string;
  };
  name: string;
};

const someoneMatch: Someone = {
  author: {
    firstName: 'koby',
    lastName: 'lee',
  },
  name: 'Typescript',
};

const someoneMismatch: Someone = {
  author: {
    name: 'React',
    /**
  β Error: Type '{ name: string; }' is not assignable 
  to type '{ firstName: string; lastName: string; }'.
  Object literal may only specify known properties, and 'name' 
  does not exist in type '{ firstName: string; lastName: string; }'.
 */
  },
  name: 'JavaScript',
};
```

κ°μ²΄μ μμ±μΌλ‘ νμμ μ¬μ©ν  μ μκΈ° λλ¬Έμ μμ²λΌ μ¬μ©νλ κ²λ³΄λ€λ μλμ κ°μ΄ μ¬μ©νλ κ²μ΄ κ°λμ±μ΄ λ μ’κ³ , μ€λ₯ λ©μΈμ§λ λ³΄λ€ λͺνν΄μ§λ€.

```ts
type Someone = {
  firstName: string;
  lastName: string;
};
type doSomethong = {
  who: Someone;
  activity: string;
};
const someoneMismatch: doSomethong = {
  who: {
    name: 'leekoby',
    /**
          β Error : Type '{ name: string; }' is not assignable to type 'Someone'.
          Object literal may only specify known properties, 
          and 'name' does not exist in type 'Someone'.
          */
  },
  activity: 'run',
};
```

</br>

## 4.2.4 μ νμ  μμ±

`?:`μ μ΄μ©ν΄μ μ νμ  μμ±μ λΆμ¬ν  μ μλ€.
μ νμ  μμ± `?:` λμ  undefinedλ₯Ό μ¬μ©ν  μ μμ
κ·Έλ¬λ `undefined`λ₯Ό μ λμΈμΌλ‘ μ μΈνλ€λ©΄ μμ± κ°μ λ°λμ μ μΈνλ€.

```ts
type Someone = {
  name: string;
  age?: number;
  work: boolean | undefined;
};
const person1: Someone = {
  name: 'Aatrox',
  age: 26,
  work: false,
};
// β Property 'work' is missing in type '{ name: string; age: number; }' but required in type 'Someone'.
const person2: Someone = {
  name: 'Aatrox',
  age: 26,
};
const person3: Someone = {
  name: 'Aatrox',
  work: false,
};
// `?:` λμ  undefined
const person4: Someone = {
  name: 'Aatrox',
  age: 26,
  work: undefined,
};
```

</br>

# π 4.3 κ°μ²΄ νμ μ λμΈ

- TS μ½λμμλ μμ±μ΄ μ‘°κΈ λ€λ₯Έ, νλ μ΄μμ μλ‘ λ€λ₯Έ κ°μ²΄ νμμ΄ λ  μ μλ νμμ μ€λͺν  μ μμ΄μΌ νλ€.

- μμ±κ°μ κΈ°λ°μΌλ‘ ν΄λΉ κ°μ²΄ νμ κ°μ νμμ μ’νμΌ ν  μ λ μλ€.

</br>

## 4.3.1 μ μΆλ κ°μ²΄ νμ μ λμΈ

- λ³μμ μ¬λ¬ κ°μ²΄ νμ μ€ νλκ° λ  μ μλ μ΄κΉκ°μ΄ μ£Όμ΄μ§λ©΄ TSλ ν΄λΉ νμμ κ°μ²΄ νμ μ λμΈμΌλ‘ μ μΆνλ€.

- μ λμΈ νμμ κ°λ₯ν κ° κ°μ²΄ νμμ κ΅¬μ±νκ³  μλ μμλ₯Ό λͺ¨λ κ°μ§ μ μλ€.
- κ°μ²΄ νμμ μ μλ κ°κ°μ κ°λ₯ν μμ±μ λΉλ‘ μ΄κΉκ°μ΄ μλ μ νμ  νμμ΄μ§λ§ κ° κ°μ²΄ νμμ κ΅¬μ± μμλ‘ μ£Όμ΄μ§λ€.

```ts
const poem =
  Math.random() > 0.5 ? { name: 'leekoby', pages: 9 } : { name: 'kimcube', rhymes: true };
/*
type:
{
    name : string;
    pages : number;
    rhymes?: undefined;  
}
|
{
    name : string;
    pages ?: undefined;
    rhymes : boolean;  
}
 */
poem.name; //string
poem.pages; // number | undefined
poem.rhymes; // booleans | undefindes
```

λ€μ `poem` κ°μ ν­μ `string` νμμΈ `name`μ΄κ³ , `pages`μ `rhymes`λ μμ μλ μκ³  μμ μλ μλ€.

</br>

## 4.3.2 λͺμλ κ°μ²΄ νμ μ λμΈ & 4.3.3 κ°μ²΄ νμ λ΄λ‘μ

- κ°μ²΄ νμμ μ‘°ν©μ λͺμνλ©΄ κ°μ²΄ νμμ λ λͺνν μ μν  μ μλ€.
- κ°μ΄ νμμ΄ κ°μ²΄ νμμΈ μ λμΈμ΄λΌλ©΄ μΌλ°μ μΌλ‘λ λͺ¨λ  μ λμΈμ μ‘΄μ¬νλ κ°λ§ μ¬μ©ν  μ μλ€.
- νμ λ΄λ‘μμ ν΅ν΄μ νμμ μ’νμ μ’ λ μ ννκ² νμμ μΆλ‘ νκ³  μ μ΄ν  μ μλ€.

```ts
type Someone = {
  name: string;
  age: number;
};
type Stranger = {
  name: string;
  marriage: boolean;
};
let person: Someone | Stranger;
person = Math.random() > 0.5 ? { name: "leekoby", age: 33 } : { name: "kimcuby", marriage: true };
person.name;
person.age;
// β Error: Property 'age' does not exist on type 'Someone | Stranger'.
//           Property 'age' does not exist on type 'Stranger'.

person.marriage;
// β Error: Property 'marriage' does not exist on type 'Someone | Stranger'.
//           Property 'marriage' does not exist on type 'Someone'.
if ("age" in person) {
  person.age;
} else {
  person.marriage;
```

- μ μ¬μ μΌλ‘ μ‘΄μ¬νμ§ μλ κ°μ²΄μ λ©€λ²μ λν μ κ·Όμ μ ννλ©΄ μ½λμ μμ μ μ§ν¬ μ μλ€.
- κ°μ΄ μ¬λ¬ νμ μ€ νλμΌ κ²½μ°, λͺ¨λ  νμμ μ‘΄μ¬νμ§ μλ μμ±μ΄ κ°μ²΄μ μ‘΄μ¬ν  κ±°λΌ λ³΄μ₯ X
- λͺ¨λ  νμμ μ‘΄μ¬νμ§ μμ μμ±μ μ κ·ΌνκΈ° μν΄ νμμ μ’νμΌ νλ κ²μ²λΌ κ°μ²΄ νμ μ λμΈλ νμμ μ’νμΌνλ€.

- νμ κ²μ¬κΈ°κ° μ λμΈ νμ κ°μ νΉμ  μμ±μ΄ ν¬ν¨λ κ²½μ°μλ§ μ½λ μμ­μ μ€νν  μ μμμ μκ² λλ©΄, κ°μ νμμ ν΄λΉ μμ±μ ν¬ν¨νλ κ΅¬μ± μμλ‘λ§ μ’νλ€.

- μ½λμμ κ°μ²΄μ ννλ₯Ό νμΈνκ³  νμ λ΄λ‘μμ΄ μ μ©λλ€.

> Typescriptλ `if(poem.pages)`μ κ°μ νμμΌλ‘ μ°Έ μ¬λΆ νμΈμ νμ©νμ§ μλλ€.

- μ‘΄μ¬νμ§ μλ κ°μ²΄μ μμ±μ μ κ·Όνλ €κ³  μλνλ©΄ νμ κ°λμ²λΌ μλνλ λ°©μμΌλ‘ μ¬μ©λλλΌλ νμ μ€λ₯λ‘ κ°μ£Ό

```js
if (poem.pages) {
}
// β Error : Property 'pages' does not exist on type 'Someone | Stranger'.
//            Property 'pages' does not exist on type 'Someone'.
```

</br>

</br>

## 4.3.4 νλ³λ μ λμΈ

- `Javascript`μ `Typescript`μμ μ λμΈ νμμΌλ‘ λ κ°μ²΄μ λ λ€λ₯Έ μΈκΈ° μλ ννλ κ°μ²΄μ μμ±μ΄ κ°μ²΄μ ννλ₯Ό λνλ΄λλ‘ νλ κ², μ΄λ¬ν ννλ₯Ό `νλ³λ μ λμΈ` μ΄λΌκ³  νλ€.
- κ°μ²΄μ νμμ κ°λ¦¬ν€λ μμ±μ΄ νλ³ κ°
- `Typescript`λ μ½λμμ νλ³ μμ±μ μ¬μ©ν΄ νμ λ΄λ‘μ μν

- νλ³λ μ λμ¨μ μ΄μ©ν΄μ νμ λ΄λ‘μμ νλ κ²μ΄ μ’λ€.

- νλ³λ μ λμ¨μ΄λ κ° κ°μ²΄λ§λ€ κ°μμ νκ·Έλ₯Ό λΆμ¬μ ν΄λΉ νκ·Έλ‘ νμμ κ΅¬λΆν  μ μλλ‘ νλ³νλ κ²μ μλ―Έ

```ts
type PoemPage = {
  name: string;
  pages: number;
  type: 'pages';
};

type PoemRhymes = {
  name: string;
  rhymes: boolean;
  type: 'rhymes';
};
type Poem = PoemPage | PoemRhymes;
const poem: Poem =
  Math.random() > 0.5
    ? { name: 'leekoby', pages: 9, type: 'pages' }
    : { name: 'kimcube', rhymes: true, type: 'rhymes' };

if (poem.type === 'pages') {
  console.log(`${poem.pages}`);
} else {
  console.log(`${poem.rhymes}`);
}

poem.type; // type : "pages" | "rhymes"
poem.pages;
// β Error : Property 'pages' does not exist on type 'Poem'.
//         Property 'pages' does not exist on type 'PoemRhymes'.
```

</br>

# π 4.4 κ΅μ°¨ νμ

μΈν°μΉμ(`&`)μ μ΄μ©νμ¬ κ° νμμ μ μΈλ λͺ¨λ  μμ±μ΄ ν©μ§ν©μΈ νμμ΄ λλ€

```ts
type Stranger1 = {
  name: string;
  age: number;
};
type Stranger2 = {
  name: string;
  marriage: boolean;
};

declare const person: Stranger1 & Stranger2;

/*
person ={
    name: string,
    age: number,
    marriage: boolean,
}
*/

person.name;
person.age;
person.marriage;
```

</br>

κ΅μ°¨ νμκ³Ό νλ³λ μ λμ¨μ κ°μ΄ μ¬μ©ν μμ

```ts
type Stranger1 = {
  age: number;
  type: 'stranger1';
};
type Stranger2 = {
  marriage: boolean;
  type: 'stranger2';
};

declare const person: { name: string } & (Stranger1 | Stranger2);

// "name: string"μ κ°μ§λ©΄μ "Stranger1"μΈ κ²½μ°
if (person.type === 'stranger1') {
  person.age;
  person.name;
}
// "name: string"μ κ°μ§λ©΄μ "Stranger2"μΈ κ²½μ°
else {
  person.name;
  person.marriage;
}
```

</br>

## 4.4.1 κ΅μ°¨ νμμ μνμ±

κ΅μ°¨ νμμ μ μ©ν κ°λμ΄μ§λ§, νΌλμ κ°μ Έμ€κΈ° μ½κΈ° λλ¬Έμ κ°λ₯ν μ½λλ₯Ό κ°κ²°νκ² μ μ§ν΄μΌνλ€.

> ### π¨ κ΅μ°¨ νμμ μλͺ» μ¬μ©νλ©΄ λΆκ°λ₯ν νμμΈ `never`κ° μμ±λ  μνμ΄ μλ€.

- κ΅μ°¨ νμμ μλͺ» μ¬μ©νκΈ° μ½κ³  μ¬μ© λΆκ°λ₯ν νμμ μμ±νλ€.
- μμ κ°μ λμμ μ¬λ¬ νμμ΄ λ  μ μκΈ°μ κ΅μ°¨ νμμ κ΅¬μ± μμλ‘ ν¨κ» κ²°ν©ν  μ μλ€.
- λ κ°μ μμ νμμ ν¨κ» μλνλ©΄ `never` ν€μλλ‘ νμλλ `never` νμμ΄ λλ€.
- `never`λ νλ‘κ·Έλλ° μΈμ΄μμ `bottom` νμ λλ `empty` νμμ λ» νλ€.
- `bottom` νμμ κ°μ κ°μ§ μ μκ³  μ°Έμ‘°ν  μ μλ νμ

```ts
// type SthType = never
type SthType = number & string;
```

λλΆλΆμ `Typescript` νλ‘μ νΈμμλ `never` νμμ κ±°μ μ¬μ©νμ§ μμ§λ§ λΆκ°λ₯ν μνλ₯Ό λνλ΄κΈ° μν΄ κ°λ μ¬μ©νλ€.
</br>

# π λ νΌλ°μ€

> Goldberg, et al. λ¬λ νμμ€ν¬λ¦½νΈ / μ‘°μ κ³¨λλ²κ·Έ μ§μ ; κ³ μΉμ μ?κΉ, 2023.

> <a href="https://typescript-kr.github.io/pages/unions-and-intersections.html" target="_blank"> Typescript νΈλλΆ </a>
