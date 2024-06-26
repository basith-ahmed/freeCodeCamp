---
id: 5900f3f61000cf542c50ff09
title: 'Problema 138: Triángulos de isóceles especiales'
challengeType: 1
forumTopicId: 301766
dashedName: problem-138-special-isosceles-triangles
---

# --description--

Consider the isosceles triangle with base length, $b = 16$, and legs, $L = 17$.

<img alt="triángulo isóceles con bordes llamados L - dos bordes con la misma longitud y base del triángulo como b; y altura del triángulo - h desde la base del triángulo hasta el ángulo entre los bordes L" src="https://cdn.freecodecamp.org/curriculum/project-euler/special-isosceles-triangles.png" style="background-color: white; padding: 10px; display: block; margin-right: auto; margin-left: auto; margin-bottom: 1.2rem;" />

Usando el teorema Pitágórico, se puede ver que la altura del triángulo, $h = \sqrt{{17}^2  8^2} = 15$, que es una longitud menor que la de la base.

Con $b = 272$ y $L = 305$, obtenemos $h = 273$, que es uno más que la longitud base, y este es el segundo triángulo isóceles más pequeño con la propiedad $h = b ± 1$.

Encuentra $\sum{L}$ para los doce triángulos de isócelas más pequeños para los cuales $h = b ± 1$ y $b$, $L$ son enteros positivos.

# --hints--

`isoscelesTriangles()` debe devolver `1118049290473932`.

```js
assert.strictEqual(isoscelesTriangles(), 1118049290473932);
```

# --seed--

## --seed-contents--

```js
function isoscelesTriangles() {

  return true;
}

isoscelesTriangles();
```

# --solutions--

```js
// solution required
```
