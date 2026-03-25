# 第六单元 — CSS 盒模型练习  |  任务 3 (3/18)
CSS 练习：使用盒模型编写控制间距、边框和大小的规则。

---

> 💡 先从 `styles.css` 开始 — 然后在 `index.html` 中应用你的规则

---

## 📌 开始之前 — 什么是盒模型？

网页上的每个元素都是一个盒子。盒模型控制每个元素**内部**、**外部**的空间以及元素的**大小**。

```
┌──────────────────────────┐
│         margin           │  ← 盒子外部的空间
│   ┌──────────────────┐   │
│   │     border       │   │  ← 盒子的边框
│   │  ┌────────────┐  │   │
│   │  │  padding   │  │   │  ← 盒子内部的空间
│   │  │ ┌────────┐ │  │   │
│   │  │ │content │ │  │   │  ← 实际内容
│   │  │ └────────┘ │  │   │
│   │  └────────────┘  │   │
│   └──────────────────┘   │
└──────────────────────────┘
```

| 属性 | 控制什么 |
|---|---|
| `padding` | 元素**内部**的空间 |
| `margin` | 元素**外部**的空间 |
| `border` | 元素**周围**的边框 |
| `width` | 元素有多**宽** |
| `height` | 元素有多**高** |

---

## 📌 提醒 — 应用多个 Class

你可以在同一个元素上应用多个 class：

```html
<p class="padded spaced has-border">
  这个段落有三个 class！
</p>
```

> 💡 你可以自由地将任何规则应用到 `<body>` 里的任何元素上。尝试一下，看看间距和大小如何变化！

---

## 第一级 — 完全引导  *(任务 1 – 5)*

我们给你规则名称、属性和值。
你的任务是用正确的语法写出规则。

```
Class 规则使用点号    →   .name { }
ID 规则使用井号      →   #name { }
```

---

**任务 1** — 编写一个名为 `padded` 的 CLASS 规则
- 属性：`padding`
- 值：`20px`
- 作用：在元素四个方向的内部各添加 20px 的空间

📖 [padding — W3Schools](https://www.w3schools.com/cssref/pr_padding.php)

---

**任务 2** — 编写一个名为 `spaced` 的 CLASS 规则
- 属性：`margin`
- 值：`20px`
- 作用：在元素外部添加 20px 的空间，将其他元素推开

📖 [margin — W3Schools](https://www.w3schools.com/cssref/pr_margin.php)

---

**任务 3** — 编写一个名为 `has-border` 的 CLASS 规则
- 属性：`border`
- 值：`3px solid black`
- 作用：在元素周围添加 3px 宽的黑色实线边框

📖 [border — W3Schools](https://www.w3schools.com/cssref/pr_border.php)

---

**任务 4** — 编写一个名为 `fixed-width` 的 CLASS 规则
- 属性：`width`
- 值：`300px`
- 作用：将元素的宽度固定为 300px

📖 [width — W3Schools](https://www.w3schools.com/cssref/pr_dim_width.php)

---

**任务 5** — 编写一个名为 `hero-box` 的 ID 规则
- 属性 1：`height` → 值：`200px`
- 属性 2：`padding` → 值：`40px`
- 属性 3：`border` → 值：`5px solid navy`
- 作用：创建一个高大的盒子，内部有较大的间距，并带有深蓝色边框

📖 [height — W3Schools](https://www.w3schools.com/cssref/pr_dim_height.php)
📖 [padding — W3Schools](https://www.w3schools.com/cssref/pr_padding.php)
📖 [border — W3Schools](https://www.w3schools.com/cssref/pr_border.php)

---

## 第二级 — 半引导  *(任务 6 – 10)*

**任务 6、7、8** — 我们给你名称和描述。你来决定属性和值。

**任务 9、10** — 我们只给你描述。你来决定名称、属性和值。

每条规则必须使用至少 **2 个盒模型属性** — `margin`、`padding`、`border`、`width` 或 `height`。

---

**任务 6** — 编写一个名为 `img-box` 的 CLASS 规则

为图片添加清晰的边框，并在图片周围添加空间，使其不会与其他元素挤在一起。

📖 [border — W3Schools](https://www.w3schools.com/cssref/pr_border.php)
📖 [margin — W3Schools](https://www.w3schools.com/cssref/pr_margin.php)

---

**任务 7** — 编写一个名为 `content-block` 的 CLASS 规则

创建一个有固定宽度的块，使其不会延伸到整个页面的宽度，并在内部添加足够的间距使文字易于阅读。

📖 [width — W3Schools](https://www.w3schools.com/cssref/pr_dim_width.php)
📖 [padding — W3Schools](https://www.w3schools.com/cssref/pr_padding.php)

---

**任务 8** — 编写一个名为 `section-gap` 的 CLASS 规则

让各个元素之间保持距离，使页面的每个部分都有足够的空间。使用 margin 在上下方向创建空间。

📖 [margin — W3Schools](https://www.w3schools.com/cssref/pr_margin.php)

---

**任务 9** — 你来决定这个 CLASS 规则的名称

让一个元素看起来像一个有边框的盒子。它应该有可见的边框，内部有 padding 使内容不会紧贴边框，并且有固定的高度。

📖 [border — W3Schools](https://www.w3schools.com/cssref/pr_border.php)
📖 [padding — W3Schools](https://www.w3schools.com/cssref/pr_padding.php)
📖 [height — W3Schools](https://www.w3schools.com/cssref/pr_dim_height.php)

---

**任务 10** — 你来决定这个 ID 规则的名称

为页面上一个特别的部分设置样式。它应该有固定的宽度，四个方向都有 padding，并且有 margin 将其与周围的元素分开。

📖 [width — W3Schools](https://www.w3schools.com/cssref/pr_dim_width.php)
📖 [padding — W3Schools](https://www.w3schools.com/cssref/pr_padding.php)
📖 [margin — W3Schools](https://www.w3schools.com/cssref/pr_margin.php)

---

## 第三级 — 开放式  *(任务 11 – 13)*

你来决定一切 — 名称、属性和值。

- 至少编写 **2 条 class 规则**
- 至少编写 **1 条 ID 规则**
- 每条规则只能使用盒模型属性：`margin`、`padding`、`border`、`width` 或 `height`
- 每条规则必须有至少 **2 个属性**
- 在 `task3-index.html` 中应用所有规则

祝你好运！🎯

---

## 附加挑战

如果你提前完成，可以试试这些！

- [ ] **附加 1** — 将 `padded`、`spaced` 和 `has-border` 同时应用到一个元素上，看看效果如何
- [ ] **附加 2** — 只用 `img-box` class 为所有五张图片设置样式
- [ ] **附加 3** — 在一个有固定宽度的元素上使用 `margin: auto`，看看会发生什么
- [ ] **附加 4** — 在一条规则中使用 `padding-top`、`padding-bottom`、`padding-left` 或 `padding-right` 来代替 `padding`
- [ ] **附加 5** — 总共编写超过 13 条 CSS 规则

---

## 参考资料

需要帮助记住某个属性的用法？使用这个参考资料：

👉 [完整 CSS 属性列表 — W3Schools](https://www.w3schools.com/cssref/css3_pr_all.php)