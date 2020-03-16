
# 01 Assignment 1: html-css-refactor

My initial approach was to scan through the html code adding comments to identify the structure of each div and give suggestions on what might need to be changed. Then I added alt text and title to most of the page images, changed the title from “website” to the company name, and added a Meta Description (CITE YOUR SOURCE FOR THIS TIP NOT TAUGHT IN CLASS). I followed up by adding and editing comments for new planned edits.

My next plans were to consolidate .benefit-lead, .benefit-brand, and .benefit-brand into a single class called .benefit-section. I followed up by applying the same logic to the <h3> and <img>  tags. This cut the number of classes from 10 to 4.

I applied this approach to the classes that made up the .content container. This cut the number of classes from 10 to 6. The class names were too descriptive (i.e. search-engine-optimization) and took up a lot of space in addition to their general redundancy. I consolidated these into a single tag called .services-section.

Next, I fixed the navigation links in the html header so that clicking on them would send the user down to the referenced container on the page. I did so by making sure div containers for social media marketing, search engine optimization, and online reputation management were assigned id’s for navigation. Renamed .services-section and cleaned up some comments and redundant classes.

The next wave of changes included rearranging elements and classes on the stylesheet so that they followed the semantic structure of each html section, adding  new comments in CSS, and changed some divs using header, section, nav, and aside semantic tags.



# 01 HTML CSS Git: Code Refactor

One of the most common tasks for front-end and junior developers is to take existing code and refactor it to either meet a certain set of standards or implement a new technology. Web accessibility is an increasingly important consideration for businesses, ensuring that people with disabilities or socio-economic restrictions have access to their website, and helping them avoid litigation.

Your task is to refactor an existing webpage to make it accessible. An important rule to follow when working with someone else's code is the Scout Rule:

> Always leave the code you are editing a little cleaner than you found it.

To impress clients, you should always go the extra mile and improve their codebase for long term sustainability. Ensure that all links are functioning correctly and clean up the CSS to make it more efficient, consolidating CSS selectors and properties, organizing them to follow the semantic structure of the HTML elements, and including comments before each element or section of the page.

## User Story

```
AS A marketing agency
I WANT a codebase that follows accessibility standards
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
THEN they fall in sequential order
WHEN I view the title element
THEN I find a concise, descriptive title
```

## Review

You are required to submit the following for review:

* The URL of the deployed application.

* The URL of the GitHub repository. Give the repository a unique name and include a README describing the project.

- - -
© 2019 Trilogy Education Services, a 2U, Inc. brand. All Rights Reserved.
