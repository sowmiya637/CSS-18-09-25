#  CSS Pseudo-class Form 
It is aimed at helping beginners understand how pseudo-classes enhance user interactions and dynamic styling in forms.


##  Pseudo-classes Used in This Demo

| Pseudo-class             | Description                                                                 |
|--------------------------|-----------------------------------------------------------------------------|
| `:first-child`           | Targets the **first input** element inside the form                         |
| `:focus`                 | Styles the input when it is **focused** (clicked or tabbed into)            |
| `:hover`                 | Styles the **button** when the mouse hovers over it                         |
| `:disabled`              | Styles an input that is **disabled**                                        |
| `:checked`               | Styles the checkbox **when it is selected**                                 |
| `:not(:checked)`         | Styles the checkbox **when it is not selected**                             |


##  How It Works

- The first input field gets a **green border** using `:first-child`.
- Focused input fields get a **blue border and light background**.
- The login button changes **color on hover**.
- A disabled input field appears **grayed out**.
- The checkbox label turns **green when checked**, and **red when unchecked** using `:checked` and `:not(:checked)`.


