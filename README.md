# BLACK BUSINESS IN READING


![image](https://user-images.githubusercontent.com/68662449/141664010-09ae9c53-0d91-4bdc-881b-a67bd58e2bbf.png)


## Author
Obiageli Onyekpe

## Project Overview
- Include a picture of site that shows it in responsive states and links to deployed code: http://ami.responsivedesign.is/
My  idea is to provide value to users by providing easy and direct access to household, personal care and food products ordinarily used and prevalent in black and ethnic minority communities. I decided to focus on the market in, Reading, UK, the town where I live.
- [deployed website](https://oonyekpe.github.io/black-businesses-in-reading/)



## UX


#### Images

I walked around ethnically diverse areas of my town and took pictures of black-owned businesses. I feel these images give a real-life impact to users and their vibrant colours would invite potential customers to the businesses.

#### Animations and Transitions

The home page has a zoom in and out effect on the mural hero image.

The footer icons rotate to the left and zoom in when hovered over, and change colour.

### Wireframes

I created a Word document and saved it as a PDF as my [wireframe](https://github.com/oonyekpe/black-businesses-in-reading/blob/main/Project1-BlackBusinessInReading.pdf).

### Features

In this section, you should go over the different parts of your project, and describe each in a sentence or so and how they tie into  your user stories.

#### Implemented Features

For some/all of your features, you may choose to reference the specific project files that implement them, although this is entirely optional.

It's easiest to break this section down into the header, footer, and each page/layer of your website. Call out any differences for mobile vs desktop presentations, include a screenshot of the implemented feature.

Don't forget your 404 error page.

#### Future Features

Use this section to discuss plans for additional features to be implemented in the future:

If you end up not developing some features you hoped to implement, you can include those in this section.


## Testing

In this section, you need to convince the assessor that you have conducted enough testing to legitimately believe that the site works well. Essentially, in this part you will want to go over all of your user stories from the UX section and ensure that they all work as intended, with the project providing an easy and straightforward way for the users to achieve their goals.

If this section grows too long, you may want to split it off into a separate file and link to it from here.

### Validation Testing
You should try to ensure you code is valid and follows proper indentation.  In this section you should write up any websites you used to validate your code. As your projects becomes more complex these tools may change.

- [CSS Validator](https://jigsaw.w3.org/css-validator/) Note, any error associated with root: color variables were ignored.
- [HTML Validator](https://validator.w3.org/)

### Cross Browser and Cross Device Testing
Create a table that lists out what devices, browsers, and operating system you tested your application on and a brief description of why you chose the mixture you did. The point is to prove that you looked at the site across various browsers, operating systems, and viewport breakpoints.

| TOOL / Device                 | BROWSER     | OS         | SCREEN WIDTH  |
|-------------------------------|-------------|------------|---------------|
| real phone: motog6            | chrome      | android    | XS 360 x 640  |
| browser stack: iPhone5s       | safari      | iOs        | XS 320 x 568  |
| dev tools emulator: pixel 2   | firefox     | android    | SM 411 x 731  |
| browserstack: iPhone 10x      | Chrome      | iOs        | SM 375 x 812  |
| browserstack: nexus 7 - vert  | Chrome      | android    | M 600 x 960   |
| real tablet: ipad mini - vert | safari      | iOs        | M 768 x 1024  |
| browserstack: nexus 7 - horiz | firefox     | android    | LG 960 x 600  |
| chrome emulator: ipad - horiz | safari      | iOs        | LG 1024 x 768 |
| browserstack                  | Chrome      | windows    | XL 1920 x 946 |
| real computer: mac book pro   | safari 12.1 | Mohave     | XL 1400 x 766 |
| browserstack                  | IE Edge 88  | windows 10 | XL 1920 x 964 |

### Manual Testing

For any scenarios that have not been automated, test the user stories manually and provide as much detail as is relevant. A particularly useful form for describing your testing process is via scenarios, such as:

1. Contact form:
    1. Go to the "Contact Us" page
    2. Try to submit the empty form and verify that an error message about the required fields appears
    3. Try to submit the form with an invalid email address and verify that a relevant error message appears
    4. Try to submit the form with all inputs valid and verify that a success message appears.
    
Here is a [Manual Testing Template](https://docs.google.com/spreadsheets/d/1vc1IVL-ydQwWeWMqnk_GRox6HE6qxDLpchGse8Crayo/edit#gid=296578096) that you can use as a starting point to keep track of your testing efforts. Make a copy of it in your own account and update as needed to reflect the browsers you are testing and features.  

It's ok to spot check specific functionality across devices and browsers but each page should be viewed as a whole for each device/browser combo at least once.

A quick way to check if items are exceeding the screen width of a project is to run this javascript in the console for various screen emulations:

```
var docWidth = document.documentElement.offsetWidth;
[].forEach.call(document.querySelectorAll('*'),function(el){if(el.offsetWidth > docWidth){console.log(el);}});
```

### Defect Tracking

You should mention  any  bugs or problems you discovered during your testing, even if you haven't addressed them yet.

Here is a [Defect Tracking Template](https://docs.google.com/spreadsheets/d/1tYB4X4wTCNEW_Y1no3hsGbclh2bLokl_I5Ev3s5EuJA/edit?usp=sharing) you use as a starting point to track defects. Make a copy of the sheet to your own account and update the Features sheet to match your project. 


### Defects of Note
Some defects are more pesky than others. Highlight 3-5 of the bugs that drove you the most nuts and how you finally ended up resolving them.


### Outstanding Defects
It's ok to not resolve all the defects you found. If you know of something that isn't quite right, list it out and explain why you chose not to resolve it.

## Accessibility

Accessibility testing is aimed to make sure that those with visual or physical disabilities can still browse your website. Some users have had strokes or accidents that make it difficult to use a mouse so they use keyboard keys to tab through sites. Others use screen readers that rely on HTML tags to help the user navigate quickly through the site to find information they want, others have color blindness or contrast issues. It's the law to provide services 
Here's a [site](https://www.w3.org/WAI/fundamentals/accessibility-intro/#:~:text=Accessibility%20is%20Important%20for%20Individuals%2C%20Businesses%2C%20Society,-The%20Web%20is&text=That%20is%2C%20the%20accessibility%20barriers,older%20people) where you can learn more about accessibility and the internet.

### Lighthouse Audits
You should run your deployed website pages through lighthouse's audit to check performance, accessibility, best practices and SEO scores. You should aim to get 85 or higher score. 
https://web.dev/measure/  If you have lower scores, read the report and follow the links to address the flagged issues. You can run this tool from Chrome Dev Tools too against your local machine, but the performance will the worst (I personally ignore my performance results unless it's deployed code. I hope for > 60 on that mark, but > 85 on the other 3)

### Keyboard Navigation
Another way to accessibility test you site is to try to click on the browser and see what happens if you use the tab, arrow and enter keys. Does it work well or does the user get stuck?


## Deployment
My website is deployed to GitHub pages, these are the steps I took:

1. Click on setting button in GitHub repository

![image](https://user-images.githubusercontent.com/68662449/141663801-49edebe2-2669-48f1-844e-603b1a90b251.png)

2. Scroll down to "Page" on left handside of page, and click on it

![image](https://user-images.githubusercontent.com/68662449/141663832-eb234481-2986-4c8e-b673-ec19518d4030.png)

3. On "Page", go to the sources button and select "main"

![image](https://user-images.githubusercontent.com/68662449/141663861-da2422d3-dabc-491e-b38c-ed1ac12b25b6.png)

4. Click on "save" button

![image](https://user-images.githubusercontent.com/68662449/141663877-6090ae96-26f5-43d3-8ee3-bd788619d15a.png)

5. You should see a success message with your deployed url

![image](https://user-images.githubusercontent.com/68662449/141663970-ca524b29-7ecf-4f43-b765-1cf4ba5c48e1.png)




## Credits




### Content

I got contents for my website by reading pages in the following links:
1.	https://www.getreading.co.uk/news/reading-berkshire-news/truth-history-readings-black-community-20344840
2.	https://www.readingmuseum.org.uk/blog/readings-early-black-history
3.	https://londontheinside.com/black-owned-businesses-in-london/
4.	https://www.goodfind.io/black-owned-sustainable-brands
5.	https://www.getreading.co.uk/whats-on/shopping/meet-young-reading-fashion-designer-20854074
6.	https://www.locallife.co.uk/c-r/the-cape-za-reading.asp
7.	https://www.tripadvisor.co.uk/Restaurants-g186363-c1-Reading_Berkshire_England.html
8.	https://www.google.co.uk/



### Media

All images were photographed by me with my phone camera, except for The black history mural at Reading Central Club [Get Reading](https://www.getreading.co.uk/news/reading-berkshire-news/truth-history-readings-black-community-20344840)

### Acknowledgments

- I used CodeInstitute's example project Love Running as a starting point. 
- My mentor Malia helped me immensely especially with mark down. I couldn't have completed this write up without her attentive and personable approach and support which helped me immensely.
- I used the flex grid from [Tania Rascia](https://codepen.io/taniarascia/pen/rOLEGe/).

