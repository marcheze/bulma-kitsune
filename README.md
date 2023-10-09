<p align="center" justify="center">
<img src="media/fox.png" style="height: 50px"></p>
<h1 align="center">bulma-kitsune | <a href="https://amarchese.com/a/1/build-a-website-with-bulma-css-framework-in-minutes-for-free">Tutorial</a></h1>

`bulma-kitsune` is a single page website for a fictional Ramer restaurant, built with <img src="./media/bulma.png" style="height: 10px"> [Bulma](https://bulma.io/), using HTML and CSS only. This repository was built for educational purposes and for you to code along in my article “[Build a Website with Bulma CSS Framework in Minutes for Free](https://amarchese.com/a/1/build-a-website-with-bulma-css-framework-in-minutes-for-free)”. You can also use this project as a base or reference to create a personal or small business website.

If you enjoyed the tutorial please ⭐ this repo.

### Project Setup

To start off with this project you only need to create `index.html` and `style.css` blank files in your project directory.

Add a starter template to `index.html` and import `style.css` into it:

```html
<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <title>Kitsune</title>
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <section class="section">
      <div class="container">
        <h1 class="title">Hello World</h1>
        <p class="subtitle">My first website with <strong>Bulma</strong>!</p>
      </div>
    </section>
  </body>
</html>
```

Notice how the starter template is using your default web browser formatting rules.

### Import Bulma

Now let's import Bulma framework in our CSS using jsDelivr as CDN by adding a line to `style.css` :

```css
@import "https://cdn.jsdelivr.net/npm/bulma@0.9.4/css/bulma.min.css";
```

After importing Bulma you can see the HTML elements formatted Bulma framework classes.

### Follow Article Step-by-Step

If you want to move on and complete the Kitsune project from scratch, follow along the steps in article “[Build a Website with Bulma CSS Framework in Minutes for Free](https://amarchese.com/a/1/build-a-website-with-bulma-css-framework-in-minutes-for-free)”

### Customizing the Project

As soon as you're done importing Bulma you are ready to add and edit Bulma layouts, components and elements as you please. Complete documentation is available on [Bulma Docs](https://bulma.io/documentation/).
