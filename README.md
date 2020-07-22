# ACCESS

### General info

ACCESS was developed by Alexander Hofmann, Philip Hofmann, Mervin Cheok and Luka Lapanashvili, during their master studies in computer science for the Departement of Informatics at university of zuerich UZH. These developers subsequently got hired by the university to deploy, maintain and extend this system for a semester, resulting in around 450 students solving, handing in and instantly recieving grades for their weekly python programming exercises.

More information is available on our [website](http://access.ch.tiberius.sui-inter.net/de/ "website"), in our [report](https://raw.githubusercontent.com/Phhofm/papers/master/ACCESS_Report.pdf "report"), or in our [gitbook](https://mp-access.gitbook.io/access/development/getting-started "gitbook").

We made our tool open source. So anyone can feel free to use this tool for their own courses or to fork it and extend the tool with further functionality or simpler deployment options.

This repository only contains this README, you find the code of the project in the following repositories:

The [Infrastructure](https://github.com/Phhofm/ACCESS_Infrastructure "Infrastructure") repository contains the configuration and docker-services needed for our application like postgres, mongodb, keycloak

The [Backend](https://github.com/Phhofm/ACCESS_Backend "Backend") repository contains our java spring backend and finally the 

[Frontend](https://github.com/Phhofm/ACCESS_Frontend "Frontend") repository contains the react frontend.

You can find all of these repos and more information on our [organizational page](https://github.com/mp-access "organizational page") where I forked the repositories from

### Context

The Department of Informatics at the University of Zürich (UZH) observed a rapid increase  in  students  for  the  introductory course "Informatics 1" over  the  last  years.This lecture involves weekly exercises for each student that get manually corrected by tutors that the department hires each semester. In 2018, the department hired 12 tutors to cope with the increasing demands, which resulted in a workload of 30 to 35 exercises to be corrected by each tutor per week. This system of tutors manually correcting the exercises is not scalable, and there are no signs that the number of participants of this course will stabilize nor decrease.

### Approach

We envisioned an automated system as a solution to the mentioned problem, which automatically corrects and grades the student exercises for this lecture,  while allowing course authors to edit content with their own tools of choice. Furthermore each edit done by the content author will be versioned for transparency. The system allows tutors to switch attention from correcting programming exercises to assisting the students. In contrast to the current situation, the system is scalable and could easily handle a further increase in student numbers. Furthermore, our envisioned system could provide the students with instant feedback, thus enhancing the learning experience. In this thesis, we come up with a design and a system that could solve the mentioned problems. We subsequently got hired by the university to deploy and put in operation our prototype for the semester, while maintaining and updating and extending the live-in-production running prototype with several features needed by the course authors of the "Informatics 1" lecture to adapt the system to the requirements of their respective exercises. The system had then been used for a semester by 450 students to solve their weekly exercises, and we received mostly positive feedback concerning our system.
