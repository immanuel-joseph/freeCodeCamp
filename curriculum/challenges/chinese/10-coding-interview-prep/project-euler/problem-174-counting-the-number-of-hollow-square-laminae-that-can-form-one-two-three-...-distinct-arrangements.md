---
id: 5900f41a1000cf542c50ff2d
title: 问题174：计算可以形成一个，两个，三个......不同排列的“空心”方形薄片的数量
challengeType: 5
videoUrl: ''
dashedName: >-
  problem-174-counting-the-number-of-hollow-square-laminae-that-can-form-one-two-three-----distinct-arrangements
---

# --description--

我们将方形薄片定义为具有方形“孔”的方形轮廓，使得该形状具有垂直和水平对称性。给定八个瓷砖，可以仅以一种方式形成薄层：3x3正方形，中间有1x1个孔。但是，使用32个瓷砖可以形成两个不同的薄片。

如果t表示使用的瓦片数，我们将说t = 8是类型L（1）并且t = 32是类型L（2）。令N（n）为t≤1000000的数，使得t为L（n）型;例如，N（15）= 832.对于1≤n≤10，ΣN（n）是多少？

# --hints--

`euler174()`应该返回209566。

```js
assert.strictEqual(euler174(), 209566);
```

# --seed--

## --seed-contents--

```js
function euler174() {

  return true;
}

euler174();
```

# --solutions--

```js
// solution required
```
