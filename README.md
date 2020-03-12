# Code Refactor

## Technologies Used
- HTML - used to create elements on the DOM
- CSS - styles html elements on page
- Git - version control system to track changes to source code
- GitHub - hosts repository that can be deployed to GitHub Pages
- Adobe Photoshop - used to resize images

## Summary 
This project is to refactor an existing webpage to make it accessible. In order to accomplish this, numerous adjustments to the source code were required including, but not limited to:

1) Cleaning up the code to properly align opening and closing tags, along with lining up similar elements
2) The addition of ` alt ` tags to all images to meet accessibility standards
3) Adding the company name to the page title
4) Specifying semantic HTML elements to the code
5) Ensuring all headers are sequentially nested
6) Grouping and renaming classes within CSS styling, and updating relevent class name in HTML code


## Code Snippet

```html
<html>

    <!-- replace div with content  -->
    <content class="content">    
        <!-- add id=search-engine-optimization  -->
        <div class="main">
            <!-- add alt tag and adjust image source to correspond with sizing adjustment to source image -->
            <img src="./images/search-engine-optimization.jpg" class="float-left" alt=""/>
                <h2>Search Engine Optimization</h2>
                    <p>
                      The dominance of mobile internet use means that users are searching for the right business as they travel, shop, or sit on their couch at home. Search Engine Optimization (SEO) allows you to increase your visibility and find the right customers for your business.
                    </p>
        </div>

        <div class="main">
            <!-- add alt tag and adjust image source to correspond with sizing adjustment to source image -->
            <img src="./images/online-reputation-management.jpg" class="float-right" alt=""/>
                <h2>Online Reputation Management</h2>
                    <p>
                      The web is full of opinions, and some of these can be negative. Social media allows anyone with an internet connection to say whatever they want about your business. Online Reputation Management gives you the control over what potential customers see when they search for your business.
                    </p>
        </div>

        <div class="main">
            <!-- add alt tag and adjust image source to correspond with sizing adjustment to source image -->
            <img src="./images/social-media-marketing.jpg" class="float-left" alt=""/>
                <h2>Social Media Marketing</h2>
                    <p>
                      Social media continues to have a sizable influence on buying habits. Social media marketing helps you determine which platforms are suited to your brand, using analytics to find the right markets and increase your lead generation.
                    </p>
        </div>
    </content>

</html>

```

```css

/* Grouped SEO, online rep, and social media marketing img elements together */

.main { 
    margin-bottom: 20px;
    padding: 50px;
    height: 300px;
    font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
    background-color: #0072bb;
    color: #ffffff;
}

/* Grouped SEO, online rep, and social media marketing img elements together */

.main img {
    max-height: 200px;
    width: auto;
}

/* Grouped SEO, online rep, and social media marketing h2 elements together */

.main h2 {
    margin-bottom: 20px;
    font-size: 36px;
}

```

## Acknowledgements
Thank you to Michael Downs for providing the resized images, along with other guidance in the refactoring of code, along with the support of Jerome Chenette, Kerwin Hy, Mahi Manikandan, Will Gibson, and Stephon Autrey in fielding questions or confirming ideas/solutions.

## Author Links
[LinkedIn](https://www.linkedin.com/in/brad-davis-7885884/)
[GitHub](https://github.com/davisbradleyj)