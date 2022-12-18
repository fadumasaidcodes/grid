# CSS Grid

CSS Grid can be used to build simple and skeletal layouts. It can also be used to create polished, professional-level layouts.

In this activity, you will use CSS Grid to re-create the design of an online furniture store.

## Instructions

### Part 1: Hero Section

Here is what we will build in this section!

<img width="711" alt="part-1-solution" src="https://user-images.githubusercontent.com/102771343/208268866-696ae111-6b4f-47b9-8528-5e434e438c3f.png">


* Open the files `index.html` and `style.css`. 

  * You’ll notice that the HTML and CSS for the navigation bar code have already been completed along with some typography-related CSS.

* The HTML for the grid in the image at the beginning of this activity has already been completed. Review the HTML structure below.

  * Make sure you review the index.html activity as you write your CSS selectors.

<img width="683" alt="1" src="https://user-images.githubusercontent.com/102771343/208268967-ce807b6b-b540-4f72-8592-5c079c62d73c.png">


* In `style.css`, create a selector that targets the `heroGrid ID`.


<img width="547" alt="heroGrid-css-selector" src="https://user-images.githubusercontent.com/102771343/208269120-b53bd14f-c290-4bcf-97b8-c0a4b29b76ff.png">


* Add the following properties to define the overall size of the grid:

<img width="744" alt="grid-size-properties" src="https://user-images.githubusercontent.com/102771343/208270610-f817094f-8f98-489d-b545-725f95627b6f.png">

* Now that you have sized the CSS Grid, it’s time to add more CSS properties. Use the `grid-template-rows:`, `grid-template-columns:`, and `grid-template-areas`: properties to create the structure of the CSS Grid.

* The `#heroGrid` ID at the top of the page has two rows and two columns.

  * The first row and first column each occupy `75%` of their respective areas.

  * The second row and second column each occupy the remaining `25%` of their respective areas.

  * Use the values above for the `grid-template-rows:` and `grid-template-columns:` properties.

  * **CSS hint:** Do not use commas between percentages. 

* Hero grid layout visual:


<img width="733" alt="hero-grid-layout" src="https://user-images.githubusercontent.com/102771343/208270679-f1634048-92fd-4aff-9870-02c469f4dcb3.png">


* Next, add to your CSS: `#heroGrid{ grid-template-areas: }`.

* **Hint:** The `featuredProduct` occupies the top and bottom left areas, the `secondaryProduct` is in the top right, and the `CTA` is in the bottom right.

* Add content to the CSS Grid.

  * HTML reference:

<img width="786" alt="html-reference" src="https://user-images.githubusercontent.com/102771343/208270720-a7c8e487-3f05-4f28-9f69-fd660eebc430.png">

* Create three CSS selectors that target the IDs of each area within the grid from the HTML: `featuredProduct`, `secondaryProduct`, and `CTA`.

  * Within each selector, define the value for the `grid-area:` property so that each CSS selector and the CSS contained within it is associated with the correct area within the grid.

  * **Hint:** Spelling and capitalization in the syntax matter here, so pay attention.

* Add a `background-image:` to each `.heroGridArea` class selector using the images provided in the images folder.

* Add the following properties and values to the `#CTA ID` selector. These will be used to style content within this grid area.

  ![CTA Properties](images/CTA-properties.png)

* Notice the repeated `.heroGridArea` class on each grid area in `index.html`. You can use CSS to target all instances of that class and style each instance the same way.
Create a CSS selector that targets the `.heroGridArea` class and add the following CSS properties:

  ![heroGridArea Properties](images/heroGridArea-properties.png)

* Open `index.html` in your browser. It should almost look complete, except for the fact that the headline `div` isn’t in the right place.

* In order to align the headline `div`, add a `border: 5px solid #FF6200;`.

* Next, add a transparent `background-color:`. 

  * You could do this with a transparent image or you can use the  `rgba()` function to define red, green, blue, and alpha (opacity) values for a color.

  * Set the value for background-color to `rgba(255,255,255,0.8);`. 

  * This will set the background color to white at 80% opacity. 

* Position the headline `div` so that it’s floating above and between the `featuredProduct` and `secondaryProduct` grid areas.

* **Hint:** You will need to use `position: absolute;` along with top and right values to achieve this.

* Lastly, add a `z-index value` to move the `headline` `div` above its parent and then add `padding` to create some spacing.

* Now, finally, open index.html in your browser. You should see your final result—the grid you just built!

---

© 2022 edX Boot Camps LLC. Confidential and Proprietary. All Rights Reserved.
