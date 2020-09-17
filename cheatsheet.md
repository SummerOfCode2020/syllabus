### GIT COMMANDS
* GIT BRANCH - Allows you to see a list of all your current branches and the one youre currently working in.

* GIT CHECKOUT "Branch name":  This is used to move between your branches.

* GIT CHECKOUT -B "Branch name":  Creates a new branch and switches to it.

* GIT STATUS: Lets you know if there are any files that have changes that need to be moved to your staging area.

* GIT ADD .: Used to move a set of changes from your working area to your staging area.

* GIT COMMIT -M "Comment detailing changes": This gets your file ready to be pushed from your local.

* GIT PULL: Used to fetch all the changes from the remote and sync them with your local.

* GIT PUSH: Used to push changes from your local repository and sync them with the remote.

* GIT CLONE "Repository link": Used to clone a remote repository and sync it with your local.

* GIT INIT: The "init" command creates a brand new Git repository.

### NODE COMMANDS
* NPM INSTALL: Used when you see a node module to install its dependencies.

* NPM RUN DEV: Makes the local host accessible and runs everything listed in the packacge.json.

* NPM INIT -Y: Creates a package.json while also answering yes to all the questions that follow the init.

* NODE "FILE_NAME": Is used to run a test on a single file, usually to view the results of a consol.log().


### HTML & CSS 

* HTML: Hyper-Text Markup Language -- a templating language used to define the structure of a webpage.

* CSS: Cascading Style Sheets. Used to format and style the layout of a webpage. They are called “cascading” because a styles styles can “cascade” from one style sheet to another, enabling multiple style sheets to be used on one HTML document

* RESOURCES: 
    - https://docs.google.com/presentation/d/1IllqEsWCTm5orDIFscBNCLEeorsg-crlARDnuqiE2yA/edit#slide=id.g7c704696bc_0_141

    - https://www.w3schools.com/html/html_basic.asp

    - https://www.w3schools.com/css/css_intro.asp


* VOCABULARY:
    - Parent Element: an HTML element is the “parent” of another element when it is directly outside that element and contains it with its opening and closing tags.

    - Child Element: an HTML element that is nested inside another element (the "parent" element).

    - Sibling Element: an HTML element is a “sibling” of another element when they share a parent element.

    - Metadata: “data about data” -- on an HTML document, metadata describes the document itself, rather than defining what the page should display in a browser.

    - Tag: the smallest building block of HTML. It always starts with a < symbol and ends with a >. Each HTML element is made up of 1-2 tags: either it has an opening and closing tag denoting the start and end of the element, or is “self-closing”, meaning it starts and ends in the same place.

    - Stylesheet: a separate file where styles are defined, which can be imported into an HTML file (or many HTML files!) to style the contents of that file.

    - href: Hypertext REFerence -- the html attribute defining a link to another file or webpage.

    - Hexadecimal Code: a color hexadecimal code is a six-digit code containing numbers 0-9 and/or letters A-F that corresponds to a color. These can be used in CSS to color HTML elements. A list of named CSS hex colors can be found here.

    - Pseudoselector: a type of CSS selector that is only applied when the selected element is in a certain state. For instance, the a:hover specifies styles we only want the link to have when the user is hovering her mouse over it.


### JAVASCRIPT

* JAVASCRIPT: A programming language that can be used to make a webpage interactive.

* RESOURCES: 
    - https://docs.google.com/presentation/d/1IllqEsWCTm5orDIFscBNCLEeorsg-crlARDnuqiE2yA/edit#slide=id.g7c704696bc_0_141

    - https://javascript.info/

    - https://www.w3schools.com/js/js_intro.asp

    - https://www.codecademy.com/learn/introduction-to-javascript

* VOCABULARY: 

    - Data Type: in programming, a data type is the “kind” of data a value can represent. Common data types in Javascript are number, string, and boolean.

    - Integer: a number without a decimal point in it, such as 57. In some programming languages these are differentiated from decimal numbers, but in Javascript they are treated interchangeably.

    - Boolean: in programming, a data type that is always either true or false.

    - String: in programming, a data type that is a series of characters, used when we need to represent text.

    - Operator: in programming, operators are symbols used to perform specific operations on the values before and/or after them. Some operators represent common mathematical operations, like + and -, while others are specific to programming.

    - Function: a block of code with a name. Once we define a function, we can use it elsewhere by reference in other parts of the code.

    - Function Parameter: an “input” of a function. A function can have any (reasonable) number of parameters, even zero!

    - Return Value: the “output” of a function. If no return value is defined for a Javascript function, it will return undefined.

    - Braces: or curly braces, refer to the { and } symbols. These symbols are used to wrap Javascript objects.

    - Brackets: or square brackets, refer to the [ and ] symbols. These symbols are used to wrap Javascript arrays.

    - Property: a value stored on an object, accessible by its key via “dot notation” (object.property). They are used similarly to the way variables are used outside an object.

    - Method: a function stored on an object, accessible by its name key via “dot notation” (object.method(). They are used similarly to the way functions are used outside an object.

    - Destructuring: in Javascript, an assignment syntax used as a “shortcut” to easily create new variables and set their values equal to a property inside an object.

### NODE
* Node: an engine for executing Javascript code outside the browser.

* RESOURCES: 
    - https://nodejs.dev/learn

    - https://developer.mozilla.org/en-US/docs/Learn/Server-side/Express_Nodejs/Introduction

    - https://www.tutorialspoint.com/nodejs/nodejs_introduction.htm

* VOCABULARY:

- Module: in software, a reusable piece of code that provides an interface to use it in other code. Javascript modules written by other people can be downloaded and used in your own code through npm. In node, individual files can be considered modules.

- module.exports: A Node keyword that allows you to define code from a file that should be available outside of the file.

- NPM: a Javascript package manager that allows you to download and use external code within your own codebase.

- package.json: a file that acts as the central repository where you configure metadata, dependencies, tools, and scripts for your node.js project.

- Linter: a tool that analyzes your code to find syntactic and stylistic errors.

- ESLint: the primary Javascript linter. It helps us keep our code style and syntax standard and correct, and can even correct style mistakes automatically.

- Dependency: a piece of software that your code requires to run. In Node, dependencies can be specified in a package.json file and stored in a node_modules directory.

- devDependencies: dependencies that are flagged in the package.json file to only be installed when running Node in development mode

- node_modules: the standard directory in a node project where external modules are stored.

- Test Driven Development: a software methodology in which you begin by writing a test for functionality you intend to implement, then write the code to implement that functionality.

- Behavior Driven Development: an Agile development practice in which you define the desired behaviors of your code through test assertions, then write the production code itself.

