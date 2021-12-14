# Mind and Body Maintenance

Mind and Body Maintenance is a site that I created to share some of my favourite sources on sleep, exercise and mindfulness. These sources will range from articles, journals, YouTube videos and websites from various experts and content creators. There is also an opportunity for users of the site to suggest their own content and suggestions for the site's function and appearance. 

![home-page](https://user-images.githubusercontent.com/91907661/145724883-0ebc6605-9b31-4fdd-94a5-27d77ab68d59.png)

## Features 

Below is a list of features that I have on this site and will detail each indivdually - there is a nav menu for each page, and there are five pages in total - Home, Sleep, Exercise, Mindfulness and a suggestions page. The home page has an aside which also loads up a YouTube video for each section. Within the Sleep, Exercise and Mindfulness pages, there is an iframe, table and list items which link to various external sources. The is a form for the Suggestions page to record data entered by users of the site. Ther is a also a footer which links the user to social media pages.

### Existing Features

- __Navigation Bar__

  - The Nav Menu bar is located on all pages and allows seamless flow for the user to access all the content on the site

![nav-menu](https://user-images.githubusercontent.com/91907661/145723593-3abdadbc-c308-4ef7-9d8e-6ed93b71f8ff.png)


- __Social Media and Back to Top__

  - There will be links to the website Social Media pages located in the footer
  - There is also a back to top link which can be clicked to reurn to Nav menu bar at any time

![back-socialmedia](https://user-images.githubusercontent.com/91907661/145724575-6b2e2cb9-8736-4a44-a0da-33ec5b712fbd.png)


- __Title Links__

  - You can click on the the Mind and Body Maintenance link and it will take you to the home page at any time, you can also click on the title for Ideas for healthy minds and bodies, and this will take you directly to the Suggestions Page, these title links apear on all pages.


![title-links](https://user-images.githubusercontent.com/91907661/145724081-9e58f592-7c15-4f93-a281-ba0bf4365b33.png)

- __Home Page Content__

  - The content on the home page includes some introduction info and links within each section to take you directly to the page
  - There is also a video that loads up automatically that you can choose to umute. Each video gives a good insite into what the correlating page is about


![home-page-content](https://user-images.githubusercontent.com/91907661/145724460-fcb18518-bc4e-4b08-8a22-67585d776290.png)

- __Sleep, Exercise and Mindfulness Pages__

  - Each section will follow the same layout. Below, the Sleep page of the site is shown as an example 
  - Below a short paragraph, an iframe will load in addition to a table of sources section off in different categories: Source, Video and Article.
  - There is also a list of more detailed studies and journals for more in depth study
  - This section can also be update by way of newly suggested content from myslef or other users on the Suggestions page 

![sleep-exercise-mindfulness-content](https://user-images.githubusercontent.com/91907661/145724847-c3522d11-7450-41c9-ba89-ba32611bdaec.png)


- __Suggestions Page__

  - This page will allow the user to enter some basic info on the form - drop down for age, text input for name and email address. There will be some radio button questions in there as well. All in all, it takes no time to complete and all these questions are required to be able to submit the form
  - The is a text box area for the user to enter suggestions and additional content for for the site, which I can implement and and give credit to the person suggesting it, if they want me to do so.

![suggestions-form](https://user-images.githubusercontent.com/91907661/145725027-bcb0b194-2261-4241-b489-1f37b94047a6.png)

<!--
For some/all of your features, you may choose to reference the specific project files that implement them.
In addition, you may also use this section to discuss plans for additional features to be implemented in the future:

### Features Left to Implement

- Another feature idea
-->

## Testing 

I have included the following errors and warnings I received from Validation testing and how and if they needed fixing:

- __Errors__
- The frameborder attribute on the iframe element is obsolete. Use CSS instead.
  - I have remnoved the obselete attribute from all instances of this element
- Bad value assets/images/woman meditating 2.jpg for attribute src on element img: Illegal character in path segment: space is    not allowed.
  - This has now been changed to proper format

- __Warnings__
- The name attribute is obsolete (for the back to top function). Consider putting an id attribute on the nearest container instead.
  - Removed name as suggested and feature still works
- Section lacks heading. Consider using h2-h6 elements to add identifying headings to all sections.
  - I have used flex with CCS on my section which contains the image, paragraph, aside and Youtube Video. A header for these sections didn't fit with plan for layout
- Value Error : padding-left Too many values or values are not recognized: 0 10px 0 10px
  - Have changed to 0 10px and removed osbolete values

### Validator Testing 

- HTML
  - No errors were returned when passing through the official [W3C validator](https://validator.w3.org/nu/?doc=https%3A%2F%2Fdavid-maura-rodgers.github.io%2FDavid.Rodgers-html-css-Port.Proj.%2F)
- CSS
  - No errors were found when passing through the official [(Jigsaw) validator](https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Fdavid-maura-rodgers.github.io%2FDavid.Rodgers-html-css-Port.Proj.%2F&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=en)

### Unfixed Bugs

Not a bug as such, just a very small difference in the size of the sleeping woman image and the 2 images below (exercise and woman meditating) This is likely due to the content being ina a flex layout. I have tried everything I know, looked at resources online and there seems to be no error or difference in the html or CSS contolling them.

## Deployment

- The site was deployed to GitHub pages. The steps to deploy are as follows: 
  - In the GitHub repository, navigate to the Settings tab 
  - From the source section drop-down menu, select the Master Branch
  - Once the master branch has been selected, the page will be automatically refreshed with a detailed ribbon display to indicate the successful deployment. 

The live link can be found here - https://david-maura-rodgers.github.io/David.Rodgers-html-css-Port.Proj./


## Credits 

Below contains the sources that are included in my site. 

### Content 

- __HTML Code__
  - For back to top page link: https://www.computerhope.com/issues/ch001475.htm
  - Fonts come from: https://fontawesome.com/
  - For links in table cells: https://stackoverflow.com/questions/10070232/how-to-make-a-cell-of-table-hyperlink
  - To esnure that all radio buttons are required before table is submitted: https://stackoverflow.com/questions/49798482/why-can-i-check-multiple-radio-buttons/49798515

- __CSS Code__
  - 

- __Info and Sources__
  -

### Media

- The photos used on the home and sign up page are from This Open Source site
- The images used for the gallery page were taken from this other open source site