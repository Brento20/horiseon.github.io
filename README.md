# READ ME - Horiseon Website 1.01



This update of the Horiseon website attempts to address HTML and CSS flow, improve loading time, improve Accessibility and optimise for search engins and was impliment following the below User story.

*User story: "**AS A** marketing agency **I WANT** a codebase that follows accessibility standards **SO THAT** our own site is optimized for search engines."*

**The following changes were done/attempted by Brenton Weaver - Brento20 - brenton.weaver@gmail.com**

 1. Accessibility and web Optimization
 2. HTML/body changes.
 3. .CSS stylesheet changes.
 4. MISC.
 5. Future improvments.

## Accessibility and web Optimization 

 - I added device width to the head meta HTML to improve readability on mobile and added a meta discription to help with general SEO. 
 - Matched the page < title > to the < H1 > to optimise for google.
 - Organised the H tags 1-6 where appropiate.
 - Added "alt" text to images.
- Added device width to the head meta HTML to improve readability on mobile and added a meta discription to help with general SEO. Images in the assest folder were too large and slowed loading speed, the original images are still in ./asset incase we need to revert but are not linked in the HTML and "-min" was added to new file names to identify compressed files.
See outline below:


|original| updated |
|--|--|
|search-engine-optimization.jpg (14.9MB) | search-engine-optimization-min.jpg (2.5MB)|
|online-reputation-management.jpg (6.9MB) | online-reputation-management-min.jpg (1MB) |
|social-media-marketing.jpg (14.2MB)| social-media-marketing-min.jpg (1.7MB)|
| digital-marketing-meeting.jpg (14.2MB) | digital-marketing-meeting.jpg (1.4MB)|

## HeadingHTML/body changes.


## .CSS stylesheet changes.
- Added a max width of 1100px (larger than any individual element) to the * css tag to keep the content sized correctly on desktop view.
- added a relitive position to the body css and a fixed position to the header tag. My goal was to keep the navigation prominant to help with accesability.
- Margins on the * tag changed to auto to center the content.


## MISC.

## Future improvments.

- Consider css animations for :hover for nav menu.
- set min widths to create a consistant experiance across viewport sizes.
- create contact form.