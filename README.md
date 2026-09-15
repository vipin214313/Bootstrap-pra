# BOOTSTRAP — Complete Notes

---

## 1. Framework kya hai?

**Framework = HTML + CSS + JS**

Framework ek pre-written code ka collection hota hai (classes, components, functions) jisse development fast aur easy ho jata hai. Hume scratch se code likhne ki zarurat nahi padti — ready-made classes use karke website design kar sakte hain.

---

## 2. Bootstrap kya hai?

Bootstrap ek **popular HTML, CSS aur JavaScript framework** hai jo **responsive** aur **mobile-friendly** websites banane ke liye use hota hai.

- Bootstrap **classes ka ek collection** hai.
- Developed by **Mark Otto** and **Jacob Thornton**.
- Pehle iska naam **"Twitter Blueprint"** tha.
- 2011 me rename hokar **"Bootstrap"** ho gaya.
- Bootstrap ka basic layout **container classes** par based hota hai.

> **Note:** Jab kisi element par Bootstrap apply ho raha hota hai, to us par **inline style** ke through bhi changes kiye ja sakte hain (override karne ke liye).

---

## 3. Container Classes

| Class | Use |
|---|---|
| `class="container"` | Fixed-width responsive container |
| `class="container-fluid"` | Full-width container (100% viewport width) |

### Row & Grid System
- Bootstrap ka **row 12 columns** me divide hota hai.
- **Rule:** Row ke andar row nahi le sakte, **lekin** row ke andar column ke andar row le sakte hain — **condition:** us column me 3 ya usse zyada columns hone chahiye.

### Devices for Bootstrap (Column Classes)

| Class | Device |
|---|---|
| `col-xl-*` | Extra Large devices |
| `col-lg-*` | Large devices |
| `col-md-*` | Medium devices |
| `col-sm-*` | Small devices |

### Basic Structure

```html
<html>
<head>
  <link href="link library" rel="stylesheet">
</head>
<body>
  <div class="container">
    <div class="row">
      <!-- write your code here -->
    </div>
  </div>
</body>
</html>
```

> Jab HTML5 use karte hain, tab `container` / `container-fluid` ke andar `container` ya `container-fluid` call karna **compulsory** hai.

---

## 4. Table Classes

| Class | Effect |
|---|---|
| `table` | Basic Bootstrap table styling |
| `table-striped` | Alternating row colors |
| `table-bordered` | Adds borders around table & cells |
| `table-hover` | Row highlight on hover |

---

## 5. Image Classes

| Class | Effect |
|---|---|
| `img img-rounded` | Rounded corners |
| `img img-responsive` | Responsive scaling |
| `img img-thumbnail` | Thumbnail border style |
| `img img-fluid` | Fluid/responsive image |
| `img img-circle` | Circular image |

---

## 6. Hover Effects

| Class | Effect |
|---|---|
| `hvr-pop` | Pop effect on hover |
| `hvr-pulse` | Pulse effect on hover |
| `hvr-buzz` | Buzz/shake effect on hover |
| `hvr-float` | Float effect on hover |

---

## 7. Icon Classes

### Font Awesome
| Class | Icon |
|---|---|
| `fa fa-facebook` | Facebook |
| `fa fa-user` | User |
| `fa fa-instagram` | Instagram |
| `fa fa-youtube` | YouTube |

### Glyphicons
| Class | Icon |
|---|---|
| `glyphicon glyphicon-eye` | Eye |
| `glyphicon glyphicon-phone` | Phone |
| `glyphicon glyphicon-trash` | Trash |

### Icofont
| Class | Icon |
|---|---|
| `icofont-user` | User |
| `icofont-phone` | Phone |
| `icofont-trash` | Trash |
| `icofont-instagram` | Instagram |
| `icofont-facebook` | Facebook |
| `icofont-pluse` | Plus |

---

## 8. Sliders

- Slider
- Slider bullets (navigation dots for slider)

---

## 9. Form Classes

| Class | Use |
|---|---|
| `form-control` | Styles input, textarea, select fields |

### Button Classes

| Class | Style |
|---|---|
| `btn btn-success` | Green button |
| `btn btn-danger` | Red button |
| `btn btn-info` | Blue/info button |
| `btn btn-warning` | Yellow/warning button |
| `btn btn-default` | Default/gray button |

---

## 10. Navbar

- Navbar
- Navbar menu
- Navbar menu ke andar sub-menu (dropdown)
- `fixed-top` class → menu ko top par fixed karne ke liye

> Note: JavaScript me id banane ke liye `data-target="#name"` ka use karte hain (modals, collapsibles etc. ke liye).

---

## 11. Animation Effects (AOS - Animate On Scroll)

### Slide Animation
| Attribute | Effect |
|---|---|
| `data-aos="slide-left"` | Slide from/to left |
| `data-aos="slide-right"` | Slide from/to right |
| `data-aos="slide-up"` | Slide up |
| `data-aos="slide-down"` | Slide down |

### Zoom Effect
| Attribute | Effect |
|---|---|
| `data-aos="zoom-in"` | Zoom in effect |
| `data-aos="zoom-out"` | Zoom out effect |

---

## 12. Other Topics Covered (Practical Files)

- Scrolling examples
- Modal examples (popup open on nav)
- Advance mixed website design (combining all above components)
- Advance navbar design using Bootstrap

---

### Quick Summary Table — All Class Categories

| Category | Example Classes |
|---|---|
| Layout | `container`, `container-fluid`, `row`, `col-*` |
| Table | `table`, `table-striped`, `table-bordered`, `table-hover` |
| Image | `img-rounded`, `img-responsive`, `img-thumbnail`, `img-fluid`, `img-circle` |
| Hover | `hvr-pop`, `hvr-pulse`, `hvr-buzz`, `hvr-float` |
| Icons | `fa fa-*`, `glyphicon glyphicon-*`, `icofont-*` |
| Form/Button | `form-control`, `btn btn-*` |
| Navbar | `navbar`, `fixed-top` |
| Animation | `data-aos="..."` |
