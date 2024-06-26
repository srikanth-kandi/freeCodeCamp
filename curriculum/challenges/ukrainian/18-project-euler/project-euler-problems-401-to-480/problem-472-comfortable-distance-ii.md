---
id: 5900f5451000cf542c510057
title: 'Завдання 472: комфортна відстань II'
challengeType: 1
forumTopicId: 302149
dashedName: problem-472-comfortable-distance-ii
---

# --description--

Ряд складається з $N$ місць. Приходить $N$ людей та вони починають займати місця згідно з такими правилами:

1. Жодна людина не сидить поруч з іншою.
1. Перша людина обирає будь-яке місце.
1. Кожна наступна людина вибирає місце, найбільш віддалене від того, хто вже сидить, до тих пір, поки не порушує правило №1. Якщо існує більше одного варіанту, що задовільняє цю умову, то людина обирає місце зліва.

Зверніть увагу, що через правило №1, деякі місця, безумовно, будуть вільними, і максимальна кількість осіб, які можуть бути розміщені, менша за $N$ (за умови $N > 1$).

Ось можливі розсадження за умови $N = 15$:

<img alt="розсадження за умови N = 15" src="https://cdn.freecodecamp.org/curriculum/project-euler/comfortable-distance-ii.png" style="background-color: white; padding: 10px; display: block; margin-right: auto; margin-left: auto; margin-bottom: 1.2rem;" />

Як бачимо, якщо перша людина обирає правильне місце, то на 15 місцях можуть сісти не більше 7 людей. Ми також можемо бачити, що перша людина має 9 варіантів, щоб максимізувати кількість осіб, яких можна розмістити.

Нехай $f(N)$ буде кількістю можливих місць першої людини, щоб максимізувати кількість сидячих людей в ряді з $N$ місць. Таким чином, $f(1) = 1$, $f(15) = 9$, $f(20) = 6$ та $f(500) = 16$.

Також $\sum f(N) = 83$ за умови $1 ≤ N ≤ 20$ та $\sum f(N) = 13\\,343$ за умови $1 ≤ N ≤ 500$.

Знайдіть $\sum f(N)$ за умови $1 ≤ N ≤ {10}^{12}$. У відповіді запишіть 8 останніх цифр.

# --hints--

`comfortableDistanceTwo()` має повернути `73811586`.

```js
assert.strictEqual(comfortableDistanceTwo(), 73811586);
```

# --seed--

## --seed-contents--

```js
function comfortableDistanceTwo() {

  return true;
}

comfortableDistanceTwo();
```

# --solutions--

```js
// solution required
```
