=# Kiosk Warriors
Group Senior Project Front-facing Website


## Roles
Evan - Scrum Master / PM<br>
Brendan - Full-stack<br>
Jack- Communications Lead<br>
Frank - Tech lead<br>
Jason - Frontend<br>
Geran - Documentation/Backend<br>

## Synopsis
The purpose of the project is to automate the employer/student interactions during the career fair. This includes signing up for and signing into interviews. Employers can create as many schedules as needed depending on how many interviewers they decide to bring to interview day.  After determining which students they will interview, employers can schedule the students on any of their schedules as long as the student is available during the chosen interview block. Each student will also have their own schedule which will let them view, cancel, and check in to interviews. When a student checks in or cancels an interview, the interviewer gets notified via a change in the status of the interview object on their schedule. The student’s schedule view will also help the student know where to go for their interview by including details such as which “zone” they will be interviewed in. The application must also be able to export all scheduled data to Symplicity’s systems. 

## Hours
#### Fall Semester
| Name                 | Role                        | Week 2 Hours | Week 3 Hours | Week 4 Hours | Week 5 Hours | Week 6 Hours | Week 7 Hours | Week 8 Hours | Week 9 Hours | Week 10 Hours | Week 11 Hours | Week 12 Hours | Week 13 Hours | Week 14 Hours | Week 15 Hours |
| -------------------- | --------------------------- | ------------ | ------------ | ------------ | ------------ | ------------ | ------------ | ------------ | ------------ | ------------- | ------------- | ------------- | ------------- | ------------- | ------------- |
| Brendan              | Full-Stack                  | 3            | 3            | 3            | 5            | 4            | 7.5          | 3            | 12           | 4.5           | 3             | 7             |               |               |               |
| Evan                 | Scrum Master/PM             | 3            | 3            | 3            | 5.25         | 3            | 2            | 4            | 4            | 4.5           | 5             | 4             | 2.5           | 8             |               |
| Frank                | Tech Lead                   | 3            | 3            | 3            | 4            | 2            | 5            | 4            | 8            | 10            | 6             | 23            |               |               |               |
| Geran                | Documentation / Backend     | 3            | 3            | 3            | 4            | 4            | 3            | 4            | 9            | 4             | 6.5           | 8.5           | 7.5           | 3             |               |
| Jack                 | Communications Lead/Backend | 3            | 3            | 3            | 5            | 3            | 3            | 4            | 5            | 10            | 2.5           | 3.5           | 2.5           | 3             |               |
| Jason                | Frontend Dev                | 3            | 3            | 3            | 6            | 3            | 3            | 3            | 4            | 5.5           | 3             | 8             | 7.5           | 3             |               |
| =/=                  | Total Hours for Week        | 18           | 18           | 18           | 29.25        | 19           | 23.5         | 22           | 43           | 38.5          | 26            | 54            | 15            | 17            | 0             |

#### Spring Semester
| Name                 | Role                        | Week 1 Hours | Week 2 Hours | Week 3 Hours | Week 4 Hours | Week 5 Hours | Week 6 Hours | Week 7 Hours | Week 8 Hours | Week 9 Hours  | Week 10 Hours | Week 11 Hours | Week 12 Hours | Week 13 Hours | Week 14 Hours | Week 15 Hours |
| -------------------- | --------------------------- | ------------ | ------------ | ------------ | ------------ | ------------ | ------------ | ------------ | ------------ | ------------- | ------------- | ------------- | ------------- | ------------- | ------------- | ------------- |
| Brendan              | Full-Stack                  |              |              |              |              |              |              |              |              |               |               |               |               |               |               |               |
| Evan                 | Scrum Master/PM             |              |              |              |              |              |              |              |              |               |               |               |               |               |               |               |
| Frank                | Tech Lead                   |              |              |              |              |              |              |              |              |               |               |               |               |               |               |               |
| Geran                | Documentation / Backend     |              |              |              |              |              |              |              |              |               |               |               |               |               |               |               |
| Jack                 | Communications Lead/Backend |              |              |              |              |              |              |              |              |               |               |               |               |               |               |               |
| Jason                | Frontend Dev                |              |              |              |              |              |              |              |              |               |               |               |               |               |               |               |
| =/=                  | Total Hours for Week        | 0            | 0            | 0            | 0            | 0            | 0            | 0            | 0            | 0             | 0             | 0             | 0             | 0             | 0             | 0             |

## Domain Model
![Domain Model](domain_model.png)

## Development Methodology
### Reasoning
Our team has decided to go with an agile methodology to achieve the frequent deliverables required for this project. There are a few main factors contributing to our decision: <br>
-Frequent customer involvement<br>
-Evolutionary artifacts<br>
-Rapid Prototyping<br>
-Relatively simple system design<br>
-Real-world and educational experience<br>
### Chosen Methodology:
Scrum is our chosen methodology, and we will be using Trello to track our backlog of tasks/stories for development. The board will have the following 5 active columns: <br>
-Sprint Backlog<br>
-In Progress<br>
-Ready for Tests<br>
-In Tests<br>
-Done<br>

### Metrics:
Sprint Velocity: N/A <br>
Learnability: N/A<br>
Ease of use: N/A<br>
Defects: N/A<br>
Test Metrics:N/A<be>

## Planned Milestones
All due dates are subject to change as we develop the application and things may be pushed back (and most likely will) so we can incorporate any feedback if needed.

|            Milestone           |                                                    Description                                                   |      Expected Date     |                 Status                 |
|--------------------------------|------------------------------------------------------------------------------------------------------------------|------------------------|----------------------------------------|
| Wireframes                     | Wireframe for the prototype.                                                                                     |          10/9          | Complete                               |
| Project Set-up                 | Have the development environment set up for individual work                                                      |          10/16         | Complete                               |
| Pipeline                       | Pipeline for deploying to a development server                                                                   |          10/26         | Complete                               |
| Data Model                     | Schema of our database.                                                                                          |          10/16         | Complete                               |
| System Architecture            | A higher level of architecture for <br>our system.                                                               |          10/16         | Complete                               |
| Authentication With Simplicity | Have a working connection/sign in <br>with simplicity APIs.                                                      |          10/23         | N/A                                    |
| Scheduling                     | Have a working view for employers and students.                                                                  |          11/30         | Started - on track                     |
| "Why is Our Project Important?" Video | Class Deliverable                                                                                         |          11/29         |                                        |
| First End-Of-Semester Presentation    | Class Deliverable                                                                                         |          12/11         | Started                                |
| Interview Notifications        | Notifications in schedules for employers <br>that a student has arrived (silently).                              |          12/11         |                                        |
| First End-of-Semester Project Review Document  | Class Deliverable                                                                                |          12/15         |                                        |
| First End-Of-Semester Retrospective            | Class Deliverable                                                                                |          12/16         |                                        |
| Administration Tools           | Administration tools that are quality of <br>life for RIT/Schools to manage information. <br>Developed as we go. |           2/19         |                                        |
| Finalized Midterm Review Document              | Class Deliverable                                                                                |            3/9         |                                        |
| Feature Complete               | All of the necessary features have been implemented.                                                             |           3/31         |                                        |
| Second Semester Code Freeze    | No more feature development, <br>only bug fixes and such.                                                        |      4/5 at latest     |                                        |
| "What are the Results of Our Project?" Video   | Class Deliverable                                                                                |           4/16         |                                        |
| Technical Report               | Class Deliverable                                                                                                |            5/4         |                                        |
| Final End-Of-Semester Team Presentation        | Class Deliverable                                                                                |            5/7         |                                        |
| Final End-Of-Semester Retrospective            | Class Deliverable                                                                                |            5/9         |                                        |
| Finalized Project Review Document              | Class Deliverable                                                                                |            5/9         |                                        |


## Communication Plan
Our communication plan is to meet with our stakeholders every Thursday to go over requirements, the project process, and any questions we have concerning the project. Every time we finish a deliverable, the communications lead will send it to both our coach and the sponsors for their feedback. We also have our coach present in the discord, so he is easily able to get in contact with us whenever needed. Furthermore, additional stakeholder management will come in the form of demoing our prototype to them at the end of each development cycle.

## Keywords
Career, Fair, Scheduling, Symplicity, Interview
