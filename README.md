# rasdan_69
This the website to advertise my products. Very simple HTML.

Template for products html:
~~~
<li class="plant-box">
    <h3>Plant Name</h3>
    <p class="availability available">availability</p>
    <a href="./images/image_of_plant.jpg.jpg" target="_blank">
        <img src="./thumb-images/image_of_plant.jpg" alt="Thumbnail" class="product-image thumbnail" data-fullsize-url="./images/image_of_plant.jpg">
    </a>
    <p>Description</p>
    <p>Physical description of plant for sale</p>
    <p>Price</p>
</li>
~~~

1. Add this html to the products directory and note the availabilty class and the image nale of full size and thumbnail.
2. Add image of product to the images directory, take note of name as path to it must be defined in product html.
3. Add the product html file name to the productFiles array in index.html

