# week-1-code-refactoring-challenge

# Description

This challenge was to refactor a codebase to make it more accessible for all those who use the site whilst also optimising the webpage for serch engines without changing the content and design of the site. 

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
WHEN I view the icon and image elements
THEN I find accessible alt attributes
WHEN I view the heading attributes
THEN they fall in sequential order
WHEN I view the title element
THEN I find a concise, descriptive title
```

## Changes Made

The changes that were made to the codebase includes:

* The title of the webpage did not reflect the name of the company and was not desciptive. The title was changed to reflect the company name and what services they provide. 
* The HTML tags were non-semantic with the use of the div tags being prevalent. To solve this, the non-semantic tags were changed to more semantic HTML tags e.g. header, footer etc.
* Added the alt tag desciprition to provide information on what the image is showing and make the page more accessible to those who use screen readers and to positively affect seo.
* Some links did not work and was not navigation to the section they were supposed to. To solve this an id class was added to the element where it was missing allowing the link to work. 
* The CSS code some elements were consolidated and cleaned up to make it easier to make changes to all of them at once (as they all had the same style rules). 
* CSS code was changed to reflect the new semantic HTML tags so that the style rules made will still apply.  

# Image 

add screenshot of page HERE!! 

![image](https://github.com/e-aji/week-1-code-refactoring-challenge/assets/156595423/394acb77-8f54-44af-a2b1-38a8bddd94ae)

(Horiseon - Marketing Agency.png) 

# Links

links to deployed application 
