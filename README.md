# User Requirement Document

## for

# Volunteer Management

# System (VMS)

### Version 1.0 approved

### Prepared by Emiliano Garcia (T00667348)

### Almat Bolatbekov (T00667332)

### 2022-10-

**_Copyright © 1999 by Karl E. Wiegers. Permission is granted to use, modify, and distribute this document._**


## 1. User classes

In the given table below you can see the user classes for the Volunteer Management system.

```
User class Type Description
```
```
Certified
Volunteers/
Senior-peer
```
```
Direct/ Favoured Senior peoplereport their need for social supportonce
they will require this service. They are one of themain
users of this system and elderly people will use the
system quite often to find themselves a senior peer for
their basic needs. The senior person will have to give
information by phone to the SPCC employee to register.
They need to see the list of the volunteers that are
appropriate depending on the given information by the
senior person.
```
```
Senior people Direct /
Favoured
```
```
Volunteers will see the list of the senior people who are
in demand of social support services. They put their
information such as personal data, hobbies, and others
in the VMS and have to be approved by the police
certificate check. Volunteers’ services will include
making daily calls to the senior people and reminding
important dates (such as medical appointments).
Moreover senior peer will be responsible for following up
on the social status and mental status of the elderly
person, to report any health issues to the VMS.
Volunteers will not be able to see the student’s or
senior’s information unless he or she is matched with
them. They will use the VMS more than the senior
people, to see any updates of their volunteer activities.
```
```
SPCC
Employee
```
```
Direct SPCC employees receive calls from senior people to
collect their information over the phone, and create
profiles for senior people at the VMS. They are also able
to change this data later in the profiles if any updates
occur. Each SPCC employee will use the system the
same as the senior person as all the process is going
through them. They need to call a volunteer senior peer
when the senior person reported about the needed
support.
```
```
Volunteer
Administrator
```
```
Direct Volunteer administrators process the data of the newly
registered volunteers and make decision about their
```

```
application, if the profile looks ok their profiles go to the
police background check.
They also should verify the educational certificates of
the volunteers who need to teach young kids. Volunteer
administrator will receive the forecast number of cases
for the next week by the VMS and receive any report
about any issues of the volunteers’ commitment
activities to take proper actions. The are going to use
the system often but not the main features of the VMS.
```
```
Police officers Indirect Police officers will receive the volunteer information and
check its background after the volunteer management
approves the application. They will do it only during the
working hours as the BCS is required the manual step to
get approval
```
```
Students/Kids Indirect The Kids will receive the volunteer teaching services but
they will be allowed to use the actual system as the
parents do not like to let the kids use this type of
applications
```
```
Uncertified
Volunteers
```
```
Disfavoured The volunteers who could not pass the background
check system or the application was not good enough
for the volunteer administrator
```
```
School
principle
```
```
Direct The School administration will request volunteers to
teach students. Since the students will not be able to
use the system, the school principle would create an
account and request for the services.
```
## 2. Actors

For this Volunteer Management system we found different actors that are interacting with the
system. The main actors are derived from favored user classes, which are senior people and
volunteers. Each actor has their own goals, you can see them on the table given below.

```
Actor’s name Goals
```

```
Volunteers
1.Create a volunteer account
```
```
2.Reporting status of the senior person\
```
```
3.Find people
```
```
4.Help people
```
```
Senior people
1.Request the volunteer for help with background check
```
```
2.Contact volunteer
```
```
Health department
1.Receive the information about the status of the senior person
```
```
2.Provide better service.
```
```
SPCC Employee
1.Create an account for senior people
```
```
2.Contact volunteer volunteers
```
```
Administrator
1.Check the application and the educational background
```
```
2.Track the volunteers engagement
```
```
School principle 1.Request volunteers with the educational background
```
2. Create an account in the VMS

```
BSC 1.Recieves the volunteer information and check the background
```
```
Customer 1.Report the volunteer
2.Request the volunteer to help
```
## 3. Use cases

The use cases for Volunteer Management system are sorted in the fully dresses, casual, brief use
cases. For each use cases there are description.


Fully dressed
Create a volunteer account - The volunteer writes their information to create a volunteer account.
Help customer (volunteer) - The volunteer who is checked by the BCS and went through the
initial screening of the administrator provides his services for elderly people or students
Request for a volunteer - Senior person or School principle request the for the volunteer help
using the VMS.

```
Use case section Comment
Use case Name Create a volunteer account
Scope Background check system, the system under design
Level User-goal
Primary Actor Volunteer
Stakeholders Volunteer : Help the senior people.
Administrator : Do the initial screening of the volunteer’sapplication, see if the
person is appropriate to be volunteer
Police officer : Check the background of the person
Preconditions
```
1. The person should be real person

```
Post conditions
```
1. The application is received by the volunteer administrator
2. The confirmation message is sent to the applied volunteers
3. The status of the Volunteer’s application process is displayed

```
Main success
scenario 1. Person enters his personal information.
```
2. The person writes the data about his hobbies.
3. The person provide the education certificate.
4. The person checks the whole information before the submission
5. The person submits his information.
6. The person gives an agreement that his information can be used to
    identify his identity or check the background.

```
Extensions 1.1 The information that person is false
1.2 The User can do mistakes when putting the information
1.3 The people can have exactly same information
```

Special requirements Each information should be given

**Use case section Comment**

Use Case Name Find customer

Scope The system under the design

Level User goal

Primary Actor Volunteer

Stakeholders Senior people: Elderly person, who are receiving the service
School principle: Finds the volunteer for this wok using VMS
Students: They are educated by the Volunteer
Volunteer: He is a person who is going to be helping senior people or students

Preconditions

1. Volunteer is approved by the administrator
2. Volunteer is approved by the background check system
3. Volunteer is not able to see the customer’s (senior person or student)
    personal information
4. The status of the volunteer is ‘seeking to help’

Post conditions

1. Confirmation fro the VMS about the finding customer who is ready to be
    helped by volunteer
2. The status of the volunteer is ‘helping’
3. Status of the seniors or school principle is ‘receiving help’

Main success
scenario 1. Volunteer opens a system

2. Volunteer log in to the account
3. See the request notifications from senior people
4. See the list of appropriate candidates to help according to the volunteers
    personal information
5. Select one candidate
6. Volunteer sees if he was approved for this customer
7. He receives the information of the senior person or student


Extensions 1.1 Volunteer is not be able to log in to the account because of some reason
1.2 There are no any senior person or student to help
1.3 the information about the customer is incorrect

Special
Requirements

**Use case
section**

```
Comment
```
Use Case
Name

```
Request for a volunteer
```
Scope The system under the design

Level User goal

Primary Actor Senior people / School principles

Stakeholders Volunteer: He is receiving the notifications in the account
Volunteer administrator: Administrator is able to see all request for volunteers and
send this request to volunteers
Senior people/ School principles: They are requesting volunteer to help with certain
services
SPCC Employee: Can request volunteer for the senior person if he is not able to use
VMS

Preconditions

1. Senior person or School principle have an account
2. The volunteer is approved by administrator
3. The volunteer is approved by background check system

Post conditions

1. The request is delivered to all volunteer who are in status ‘seeking to help’
2. Confirmation of the request

Main success
scenario

1. Senior person, School principle or SPCC Employee opens an app
2. They describe what type of the service is required
3. Select the type of the request (emergency, non-emergency)
4. They sent the request to the VMS
5. Notified that number of volunteers is ready to help
6. Look at the volunteers information
7. Choose like volunteer for this job


8. Receive the confirmation from the Volunteer
9. Volunteer provide his services.
Extensions 1.1 Volunteer can forget about the help or intentionally not to come
1.2 The emergency status request is processes a long time
1.3 Shortage of volunteers
1.4 There is no like volunteer
Special
Requirements

Casual
Treat senior people (Health) - Once the VMS will recieve the status information of the senior
person, they will come to hi, and treat elder person
Check the background (BCS) - The system takes the information of the volunteer and checks the
background of this person, if any crime was done by this person the system reports it to the VMS
Report the status of the senior person (Volunteer) - Volunteer report the status of the senior
person in order to maintain his mental and health status
Do the initial screening - Administrator looks at the application and looks for the education
certificate in order to confirm it. Once everything is done the information is sent to the BCS

Treat senior people (Health)
Main success scenario:

1. Volunteer reports to the VMS of the bad status of the senior person
2. The VMS contacts the Emergency or hospital
3. The hospital receives the senior information (name, address, age)
4. The hospital checks the health condition of the senior person in the database
5. Takes required drugs
6. Drives to the senior person's address
7. Treats the senior person
8. The senior person feels better

Extensions:

1. The senior’s information is not found in the hospital database
2. Driver drive to the false address

Check the background (BCS):
Main success scenario:


1. The BCS receives the volunteers' data
2. The police officer starts the process of the background check manually
3. The check was completed
4. The status of the application is received by the volunteer
5. The information from BCS is processed by the administrator
6. The volunteer is approved

Extensions:

1. The volunteer did not pass the background check
2. The background check system shuts down

Report the status of the senior person (Volunteer)
Main success scenario:

1. Volunteer contacts the senior person
2. The volunteer comes to the senior’s location
3. The volunteer provides his services
4. Volunteer reports the status of the senior person every 1 hour.
5. If something happens to the volunteer he reports it right away to the VMS

Extension:

1. Volunteer forgets to report the status of the senior person
2. The report can be not sent because of the Internet or connection problem

Brief
Track the volunteers’ engagement - Administrator chekcs any complaints for the employers
Create account - the account sis created by the SPCC employee for the senior people.

Do the initial screening (administrator
Main success scenario:

1. The administrator receives the volunteer’s application data
2. The administrator checks for the profile (the first impression)
3. The administrator looks at the education certificate of the volunteer
4. Defines the university or school where a volunteer was educated


5. Contact the University or school to confirm this ability
6. The administrator approves the application
7. Application is sent to the background check system

Track the volunteers’ engagement
Main success scenario:

4. The administrator receives reviews from the customer
5. Looks like the volunteers activates
6. Report the volunteer or make a warning if he received reports including problems that he has
    done
7. If the report on the volunteer was received more than 3-time the administrator deletes his
    account

### 7.1. Use case diagram

The use case diagram represents how the Actors interact with the VSM use cases.


### 7.2. Create new volunteer use case

There are three main use cases that we go into detail and we start by describing the situation of
creating a new volunteer.

```
Use case name Create new volunteer
Subject area Volunteer management
Business event A person wants to help as a volunteer and needs to be registered.
Actors Volunteers
Use case overview Use case to register a new volunteer. It only involves the volunteer
who is the user. Volunteers are required to fill in information and
submit it.
Preconditions Volunteers have available all information needed to answer
questions. Volunteers have some basic technology knowledge in
order to use the system. Volunteers have no accessibility specific
needs that prevents them from using the application.
Termination outcome Successfully submitted profile. Incorrect or invalid information
entered. Failed to submit to the server.
Condition affecting
termination outcome
```
```
Connection to the server is successful. Information entered has the
right format and length. There is no required information missing.
Use case description User opens the system. Inputs all the information required and
uploads any documents for validation. Reviews data entered.
Confirms submission and get verification or tracking ID.
Use case associations Approve new volunteers. Modify existing volunteers. Remove
volunteers.
Traceability to Volunteer Management System (VMS)
Input summary Personal information. Background. Experience. Resume and cover
letter. Certifications. Preferences for volunteering.
Output summary Confirmation code and estimated processing time.
Usability index 8 out of 10
Use case notes N/A
```

### 7.3. Approve new volunteer use case

The second use case consists of approving a new volunteer after we already created it. These
two go hand by hand and are corresponding to the same group.

```
Use case name Approve new volunteer
Subject area Volunteer management
Business event A volunteer submitted their profile and a decision needs to be made
to either approve or deny the request.
Actors Volunteer talent manager.
Use case overview Use case to approve a new volunteer. It only involves the manager
for the volunteers. System user is required to review information
and approve or deny candidate.
Preconditions System has access to the database and can get information.
System labeled volunteers as ready to review and is finished with
police clearance. System is able to successfully display documents
submitted.
Termination outcome Candidate is approved. Candidate is requested to provide more
information or documentation. Candidate is refused.
Condition affecting
termination outcome
```
```
Successful connection to the server and data retrieval. Successful
review of documentation and manager approval.
Use case description System loads all data. System displays required documentation.
Manager approves volunteer. System updates and confirms
volunteer approval.
Use case associations Create new volunteers. Modify existing volunteers. Remove
volunteers.
Traceability to Volunteer Management System (VMS)
Input summary Extra information needed from volunteer and final approval decision
Output summary Confirmation of successful status update.
Usability index 6 out of 10
Use case notes N/A
```

### 7.4. Generate daily report use case

The last use case that we go into detail is generate daily reports. This is another very common
situation that we need to model in the fully dressed level of detail to ensure good
implementation.

```
Use case name Generate daily report
Subject area Statistics report and analysis
Business event Generated automatically every day without the need of manual input
from any user.
Actors Program administrator
Use case overview Use case to generate daily report and review by an administrator. It
only involves the administrator or manager of the program. Only
user action required is the review of the forecast.
Preconditions System access to the database and collects corresponding data.
System calculates forecasts for next week. System is able to
generate report and save it. System sends a notification to the
administrator to review the forecast.
Termination outcome Report is not generated because of missing data. Report is partially
generated with incomplete data. Report is successfully generated
and reviewed.
Condition affecting
termination outcome
```
```
Successful connection to the server and data retrieval. Successful
report generation. Successful review of report.
Use case description System downloads all data required. System calculates forecasts.
System puts together a report with predicted stats. System stores
report and notifies the administrator. Manager reviews the report.
Use case associations Specific data query report. Monthly, quarterly, or yearly reports.
Traceability to Volunteer Management System (VMS)
Input summary No input needed for use case. Generated automatically and only
meant to be reviewed by manager
Output summary Notification to administrator of successful report creation.
Usability index 7 out of 10
Use case 
