---
id: 5900f5431000cf542c510055
title: 'Завдання 470: супер рамвок'
challengeType: 1
forumTopicId: 302146
dashedName: problem-470-super-ramvok
---

# --description--

Розглянемо звичайну гру в рамвок:

Нехай $t$ означає максимальну кількість ходів за цілу гру. Якщо $t = 0$, гра одразу закінчується. В іншому випадку, гравець викидає кубик за кожен хід $i$. Після цього, якщо $i &lt; t$, то гравець може або зупинити гру та отримати виграш, рівний отриманому числу, або скасувати свій хід та спробувати ще раз. Якщо $i = t$, то хід не можна скасувати і потрібно прийняти свій виграш. Гравець обирає $t$ перед початком гри та має оплатити аванс в розмірі $ct$ для сталого значення $c$. Якщо $c = 0$, то $t$ може бути нескінченним (аванс дорівнює 0). Нехай $R(d, c)$ буде очікуваним прибутком (тобто чистим виграшем), який гравець отримає за одну оптимально зіграну гру «Рамвок», використовуючи чесний $d$-бічний кубик та сталу ціну $c$. Наприклад, $R(4, 0.2) = 2.65$. Припустимо, що гравець має достатньо коштів для оплати будь-якого авансу.

Тепер розглянемо гру в супер рамвок:

В грі «Супер рамвок», рамвок грається декілька разів, але з невеликим доповненням. Після кожної гри гральний кубик змінюється. Зміна здійснюється таким чином: гральний кубик викидається один раз, і якщо на отриманій грані можна побачити значення, це значення потрібно стерти. Якщо грань вже порожня, то потрібно повернути початкове значення. Після зміни починається інша гра в рамвок, під час якої гральний кубик викидається, поки не з’явиться грань зі значенням. Гравець завжди знає, які грані порожні та повні. Гра закінчується, коли всі грані кубика будуть порожніми.

Нехай $S(d, c)$ буде очікуваним прибутком, який гравець отримає за одну оптимально зіграну гру «Рамвок», використовуючи чесний $d$-бічний кубик (з видимими значеннями) та сталою ціною $c$. Наприклад, $S(6, 1) = 208.3$.

Нехай $F(n) = \sum_{4 ≤ d ≤ n} \sum_{0 ≤ c ≤ n} S(d, c)$.

Знайдіть $F(20)$, заокруглене до найближчого цілого числа.

# --hints--

`superRamvok()` має повернути `147668794`.

```js
assert.strictEqual(superRamvok(), 147668794);
```

# --seed--

## --seed-contents--

```js
function superRamvok() {

  return true;
}

superRamvok();
```

# --solutions--

```js
// solution required
```
