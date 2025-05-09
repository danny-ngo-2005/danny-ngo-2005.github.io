---
layout: essay
type: essay
title: "Final Project Idea"
date: 2025-04-01
labels:
  - Software Engineering
  - Nextjs
---

<img width="200px" class="rounded float-start pe-4" src="https://www.thoughtco.com/thmb/OwJ0ejT-4-IS9_O3yxZanVc82Vw=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc()/GettyImages-829436700-5b297785fa6bcc0036065232.jpg">

Collaborator with: Royce Jarvy Uy

## Overview
Problem: To be successful in class and in their education, students must be well prepared for what their class entails and have whatever the materials are necessary. However, some students lack the proper materials needed in class due to either students entering college for the first time or students having to attend other activities that could conflict with their education.

Solution: Rather than go through each individual syllabus of each class, We proposed is to build a website that gathers all the classes that a particular student enrolls in, and makes a list detailing all the materials required for each class and the total cost. There will also be an account for a professor to log in and be able to add in their own classes with their respective material.

## Mockup Page Layout
The website will first send you to the home page that will display the title and description of its intent. The header will contain two types of headers: a registration page where users can sign up, and a login page for existing users. The footer will contain an About Us section and a Contact Us section, along with other bootstrap icons for display(i.e. Twiiter, Instagram).

Two types of user pages will be present: one for students and one for teachers

  For students:

  <ul>
    <li>
      Given a new user page, an empty list will be displayed. If the user's page does have a class in their list, the user should be able to delete that class on that list page.
      <ul>
        <li>
          A page will be dedicated for students that want to add classes. The only element choice is the class itself.
        </li>
        <li>
          Once the student is done filling their list with the classes that they enrolled in, another page will be the total material page where it will:
          <ul>
            <li>
              Show all classes that the student pick
            </li>
            <li>
              All the materials that the student needs
            </li>
            <li>
              Total cost of materials
            </li> 
          </ul>
        </li>
      </ul>
    </li>
  </ul>

  For professors:
  Very similar to the student page. However, the main configuration is the page for adding classes.
  <ul>
    <li>
      When adding classes, several options must be applied for it to be a valid class
      <ul>
        <li>
          Name of class, i.e. ICS 311, PHYS-272.
        </li>
        <li>
          The materials that are needed for the class
          <ul>
            <li>
              Conditions of specified materials, i.e. books, calculators, etc.
            </li>
            <li>
              Quantity of materials, i.e. number of pencils, notebooks, etc.
            </li>
            <li>
              Cost of each material
            </li>
          </ul>
        </li>
      </ul>
    </li>
    <li>
      Total cost will be calculated for all materials for the class
    </li>
  </ul>

  
## Case Ideas:
<ol>
  <li>
    Incoming freshmen who may be inexperienced with the "flow" of college classes. Compiling their materials on a single app could help them be prepared for their courses.
  </li>
  <li>
    Foreign/international students who may be unfamiliar with required materials for their classes.
  </li>
  <li>
    Outside of syllabi, professors are able to help their students prepare for the class in upcoming semesters.
  </li>
  <li>
    Other students can get an idea of what kinds of materials are used in classes they may take in the future.
  </li>
  <li>
    Full-time students who could be occupied in multiple different activites.
  </li>
</ol>

## Beyond the Basics
  -  Whenever a professor needs to revise a class, an email will be sent to every student who enrolls in that class, in order to update them of any additional materials required or if they will not need that material.
  -  Same classes with different professors may cause confusion since different professors would require students to bring different materials, so classes could also have a unique ID to represent that class with that required materials.
