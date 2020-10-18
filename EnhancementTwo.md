# CS-499 ePortfolio

## Introduction - Data Structures and Algorithms Artifact

This artifact was part of my Final Project from CS-405 Secure Coding, which I took in September 2019. In that class, I was given a small C++ project with five source files and I was to find vulnerabilities and security flaws in the project code. As part of the Final Project in that class, I created a document that listed the vulnerabilities and security flaws I found and the solutions I implemented.
My enhancement to the artifact was to apply the same procedures of analysis to a more complicated set of C++ code files and to produce the same type of solutions report.

## Why I Included This Artifact

In this project, I demonstrated my mastery of the following outcomes – analyzing source code using manual and automated testing methods for the identification of potential vulnerabilities and code weaknesses, evaluating the vulnerabilities I identified using best practices and industry standards, and describing the implications on non-secure code, modifying the code by correcting weaknesses and reducing vulnerabilities, and recommending testing processes and necessary protocols for producing secure code.

I chose the artifact for the following reasons:
- It showcases my ability to develop secure code.
- It displays my skill in analyzing existing code for vulnerabilities and security weaknesses and in fixing that code to eliminate risks.

## Using this Artifact

The entire artifact C++ source file shows the inclusion of block and line comments that make the code more understandable. The addition of the comments will show that I can read, understand and document code. I created a separate document with details on the vulnerabilities and security flaws I found in the code. That summary list shows that I can analyze one or more code files and determine where weaknesses, security flaws and bad coding practices exist, and how I fixed them to produce robust code.

## How this Artifact Was Improved

The artifact was improved by removing code vulnerabilities and security weaknesses and by adding block and line comments. When received, the code had no comments of any form. I added numerous block and line comments to the code.

![Image](images/E2/TopLevelCommentBlockAdded.png)

I changed all the hard-coded string buffer lengths into const int variables and the set the buffers to the assigned length. Nothing is hard coded anymore.

![Image](images/E2/ConstInt.png)

Library functions such as gets and strcpy were changed to a secure version of the function gets_s and strcpy_s that includes the length of the data to be processed.

![Image](images/E2/Strcpy.png)

Removed all inline string literals from the code and placed them together for easy reference. Each string is identified by a static const char*  value.

![Image](images/E2/StringLiterals.png)

Comments were added to all of the code, below is an example of comments added to a loop.

![Image](images/E2/CodeComments.png)

## What Did I Learn By Enhancing The artifact

When inspecting the artifact visually, I used the SEI CERT C Coding Standard (Svoboda, 2018) as my guide when looking for vulnerabilities. The Software Engineering Institute (SEI) "was established in 1984 as a federally funded research and development center" (Software Engineering Institute, n.d.). The coding standards developed at SEI included support for many programming languages. I used the standards that were developed for C and C++ when reviewing the Railway Reservation System. I learned about coding standards and the standards for developing secure code that mitigates weaknesses and security flaws.
I also reviewed and used several static analysis tools in the process of improving the code I selected. Two of the tools easily integrated with Visual Studio, a third tool ran from the Windows command line with the path and name of the file provided.

The only challenge I faced was the amount of time it took to modify the original code with all of the changes that needed to be made. After doing a visual inspection of the code, and running two static analysis tools on the code, I needed to make lots of changes to functions and character strings. Then I began slowly walking through the code and adding comments to the code. Understanding and then documenting the code took more time than the inspections I had performed.

### Portfolio Links

**Porfolio Links**<br>
* [Professional Self-Assessment](index.html)<br>
* [Refinement Plan & Code Review](CodeReview.html)<br>
* [Enhancement One - Software Engineering & Design](EnhancementOne.md)<br>
* [Enhancement Two - Data Structures & Algorithms](EnhancementTwo.md)<br>
* [Enhancement Three - Databases](EnhancementThree.md)
