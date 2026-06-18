# 💖 Our Story Timeline Template

A free romantic timeline website template designed for couples who want to showcase their relationship journey year by year.

Feel free to use, modify, improve, and share this template for personal projects.

---

## ✨ Features

- Elegant romantic design
- Year-by-year timeline
- Individual pages for each year
- Photo placeholders when images are missing
- Optional video section
- Mobile-friendly layout
- Decorative animations and floating elements

---

# 📌 Getting Started

The template consists of two main pages:

- `main.html` → Timeline overview page
- `year.html` → Detailed page for each year

---

# 🗓️ Editing the Timeline (main.html)

## Navigation Year Bubbles

Locate:

```html
<div class="year-bubbles"></div>
```

Example:

```html
<a class="yb" href="#year-2020">2020</a>
<a class="yb" href="#year-2021">2021</a>
<a class="yb" href="#year-2022">2022</a>
```

Add or remove years based on your relationship length.

If your relationship started in 2018:

```html
<a class="yb" href="#year-2018">2018</a>
<a class="yb" href="#year-2019">2019</a>
<a class="yb" href="#year-2020">2020</a>
```

---

## Timeline Cards

Each year uses a card like:

```html
<div class="tl-row left" id="year-2020"></div>
```

or

```html
<div class="tl-row right" id="year-2021"></div>
```

### Alternate Left and Right

Use this pattern:

```html
2020 = left 2021 = right 2022 = left 2023 = right 2024 = left 2025 = right
```

To add another year:

Copy an existing card and update:

- Year ID
- Year label
- Title
- Description
- Link

Example:

```html
<p class="year-tag">2026</p>

<p class="card-title">Our New Adventure</p>

<p class="card-text">A short description of this year.</p>
```

---

## Card Images

Locate:

```html
<img src="" />
```

Replace with your image:

```html
<img src="img/2020.jpg" />
```

If left empty:

```html
<img src="" />
```

the template automatically shows the placeholder design.

---

## Card Links

Locate:

```html
<a href="year.html"></a>
```

Change to the matching year page:

```html
<a href="2020.html"></a>
```

Example structure:

```text
index.html
2020.html
2021.html
2022.html
2023.html
2024.html
```

---

# 📖 Editing Year Pages (year.html)

You can duplicate `year.html` and rename it:

```text
2020.html
2021.html
2022.html
2023.html
```

Each page represents one year of your story.

---

## Year Title

Locate:

```html
<h1 class="year-title">20<span>2X</span></h1>
```

Change to:

```html
<h1 class="year-title">20<span>20</span></h1>
```

or

```html
<h1 class="year-title">20<span>24</span></h1>
```

---

## Letter Section

Locate:

```html
<p class="letter-text"></p>
```

Write your story for that year.

Example:

```html
<p class="letter-text">
  This was the year we first met. We spent countless hours talking, learning
  about each other, and creating unforgettable memories.
</p>
```

---

## Signature / Remarks

Locate:

```html
<span class="letter-sign"> Remarks ♥ </span>
```

Examples:

```html
<span class="letter-sign"> Love Always ♥ </span>
```

```html
<span class="letter-sign"> To Many More Years ♥ </span>
```

---

## Polaroid Photos

Locate:

```html
<img src="" />
```

Replace with your image:

```html
<img src="img/photo1.jpg" />
```

Leave blank if you do not have a photo yet.

The template will automatically display a placeholder.

---

## Video Section

Locate:

```html
<source src="" type="video/mp4" />
```

Replace with:

```html
<source src="video/2020.mp4" type="video/mp4" />
```

If no video is provided, the template will show a placeholder.

---

# 🎨 Customization

You are encouraged to:

- Change colors
- Change fonts
- Modify layouts
- Add animations
- Add music
- Add galleries
- Add more timeline effects
- Improve responsiveness
- Create your own design variations

This template is intended as a starting point, not a limitation.

---

# ❤️ Free to Use

This project is free to use for personal and educational purposes.

Feel free to:

- Fork it
- Modify it
- Improve it
- Share it
- Build upon it

Credit is appreciated but not required.

---

Made with love for couples who want to preserve their memories in a beautiful timeline.
