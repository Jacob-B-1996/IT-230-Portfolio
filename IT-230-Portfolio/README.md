# IT 230 Portfolio — Software Development

## Project Overview

For IT 230, I worked on two versions of a student course registration application: ConsoleRegisterStudent for Final Project Part I and WPFRegisterStudent for Final Project Part II. The goal was to let a student choose from seven IT courses while making sure they could not register for the same course twice or go over nine credit hours. Each course counts as three credits. The applications needed to make registration straightforward and let the student know whether a selection was accepted or rejected.

## What I Did Well

I think I did a good job working through the registration rules and checking that the results were right instead of just getting the program to run. In the console project, I corrected the course-number range, duplicate-course checking, and credit-hour validation. I tested selecting the same course twice, trying an invalid number, and adding a fourth course after reaching nine credits. In the WPF project, I tested those limits again and checked that the course list and total credits updated after a successful registration.

## Console vs. WPF Design

The console version uses a numbered course menu and text prompts. It works well for entering a course choice and seeing messages about the registration, but the user has to type responses and read the results in the console. The WPF version is more visual. It has a dropdown to select a course, a registration button, a list showing registered courses, a box showing total credit hours, and pop-up messages for confirmations or problems. These features help the user see their choices and current registration without remembering numbers or commands. I think the WPF design is easier to follow, while the console version helped me understand the program logic more directly.

## Debugging and Coding Approach

I approached the projects by checking what the program was supposed to do, reviewing the existing code, and testing one behavior at a time in Visual Studio. For Part I, I kept the original structure and focused on the conditions that were causing incorrect registration results. For Part II, I checked how the Course class and button-click code worked together to track registered classes and credits. Testing duplicate selections, the nine-credit limit, and the case where no course was selected helped me catch problems that might not show up during a normal registration. I can use this same process in future projects: understand the requirements, make focused changes, and test both normal and error cases.

## Challenges and What I Learned

One challenge was making sure the registration rules worked in both a text-based program and a graphical application. The console project needed the right validation logic so a valid course could be added without allowing duplicates or extra credits. In WPF, I also had to make sure the screen matched what was happening in the code, including the registered-course list and total credits. Working through those differences helped me see how the same requirements can be implemented through different user interfaces. I also learned that a program can compile and still have logic errors, so testing the actual output is an important part of development.

## Portfolio Artifacts

- [Final Project Part I — ConsoleRegisterStudent](Balderas_Jacob_consoleregisterstudent.docx)
- [Final Project Part II — WPFRegisterStudent](Balderas_Jacob_wpfregisterstudent.docx)
