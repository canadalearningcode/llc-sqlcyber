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
Dataset | Multi | SQLite database file (clccyber.db): [https://bit.ly/llc-sqlcyber-db](https://bit.ly/llc-sqlcyber-db)

## Versioning

### 1.0.0-a.1 (July 2023)

* Initial release


---

## Workshop Overview

### Description

With digital platforms and services being an increasingly inescapable part of our day-to-day lives, have you ever stopped to ask yourself, _"Is my personal data safe? Is my sensitive data being handled with care? Is my privacy being protected?"_ **Cybersecurity** is the practice of establishing and maintaining confidentiality, integrity, and availability of information, and it is the job of cybersecurity professionals to protect networks, devices, people, and data from unauthorized access or criminal exploitation.

Cybersecurity professionals apply their knowledge and skills alongside a wide variety of tools and best practices to establish preventive security measures or, in the event of an attack or attempted breach, understand the impact of such an event and do their best to mitigate any damage caused.

#### **Why learn SQL?**

One of the most useful tools in their toolbelt is usage log data recorded by their systems and stored in databases, however having large amounts of data at their disposal creates a new challenge: how can this data be made useful?

**Structured query language (or SQL)** is one of the most commonly-used computer languages for working with data and communicating with databases. SQL is a powerful language that allows us to extract useful insights from large quantities of data stored in databases. Cybersecurity professionals need to be able to efficiently sift through large amounts of data to be able to find irregularities that may indicate that their systems have been—or are being—targeted for an attack and SQL is a handy tool to accomplish that.

#### **The bottom line:**

Whether you've heard of databases or are brand new to them, this experience is designed for you. In this experience, you will learn the basics of SQL through a cybersecurity lens. Through hands-on exercises that will have you writing and executing SQL queries, you will learn to retrieve, filter, and sort data stored in a database to be able to address common cybersecurity problems and questions that cybersecurity professionals deal with on a regular basis.

---

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
Preamble | 1-12 |
Data | 13-18 |
Cybersecurity: Preparing for a storm | 19-26 |
Databases | 27-30 |
Today's tool | 32-28 |
Exercise 0: `SELECT` | 45 |
Exercise 1: `SELECT` & multiple columns | 53 |
Exercise 2A: `WHERE` | 58 | 
Exercise 2B: `WHERE` | 61 |
Exercise 2C: `BETWEEN`, `NOT`, and `IN` | 64 |
Exercise 2D: SQL functions | 68 |
Exercise 3A: Dates and `LIKE` | 70-71 |
Exercise 3B: Scavenger hunt | 72 |
Exercise 4A: `ORDER BY` | 74 |
Exercise 4B: `ORDER BY` | 75 |
Exercise 4C: _"Hope it's a good one!"_ | 76-77 |
Exercise 5: `GROUP BY` | 84 |
Related tables and `JOIN` | 85-92 |

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
* [ ] General understanding of data, databses and cybersecurity.
* [ ] Basic SQL syntax (common keywords and symbols; structure) .
* [ ] SQL wildcards: `*`, `%`, `_`
* SQL keywords used for read operations, such as:
  * [ ] `SELECT`
  * [ ] `FROM`
  * [ ] `WHERE`
  * [ ] `ORDER BY`
  * [ ] `GROUP BY`
  * [ ] `JOIN`
* The behaviour and application of common **SQL comparison operators**, such as:
  * [ ] `=`, `>`, `=>`, `<`, `=<`
  * [ ] `NOT`
  * [ ] `AND`
  * [ ] `IN`
  * [ ] `BETWEEN`
  * [ ] `LIKE`
* The behaviour and application of common **SQL functions**, such as:
  * [ ] `COUNT()`
  * [ ] `MIN()`
  * [ ] `MAX()`
  * [ ] `AVG()`
  * [ ] `SUM`
  * [ ] `SUBSTRING()`

## Delivery Notes

* __Minimize the time spent on slides before coding begins.__ This workshop is fairly dense, and while these early slides provide important context (which is why they are included), trying to maximize learner interaction at this early stage is less valuable than getting into, and through, the content and exercises.
* If this is being delivered online and mentors & breakout rooms are being used, consider still starting each exercise as the whole group, to get the ball rolling. Encourage mentors or co-facilitators to actively move learners through the exercises when in breakout rooms.
* Solutions for each exercise are included either in the slides or in the slide notes.

## Supplemental Resources

### Key Terms and Concepts

#### Boolean value
* A value that is either `true` or `false`.
* Boolean values are often the result of a comparison [operator](#operator-sql) and can be used to filter data based on whether a specified condition is `true` or `false`.

#### Clause (SQL)
* A part of a query built around a particular SQL keyword (e.g., `SELECT`, `WHERE`, `ORDER BY`).
* Clauses are used to describe what data should be returned by a database.

#### Data
* Pieces of information usually formatted in a specific way.
* Data can have many forms, including numbers, pictures, words and audio.

#### Database
* A structured collection of data which can be queried.
* [SQLite](#sqlite), the database technology used in this experience, is a kind of database known as a [relational database](#relational-database).

#### Development environment
* _See [integrated development environment (IDE)](#integrated-development-environment-ide)._

#### Integrated development environment (IDE)
* An application that is used to write code. It often has features that make writing code easier, such as language-specific syntax highlighting. It also often has tools to facilitate development-related tasks such as version control.

#### Keyword (SQL)
* A word that carries a specific meaning in the context of an SQL query.
* Keywords are *reserved words*, which means that these specific words can only ever be used for a predetermined purpose, and cannot be freely used or reassigned.

#### Non-relational database (SQL)
* Sometimes called NoSQL (for "Not only SQL"), this kind of database structure is often used to store less structured data (e.g., documents that can have different parts or sections), relationships between data (called a graph), or short-lived, temporary data (e.g., a list of user logins in the past 24 hrs)
* Non-relational databases trade the structure and consistency that is part of relational databases for flexibility and speed.
* This type of database structured is in contrast to [relational databases](#relational-database-sql)

#### Operator (SQL)
* Special symbols or [reserved words](#keyword-sql) that can be used to compare, calculate, and manipulate data.
* Common **comparison operators** (usually found in a query's `WHERE` clause and which usually return a [boolean value](#boolean-value)) include: `=`, `>`, `=>`, `<`, `=<`, `NOT`, `AND`, `IN`, `BETWEEN`, `LIKE`.

#### Query (SQL)
* A question for a database, made up of one or more [clauses](#clause).

#### Relational database (SQL)
* A type of database that stores related data together in tables, called relations (e.g., a `PERSON` table). Technologies built on these, such as [SQLite](#sqlite), are often called relational database management systems or RDBMSes.
* Table **columns** describe attributes of the data (e.g., the `first_name` and `last_name` of a person).
* Table **rows** represent a data object (e.g., an individual person).
* Rows are uniquely identified by an ID (similar to how people can be identified by social insurance number or `SIN`) called primary keys.
* This type of database structure is in contrast to [non-relational databases](#non-relational-database-sql)

#### SQL
* Structured query lanaguage.
* A computer language used to access and manipulate data contained in a database.

#### SQL Online IDE
* A web-based [integrated development environment (IDE)](#integrated-development-environment-ide) used to work with different kinds of database technologies without needing to install an application.
* URL: [https://sqliteonline.com](https://sqliteonline.com)

#### SQLite
* A small, self-contained, SQL-based database management system.

#### Syntax
* The rules and structure of a language (including programming languages) that allow it to be consistently understood and executed.

### Modifications and Extensions

#### Modifications
* The exercises can also be run as a large group (a mix of `we` & `you`), if breakout rooms aren't an option.

#### Extensions

_More coming soon!_