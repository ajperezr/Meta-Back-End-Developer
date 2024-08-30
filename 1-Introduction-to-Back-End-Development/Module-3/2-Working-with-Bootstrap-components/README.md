## Lab: Working with Bootstrap components
## Introduction
In this exercise, you will practice adding Bootstrap components to a webpage.

## Goal
Update the Little Lemon website to use Bootstrap Components.

## Objectives
-	Add a Badge component to the page to notify customers of the new falafel dish.
-	Add an alert component to the page to notify customers that the restaurant will be closed on New Year's Day.
-	Add a Button component to the page with the text Order Online.

## Instructions
1. Open `index.html`
2. Add another `div` element below the `Our Menu` `text-center` `div` element.
3. Add a `class` attribute to the element with the value alert `alert-info`.
4. Add a `role` attribute to the element with the value `alert`.
5. Add the message `Our restaurant will be closed on New Year's Day`, inside the `div` element.
```HTML
<div class="row">
    <div class="col-12">
        <div class="text-center">
            <h1>Our Menu</h1>
        </div>
        <div class="alert alert-info" role="alert">
            Our restaurant will be closed on New Year's Day
        </div>
    </div>
</div>
```
6. Add a `span` element inside the `Falafel` `h2` element, before the closing `h2` tag.
7. Add a `class` attribute to the `span` element, with the value `badge bg-secondary`.
```HTML
<h2>Falafel <span class="badge bg-secondary">New</span></h2>
```
8. Add another `div` element after the last `row` element.
9. Add a `class` attribute with the value `row` to the `div` element.
10. Add a `div` element inside the `row` `div` element.
11. Add a `class` attribute with the value `col-12` to the `div` element.
12. Add another `div` element inside the `col-12` `div` element.
13. Add a `class` attribute with the value `text-center` to the `div` element.
14. Add a `button` element inside the `text-center` `div` element.
15. Add a `type` attribute with the value `button`.
16. Add a `class` attribute with the value `btn btn-primary`.
17. Add the text `Order Online` inside the `button` element.
```HTML
<div class="row">
    <div class="col-12">
        <div class="text-center">
            <button type="button" class="btn btn-primary">Order Online</button>
        </div>
    </div>
</div>
```
18. Save the file.
19. Click on 'Go live', which is at the bottom right of your editor.
<br>Once the server is up and running, you'll see the exposed port.
20. Now click on browser preview. 
<br>Enter the url as http://localhost:5500
21. Verify that the alert is displayed on the web page.
22. Verify at the new badge is displayed on the Falafel header.
23. Verify that the Order Online button is displayed.
24. Make sure to close the server by clicking on exposed Port number (e.g. 5500) after completing the lab.
<br>You should see a notification like this which confirms the server has been stopped.
 
## Tips
-	Make sure to add your columns to row elements.
-	Remember that Bootstrap uses a 12-column grid system.
-	There are plenty of examples in the Bootstrap documentation.
-	Review the lessons *Using Bootstrap Styles* and *Bootstrap Components*.
