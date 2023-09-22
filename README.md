# Horisean Consultancy 

## Technology Used 

| Technology Used | Resource URL | 
| ------------- |:-------------:| 
| HTML | [https://developer.mozilla.org/en-US/docs/Web/HTML](https://developer.mozilla.org/en-US/docs/Web/HTML) | 
| CSS | [https://developer.mozilla.org/en-US/docs/Web/CSS](https://developer.mozilla.org/en-US/docs/Web/CSS) | 
| Git | [https://git-scm.com/](https://git-scm.com/) | 

## Description 
With this project, making the site fall within accessibility guidlines as well as condensing aspects of the code for simplicity's sake was the main goal. While working on this project

[Visit the Deployed Site](https://youtu.be/BFyeuLhjcPY) 

![meeting.png](assets/images/Meeting.png)


## Code Refactor Example 

What are the steps required to install your project? Provide a step-by-step description of how to get the development environment running. 


 
  <!-- removed image from css and added here to html -->

    <img class="marketing-image" src="./assets/images/digital-marketing-meeting.jpg" alt="image of a team in a meeting room discussing potential options and outcomes"/>
    <!-- added alt  -->
    <!-- changed from Div to Section -->
    <section class="content"> 
        <article id="search-engine-optimization" class="search-engine-optimization">
        <!-- changed to article -->
        <img src="./assets/images/search-engine-optimization.jpg" class="float-left" alt="image of a book with artistic cover reading search engine optimization"/>
        <!-- added alt -->
            <h2>Search Engine Optimization</h2>
            <p>
                The dominance of mobile internet use means that users are searching for the right business as they travel, shop, or sit on their couch at home. Search Engine Optimization (SEO) allows you to increase your visibility and find the right customers for your business.
            </p> 
            <!-- changed to article -->
        </article>
        <article id="online-reputation-management" class="online-reputation-management">
            <img src="./assets/images/online-reputation-management.jpg" class="float-right" alt="image of a laptop computer showcasing a diagram reporting reputation"/> 
            <!-- added alt -->

Converting the above non-semantic div with the class of 'header' to 'nav' [<header> semantic element](https://www.w3schools.com/html/html5_semantic_elements.asp). 


<header>
        <h1>Hori<span class="seo">seo</span>n</h1>
        <nav>
            <ul>
                <li>
                    <!-- repaired link -->
                    <a href="#search-engine-optimization">Search Engine Optimization</a>
                </li>
                <li>
                    <a href="#online-reputation-management">Online Reputation Management</a>
                </li>
                <li>
                    <a href="#social-media-marketing">Social Media Marketing</a>
                </li>
            </ul>
        </nav>
    
        <!-- changed from Div to Nav -->
        <!-- added closing Header -->
    </header>

 

The changes I made required  additional modification to the CSS selector such as header. I made it so it no longer targeting the element on the page with the class of 'header' but instead the css selector targeting the 'header' element : 

```css 
header { 
padding: 20px; 
font-family: 'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif; 
background-color: #2a607c; 
color: #ffffff; 
} 
``` 


## Learning Points 

This was an interesting aspect of the bootcamp, as I was completely unaware of the concept of accessibility for websites.
This is a good place to Explain what you Learned by creating this application. 
This is a great way to remind about all of the Complex Skills you now have. 
If the user is less experienced than you: 
They will be impressed by what you can do! 

If the user is more experienced than you: 
They will be impressed by what you can do! 

Remember, it is easy to forget exactly how Valuable and Impressive your skills are, as well as How Much You’ve Learned! 
So quantify that here! 


## Author Info
Armand Araujo
Age: 28
Location: Santa Barbara, CA

 
* [LinkedIn](https://www.linkedin.com/in/armand-araujo-a82ba2291/) 
* [Github](https://github.com/Armand57araujo) 


## Credits 
