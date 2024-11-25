# Event Listeners Practice

Our **pizza website** is looking good, so let's add some fun functionality! Let's make it so that we can change the color of the description by clicking on the pizza images. 

When we click on the pepperoni pizza, we'll change the description's color to red! Click on the veggie pizza, it'll turn green! Click on the chicken pizza, it's orange now! Finally, clicking the description itself will make it black again.

Let's add this cool function using JavaScript!
### Tasks:

1. Create a function called **changeColor(color)**. This function should change the description's color to the given parameter.

2. Add an event listener to the Pepperoni Pizza image, with event "click" and a function that calls changeColor("red")!

* ``` Hint: Since we're making an event listener for a function with a parameter, we have to use the function() notation.```

3. Add event listeners to the other two pizzas!

4. Add the onclick property to the description in the HTML that calls changeColor("black")!

Both event listeners and the onclick property worked here! Onclick is easier to use, but event listeners are easier to add and remove! Keep this in mind!
