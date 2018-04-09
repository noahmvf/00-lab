##### How did you determine which rules should be placed in each new CSS file?

I started with the base.css file, and ensured that only the most general elements and styling were added. I then focused on the layout.css file, where I input all styling that solely focused on layout. Even if an element was specified by a class or id, and was more specific than a nav or footer, I included it in the layout if the styling for that particular designation was solely layout focused. Third, I added more specific styling such as coloring, and multiple styles on smaller elements to the modules.css

---

##### Did you do any refactoring of the existing CSS? If so, briefly explain what you did and why.
I refactored some of the ways in which the tags were targeted in the CSS. For example, changing 'main p' to 'article p' to ensure that if other 'p''s are added to the 'main' they won't all be styled the same. I also specified the 'nav' to be the 'header-nav' in case other navigation is to be added at some other point on the page.

(Put your answer here)
