<link rel="stylesheet" href="../../css/github.css">
<link rel="stylesheet" href="../../css/styles.css">

![Toi Ohomai Logo](../../images/toi-logo.jpg)

# COMP.5202 Fundamentals of Programming & Problem Solving
# Semester 2, 2017

<table>
    <tr>
        <th>Assessment</th>
        <th>Type of Assessment</th>
        <th>Due</th>
        <th>Marks</th>
        <th>Weighting</th>
    </tr>
    <tr>
        <td>Assessment #1</td>
        <td>Practical programming assignment</td>
        <td>13th October 2017, 4pm</td>
        <td>130 Marks</td>
        <td>50%</td>
    </tr>
    <tr>
        <th colspan="5">
        Learning outcomes Assessed:
        </th>
    </tr>
    <tr>
        <td colspan="5">
        <ol><li>Apply programming concepts and tools to system management tasks.</li>
        <li>Demonstrate awareness of procedural and object oriented programming.</li>
        <li>Apply principles of implementation (user testing, deployment).</li>
        <li>Demonstrate programming using core logic and mathematical concepts such as problem solving methods, critical thinking, abstract reasoning; and systems thinking.</li></ol>
        </td>
    </tr>
</table>

# Instructions

This is an individual assignment to be completed using visual studio code.

<br>
Please ask any questions about the assignment directly with your tutor or post it in the slack channel.

<br>
The assignment needs to be submitted using git. You will submit it using 2 links. One for Part A and one for Part B.

### NOTE:  This assessment contributes to 50% to your overall grade in COMP.5202

<div style="page-break-after: always;"></div>
# Part A – Object oriented programming

## Instructions

* Read the scenario and program specifications for PART A below.
* Create a One page website in Visual Studio Code for each of the questions in Part A, based the specifications given for each. 
* Ensure that you document (or comment) your code thoroughly (include a description of the program, the name of the developer and the version) and name your classes, methods, arrays and variables effectively.
* Note: If you cannot get some of your code to compile or if it causes your program to crash immediately, comment out that piece of code so that your program will still run.

## Scenario

Rotovegas Airways, a small local airline, has just purchased a computer for its new automated system. 

You have been asked to develop a prototype of the new system.  This will be developed in three parts.  The first part is to be a program which will replicate the airline staff login system, the second is to replicate the airline seat booking system and the third one is to replicate the staff pay system.

## Question 1: Methods - Airline Login System

You are to write a single webpage to replicate the airline login system.

The initial screen should contain a welcome message and then prompt the user to set up their staff login by entering the following:
* a username (which must be 8 characters long)
* a password (which must be entered twice i.e. Pwd1 and Pwd2 and both entries must match)

All three of these (the username and two passwords) should be declared as static variables that are accessible by all methods in the program.

 The program should contain two static methods as outline below:

* A ValidateUsername method that checks the username is at least 8 characters long 
* A ValidatePassword method that checks both password entries match

Appropriate error messages should be displayed if the username and passwords do not meet the correct criteria, then giving user an opportunity to try again.

If all data is correct, the message **“Username and password has been set”** should be displayed.


