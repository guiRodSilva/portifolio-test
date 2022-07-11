# Portifolio

What's up guys!💙 

This is a little challenge by Rocketseat that I tried to reproduce by myself with my habilities in HTML and CSS.

It consists basically in a begginer portifolio which shows my relevants informations, such as social media, experience with programming and my education. Besides, it shows my projects in general and below recents projects. It's a simple project, it's not even responsive, just to train begginer front-end skills.

Now I'm gonna put some relevant tips I used in my code! 
Let's go🚀😀

# CSS Images
 
 If you have so many images, like in that example we have 3 images, and don't want to set a class to each one to select in CSS afterwards:
```html
<div class="content-title">
<img src="images/icons/folder.svg" alt="folder">
<h4> my-onix</h4>
</div>
<p> Consulte os códigos de erro que aparecem no painel do veículo Onix</p>

<div class="bottom-info">
<div>
<div>
    <img src="images/icons/star.svg" alt="star">
    <p>100</p>
</div>

<div>
    <img src="images/icons/git-branch.svg" alt="branch">
    <p>100</p>
</div>
```
You can do it in CSS to select only the image you want:
```css
section img[src="images/profile.jpeg"]{
```
It will select only the image with the especific source in HTML

# CSS Object-fit

And to finish the tips, if you lost the proportion of the image you want to put in your project and it seems larger or smaller than you want, you can use the CSS property `object-fit: cover`

```css
object-fit: cover;
```
That property will fix your image and get it perfect in your viewport

Thank you guys to read it! If you have a suggestion, make a pull request, I will check all of them!💙
