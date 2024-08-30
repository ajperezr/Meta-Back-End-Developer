## Lab: Working with Bootstrap grid
## Introduction
In this exercise, you will practice building a webpage using the Bootstrap Grid.

## Goal
Create a two-columns food menu for Little Lemon.

## Objectives
-	Set up the Bootstrap container.
-	Display the Little Lemon logo in the top center of the webpage using Bootstrap.
-	Display the food menu in two columns using Bootstrap Grid.

## Instructions
1. Open `index.html`
2. Add a `div` element inside the `body` element. This `div` will be the Bootstrap container.
3. Add the `class` attribute to this element with the value `container`.
```HTML
<body>
    <div class="container">
     </div>
</body>
```
4. Add three `div` elements to the Bootstrap container element. Each of these `div` elements will be a Bootstrap row. Add the `class` attribute to this element with the value `row`.
```HTML
<body>
    <div class="container">
        <div class="row">
        </div>
        <div class="row">
        </div>
        <div class="row">
        </div>
    </div>
</body>
```
5. The first row will contain the Little Lemon logo. Add a `div` element to the first row.
6. Add the `class` attribute to this element with the value `col-12`. This will take up 12 columns spaces.
```HTML
<body>
    <div class="container">
        <div class="row">
            <div class="col-12">
            </div>
        </div>
        <div class="row">
        </div>
        <div class="row">
        </div>
    </div>
</body>
```
7. Add another `div` element to the `col-12` element.
8. Add the `class` attribute to this element with the value `text-center`. This will allow you to center the logo.
```HTML
<body>
    <div class="container">
        <div class="row">
            <div class="col-12">
                <div class="text-center">
                </div>
            </div>
        </div>
        <div class="row">
        </div>
        <div class="row">
        </div>
    </div>
</body>
```
9. Add an image element in the `text-center` element with `img-fluid` class applied to it.
```HTML
<body>
    <div class="container">
        <div class="row">
            <div class="col-12">
                <div class="text-center">
                    <img src="logo.png" class="img-fluid">
                </div>
            </div>
        </div>
        <div class="row">
        </div>
        <div class="row">
        </div>
    </div>
</body>
```
10. In the second row, add another `div` element with the class `col-12`.
```HTML
<body>
    <div class="container">
        <div class="row">
            <div class="col-12">
                <div class="text-center">
                    <img src="logo.png" class="img-fluid">
                </div>
            </div>
        </div>
        <div class="row">
            <div class="col-12">
            </div>
        </div>
        <div class="row">
        </div>
    </div>
</body>
```
11. Add a `div` element to the column and apply the class `text-center`.
```HTML
<body>
    <div class="container">
        <div class="row">
            <div class="col-12">
                <div class="text-center">
                    <img src="logo.png" class="img-fluid">
                </div>
            </div>
        </div>
        <div class="row">
            <div class="col-12">
                <div class="text-center">
                </div>
            </div>
        </div>
        <div class="row">
        </div>
    </div>
</body>
```
12. Inside the element, add an `h1` element with the text `Our Menu`.
```HTML
<body>
    <div class="container">
        <div class="row">
            <div class="col-12">
                <div class="text-center">
                    <img src="logo.png" class="img-fluid">
                </div>
            </div>
        </div>
        <div class="row">
            <div class="col-12">
                <div class="text-center">
                    <h1>Our Menu</h1>
                </div>
            </div>
        </div>
        <div class="row">
        </div>
    </div>
</body>
```
13. Add two `div` elements in the final row.
14. Add a `class` attribute to each element with the value `col-12 col-lg-6`.
```HTML
<body>
    <div class="container">
        <div class="row">
            <div class="col-12">
                <div class="text-center">
                    <img src="logo.png" class="img-fluid">
                </div>
            </div>
        </div>
        <div class="row">
            <div class="col-12">
                <div class="text-center">
                    <h1>Our Menu</h1>
                </div>
            </div>
        </div>
        <div class="row">
            <div class="col-12 col-lg-6">
            </div>
            <div class="col-12 col-lg-6">
            </div>
        </div>
    </div>
</body>
```
15. Add the following elements in the first `col-12 col-lg-6` element:
-	An `h2` element containing the text `Falafel`.
-	A paragraph element containing the text `Chickpea, herbs, spices`.
-	An `h2` element containing the text `Fried Calamari`.
-	A paragraph element containing the text `Squid, buttermilk`.
16. Add the following elements in the second `col-12 col-lg-6` element:
-	An `h2` element containing the text, `Pasta Salad`.
-	A paragraph element containing the text `Lettuce, vegetables, mozzarella`.
-	An `h2` element containing the text `Greek Salad`.
-	A paragraph element containing the text `Cucumbers, onion, feta cheese`.
```HTML
<body>
    <div class="container">
        <div class="row">
            <div class="col-12">
                <div class="text-center">
                    <img src="logo.png" class="img-fluid">
                </div>
            </div>
        </div>
        <div class="row">
            <div class="col-12">
                <div class="text-center">
                    <h1>Our Menu</h1>
                </div>
            </div>
        </div>
        <div class="row">
            <div class="col-12 col-lg-6">
                    <h2>Falafel</h2>
                    <p>Chickpea, herbs, spices.</p>
                    <h2>Fried Calamari</h2>
                    <p>Squid, buttermilk<./p>
            </div>
            <div class="col-12 col-lg-6">
                    <h2>Pasta Salad</h2>
                    <p>Lettuce, vegetables, mozzarella.</p>
                    <h2>Greek Salad</h2>
                    <p>Cucumbers, onion, feta cheese.<./p>
            </div>
        </div>
    </div>
</body>
```
17. Save the file.
18. Click on 'Go live', which is at the bottom right of your editor.
<br>Once the server is up and running, you'll see the exposed port.
19. Now click on browser preview.
<br>Enter the url as http://localhost:5500 
20. Select the device toolbar and choose MacBook 15 as device.
21. Verify that the web page displays the Little Lemon menu in two columns.
22. Make sure to close the server by clicking on exposed Port number (e.g. 5500) after completing the lab.
<br>You should see a notification like this which confirms the server has been stopped.
 
## Tips
-	Make sure to add your columns to row elements.
-	Remember that Bootstrap uses a 12-column grid system.
-	Review the lessons *Using Bootstrap Styles* and *Bootstrap Grid*.
