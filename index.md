## Ted's resources for mentees

Books and online resources to help you get started "drinking from the firehose"! I'll try to favor free resources here, and will note with "$" when they cost something. Check back here often, as I'll be updating this list as I recall or rediscover useful resources I think can help you. If there's something you'd like to learn more about, or a link you think would benefit others, please let me know. [N.B. 🐝 means newer content.]

Contents: [General topics](#general-topics) &bull; [HTML & CSS](#html--css) &bull; [Java](#java) &bull; [JavaScript](#javascript) &bull; [Markdown](#markdown) &bull; [Python](#python)

### General topics

General resources not specific to any language, including for [source control](#source-control), [time management](#time-management),
[computing and programming](#computing-and-programming), and [writing](#writing).

#### Source control

* [_Pro Git_](https://git-scm.com/book/en/v2) by Scott Chacon and Ben Straub [book]\
  A good and thorough intro to Git (source code control) by the founder of GitHub. Free online book available for download in multiple formats, or
  read online. The first couple of chapters alone will make everything about Git a lot clearer.

* [Git Cheat Sheet](https://education.github.com/git-cheat-sheet-education.pdf) from GitHub [PDF]\
  I also like this single-page [Git cheat sheet](http://rogerdudler.github.io/git-guide/files/git_cheat_sheet.pdf) from 
  [http://rogerdudler.github.io/git-guide/](http://rogerdudler.github.io/git-guide/) (which is also a nice and quick guide to Git basics if you're
  in a hurry).
  
* 🐝 [Learn Git Branching](https://learngitbranching.js.org/) [website] 🐝 \
  This JavaScript-based online tutorial is a great intro to branching in Git. Branching is super powerful source control feature, and Git
  makes it particularly easy.

#### Time management

* [Maker's Schedule, Manager's Schedule](http://www.paulgraham.com/makersschedule.html) by Paul Graham [blog post]\
  Influential blog post on managing your time as a developer (maker). Takeaway: Try scheduling blocks of time on your calendar for focused, 
  uninterrupted development ("maker time").

#### Computing and programming

* [Stack Overflow](https://stackoverflow.com/questions) [website]\
  The most popular question-and-answer forum for programmers. Whatever problem you're trying to solve, it's likely someone else tried to solve 
  the same problem, asked on Stack Overflow, and got one or more answers (which are ranked by popularity). Many, _many_ technologists use this site,
  often several times a week. When you're jammed, this should be your second stop (after a Google search).

* [The Absolute Minimum Every Software Developer Absolutely, Positively Must Know About Unicode and Character Sets (No Excuses!)](https://www.joelonsoftware.com/2003/10/08/the-absolute-minimum-every-software-developer-absolutely-positively-must-know-about-unicode-and-character-sets-no-excuses/) by Joel Spolsky [blog post]

* [devdocs.io](http://devdocs.io) [website]\
  DevDocs combines API documentation from multiple sources into a single, organized, and searchable interface.

* [Guerrilla Testing with Usability Cafe](https://youtu.be/0YL0xoSmyZI) [video]\
  Discovering bugs and getting feedback on your app as early as possible is huge - the longer you wait, the more costly (difficult) it is to
  make changes. Guerrilla testing is an informal technique to get feedback from real users and uncover the most important problems with the
  least amount effort. (If you want to dive deeper, check out Steve Krug's
  [_Rocket Surgery Made Easy_](https://sensible.com/rocket-surgery-made-easy/).)

* [User Stories](https://www.mountaingoatsoftware.com/agile/user-stories) [website]\
  An [Agile](https://en.wikipedia.org/wiki/Agile_software_development) technique for quickly capturing requirements. User stories are
  short, formulaic descriptions of desired features or capabilities, written from the perspective of the person (role) who wants it.
  A good set of user stories succinctly describes the features and capabilities you need to include in your application.

* 🐝 [Why Learning to Code is So Damn Hard](https://www.thinkful.com/blog/why-learning-to-code-is-so-damn-hard/) by Eric Trautman [blog] 🐝\
  Sage advice about the difficult path you're on, and how to persevere and succeed.

<!-- TODO:
* Efficiency and performance
-->

##### Debugging

* Browser developer tools:
  * [Chrome DevTools](https://developer.chrome.com/docs/devtools/) [doc website]
  * [Firefox DevTools User Docs](https://firefox-dev.tools/) [doc website]
  * [Microsoft Edge DevTools documentation](https://docs.microsoft.com/en-us/microsoft-edge/devtools-guide-chromium/landing/) [doc website]
  * [Safari Web Development Tools](https://developer.apple.com/safari/tools/) [doc website][^safari-enable]
    
[^safari-enable]: Note that you have to explicitly [enable this in Safari](https://developer.apple.com/library/archive/documentation/NetworkingInternetWeb/Conceptual/Web_Inspector_Tutorial/EnableWebInspector/EnableWebInspector.html).

##### Some recommended general programming books

* [_Cracking the Coding Interview_](https://www.crackingthecodinginterview.com/) by Gayle Laakmann McDowell [book, $]\
  This is a very well-known and popular book (in its 6th edition as of this writing), filled with programming problems (and solutions),
  that will serve you well, and not only in preparing for coding interviews. There's lots to be learned from studying these programming
  problems, and porting them to whatever language you're working in. Many touch on classic computer science problems.
  
* [_Head First Design Patterns_](https://smile.amazon.com/Head-First-Design-Patterns-Object-Oriented/dp/149207800X) by Eric Freeman and Elisabeth Robson 
  [book, $]\
  "Design patterns" are time-proven solutions to common programming problems, solutions engineers have evolved over the years. 
  They're given shorthand names like "Model-View-Controller" and "Factory" and "Singleton" and "Visitor" that you'll often hear in conversation 
  with seasoned engineers. Design patterns are really worth studying and knowing because they'll help you design your code in ways that will save 
  headaches down the road. This book is a great introduction to the topic; it's been recommended to me many times over the years by experienced
  software engineers.
  
* [_Extreme Programming Explained: Embrace Change_](https://smile.amazon.com/Extreme-Programming-Explained-Embrace-Change-ebook/dp/B00N1ZN6C0)
  by Kent Beck and Cynthia Andres [book, $]\
  A short and powerful book on the software engineering process, and one of my favorites. This seminal book kicked off the
  [Agile](https://en.wikipedia.org/wiki/Agile_software_development) programming movement.
  Worth reading if only for the "cost of change" discussion (priceless lesson).[^xp-first]

[^xp-first]: I'm only familiar with the [first edition](https://www.amazon.com/Extreme-Programming-Explained-Embrace-Change/dp/0201616416), but I read that the second edition is quite good too.

#### Writing

Love to write, hate to write… There's no escaping it: email, requirements, design specs, code comments, user guides - it's all part of a programmer's life. You'll write way more prose than code. And a software engineer who can write well has a super-power over colleagues who cannot (read "more valuable to employers").

* [Google developer documentation style guide](https://developers.google.com/style/) [website]\
Keep this writing reference handy; it'll dig you out of many writing dilemmas.

* [Technical Writing Courses for Engineers](https://developers.google.com/tech-writing) [website]\
Google's free, short, self-study writing courses for engineers (Technical Writing One, Technical Writing Two, and [more]([url](https://developers.google.com/tech-writing/overview))).

See also [_Markdown_](#markdown) below.

### HTML & CSS

* [MDN - Web technology references](https://source.corp.google.com/piper///depot/google3/engedu/languages/cpp/cpp201/) [website]\
Reference docs from the Mozilla Developer Network (Mozilla is the not-for-profit behind the Firefox browser), the [HTML reference](https://developer.mozilla.org/en-US/docs/Web/HTML) and [CSS reference](https://developer.mozilla.org/en-US/docs/Web/CSS) are really great - most web developers depend on these. Look up individual HTML tags or CSS properties and selectors here (left pane).

* [Web Development Course Resources List](https://appbrewery.com/p/web-development-course-resources) [website]\
Resource list supporting [The Complete 2022 Web Development Bootcamp](https://www.udemy.com/course/the-complete-web-development-bootcamp/) on Udemy ($[^dontpay]).

[^dontpay]: Don't pay a hundred dollars or more for Udemy courses; they go on sale all the time. I usually spend $15-25 for apiece for these courses. You may need to register on the site to get the deals - some of the courses themselves are quite good.

* [w3schools.com](https://www.w3schools.com/cssref/css_selectors.asp) [website]\
Tutorials and reference lists I've been using for years, mostly:

  - [HTML element reference](https://www.w3schools.com/tags/default.asp)
  - [CSS reference](https://www.w3schools.com/cssref/default.asp)
  - [CSS selector reference](https://www.w3schools.com/cssref/css_selectors.asp)

### Java

* [The Java Tutorials](https://docs.oracle.com/javase/tutorial/) [website]\
Old, but still very effective and applicable.

* [OpenJDK documentation](https://devdocs.io/openjdk/) [website]\
Javadocs on the SDK libraries from OpenJDK's open source Java implementation.

* [JDK API documentation](https://docs.oracle.com/en/java/javase/index.html) [website]\
Javadocs on the SDK libraries from Oracle's commercial distribution.

### JavaScript

* [MDN - JavaScript](https://developer.mozilla.org/en-US/docs/Web/JavaScript) [website]\
Authoritative reference on the language with excellent tutorials, from the Mozilla Developer Network.

* 🐝 [The Complete JavaScript Course 2022: From Zero to Expert!](https://www.udemy.com/course/the-complete-javascript-course/) by Jonas Schmedtmann on Udemy [online course $] 🐝 \
i've taken and surveyed a _lot_ of online training courses, and this is **one of the best** I've found. Very deep dive into JavaScript, with a lot of fun projects throughout.

* [_Eloquent JavaScript_](https://eloquentjavascript.net/) by Marijn Haverbeke [book]\
Highly praised by many experts, freely available online.

* [The Net Ninja](https://www.youtube.com/channel/UCW5YeuERMmlnqo4oq8vwUpg) [YouTube channel]\
Nice YT tutorial on JavaScript, and other frameworks.

### Markdown

* [Daring Fireball](https://daringfireball.net/projects/markdown/) [website]\
Website of Markdown inventor John Gruber. Contains basics and syntax that will work in most Markdown servers, plus gives the general gist behind Markdown. Also check out the [Dingus](https://daringfireball.net/projects/markdown/dingus) page where you can experiment with MD right in your browser.

* [Basic writing and formatting syntax](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax) [website]\
GitHub's guide on writing "GitHub-Flavored Markdown" (they're own variant on the original Markdown spec).

* [GitHub Pages](https://pages.github.com/) [website]\
Easily create web sites from simple Markdown and/or HTML/CSS/JS. Pretty neat and free (all you need is a free GitHub account) - this page is itself a GitHub Pages page.

See also [_Writing_](#writing) above.

### Python

* [_Tiny Python Projects_](https://www.manning.com/books/tiny-python-projects) by Ken Youens-Clark [book, $]\
Currently my favorite intro-to-Python book. A series of fun test-driven projects, with accompanying YouTube videos if you want them.

* [Python documentation](https://docs.python.org/3/) [website]\
Official docs on [python.org](http://python.org). 
Indespensible if you're writing any Python. Especially:

  - [Python Library Reference](https://docs.python.org/3/library/)
  - [The Python Language Reference](https://docs.python.org/3/reference/)

* [Flask](https://flask.palletsprojects.com/) [framework]\
Flask is an extremely popular framework for creating Python-driven websites and web applications.

<!--

## Welcome to GitHub Pages

You can use the [editor on GitHub](https://github.com/eccentricon/mentees/edit/gh-pages/index.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [Basic writing and formatting syntax](https://docs.github.com/en/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/eccentricon/mentees/settings/pages). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://support.github.com/contact) and we’ll help you sort it out.

-->
