# gt-accessibility-html

# 1. Code Refactor
Week One
GT Coding Bootcamp

## Description

In this assignment I have been tasked with taking a visibly good website and converting to meet Current Accessibility Standards.  There are legal reasons for doing this as a company, but the #1 reason is to make sure all of your site's visitors have a positive experience.  I first attempted to clean up the html, but found that it went quicker once I looked at the CSS to find opportunities.  That helped me visualize the div's as sections and helped me consolidate the classes.  In this README.MD file I am attempting use as many features as makes sense.

I am adding lorem ipsum to mockup a longer README.  At vero eos et accusamus et iusto odio dignissimos ducimus qui blanditiis praesentium voluptatum deleniti atque corrupti quos dolores et quas molestias excepturi sint occaecati cupiditate non provident, similique sunt in culpa qui officia deserunt mollitia animi, id est laborum et dolorum fuga. Et harum quidem rerum facilis est et expedita distinctio. Nam libero tempore, cum soluta nobis est eligendi optio cumque nihil impedit quo minus id quod maxime placeat facere possimus, omnis voluptas assumenda est, omnis dolor repellendus. Temporibus autem quibusdam et aut officiis debitis aut rerum necessitatibus saepe eveniet ut et voluptates repudiandae sint et molestiae non recusandae. Itaque earum rerum hic tenetur a sapiente delectus, ut aut reiciendis voluptatibus maiores alias consequatur aut perferendis doloribus asperiores repellat.

At vero eos et accusamus et iusto odio dignissimos ducimus qui blanditiis praesentium voluptatum deleniti atque corrupti quos dolores et quas molestias excepturi sint occaecati cupiditate non provident, similique sunt in culpa qui officia deserunt mollitia animi, id est laborum et dolorum fuga. Et harum quidem rerum facilis est et expedita distinctio. Nam libero tempore, cum soluta nobis est eligendi optio cumque nihil impedit quo minus id quod maxime placeat facere possimus, omnis voluptas assumenda est, omnis dolor repellendus. Temporibus autem quibusdam et aut officiis debitis aut rerum necessitatibus saepe eveniet ut et voluptates repudiandae sint et molestiae non recusandae. Itaque earum rerum hic tenetur a sapiente delectus, ut aut reiciendis voluptatibus maiores alias consequatur aut perferendis doloribus asperiores repellat.

At vero eos et accusamus et iusto odio dignissimos ducimus qui blanditiis praesentium voluptatum deleniti atque corrupti quos dolores et quas molestias excepturi sint occaecati cupiditate non provident, similique sunt in culpa qui officia deserunt mollitia animi, id est laborum et dolorum fuga. Et harum quidem rerum facilis est et expedita distinctio. Nam libero tempore, cum soluta nobis est eligendi optio cumque nihil impedit quo minus id quod maxime placeat facere possimus, omnis voluptas assumenda est, omnis dolor repellendus. Temporibus autem quibusdam et aut officiis debitis aut rerum necessitatibus saepe eveniet ut et voluptates repudiandae sint et molestiae non recusandae. Itaque earum rerum hic tenetur a sapiente delectus, ut aut reiciendis voluptatibus maiores alias consequatur aut perferendis doloribus asperiores repellat. from [lipsum dot com](https://www.lipsum.com/)

## Table of Contents

* [User_Story](#user_story)
* [Acceptance_Criteria](#acceptance_criteria) 
* [Changes_Made](#changes_made)
* [Credits](#credits)
* [License](#license)

## User_Story

```
AS A marketing agency
I WANT a codebase that follows accessibility standards
SO THAT our own site is optimized for search engines
```

## Acceptance_Criteria

```
GIVEN a webpage meets accessibility standards
WHEN I view the source code
  THEN I find semantic HTML elements = Yes
WHEN I view the structure of the HTML elements
  THEN I find that the elements follow a logical structure independent of styling and positioning = Yes
WHEN I view the image elements
  THEN I find accessible alt attributes = Yes
WHEN I view the heading attributes
  THEN they fall in sequential order = Yes
WHEN I view the title element
  THEN I find a concise, descriptive title = Yes
```

## Changes_Made

* HTML
Changed <title> to have company name and keywords-->
Replaced <div class header> with <header> // Replaced div with ul with <nav> // -->
Left div class hero the same -->
Converted div class content into <main class content> // Kept id the same for navigation // Consolidated section classes into 'offering' //
      Added alt text to img tags -->
Replaced div benefits with <aside class benefits> // Consolidated benefit-* classes into benefit // -->
Replaced div class footer with <footer> -->

* CSS
Replaced class header with tag <header> */
Left class seo the same */
Replaced heeder div with tag <nav> */
Consolidated company offering classes into 'offering' */
Consolidated benefit-_____ classes */

## Credits
Good-README-Guide
[lipsum dot com](https://www.lipsum.com/)


## License

MIT License

Copyright (c) [2020] [Steve Morris]

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
