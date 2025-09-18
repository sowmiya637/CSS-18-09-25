#  Blog Page – CSS Combinators 

This demonstrates the use of various **CSS combinators** (`descendant`, `child`, `adjacent sibling`, and `general sibling`) through a simple blog-style layout.

---

##  Features & Learning Highlights

This demo includes the following **CSS combinators**:

| 🔢 | Selector             | Name                  | Description                                                                 |
|-----|----------------------|-----------------------|-----------------------------------------------------------------------------|
| 1️⃣ | `article p`          | **Descendant**        | Targets all `<p>` elements inside `<article>`, at any depth                 |
| 2️⃣ | `section > h2`       | **Child**             | Targets only `<h2>` elements that are **direct children** of `<section>`   |
| 3️⃣ | `h2 + p`             | **Adjacent Sibling**  | Targets the first `<p>` **immediately after** each `<h2>`                  |
| 4️⃣ | `h3 ~ p`             | **General Sibling**   | Targets **all `<p>` siblings** that come **after** `<h3>`                  |

---

## 🖼 Visual Behavior in the Page

- 🔴 **Red text**: All `<p>` inside `<article>` via `article p`  
- 🔵 **Dark blue headings**: `<h2>` directly under `<section>` via `section > h2`  
- *Gray italic text*: `<p>` immediately after `<h2>` via `h2 + p`  
- 🟨 **Yellow background**: `<p>` after `<h3>` via `h3 ~ p`  
- 🟣 **Purple list items**: `<li>` inside `.sidebar > ul > li`



