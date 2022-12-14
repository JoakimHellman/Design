---
Title: Test
Description: This is my test page
---

Test
======================

<h4>Bild utan begränsing på storlek</h4>

![Bild på movment](image/movement.jpg?w=400&h=400&q=50)

![Bild på movment](image/movement.jpg?w=400&h=400&q=50&sharpen&crop-to-fit&area=0,0,0,20)

![Leaf](image/leaf_256x256.png?h=250&w=50&stretch)
![Leaf](image/leaf_256x256.png?h=250&w=100&crop-to-fit)

<picture>
    <source media="(min-width: 668px)" srcset="%base_url%/image/bild1.jpg?q=60">
    <source media="(min-width: 376px)" srcset="%base_url%/image/bild1.jpg?w=667&q=60">
    <img src="%base_url%/image/bild1.jpg?w=375&q=60" alt="sheep">
</picture>

<div class="embed-container">
    <iframe src="https://www.youtube.com/embed/KedgG1rl3oM" frameborder="0" allowfullscreen></iframe>
</div>

<a href="%base_url%/image/bild2.jpg" target="_blank">
    <picture>
        <source media="(min-width: 668px)" srcset="%base_url%/image/bild2.jpg?q=60">
        <source media="(min-width: 376px)" srcset="%base_url%/image/bild2.jpg?w=667&q=60">
        <img src="%base_url%/image/bild2.jpg?w=375&q=60" alt="sheep">
    </picture>
</a>