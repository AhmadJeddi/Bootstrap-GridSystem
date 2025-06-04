# Bootstrap-GridSystem – FloatGrid: A Lightweight Float-based Grid

**FloatGrid** is a lightweight, responsive 12-column grid system inspired by [Bootstrap](https://getbootstrap.com), but built entirely with `float`, `inline-padding`, and `media queries`. Perfect for projects where Flexbox or CSS Grid is not required — and great for RTL layouts!

---

## 📦 Features

- ✅ 12-column layout with responsive breakpoints
- ✅ Offset support for spacing between columns
- ✅ Pure CSS (Sass-powered) – no JavaScript
- ✅ No dependencies – easy to integrate
- ✅ RTL-compatible

---

## 🧰 Utilities

The grid system includes a wide range of utility classes for layout, spacing, positioning, visibility, alignment, and more. These classes are lightweight, reusable, and designed to give you full control over your layout without writing custom CSS.

### 📐 Display & Flexbox

| Class             | CSS Property             |
| ----------------- | ------------------------ |
| `.d-none`         | `display: none`          |
| `.d-inline`       | `display: inline`        |
| `.d-inline-block` | `display: inline-block`  |
| `.d-block`        | `display: block`         |
| `.d-flex`         | `display: flex`          |
| `.flex-row`       | `flex-direction: row`    |
| `.flex-column`    | `flex-direction: column` |

### 🧭 Justify & Align (Flexbox)

| Class                      | CSS Property                     |
| -------------------------- | -------------------------------- |
| `.justify-content-start`   | `justify-content: start`         |
| `.justify-content-end`     | `justify-content: end`           |
| `.justify-content-center`  | `justify-content: center`        |
| `.justify-content-between` | `justify-content: space-between` |
| `.justify-content-around`  | `justify-content: space-around`  |
| `.justify-content-evenly`  | `justify-content: space-evenly`  |
| `.align-items-start`       | `align-items: start`             |
| `.align-items-end`         | `align-items: end`               |
| `.align-items-center`      | `align-items: center`            |
| `.align-items-baseline`    | `align-items: baseline`          |
| `.align-items-stretch`     | `align-items: stretch`           |

### ✍️ Text Alignment

| Class           | CSS Property          |
| --------------- | --------------------- |
| `.text-start`   | `text-align: start`   |
| `.text-center`  | `text-align: center`  |
| `.text-end`     | `text-align: end`     |
| `.text-justify` | `text-align: justify` |

### 🔠 Font Weight

| Class         | CSS Property           |
| ------------- | ---------------------- |
| `.fw-bold`    | `font-weight: bold`    |
| `.fw-lighter` | `font-weight: lighter` |

### 👁️ Visibility

| Class        | CSS Property          |
| ------------ | --------------------- |
| `.visible`   | `visibility: visible` |
| `.invisible` | `visibility: hidden`  |

### 📏 Vertical Alignment

| Class                | CSS Property                  |
| -------------------- | ----------------------------- |
| `.align-baseline`    | `vertical-align: baseline`    |
| `.align-top`         | `vertical-align: top`         |
| `.align-middle`      | `vertical-align: middle`      |
| `.align-bottom`      | `vertical-align: bottom`      |
| `.align-text-top`    | `vertical-align: text-top`    |
| `.align-text-bottom` | `vertical-align: text-bottom` |

### 📦 Positioning

| Class                | CSS Property         |
| -------------------- | -------------------- |
| `.position-static`   | `position: static`   |
| `.position-relative` | `position: relative` |
| `.position-absolute` | `position: absolute` |
| `.position-fixed`    | `position: fixed`    |
| `.position-sticky`   | `position: sticky`   |

### 🌊 Overflow

| Class                | CSS Property         |
| -------------------- | -------------------- |
| `.overflow-auto`     | `overflow: auto`     |
| `.overflow-x-auto`   | `overflow-x: auto`   |
| `.overflow-y-auto`   | `overflow-y: auto`   |
| `.overflow-hidden`   | `overflow: hidden`   |
| `.overflow-x-hidden` | `overflow-x: hidden` |
| `.overflow-y-hidden` | `overflow-y: hidden` |

### 📐 Margin

| Class     | CSS Property   |
| --------- | -------------- |
| `.m-auto` | `margin: auto` |

### 🖼️ Images

| Class        | Description                                                         |
| ------------ | ------------------------------------------------------------------- |
| `.img-fluid` | Makes the image scale fluidly with `width: 100%` and `height: auto` |

### 📦 Containers

| Class              | Description                                                       |
| ------------------ | ----------------------------------------------------------------- |
| `.container`       | Fixed-width container with horizontal padding and centered layout |
| `.container-sm`    | Responsive container (small breakpoint)                           |
| `.container-md`    | Responsive container (medium breakpoint)                          |
| `.container-lg`    | Responsive container (large breakpoint)                           |
| `.container-xl`    | Responsive container (extra large breakpoint)                     |
| `.container-xxl`   | Responsive container (extra extra large breakpoint)               |
| `.container-fluid` | Full-width container spanning the entire viewport                 |

---

## 🎯 Breakpoints

| Class Prefix | Min-width | Container Max-width |
| ------------ | --------- | ------------------- |
| `.col-xs-*`  | 1px       | 100% (fluid)        |
| `.col-sm-*`  | 576px     | 540px               |
| `.col-md-*`  | 768px     | 720px               |
| `.col-lg-*`  | 992px     | 960px               |
| `.col-xl-*`  | 1200px    | 1140px              |
| `.col-xxl-*` | 1400px    | 1320px              |

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
```
