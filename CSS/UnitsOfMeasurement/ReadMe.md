
noteId: "c62b4760098911f0ab2617f08ed8ccd8"
tags: []

# Units of Measurement
- Css provides various units of specifying length, size and positioning of elements.
- This unit can be categorized into into absolute and relative units.

**1. Absolute Units**
- These units have fix units regardless of screen size or parent element.
**Common Used Absolute Units**
2. ```cm (centimeters)``` - Rarely used in screen design.
3. ```mm (millimeters)``` - More common in print designs.
4. ```in (inches)``` - 1 inch = 96px = 2.54cm
5. ```pt (points)``` - 1pt = 1/72 of inch
6. ```pc (picas)``` - 1pc = 12pt = 1/6 inch

**NB: Use absolute units for:**
- Print stylesheets
- When exact dimensions are needed (e.g., invoices, certificates)

**2. Relative units**
- These units scale relative to another measurement e.g parent element or viewport
1. ```em``` - relative to font-size of parent element. 
2. ```rem``` - relative to font-size of root element. 
3. ```%``` - relative to % of parent element. 
4. ```vw``` - relative to 1% of viewport width. Best for responsive design.
5. ```vh``` - relative to 1% of viewport height. Used to make full-height sections.
6. ```vmin``` - smaller of vw or vh. Adapts better to screen orientation.
7. ```vmax``` - larger of vw or vh. Good for wide layouts.


**NB: Pro Tip**
- Always use ```rem``` for font sizes to ensure better accessibility and consistency.
- Combine relative units ```(em, %)``` with media queries for powerful responsive design.
- Avoid using ```px``` exclusively — it can break responsiveness.
