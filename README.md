# Font-awesome-template
A basic tutorial teaching you how to use font awesome icons.
For a "live" demo, check out <em><a href="https://Font-awesome-live-demo.flameory.repl.co">the live demo<a></em>

## Basic example
This is an example, it displays the Github logo.
***
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="style.css">
    <!---imports icons---!>
    <link rel="stylesheet" href="fontawesome.com/releases/v6.0.0-beta3/scss/solid.scss">
    <title>Example</title>
   <body>
   <!---add your icons here---!>
   <i class="fa-brands fa-github"></i>
   </body>
    </html>
```
## Explained
First, open *[Font Awesome](https://fontawesome.com)*. Then create a basic html file, kinda like this:

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    
</body>
</html>
```
Then, create a *[Font Awesome](https://fontawesome.com)* account. Now copy the link you got from *[Font Awesome](https://fontawesome.com)*.
Now with that link, use it as a stylesheet. Here is how that goes:
```html
<link rel="stylesheet" href="fontawesome.com/releases/v6.0.0-beta3/scss/solid.scss">
```
With all changes, this is how it looks like:
***
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="style.css">
    <link rel="stylesheet" href="fontawesome.com/releases/v6.0.0-beta3/scss/solid.scss">
    <title>Document</title>
   <body>

   </body>
    </html>
```
## Final comments
And, remember that if you want to make a cool hover effect or something like that, that you use the color method.
Not the background color method.
## Full CSS:
Finally, here's the full css:
```css
body{
   background-color: #2c323c;
}
i{
  padding: 6px 8px 6px 16px;
  text-decoration: none;
  font-size: 25px;
  padding-bottom:20px;
  color: #41ff8ad2;
  place-items: center;
  display: grid;
  transition: 300ms;
}
i:hover{
 color: #f1f1f1;
}
h1, p, h2, h3{
  color: #f1f1f1;
  font-family: sans-serif;
}
```
