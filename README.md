# HW-1-Code-Refactor

![languages used badge](https://img.shields.io/github/languages/count/dorrianweber/horiseon_code-refactor)
![top language badge](https://img.shields.io/github/languages/top/dorrianweber/horiseon_code-refactor?color=darkred)


# The Assignment
This week for homework, we were given a mock on-the-job ticket in which a marketing company hired us to ensure that the codebase for their website was up to the proper accessibilty standards.

To accomplish this, I made the following changes:

* Added highly-descriptive alt-text to all images and logos in the HTML file, except the large background image towards the top of the page (see: Issues section).

* Consolidated selectors in stylesheet that had the same attributes & values.

* Re-ordered selectors in stylesheet to match order they appear in HTML file.

* Changed multiple `<div>` tags to more specific semantic elements.

* Added "whitespace" to the code to improve readability.

* Added comment lines in both the HTML file & the style sheet.

* Changed title element to the company's name.

# Issues

The first thing I took a stab at with this project was adding alt text to all the images & logos. Easy enough, right? Well, it was, until I got to the large image of the business meeting just under the header. Unsure of how to add alt text to the style sheet...
```
.hero {
    height: 800px;
    width: 100%;
    margin-bottom: 25px;
    background-image: url("../images/digital-marketing-meeting.jpg");
    background-size: cover;
    background-position: center;
}
```
I attempted to change the way the image was addded to page by using an `<img src>` element in the HTML file, thinking this would allow me to easily add alt text in the way with which I was already familiar.

However, when I made this change, the styling of the image went completely haywire. I couldn't figure out how to resize it, and upon asking for help with this from my instructors & classmates I was told it wasn't that important to mess with seeing as the image was purely there for decorative purposes and didn't communicate any important information to the user. So I decided to just reverse my changes and move on.

# Looking Forward

If I come back to tinker with this project, I want to figure out how to:
* fix the errors I caused when I tried to change the method in which the aforementioned image was incorporated.
* figure out how to make the webpage styling look nice when you change the window size, on a mobile device, etc.

<img src="./assets/completed_screenshot.png" alt="Screenshot of Horiseon webpage">

# Installation

Simply follow the link and view the webpage.

# Usage

Clicking any of the three navigation links in the top right-hand corner shifts your window to view their corresponding sections in the body of the page.


# Credits

Thanks to my wonderful TA's Zac Warner & Ryan Skog for helping me with this homework assignment.