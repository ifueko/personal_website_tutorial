# Personal Website Tutorial
## author: Ifueko Igbinedion
This is a quick website tutorial for those trying to make a personal website or
a website that does not require siginifant e-commerce (or other features requiring
advanced authentication or server-side programming). Check out
[this youtube video](https://youtu.be/JzjYUU4EpmM) for a quick intro!

## TOOLS USED
### [Editor: Atom](https://atom.io/)
Any editor should suffice, but I like Atom because of its easy github integration mechanisms.

### Languages
#### [HTML](https://www.w3schools.com/html/)
#### [CSS](https://www.w3schools.com/css/default.asp)
#### [JS](https://www.w3schools.com/js/default.asp)
This tutorial does mostly HTML/CSS editing, with a bit of javascript.

### [Bootstrap](https://getbootstrap.com/docs/4.5/getting-started/introduction/)
This is the framework we are using to make the websites as responsive as possible
with minimal work. Check the documentation for more details.

### Animate on Scroll ([AOS](https://michalsnik.github.io/aos/)) Library
This allows for extremely easy animations to be added to your website, with very little setup.

### [Favicon Generator](favicon.io)
This is a great favicon generator that allows you to make icons for your website from png, emoji or text.

### [jQuery](https://jquery.com/)
We actually arent doing too much with jquery, but its useful for any type of dynamic content that is client-side.

### [Google Drawings](https://drawings.google.com)
This is basically a paint application, and is good for simple graphics.

### [GIMP](https://www.gimp.org/)
This is a powerful, free photo manipulation tool, similar to photoshop/illustrator. Many people suggest it because of the ease of figuring things out (comparatively...)

### [Google Domains](domains.google.com)
This is where I typically purchase my domains, as they are often standardized at $12/year. Some are more expensive, but the majority are at this price. It also alows for cheap email and FREE email forwarding.

We edit the DNS settings in this dashboard to publish our website.

### GitHub/Github Pages
We're hosting on github pages in this tutorial. Check out the documentation for details, but most of the settings you need to

## CAVEATS

### Github Pages: No "Dynamic" Server Side Code
None of the code that you launch on github pages can be executed on  the server side. So any php, python, etc bindings you try to create that may work on a different hosting service will not work with this type of website.


### GitHub Free SSL: Certificate Mismatches
While github pages allows for SSL that is in fact secure, if you add https with www in your url, it will show up as insecure because the certificate is owned/licensed by github. To avoid this, never link using both https and www at the same time. I typically just suggest using http, as the site will still resolve to https.


## TUTORIAL
### 0. [understanding the starter template development environment and file structure](docs/0.Setup.md)
### 1. [generating your Favicon](docs/1.Favicons.md)
### 2. [boilerplate webpage structure and content](docs/2.Basic_Structure_And_Content.md)
### 3. [graphics](docs/3.Easy_Graphics.md)
### 4. [Styling: CSS and Animations](docs/4.Styling.md)
### 5. [dynamic content: links + iframes](docs/5.Dynamic_Content.md)
### 6. [publishing to GitHub Pages](docs/6.Github_Pages.md)
### 7. [custom domain + SSL configuration using Google and Github Pages](docs/7.Custom_Domains.md)
