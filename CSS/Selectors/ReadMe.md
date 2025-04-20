
noteId: "d264e3b008b711f0a75da7bed4f6c72e"
tags: []

# CSS Selectors and Specificity
- **Selectors** are patterns used to select and style html elements.
- They help target specific area of html document.

# Types of Selectors
1. **Universal Selector(*)**
   - Targets all elements within html document.
2. **Type selector**
   - Targets all instances of particular element.
3. **ID selector (#)**
4. **Class selector (.)**
   - Targets all elements with specific ```class``` attribute.
5. **Attributes selector**
   - Targets all elements with specific attributes.
6. **Grouping selector (,)**
   - Targets multiple elements with same style.

# Pseudo-classes and pseudo-element
- can be defined as classes which apply style based on particular state or part of element.

1. **Pseudo-classes (:)**
   - Targets elements based on their state or position.
   - Examples
   1. **:hover** - When mouse is over the element.
   2. **:focus** - when element is focused e.g textbox clicked
   3. **:nth-child(n)** - Target element based on their position within the parent element.

2. **Pseudo-element (::)**
   - Style specific part of html element.
   - Example
   1. **::before** - adds content before an element.
   2. **::after** - adds content after an element.
   3. **::first-letter** - Styles first-letter of block of text.
   4. **::first-line** - Styles first-line of block of text.

# Specificity and Important
-when multiple CSS styles are are applied on same element, CSS uses specificity to determine which styles to apply.

**Specificity Calculation**
   1. **Inline styles** - Highest (1000points)
   2. **ID selector** - Higher (100points)
   3. **Class, Pseudo-class, Attribute selector** - Medium (10points)
   4. **Type selector** - Lower (1points)
   5. **Universal selector** - Lowest (0points)

**NB: Using !Important** - Overrides all other CSS styles, but should be avoided unless necessary.
