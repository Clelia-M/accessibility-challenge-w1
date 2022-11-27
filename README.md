# Accessibily Challenge - Bootcamp Module 1

## Table of Contents
- [Description](#description)
- [Changes Made HTML](#html)
- [Changes Made CSS](#css)
- [Credits](#credits)

## Description

**Scope of the project**: to modify the code contained in the starter folder to folllow best practice on accessibility and semantic HTML. (Code Refactor Challenge)

**User story**: 
AS A marketing agency
I WANT a codebase that follows accessibility standards
SO THAT our own site is optimized for search engines

**Workflow**: 
1. HTML review per section to use Semantic HTML whenever possible
2. CSS update based on new HTML to clear code
3. Final review, last changes and README

## HTML
**Changes made per section**

HEAD Section

1. Removed GB from lang because the website is for a US based company not a UK one
2. Removed closing / from meta charset
3. Changed the title of the website

HEADER Section

4. Substitued div header class with a header tag
5. Substitued div for the navbar with a nav tag
6. Removed span class not needed to target the contet in CSS

HERO Section

7. Substitued div with a section tag
8. Specified class "hero-img" instead of just "hero"
9. Moved img to HTML instead of CSS background to add an alt attribute

MAIN section

10. Substitued div tag with main tag to contain all 3 articles
11. Subsituted div tag with article tags for all 3 cards
12. Removed 3 articles classes and changed with one class named "article-card"
13. Added the missing id on the first article to use it on the nav bar
14. Img Alt added to all 3 articles imgs

SIDEBAR section

15. Substitued div tag with an aside tag to contain sidebar content
16. Removed 3 articles classes and changed with one class named "sidebar-card"
17. Img Alt added to all 3 articles icons
18. Img closing tag removed from the Cost mgmt icon img

FOOTER section

19. Substitued div tag with footer tag to contain footer content
20. Substitued footer class with footer tag semantic element
21. Added span tag to the emoji to describe role and content

22. Final review and section comments to reorganize content

## CSS

**All changed made**

1. Substitued header class with header tag on all instances
2. Substitued div for the navbar with a nav tag
3. Removed span class seo to target the content just using header h1 span
3. Substitued hero class with hero-img class
4. Moved hero-class img to hTML and targeted hero-img img to apply styling
5. Removed all articles classes as they were all identical and changed with one class named "article-card"
6. Targeted img and h2 of artcle class and removed all identical properties
7. Removed benefits class and changed for more generic sidebar class
8. Removed all benefit classes as they were all identical and changed with one class named "sidebar-card"
9. Substitued footer class with footer semantic tag element


## Credits

Starter code provided as part of the Module challenge for the challenge for the Trilogy Skills Bootcamp in Front-End Web Development.

