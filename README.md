
# Assignment 1: html-css-refactor

My initial approach was to scan through the html code adding comments to identify the structure of each div and give suggestions on what might need to be changed. Then I added alt text and title to most of the page images, changed the title from “website” to the company name, and then added a Meta Description as suggested by a <a href="https://neilpatel.com/blog/website-source-code-seo/">Neil Patel article</a> from 2014. I followed up by adding and editing comments for new planned edits.

My next plans were to consolidate .benefit-lead, .benefit-brand, and .benefit-brand into a single class called .benefit-section. I followed up by applying the same logic to the h3 and img tags. This cut the number of classes from 10 to 4.

I applied this approach to the classes that made up the .content container. This cut the number of classes from 10 to 6. The class names were too descriptive (i.e. search-engine-optimization) and took up a lot of space in addition to their general redundancy. I consolidated these into a single tag called .services-section.

Next, I fixed the navigation links in the html header so that clicking on them would send the user down to the referenced container on the page. I did so by making sure div containers for social media marketing, search engine optimization, and online reputation management were assigned id’s for navigation. Renamed .services-section and cleaned up some comments and redundant classes.

The next wave of changes included rearranging elements and classes on the stylesheet so that they followed the semantic structure of each html section, adding  new comments in CSS, and changed some divs using header, section, nav, and aside semantic tags. Lastly, I added a title attribute to .hero class.

The last wave of changes included changing the div containing the footer to a footer semantic tag, changed the remaining divs to sections, adjusting the color of the .seo class to a slightly bluer tint, and writing a description for this README.md file.