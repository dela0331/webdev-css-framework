# Custom-CSS-Framework
Custom CSS Framework Assignment - MTM6407 Web Development IV

## Overview
KOY CSS Framework
KOY is a simple, flexible, and customizable CSS framework built with Sass. It provides responsive typography, font-weight control, and list styling for your web projects. KOY allows easy font customization and can be integrated into any design project for a cohesive typographic system.

## Installation

To install and use the framework in your project, follow these steps:

1. **Clone the repository** or download the framework files.
2. **Compile the Sass** into regular CSS using a Sass compiler of your choice.
3. **Include the compiled CSS** in your HTML file:

```html
<link rel="stylesheet" href="css/style.css">
```

### Sass Compilation
Make sure you have a Sass compiler installed. If not, you can install sass globally:
npm install -g sass

To compile the framework:
sass src/main.scss css/style.css

## Usage
### Variables
You can customize your form elements by adjusting the variables located in the _variables.scss file.

### Form Structure
Use the following HTML structure for forms:
```
<form action="#" method="POST">
  <label for="name">Name</label>
  <input type="text" id="name" name="name" placeholder="Enter your name">

  <label for="email">Email</label>
  <input type="email" id="email" name="email" placeholder="Enter your email">

  <label for="message">Message</label>
  <textarea id="message" name="message"></textarea>

  <div class="button-group">
    <button type="submit" class="button button-submit">Submit</button>
    <button type="reset" class="button button-reset">Reset</button>
  </div>
</form>
```

### Buttons
Two types of buttons are available:
1. Submit Button (Green):
```
<button type="submit" class="button button-submit">Submit</button>
```
2. Reset Button (Red):
```
<button type="reset" class="button button-reset">Reset</button>
```
