# 01_Code_Refactor_NN
BootCamp Homework - 01 HTML CSS Git: Code Refactor

## The Challenge
In today's age, marketing agency requires existing websites to be accessible to all readers. 
Web accessibility is profitable for companies, as they rank higher in search engines like Google.
We are going to refractor a code for an existing web application to organize them in a semantic structure and increase its efficiency.

![](./develop/assets/images/webpage.png)

## User Story

```
As A marketing agenecy
I WANT a codebase the follows accesibility standards
SO THAT our own site is optimized for search engines
```

## Acceptance Criteria

```
GIVEN a webpage meets accessibility standards
WHEN I view the source code
THEN I find semantic HTML elements
WHEN I view the structure of the HTML elements
THEN I find that the elements follow a logical structure independent of styling and positioning 
WHEN I view the image elements
THEN I find accessible alt attributes
WHEN I view the heading attributes
THEN They fall in sequential order
WHEN I view the title element
THEN I find a concise, descriptive title
``` 

## The Process
To satisfy our client's needs, we had to:
- Identify a proper semantic structure for the HTML and CSS file
- Provide descriptive comments for each section of the HTML and CSS file
- Modify the HTML and CSS file in a way that would fit a proper semantic structure
- Combine multiple rules into one rule

Specific modifications to the HTML file

```
Changed title to company's name for Page's title
Changed div to header for Page's Header
Changed div to main for Page's Main Content
Changed div to aside for Page's Additional Content
Changed div to footer for Page's Footer
Include alt properties with related description for each image 
Added an id for search-engine-optimization so that the web application would scroll down when users click it
```

Specific modifications to the CSS file

```
Added structural comment for each section of the HTML file
Rearrange some rules to fit a proper semantic structure
Simplified multiple rules into one rule:

#search-engine-optimization,
#online-reputation-management,
#social-media-marketing {
    margin-bottom: 20px;
    padding: 50px;
    height: 300px;
    font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
    background-color: #0072bb;
    color: #ffffff;
}

#search-engine-optimization img,
#online-reputation-management img,
#social-media-marketing img {
    max-height: 200px;
}

#search-engine-optimization h2,
#online-reputation-management h2,
#social-media-marketing h2 {
    margin-bottom: 20px;
    font-size: 36px;
}

#benefit-lead,
#benefit-brand,
#benefit-cost {
    margin-bottom: 32px;
    color: #ffffff;
}

#benefit-lead h3,
#benefit-brand h3,
#benefit-cost h3 {
    margin-bottom: 10px;
    text-align: center;
}

#benefit-lead img,
#benefit-brand img,
#benefit-cost img {
    display: block;
    margin: 10px auto;
    max-width: 150px;
}
```

## The Result
After refractoring the existing code, we were able to provide an accessible, efficient, and stuctured project for our client. 

## Submission
This project was uploaded to GitHub at the following respository link:
[https://github.com/nhanng19/challenge01](https://github.com/nhanng19/challenge01)

Depolyed Web Application Link:
[https://nhanng19.github.io/challenge01/develop/index](https://nhanng19.github.io/challenge01/develop/index)

