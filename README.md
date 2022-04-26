# link-tree
Welcome on my HTML5 and CSS link tree, a landing page that reference all my social media and information for my professionnal and personnal activities.

Feel free to use this template and to reach me out on Twitter or Instagram to show me the result of your LinkTree!

## Change the links 
In order to change the links you will need to go to the HTML file at the `<script>` element at the end of the `index.html` file.

You will find the `links` object. The `key` is the input displayed on the button and the `value` is the link of the website. 

```
let links = {
    "Portefolio": "http://adleysalabi.com",
    "Linkedin": "https://www.linkedin.com/in/adleysalabi/",
    "GitHub": "https://www.github.com/AdleySlbi",
    "Twitter": "https://www.twitter.com/AdleySlb",
    "Instagram": "https://www.instagram.com/adleyslb/",
    "Schedule an appointment": "https://www.calendly.com/adley-salabi/adley-salabi",
    "Send me a mail": "mailto:contact@adleysalabi.com",
    "Vinted": "https://www.vinted.fr/member/12481249-adleysalabi",
}
````


## Using SCSS 
Sass is a preprocessor scripting language that is interpreted or compiled into Cascading Style Sheets. SassScript is the scripting language itself. [Sass](https://sass-lang.com/)

Using the `input.scss` will allow you to use the scss variables and the concatenation of the code. 

Launch this command to watch any changes on the project and to update the `output.css` file, the file use in the HTML.
```
cd css
sass --watch input.scss output.css
```

### Variables
Three variables are used on this website, feel free to change them and make the website fit your needs!

```
// Colors Variables
$grey-medium: #dedede;
$grey-cloud: #C5C6D0;
$gray-bold: #646464;
```

## Using BrowerSync
BrowerSync cuts out repetitive manual tasks and autoreload the website on any changes. It’s like an extra pair of hands. [Brower-Sync](https://browsersync.io/)
```
npm install -g browser-sync
// Launching the live server 
browser-sync start --server --files "."
```

## Font 
The font [Roboto](https://fonts.google.com/specimen/Roboto) is uses for all of the website. 

To use the font inside the code, use the variable `$roboto`. 
```
a {
    font-family: $roboto
}
```