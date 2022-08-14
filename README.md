# Code Refactor Starter Code

## Description
This project aims to refactor the existing code for Horiseon's website to make the site more accessible. The goal of the project is to meet the following acceptance criteria: 

```
GIVEN a webpage meets accessibility standards
WHEN I view the source code
THEN I find semantic HTML elements
WHEN I view the structure of the HTML elements
THEN I find that the elements follow a logical structure independent of styling and positioning
WHEN I view the icon and image elements
THEN I find accessible alt attributes
WHEN I view the heading attributes
THEN they fall in sequential order
WHEN I view the title element
THEN I find a concise, descriptive title
```

To meet these criteria, I made a series of changes that replaced HTML elements such as Div with Semantic elements like Header, Navigation, Section, and Footer. The reason for this is to create an accessible page where tools such as screen readers can help users easily follow the flow of the page. With accessibility in mind, I've also used ensured the Heading elements were in a logical order by replacing the footer's heading from h2 to h4.

When refactoring the stylesheet, I've condensed selectors by grouping elements into classes to consolidate repetitive selectors and properties. I've also updated the selectors to match the semantic HTML elements in the index.html sheet. Finally, I've arranged the selectors in the CSS file to match the flow of the HTML sheet, keeping in mind parent and child relationships.  

Below is the final mockup of the refactored website:
![Mock up of Refactored Website](https://user-images.githubusercontent.com/108312371/184554045-35953f79-5086-4bf9-b3ab-670be1e4ae3f.png)

