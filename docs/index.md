---
title: "Introduction to SQL and Cybersecurity: Instructor Notes"
---

## Quick Links and Requirements

Skip to [delivery notes](#delivery-notes).

### Software

* Zoom (video conferencing software): [Online version](https://zoom.us) or [Desktop version](https://zoom.us/download)

### Content

Type | Language | Link 
--- | --- | ---
Instructor notes 👈 _YOU ARE HERE_ | English | [GitHub Pages](https://canadalearningcode.github.io/llc-sqlcyber/)
Slides | English | Google Slides: [Online or in-person](https://bit.ly/llc-sqlcyber)
Dataset | Multi | CLC Cyber
<!--
Learner references  | English | Github Wiki: [bit.ly/llc-jsweb-refs](https://bit.ly/llc-jsweb-refs)
Starting project / development environment | English | CodeSandbox: [bit.ly/llc-jsweb-ide](https://bit.ly/llc-jsweb-ide)
Finished project / demo | English | CodeSandbox: [bit.ly/llc-jsweb-demo](https://bit.ly/llc-jsweb-demo)
-->

## Versioning
### 1.0.0-a.1 (July 2023)
* Initial release


---

## Workshop Overview

### Description

With digital platforms and services being an increasingly inescapable part of our day-to-day lives, have you ever stopped to ask yourself, _"Is my personal data safe? Is my sensitive data being handled with care? Is my privacy being protected?"_ **Cybersecurity** is the practice of establishing and maintaining confidentiality, integrity, and availability of information, and it is the job of cybersecurity professionals to protect networks, devices, people, and data from unauthorized access or criminal exploitation.

Cybersecurity professionals apply their knowledge and skills alongside a wide variety of tools and best practices to establish preventive security measures or, in the event of an attack or attempted breach, understand the impact of such an event and do their best to mitigate any damage caused.

#### Why learn SQL?

One of the most useful tools in their toolbelt is usage log data recorded by their systems and stored in databases, however having large amounts of data at their disposal creates a new challenge: how can this data be made useful?

**Structured query language (or SQL)** is one of the most commonly-used computer languages for working with data and communicating with databases. SQL is a powerful language that allows us to extract useful insights from large quantities of data stored in databases. Cybersecurity professionals need to be able to efficiently sift through large amounts of data to be able to find irregularities that may indicate that their systems have been—or are being—targeted for an attack and SQL is a handy tool to accomplish that.

#### The bottom line:

Whether you've heard of databases or are brand new to them, this experience is designed for you. In this experience, you will learn the basics of SQL through a cybersecurity lens. Through hands-on exercises that will have you writing and executing SQL queries, you will learn to retrieve, filter, and sort data stored in a database to be able to address common cybersecurity problems and questions that cybersecurity professionals deal with on a regular basis.

### Learning objectives

By the end of this experience, learners will be able to:
1. Describe, in general terms, the concepts of **data** and **databases**.
2. Describe, in general terms, the concept of **cybersecurity** and the role that **cybersecurity professionals** play in protecting access to networks and information.
3. Use **Structured Query Language (SQL)** to:
   * Retrieve data from a database
   * Filter retrieved data using conditions and keywords
   * Group data into categories and caluclate simple statistics for data or a dataset

### Prerequisities
None

## Workshop schedule and breakdown

### Est. total time
3 hrs 

### Breakdown

Element | Slides | Length
--- | --- | ---
Introduction | 1-14 |
Today's tool: CodeSandbox.io | 15-19 |
JavaScript _and_ the Web | 20-23 |

## Prep Work
Before the workshop...
### General preparation
* [ ] Review instructor resources (e.g., notes, slides, solution sheet, example projects, learner references)
    * [ ] Review learning objectives and ensure you understand when and how they are accomplished within the content
    * [ ] Review coding concepts and ensure you are confident describing them to your group (see [technical preparation](#technical-preparation))
    * [ ] Code and build (if applicable) the workshop’s main project, ensuring you are comfortable with all steps outlined
* _If applicable:_
    * [ ] Decide which content primary instructor and co-instructor are responsible for covering in the workshop
    * [ ] Conduct additional research on any concepts or tools (see Supplemental Training Resources to get started)
* [ ] Prepare a land acknowledgment appropriate for your region. 
* [ ] Ensure landing pages to links, videos, and/or examples are correct. _If you find something that's broken, missing, or incorrect, submit a Content Repair Request._

### Technical preparation
You will need to have an understanding of the following concepts to deliver this workshop:
* [ ] Basic JavaScript syntax (common keywords and symbols; structure) 
* [ ] Writing to the web browser console with `console.log()`.
* [ ] Using dot notation to access an object's properties.
* [ ] Using dot notation to invoke an object's methods.
* [ ] Invoking functions that require arguments. 

## Delivery Notes

<!--
* __Minimize the time spent on slides before coding begins.__ This workshop is fairly dense, and while these early slides provide important context (which is why they are included), trying to maximize learner interaction at this early stage is less valuable than getting into, and through, the content and exercises.
* If this is being delivered online and mentors & breakout rooms are being used, consider still starting each exercise as the whole group, to get the ball rolling.
* The timings provided for the exercises are guidelines. Generally speaking, the exercises aren't particularly long and shouldn't actually take as long as described. Be strict on calling everyone back once the time limit has been reached and consider having shorter breakout times to account for time used if taking up the solutions to the exercises. 
-->

## Supplemental Resources

### Key Terms and Concepts

#### Application programming interface (API)
* A structured way for two or more applications to communicate with each other and share or request data.
* The document object model that we use to access many of the features and functionality of a web page or site is one of many so-called [Web APIs (External link: Mozilla Developer Network)](https://developer.mozilla.org/en-US/docs/Web/API).
#### Cascading Style Sheets (CSS)
* A rules-based computer language that can be used to apply different styles to specified sets of HTML elements, based on a [selector](#selector-css) pattern, to change the visual appearance or layout of a web page.
#### CodeSandbox.io
* A web-based [integrated development environment (IDE)](#integrated-development-environment-ide) built around an industry standard tool, Microsoft Visual Studio Code (VSCode).
#### `console` object
* An object that is provided by a web browser as a way for a web page to communicate with a browser's built-in console.
* Messages are sent to a browser's console using various methods that are part of the Console [API](#application-programming-interface-api), such as `log()` or `warn()`.
* _Read more about this in the [MDN Web Docs: console](https://developer.mozilla.org/en-US/docs/Web/API/console) reference page_.
#### Development environment
* _See [integrated development environment (IDE)](#integrated-development-environment-ide)._
#### `document` object
* An object provided by the [document object model (DOM)](#document-object-model-dom) [API](#application-programming-interface-api) that is a data representation of the structure and content that is defined by the HTML code of a web page. 
* The `document` object provides many useful methods, including ones for creating, removing, selecting and modifying HTML elements.  
* _Read more about this on the [MDN Web Docs: Document](https://developer.mozilla.org/en-US/docs/Web/API/Document) reference page._
#### Document object model (DOM)
* One of many Web [API](#application-programming-interface-api)s provided by the web browser, the document object model (DOM) allows JavaScript to interact with the web page that has been loaded.
* _Read more about this on the [MDN Web Docs: Introduction to the DOM](https://developer.mozilla.org/en-US/docs/Web/API/Document_Object_Model/Introduction) reference page._
#### Integrated development environment (IDE)
* An application that is used to write code. It often has features that make writing code easier, such as language-specific syntax highlighting. It also often has tools to facilitate development-related tasks such as version control.
#### Method (JS)
* A function that is a [property](#property-js) of an [object](#object-js).
#### Object (JS)
* An object is a way to organize related information and functions together, using [properties](#property-js).
#### Property (JS)
* A property is data or a function that has been associated with an [object](#object-js).
* Data properties can be accessed using dot notation, in the form of `objectName.propertyName` (_note the dot separating the object name and the desired property_).
* A property that is a function is called a [method](#method-js).
* Function properties are accessed the same way as data properties (dot notation) and are invoked like non-property functions, using `()`, e.g., `objectName.methodName()`.
#### Selector (CSS)
* A pattern that defines which HTML elements will be affected by a given set of CSS rules.
* _See also: [Selector (JS)](#selector-js)_.
#### Selector (JS)
* A pattern that can be used with a query method to find and return (select) references to specific HTML elements on a web page.
* JavaScript selector syntax follows the same rules as the selector syntax used by [CSS selectors](#selector-css). 
#### Syntax
* The rules and structure of a language (including programming languages) that allow it to be understood. Code structure, symbols and keywords are all part of JavaScript's syntax.
#### Web triad
* A collection of three computer languages, [Cascading Style Sheets (CSS)](#cascading-style-sheets-css), [HyperText Markup Language (HTML)](#hypertext-markup-language-html), and [JavaScript (JS)](#javascript-js), that are found on most, if not all, web pages on the internet.

### Modifications and Extensions
#### Modifications
* The exercises can also be run as a large group (a mix of `we` & `you`), if breakout rooms aren't an option.

#### Extensions
* If all the content is completed, the content for Part 2 is included as "stretch" content and can be started.

_More coming soon!_

---
[^syntax-1]: JavaScript Syntax 1: Basics of JavaScript syntax (keywords, symbols); dot notation to invoke an object's methods or access its properties, e.g. `objectName.someProperty`.  
[^syntax-1-5]: JavaScript Syntax 1.5: Comments `//`, objects  
[^syntax-2]: JavaScript Syntax 2: Arguments, text strings, variables  
[^syntax-3]: JavaScript Syntax 3: Arrays and lists  
