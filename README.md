# Unit 6 — CSS Box Model Practice  |  Task 3 (3/18)
CSS practice: Writing rules that control spacing, borders, and size using the box model.

---

> 💡 Start in `styles.css` — then apply your rules in `index.html`

---

## 📌 Before You Start — The Box Model

Every element on a web page is a box. The box model controls the space **inside**, **around**, and the **size** of every element.

```
┌──────────────────────────┐
│         margin           │  ← space OUTSIDE the box
│   ┌──────────────────┐   │
│   │     border       │   │  ← the box wall
│   │  ┌────────────┐  │   │
│   │  │  padding   │  │   │  ← space INSIDE the box
│   │  │ ┌────────┐ │  │   │
│   │  │ │content │ │  │   │  ← the actual content
│   │  │ └────────┘ │  │   │
│   │  └────────────┘  │   │
│   └──────────────────┘   │
└──────────────────────────┘
```

| Property | What it controls |
|---|---|
| `padding` | Space **inside** the element |
| `margin` | Space **outside** the element |
| `border` | The wall **around** the element |
| `width` | How **wide** the element is |
| `height` | How **tall** the element is |

---

## 📌 Reminder — Applying Multiple Classes

You can apply more than one class to the same element:

```html
<p class="padded spaced has-border">
  This paragraph has three box model classes on it!
</p>
```

> 💡 You are free to apply any of your rules to any element inside the `<body>`. Experiment and see how the spacing and size changes!

---

## Level 1 — Fully Guided  *(Tasks 1 – 5)*

We give you the rule name, the property, and the value.
Your job is to write the rule using the correct syntax.

```
Class rules use a dot      →   .name { }
ID rules use a hashtag     →   #name { }
```

---

**Task 1** — Write a CLASS rule called `padded`
- Property: `padding`
- Value: `20px`
- What it does: adds 20px of space inside the element on all four sides

📖 [padding — W3Schools](https://www.w3schools.com/cssref/pr_padding.php)

---

**Task 2** — Write a CLASS rule called `spaced`
- Property: `margin`
- Value: `20px`
- What it does: adds 20px of space outside the element, pushing other elements away from it

📖 [margin — W3Schools](https://www.w3schools.com/cssref/pr_margin.php)

---

**Task 3** — Write a CLASS rule called `has-border`
- Property: `border`
- Value: `3px solid black`
- What it does: adds a solid black border 3px thick around the element

📖 [border — W3Schools](https://www.w3schools.com/cssref/pr_border.php)

---

**Task 4** — Write a CLASS rule called `fixed-width`
- Property: `width`
- Value: `300px`
- What it does: sets the element to a fixed width of 300px

📖 [width — W3Schools](https://www.w3schools.com/cssref/pr_dim_width.php)

---

**Task 5** — Write an ID rule called `hero-box`
- Property 1: `height` → Value: `200px`
- Property 2: `padding` → Value: `40px`
- Property 3: `border` → Value: `5px solid navy`
- What it does: creates a tall box with thick padding and a navy border

📖 [height — W3Schools](https://www.w3schools.com/cssref/pr_dim_height.php)
📖 [padding — W3Schools](https://www.w3schools.com/cssref/pr_padding.php)
📖 [border — W3Schools](https://www.w3schools.com/cssref/pr_border.php)

---

## Level 2 — Semi Guided  *(Tasks 6 – 10)*

**Tasks 6, 7, 8** — We give you the name and a description. You decide the properties and values.

**Tasks 9, 10** — We give you only a description. You decide the name AND the properties and values.

Every rule must use at least **2 box model properties** — `margin`, `padding`, `border`, `width`, or `height`.

---

**Task 6** — Write a CLASS rule called `img-box`

Style an image so it has a clear border and space around it so it does not feel crowded by other elements.

📖 [border — W3Schools](https://www.w3schools.com/cssref/pr_border.php)
📖 [margin — W3Schools](https://www.w3schools.com/cssref/pr_margin.php)

---

**Task 7** — Write a CLASS rule called `content-block`

Create a block that has a set width so it does not stretch all the way across the page, and enough padding inside so the text is easy to read.

📖 [width — W3Schools](https://www.w3schools.com/cssref/pr_dim_width.php)
📖 [padding — W3Schools](https://www.w3schools.com/cssref/pr_padding.php)

---

**Task 8** — Write a CLASS rule called `section-gap`

Push elements away from each other so that each section of the page has breathing room. Use margin to create space above and below.

📖 [margin — W3Schools](https://www.w3schools.com/cssref/pr_margin.php)

---

**Task 9** — You decide the name for this CLASS rule

Make an element look like a framed box. It should have a visible border, padding inside so the content does not touch the border, and a set height.

📖 [border — W3Schools](https://www.w3schools.com/cssref/pr_border.php)
📖 [padding — W3Schools](https://www.w3schools.com/cssref/pr_padding.php)
📖 [height — W3Schools](https://www.w3schools.com/cssref/pr_dim_height.php)

---

**Task 10** — You decide the name for this ID rule

Style a single standout section on the page. It should have a fixed width, padding on all sides, and a margin to separate it from everything around it.

📖 [width — W3Schools](https://www.w3schools.com/cssref/pr_dim_width.php)
📖 [padding — W3Schools](https://www.w3schools.com/cssref/pr_padding.php)
📖 [margin — W3Schools](https://www.w3schools.com/cssref/pr_margin.php)

---

## Level 3 — Open Ended  *(Tasks 11 – 13)*

You decide everything — the name, the properties, and the values.

- Write at least **2 class rules**
- Write at least **1 ID rule**
- Every rule must only use box model properties: `margin`, `padding`, `border`, `width`, or `height`
- Each rule must have at least **2 properties**
- Apply all of them somewhere in your `task3-index.html`

Good luck! 🎯

---

## Bonus Challenges

Try these if you finish early!

- [ ] **Bonus 1** — Apply `padded`, `spaced`, and `has-border` all to the same element and see what it looks like
- [ ] **Bonus 2** — Style all five images using only the `img-box` class
- [ ] **Bonus 3** — Use `margin: auto` on an element with a fixed width and see what happens
- [ ] **Bonus 4** — Use `padding-top`, `padding-bottom`, `padding-left`, or `padding-right` instead of just `padding` on one rule
- [ ] **Bonus 5** — Write more than 13 CSS rules total

---

## Reference

Need help remembering how a property works? Use this reference:

👉 [Full CSS Property List — W3Schools](https://www.w3schools.com/cssref/css3_pr_all.php)