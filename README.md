# FloatGrid – A Simple Bootstrap-like Float-based Grid System

**FloatGrid** is a lightweight, responsive 12-column grid system inspired by [Bootstrap](https://getbootstrap.com), but built entirely with `float`, `inline-padding`, and `media queries`. It’s perfect for projects where Flexbox or CSS Grid is not preferred or needed. Ideal for RTL layouts as well!

---

## 📦 Features

- ✅ 12-column layout with responsive breakpoints
- ✅ `offset` support for spacing columns
- ✅ Pure CSS (Sass-powered) – no JavaScript
- ✅ RTL-compatible using `margin-inline-start`
- ✅ No dependencies – use in any project

---

## 🧰 Utility Classes

<ul>
  <li>`.container`: max width with appropriate margin and padding</li>
  <li>`.container-fluid`: full width container</li>
  <li>`.img-responsive`: responsive images adapting to parent width</li>
</ul>

---

## 🎯 Breakpoints

| Class prefix | Min-width  | Container max-width |
|--------------|------------|----------------------|
| `.col-xs-*`  | 1px        | 100% (fluid)         |
| `.col-sm-*`  | 576px      | 540px                |
| `.col-md-*`  | 768px      | 720px                |
| `.col-lg-*`  | 992px      | 960px                |
| `.col-xl-*`  | 1200px     | 1140px               |
| `.col-xxl-*` | 1400px     | 1320px               |

---

## 🛠 Usage

1. Clone or download the repository.
2. Import the Sass file into your project.
3. Compile it using your preferred Sass compiler.
4. Use classes like `.col-sm-6`, `.col-md-offset-3`, etc.

```html
<div class="container">
  <div class="row">
    <div class="col-sm-4">Left</div>
    <div class="col-sm-4 col-sm-offset-4">Right</div>
  </div>
</div>```

---

##👤 Author
Developed with ❤️ by AhmadJeddi
