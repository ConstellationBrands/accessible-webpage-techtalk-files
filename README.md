# accessible-webpage-techtalk-files
## by Mark Foster

## Introduction
The files in this repo go with a tech talk I am giving at WicHacks 2022: _Build and host an accessible web page in 30 minutes_  This is a beginner-level talk to help folks learn how to build a simple, accessible web page from scratch and host it on Netlify.  If you notice a mispelling or other mistake please send a pull request. :)

Imagine we have been sent back in time to help Katherine Johnson (NASA) build a portfolio web page.  We want to make sure it highlights her accomplishments and is accessible to users with impairments.

We will start with an empty HTML file in Visual Studio Code (VSS) and build an accessible web page from the ground up using semantic HTML.  The included Katherine.Johnson.md file provides some interesting content about Katherine Johnson we can copy-paste into our HTML.

## Talk Outline

### Let's get started
* Who is [Katherine Johnson](https://en.wikipedia.org/wiki/Katherine_Johnson) AKA "human computer"?
* What is [HTML](https://www.w3.org/standards/webdesign/htmlcss)?
* Start Visual Studio Code and create an empty index.html file

### Create a hello world page
* HTML ```<!DOCTYPE html>``` Declaration
* Top level elements: **html**, **head**, **title**, **body**
* Basic elements: **h1-h6**, **p**, **br**
* Images: **img** Use the **alt** property on **img** elements to provide a description of the image and leave it empty if the image is not important.
* Non semantic elements for positioning or styling: **div**, **span**

### Semantic elements - Screen Reader Friendly!
* **header** Holds header content for the page
* **nav** Navigation/menu
* **article**, **section**, **main**
* **details**
    ```
    <details>
        <summary>Summary</summary>
        <p>details go here</p>
    </details>
    ```
* **progress** Use to show progress so user knows something is happening
* **button** Use the button element to define buttons instead of div elements
* **footer** Hold footer content for the page
* **figure**, **figcaption**
* **dl**, **dt**, **dd** Definition lists
* **tables** Use tables for tabular data.  Not page layout!
* **label** Use on forms to label **input** fields.  Link by **id** or wrap **input** elements.

### Accessibility considerations
* Use good contrast/color contrast so users can easily read text.
* Use **tabIndex** to guide users through the page content.
* Use focus/hover so users can see where they are when tabbing throught the page.
* Accessibility linting tools are available for Visual Studio Code I.e., axe.
* @media(prefers-reduced-motion) can be used to disable animations if the user prefers.
* Avoid modals or ensure they are screed reader friendly
* Install a screen reader extension and test!

## HTML Resources
* [HTML Standard](https://html.spec.whatwg.org/)
* [W3Schools.com](https://www.w3schools.com/)
* [MDN Web Docs](https://developer.mozilla.org/en-US/)

## Accessibility Resources
* [W3C Web Accessibility Initiative (WAI)](https://www.w3.org/WAI/)
* [Deque: Creators of the Excellent axe DevTools and free browser extensions](https://www.deque.com/)
* [Accessibility For Everyone by Amy Kapernick on LevelUpTutorials - Pay course but very good.](https://leveluptutorials.com/)
* [Digital Accessibility Foundation Free Online Course](https://www.w3.org/WAI/fundamentals/foundations-course/)

## More info on Katherine Johnson
* [Katherine Johnson's Website](https://katherinejohnson.net/)
* [Katherine Johnson on Wikipedia](https://en.wikipedia.org/wiki/Katherine_Johnson)
* [Reaching for the Moon: The Autobiography of NASA Mathematician Katherine Johnson on Amazon](https://www.amazon.com/Reaching-Moon-Autobiography-Mathematician-Katherine/dp/1534440836)
* [Hidden Figures Book and Movie](https://www.hiddenfigures.com/)
* [Katherine Johnson: Computer to the Stars](https://hackaday.com/2018/02/28/katherine-johnson-computer-to-the-stars/)
* [NASA.gov Katherine Johnson Biography](https://www.nasa.gov/content/katherine-johnson-biography)
  
