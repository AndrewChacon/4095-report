
# Andrew Chacon

**Class:** CSE 4095  
**Date:** 27 April 2025

___

# 🛠️ Using Bootstrap as a Tool for Building Prototypes

## 1. What is Bootstrap? 
Bootstrap is a **free, open-source front-end framework** used to quickly design and customize **responsive** websites and web applications.  
It includes **ready-made HTML, CSS, and JavaScript components** like buttons, forms, navigation bars, and grids — making web development much faster and easier!

---

## 2. Why Do We Want to Use It?
**Key benefits of Bootstrap for prototyping:**
- **Speed:** Quickly create layouts without starting from scratch.
- **Responsiveness:** Websites automatically adjust to different screen sizes
- **Consistency:** Predefined styles ensure a uniform look across all browsers and devices.
- **Prebuilt Components:** Save time with ready-to-use buttons, cards, forms, modals, and more.

---

# ⚙️ Implementation

## Step 1: Create a Basic `index.html` and Add Bootstrap

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Bootstrap Example</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">
</head>
<body>
    <h1>Hello Bootstrap!</h1>
</body>
</html>
```

✅ This simple setup adds all of Bootstrap’s styles to your project.  
(You can also add Bootstrap's JavaScript bundle if needed for interactive components!)

---

# 🧩 Layouts and Components

## Example 1: Grid Layout (Responsive Columns)

```html
<div class="container">
  <div class="row">
    <div class="col-md-6">
      <p>This is half the width on medium+ screens.</p>
    </div>
    <div class="col-md-6">
      <p>This is the other half.</p>
    </div>
  </div>
</div>
```

---

## Example 2: Navigation Bar (Navbar)

```html
<nav class="navbar navbar-expand-lg navbar-light bg-light">
  <a class="navbar-brand" href="#">MySite</a>
</nav>
```

---

## Example 3: Form

```html
<form>
  <div class="mb-3">
    <label for="exampleInputEmail" class="form-label">Email address</label>
    <input type="email" class="form-control" id="exampleInputEmail">
  </div>
  <button type="submit" class="btn btn-primary">Submit</button>
</form>
```

---

# 📚 Visit the Bootstrap Documentation

For more detailed explanations, live examples, and the latest updates, check out the official Bootstrap docs:

👉 [https://getbootstrap.com/docs/](https://getbootstrap.com/docs/)

The documentation offers:
- 🎨 **Examples** of layouts, components, utilities, and more.
- 🛠️ **Custom build tools** to personalize your Bootstrap download.
- 🎨 **Theming guides** to change colors, fonts, and styles easily.
- 🚀 **Starter templates** to quickly set up a new project.
- ♿ **Accessibility resources** to make your designs more inclusive.

---
