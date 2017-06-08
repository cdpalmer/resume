# Cody Palmer
Denver, CO 80222 - cody.palmer08@gmail.com - [Github](https://github.com/cdpalmer)

---

### Objective

___

To lead teams solving challenging problems while bridging the gap between business and engineering

### Summary of Qualifications

---

- Experienced in both backend and frontend web development positions
- Lead a frontend 'reskin' using Ruby on Rails, javascript, Sass, and Foundation
- Head engineer on a RESTful API with Ruby on Rails and Postgres to spec with JSONAPI standards
- Introduced and anchored features for Pivotal Tracker

### Education

---

###### CISSP certification - July 2015
Certification number: #410327

###### University of Iowa, Iowa City, Iowa
Bachelor of Art in Computer Science, December 2008

### Engineering Experience

---

**Software Engineer**

Pivotal Labs	(_Sept, 2015 - Present_)

- Created keyboard shortcut prototype for the Pivotal Tracker agile management tool
- Anchored/Lead a feature using a mixture of Backbone and React.js
- Developed new endpoints in custom Ruby on Rails endpoints

**Sr Software Engineer (Contract)**

Oppenheimer Funds	(_April, 2015 - August,2015_)

- Optimized and debugged production level defects in large existing web application
- Extended search functionality using SOLR search architecture
- Proposed and implemented improved use of Redis caching

**Software Engineer**

NCC Group Domain Services	(_June, 2013 - April, 2015_)

- Developed APIs and front-end applications for a Service Oriented Architecture (SOA) with Ruby on Rails
- Continually chosen as lead developer for large features and products
- Assumed roles as project manager and developer for multiple applications
- Built quality front-end applications using HAML, Javascript, Foundation, Sass, Neat and Bourbon

**Software Engineer**

Charles Schwab	(_Feb, 2013 - June, 2013_)

- Added functionality to an existing application that is exposed to internal and external customers in ASP .NET
- Drove pilot program to test several web applications in Windows 8 to help future transition

**Software Enginner**

Rockwell Collins (_Dec, 2011 - June, 2013_)

- Built manual and automated scripts in C#/.NET for the End Cryptographic Unit (ECU)
- Developed C#/.NET application to interface with the ECU
- Created test plans to satisfy NSA Type 1 cryptographic standards
- Exercised knowledge of cryptography for integration and debugging

**Software Technician**

Rockwell Collins (_Aug, 2010 - Dec, 2011_)

- Prepared product for Type 1 NSA security verification 
- Created GUI application for data file processing in Java
- Implemented and stress tested new functionality for a CSS (Common Cryptographic Subsystem) product


## Side projects

### Ruby
#### [Loan payoff calculator](https://github.com/cdpalmer/debt_payoff_calculator)
  
  Ruby script that will take in a hash of the details to all your loans, e.g. 
```
{
  title: "Sallie Mae",
  interest_rate: 0.065,
  original_balance: 10000,
  current_balance: 10000,
  min_payment: 200
},
{
  ...
}
```
   With that information, you can run the script with one input (how much you 
   budget towards debt) and it will spit out how many months it will take to pay
   off all of your debt using the avalanche method (however, could be tweaked easily
   to use the snowball method).  These methods are just what debts get paid first with
   any spare money you have each month.
   
#### [Boggle Solver](https://github.com/cdpalmer/boggle_solver)

Given a board and a Dictionary, it leverages a Trie to discover all words that are on 
the boggle board.  Used as follows:

```
master ✔ $ ruby boggle_the_ripper.rb
Starting Boggle Solver Engine!
 This is our working board:
    X X B X X
    X X A G X
    X E R X Y
    X X X X D
    X X X C O


*   Found word! (bag)
*   Found word! (bare)
*   Found word! (a)
*   Found word! (are)
*   Found word! (rag)
*   Found word! (gab)
*   Found word! (grab)
*   Found word! (cod)
*   Found word! (cody)
*   Found word! (doc)


 These are all found words:
["bag", "bare", "a", "are", "rag", "gab", "grab", "cod", "cody", "doc"]
```

### Java
#### Blackjack

Command line game where you could establish your budget and play blackjack.  It would
accept all actions (`Hit`, `Double Down`, `Split`, `Stand`), and you could play until
you ran out of money or the shoe is finished.  It would also keep a running count for
card counting and would quiz you what the running count was.  I have no idea where this
code is anymore.  Lost in the ether.

#### Trash can Mint

Loving nickname for a desktop Java app that would do a really crappy version of what
Mint currently does.  You would copy and paste your checking account transactions
(nope, didn't even use CSV... Hey! This was the first 4 months of my career!) where 
the app would parse all descriptions, deductions, and credits and give you a summary
of your monthly expenditures.  It also had an similar feature of the debt payoff calculator.
Code?  Also lost in the ether.


### Swift

#### Blackjack Ninja

Current work in progress.  iOS game that trains you to learn to play Basic Strategy.
Instead of the flash-card style that most apps use, you play a game that incrementally
teaches you different parts of Basic Strategy.  Just imagine a mix between Super Mario
Brothers, Guitar Hero, Zelda, and Blackjack.  Stay tuned

### Rails

#### [Kangaroo](https://github.com/cdpalmer/kangaroo)

Ever go on movie marathons?  Or movie hop into another movie after the first one was over?
Well I made an app that pulled in all movie showtimes and theaters in a 15 mile radius
of a zip code you entered and would display to you every combination of movie marathons
you could see at a given theater.
