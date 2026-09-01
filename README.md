# 📰 Newspaper Article

A simple **Newspaper Article Page** built with HTML and CSS. This project demonstrates how typography, relative units, text styling, and pseudo-elements can be used to create a newspaper-inspired layout.

## 📌 Features

* Newspaper-style article layout
* Custom newspaper name and date
* Main headline and sub-headline
* Author information
* Article paragraphs
* Styled first letters
* Uppercase newspaper name and author
* Custom font families
* Responsive page structure

## 🛠️ Technologies Used

* **HTML5** – For the article structure and content
* **CSS3** – For typography, spacing, text transformations, and pseudo-elements

## 📂 Project Structure

```text
Newspaper-Article/
│
├── index.html
├── styles.css
└── README.md
```

## 🚀 How to Run

1. Clone the repository:

```bash
git clone https://github.com/your-username/Newspaper-Article.git
```

2. Open the project folder.

3. Open `index.html` in your web browser.

No additional dependencies or installations are required.

## ✍️ Typography and CSS Concepts

The project demonstrates the use of relative font units:

```css
html {
  font-size: 24px;
}

.newspaper {
  font-size: 16px;
  font-family: 'Open Sans', sans-serif;
}
```

The newspaper name uses `rem`:

```css
.name {
  font-size: 2rem;
  font-family: 'Times New Roman', serif;
  text-transform: uppercase;
}
```

The headline and sub-headline use `em` units:

```css
.headline {
  font-size: 2em;
  font-weight: bold;
}

.sub-headline {
  font-size: 1.5em;
  font-weight: 100;
  font-style: italic;
}
```

The first letter of each article paragraph is emphasized using the `::first-letter` pseudo-element:

```css
.text::first-letter {
  font-weight: bold;
  font-size: 2em;
}
```

## 🎯 Learning Objectives

This project helps practice:

* CSS typography
* `rem` and `em` units
* Font families and fallbacks
* Font weights and styles
* `text-transform`
* `text-indent`
* `line-height`
* CSS pseudo-elements
* Semantic HTML structure
* Creating newspaper-style layouts


This project was created for educational and learning purposes.
