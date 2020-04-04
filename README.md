# Homework-01-Refactor
First assignment of refactoring code 
1. The title tag did not have a specific description. Changed the tag from "website" to "Horiseon Management". This will allow the user to
know specifically which tab this is, should there be multiple tags open.

2.I refactored the <h1>Hori<span class="seo">seo</span>n</h1> under the parent tag div="classes", by by calling the .seo class and changing the three letter's to 
a different color from the the rest of the word so for example: Hori<color-change>seo</color-change>. I did this because according the company's browser, it seems as if "seo" is an acronym they would like to utilize for the purpose of marketing.

3.The unordered list tag inside the parent of the div header class, I gave a pseudo-class to a:hover > color: red; I found this necessary in order to give the user confirmation of what specific tag they intend on selecting.

4. Under the parent div tag"class content", I added the ID"search-engine-optimization". As far as consistecy goes and code structure, I figured it only made sense to give it an ID along with a class. Seeing as how the images used below, but also part of the same parent class had and ID in addition to having a class.

5.When attempting to refactor the code the background-image under the div tag "hero", I need to change the URL in the stylesheet to the direct file path in order for the image to load.

6.There multiple lines of code that could use redactoring, in order to reduce the amount of duplicate code in the CSS stylesheet.

7.