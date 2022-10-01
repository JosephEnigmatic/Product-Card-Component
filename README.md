# Product-Card-Component

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

# ScrrenShots
![](../../../Downloads/Screenshot%202022-09-30%20at%2015-30-28%20Frontend%20Mentor%20Product%20preview%20card%20component.png)

![](../../../Downloads/Screenshot%202022-09-30%20at%2014-51-32%20Frontend%20Mentor%20Product%20preview%20card%20component.png)

# My Process
- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I Learned
-Used the picture tag and source tag to change the image after a specific width was reached, with a default image tag as fallback

            <picture>
                <source media="(min-width: 640px)" srcset="./product-preview-card-component-main/images/image-product-desktop.jpg">
                
                <img src="./product-preview-card-component-main/images/image-product-mobile.jpg" alt="">
            </picture>

### Future Development
-using Scss
-learn white spacing
-line-height
