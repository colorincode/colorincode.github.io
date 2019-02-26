# vans devs hub

This is intended to be a non judgmental, collaborative tool to help us all code better, learn from mistakes, learn from others, and an overall resources for devs / design to work together to make more happen. This may also help the team identify strengths and weaknesses within so we can improve our workflow.

### - Goals and Anti Goals

While no exact goals have been set, it might be a good idea to set measurable goals:
Have 100% of team reviewing code.
Have all code meeting 60-80% of (internal) code standards.

- **Main individual and team goals**  
1. To break good code, and make it better.
2. Be grateful for the reviewer's suggestions. ("Good call. I'll make that change.")
3. Avoid innuendo, personal attacks, brutality in review. The code is under a microscope, not the dev. 
4. Don't be a know it all smarty pants. We are all smart, offer alternative implementations, but assume the author already considered them. 
5. Accept that many programming decisions are opinions. Discuss tradeoffs,preferences, reach a resolution quickly. Just because this isn't how you would have done it, does NOT mean that it is incorrect. 

### Step by Step Process
        
1. **Fork peer's code from github** (or send manually if necessary) - pull requests / commits / branches are a good idea here - but we probably need a system for those. 
2. **Follow this google form** to go through the code. Good tips: Try not to read through more than 500 lines of code per hour, and try to make sure that you thoroughly review the code. A good code review typically takes at least 1 hour. 

### - Here is what to check, why and examples:
 **For deeper reading into these methods, check the resources section, there are a lot of great links there.**
1. **Check naming conventions first**. Does the naming of variables follow common sense logic? Does CSS follow a BEM standard? Does the variable or class name state intent (either in comments or in the name itself?) 
Examples of statement of intent can include:<br/>
<code>"main--slider--wrapper"</code><br/>
<code>or "$vansredbtn"</code> <br/>
<code><!--this is the main wrapper main--slider--wrapper--> </code><br/>
<code> /* this (function, class, mixin) does x */</code><br/>
Follow up: Does the code actually do what the statement of intent declares? 

2. **Functionality** Does this code have a readme.md? Can this code be broken? If it can, how? Are there systems or scenarios in which this code would not work? What could be added or refactored? Does this code work in the real world? Does this work across all browsers and platforms?

3. **Usability and Interface** For any page inspection, **try to think of different "scenarios"** this code would be useful, or not useful. (From the perspective of a customer that has never used this page, is the design usable? Is it intuitive? Can it be learned quickly?... From the perspective of a shareholder or your boss, does this code drive/encourage the customer to point of sale?) This is important, since the code will be shown to many different people, and we want to make sure it is useful to most. The ten usability heurtistics is an excellent resource(see resources) to check out for user interface design. 
4. **Security and Vulnerability** This one is fairly self explanatory. This is not an all inclusive list, but a secondary security check to ensure code doesn't expose any easy-to-fix security flaws. Is everything up-to-date that can be within npm/package modules? Can any code be injected/inserted at runtime in the application built? Every single image and piece of media being served over secure connection?
5. **Code styling,layout,scabalability/reusability** Explain why the code exists. ("It's like that because of these reasons. Would it be more clear if I rename this class/file/method/variable?"). Are JS functions scoped, is CSS coherent? Run final linters/automated code tests to find any semantic errors, address them. If there is a reason a standard should NOT be followed, then include in the readme.md why that is the case. Could this code be reused in the future? Could this code be scaled (meaning, more users/server load?). Is this code modern (e.g. using new technologies, new methodologies)? Do you and author know why this methodology might be better than another?)

### - Research / Justification

<img src="http://s7d2.scene7.com/is/image/VansBrand/dev-case-study-1?$original-file$" />
        
- **HTML Source:**  The generated HTML before your browser makes it pretty.
- **Lexer Data:**  What [marked] uses internally, in case you like gory stuff like this.
- **Quick Reference:**  A brief run-down of how to format things usin

## Resources

   [BEM](http://getbem.com/introduction/)
   [OOCSS](http://oocss.org/)
   [CSI Commenting Showing Intent Standard](https://standards.mousepawmedia.com/csi.html)
   [The Ten Usability heuristics](https://www.nngroup.com/articles/ten-usability-heuristics/)


- **Preview:**  A live display of the generated HTML as it would render in a browser.
- **HTML Source:**  The generated HTML before your browser makes it pretty.
- **Lexer Data:**  What [marked] uses internally, in case you like gory stuff like this.
- **Quick Reference:**  A brief run-down of how to format things usin

# colorincode.github.io

## Peer Reviews
### child of
### child of
### child of 
## Resources
    child of
    ### [1] [Google](http://www.google.com)
    ### [2] [Google](http://www.google.com)


- **Preview:**  A live display of the generated HTML as it would render in a browser.
- **HTML Source:**  The generated HTML before your browser makes it pretty.
- **Lexer Data:**  What [marked] uses internally, in case you like gory stuff like this.
- **Quick Reference:**  A brief run-down of how to format things usin

# colorincode.github.io

## Peer Reviews
### child of
### child of
### child of 
## Resources
    child of
    ### [1] [Google](http://www.google.com)
    ### [2] [Google](http://www.google.com)


- **Preview:**  A live display of the generated HTML as it would render in a browser.
- **HTML Source:**  The generated HTML before your browser makes it pretty.
- **Lexer Data:**  What [marked] uses internally, in case you like gory stuff like this.
- **Quick Reference:**  A brief run-down of how to format things usin

# colorincode.github.io

## Peer Reviews
### child of
### child of
### child of 
## Resources
    child of
    ### [1] [Google](http://www.google.com)
    ### [2] [Google](http://www.google.com)


- **Preview:**  A live display of the generated HTML as it would render in a browser.
- **HTML Source:**  The generated HTML before your browser makes it pretty.
- **Lexer Data:**  What [marked] uses internally, in case you like gory stuff like this.
- **Quick Reference:**  A brief run-down of how to format things usin

# colorincode.github.io

## Peer Reviews
### child of
### child of
### child of 
## Resources
    child of
    ### [1] [Google](http://www.google.com)
    ### [2] [Google](http://www.google.com)


- **Preview:**  A live display of the generated HTML as it would render in a browser.
- **HTML Source:**  The generated HTML before your browser makes it pretty.
- **Lexer Data:**  What [marked] uses internally, in case you like gory stuff like this.
- **Quick Reference:**  A brief run-down of how to format things usin
