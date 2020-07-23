# Daniel Lew Assessment for LS_209

You'll find all necessary the necessary files in this folder,

- `index.html` is where the html code is located
- `style.css` is where the css code is located
- I used the `whitespace-reset.css` from earlier projects in the course.
- Passed W3C HTML Validation and W3C CSS Validation (besides a few expected warnings)


### A few notes

Regarding mobile `@media` queries, in my browsers it shows the display as everything fits even though nothing is resized (it displays as a shrunken version of the main page), I'm not sure if this is actually how the mobile will look, or if the `335` pixel width for the navigation menu will stay as is and consume the majority of the window. I treated it as I did with the `max-width: 768` media query where I would hide the navigation sidebar and display the hamburger menu-toggle button.  

I also implemented a resize for the edit form as the window got smaller, and moved the fixed position relating to the entire window rather than just the main content section. This way the form would always be visible and displayed center in the screen when the main content section is too small.  

I checked across multiple browsers to make sure that I wasn't allowing browsers to implement default styles.  

For the select drop down boxes the assignment mentioned to get rid of the `border-radius: 5px` default for the boxes. I tried to find a way to change the drop-down menu rounded corners but I couldn't find a solution for that. I'm not sure if that's what the assignment was even asking for or if it just wanted the box itself to not have rounded corners.  

With letter spacing I found it difficult to emulate the design file given as some words seemed to have varied spacing in itself, but I did the best approximation I could.  

