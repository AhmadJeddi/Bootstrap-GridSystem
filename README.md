# Bootstrap-GridSystem – FloatGrid: A Lightweight Float-based Grid

**FloatGrid** is a lightweight, responsive 12-column grid system inspired by [Bootstrap](https://getbootstrap.com), but built entirely with `float`, `inline-padding`, and `media queries`. Perfect for projects where Flexbox or CSS Grid is not required — and great for RTL layouts!

---

## 📦 Features

- ✅ 12-column layout with responsive breakpoints  
- ✅ Offset support for spacing between columns  
- ✅ Pure CSS (Sass-powered) – no JavaScript  
- ✅ RTL-compatible using `margin-inline-start`  
- ✅ No dependencies – easy to integrate

---

## 🧰 Utility Classes

- `.container`: Fixed-width container with padding and centered layout  
- `.container-fluid`: Full-width container spanning the viewport  
- `.img-responsive`: Makes images scale fluidly within their parent

---

## 🎯 Breakpoints

| Class Prefix   | Min-width | Container Max-width |
|----------------|-----------|----------------------|
| `.col-xs-*`    | 1px       | 100% (fluid)         |
| `.col-sm-*`    | 576px     | 540px                |
| `.col-md-*`    | 768px     | 720px                |
| `.col-lg-*`    | 992px     | 960px                |
| `.col-xl-*`    | 1200px    | 1140px               |
| `.col-xxl-*`   | 1400px    | 1320px               |

---

## 🛠 Usage

1. Clone or download the repository  
2. Import `grid-system.scss` into your project  
3. Compile it using your Sass compiler  
4. Use the classes like `.col-sm-6`, `.col-lg-offset-3`, etc.

```html
<div class="container">
  <div class="row">
    <div class="col-sm-4">Left</div>
    <div class="col-sm-4 col-sm-offset-4">Right</div>
  </div>
</div>
