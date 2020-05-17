Code Refactor

Motivation: A poorly written code given to the student for reviewing wrong and not optimal parts of the code. From aesthetics to actual mistakes, the student was supposed to take a look, use all the knowledge obtained so far in the course and do it's best to correct it.


Features:

On `index.html`:

* Changed `<div class="header">` tag to `<header>` 
* Given the `alt` attribute to all images (lines 30, 36, 43, 54, 61, 68)
* Removed unused `id` tags (lines 36, 43)
* Changed `div` tags from lines 29, 35, 36, 42, 43 and 49 to `section` tags
* Changed `div` tags from 51 and 73 to `aside` tags
* Changed `<div class="footer">` tag to `<footer>` 


On `style.css`:

* Changed `.header` and `.footer` to `header` and `footer`
* Grouped various classes with the same style configuration into the same block of code
    - `.benefit-lead`, `.benefit-brand`, `.benefit-cost`
    - `.benefit-lead img`, `.benefit-brand img`, `.benefit-cost img`
    - `.search-engine-optimization`, `.online-reputation-management`, `.social-media-marketing`
    - `.search-engine-optimization img`, `.online-reputation-management img`, `.social-media-marketing img`
* Added ' to several font-families which were missing int