# Framework Bootstrap

_April 2021_

> 🔨 Overview and exemple. From Udemy [Bootstrap en partant de Zéro - Enzo Ustariz](https://www.udemy.com/course/bootstrap-en-partant-de-zero).

---

Quickly design and customize responsive mobile-first sites with Bootstrap, the world’s most popular front-end open source toolkit, featuring Sass variables and mixins, responsive grid system, extensive prebuilt components, and powerful JavaScript plugins.

<h1 align="center">
    <img src="_readme-img/logo_bootstrap.jpg">
</h1>

<h1 align="center">
    <img src="_readme-img/site-capture.png">
</h1>

## Demo on Github pages

- [Overview](https://raigyo.github.io/bootstrap-overview/overview/01-content/1_Titre.html)
- [Site Easy Job](https://raigyo.github.io/bootstrap-overview/index.html)

## Overview

### Content

- Title and Typography
- Alignment and Display
- Marge, Padding
- Colors and Backgrounds
- Size and Borders
- Floats and Fixed position
- Images

### Grid

- Grid
- Alignment
- Flexbox
- Margin, Wrap and Order

### Component

- Buttons
- Navbars
- Lists
- Forms
- Inputs
- The tables
- The cards
- Jumbotron
- Alerts
- Progress bars

### Javascript / JQuery

- Carousel
- Collapse
- Popover & Tooltips
- Modals
- Scroll

## Notes

Body default:

```css
font-size: 16px; /*1rem**/
line-height: 1.5;
font-family: “Helvetica Neue”, Helvetica, Arial, sans-serif;
```

What is the default size of h1 Bootstrap heading?
2.5rem / 40px

What is the default size of h2 Bootstrap heading?
2rem / 32px

What is the default size of h3 Bootstrap heading?
1.75rem / 28px

What is the default size of h4 Bootstrap heading?
1.5rem / 24px

What is the default size of h5 Bootstrap heading?
1.25rem / 20px

#### Texts

`.display-1` 6rem / 90px
`.display-2` 5.5r / 82.5px
`.display-3` 4.5rem / 67.5px
`.display-4` 3.5rem / 52.5px

### Grid

Extra small: <576px

Small: ≥576px et <768px

Medium: ≥768px et <992px

Large: ≥992px et <1200px

Extra large: ≥1200px

Note:

The "col-xs-" class does not exist, when we switch to extra-small mode, below 576px, we directly put col-x to define the number of columns in extra small.

Ex:

```html
<div class="col-6 col-sm-4 col-md-6 col-lg-10"></div>
```

So this div will take: 6 columns in extra small, 4 in small, 6 in medium and finally 10 in Large.

## Useful links

- [Bootstrap](https://getbootstrap.com/)
- [Ziratsu/Bac-a-Sable-1](https://github.com/Ziratsu/Bac-a-Sable-1)
- [Ziratsu/Bac-a-Sable-2-Grille](https://github.com/Ziratsu/Bac-a-Sable-2-Grille)
- [Ziratsu/Bac-a-Sable-3-Composants](https://github.com/Ziratsu/Bac-a-Sable-3-Composants)
- [Ziratsu/Bac-a-Sable-4-JavaScript](https://github.com/Ziratsu/Bac-a-Sable-4-JavaScript)
- [Ziratsu/ProjetBootstrapFormation](https://github.com/Ziratsu/ProjetBootstrapFormation)
