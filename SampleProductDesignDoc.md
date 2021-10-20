# **IPro 497 – Product Direction Document**

## **Problem Statement**

IIT students need study spaces, but there is no way to know where spaces are available and preferred spaces aren&#39;t always utilized efficiently. This is complicated by social distancing requirements. Students may now choose their study time period and place more freely and conveniently allowing them more time to study, thanks to a study room reservation system.

## **Customer**

### **Description**

College students who need to study on campus

### **Customer Demographic**

Ages: 18-30

Occupation: Undergrad/Grad Student

### **Customer Personas**

#### Persona 1

**Name:** Austin Brown

**Background:**

- Co-Terminal Computer Science Student @ IIT
- On Campus
- Past Summer Internship @ Accenture

**Demographics:**

- Age: 20

**Goal:** Efficiently find/reserve a study space on campus.

**How we can help** :

- Provide a platform that allows students to book study spaces on campus
  - Real-time update of the occupancy of the seats or study room
  - Provide online booking function
- Optional: Seats can be automatically allocated according to management needs

#### Persona 2

**Name:** Maria Rodríguez

**Background:**

- Graduate Biological Engineering Student @ IIT
- Commuter
- Research assistant @ IIT. Working part-time as a nanny.

**Demographics:**

- Age: 23

**Goal:** Ensure a place to sit while waiting between classes.

**How we can help** :

- Provide a platform that allows students to book study spaces on campus
  - Real-time update of the occupancy of the seats or study room
  - Provide online booking function
- Optional: Seats can be automatically allocated according to management needs

**Other Customers and Stakeholders**

- School Administration, Cleaning and Maintenance Staff, Campus Security, IT Administrators.

## **Application Type**

Web App

## **Tech Stack**

Django

Django Tutorial: [https://www.youtube.com/playlist?list=PL6gx4Cwl9DGBlmzzFcLgDhKTTfNLfX1IK](https://www.youtube.com/playlist?list=PL6gx4Cwl9DGBlmzzFcLgDhKTTfNLfX1IK)

React Tutorial: [https://www.youtube.com/playlist?list=PL6gx4Cwl9DGBuKtLgPR\_zWYnrwv-JllpA](https://www.youtube.com/playlist?list=PL6gx4Cwl9DGBuKtLgPR_zWYnrwv-JllpA)

Django + React Architecture: [https://stackoverflow.com/questions/41867055/how-to-get-django-and-reactjs-to-work-together](https://stackoverflow.com/questions/41867055/how-to-get-django-and-reactjs-to-work-together)

Django Documentation: [https://docs.djangoproject.com/en/3.2/contents/](https://docs.djangoproject.com/en/3.2/contents/)

MySQL Documentation: [https://docs.oracle.com/cd/E17952\_01/mysql-8.0-en/index.html](https://docs.oracle.com/cd/E17952_01/mysql-8.0-en/index.html)

| **Member** | **Languages** | **FE frameworks** | **BE frameworks** | **Databases** |
| --- | --- | --- | --- | --- |
| Eric | Python, Java, C++, Javascript | N/A | N/A | N/A |
| Sameer | Python, Java, C | N/A | N/A | PostgreSQL |
| Hannah | JavaScript, Python, Java, Swift, PHP, Go, C# | React.js | Node.js | mysql, Firebase |
| Xiyuan | Java Python PHP C | N/A | N/A | mysql |
| Tyrone | Javascript, Python, Java (haven&#39;t touched it in FEW semesters) | N/A | N/A | mysql |

### **Client Tech**

- Web Browser

### **Server Tech**

- Django (Backend)
- js (Frontend)
- MySQL Database

## **Top Application Capabilities (name at least 5)**

1. View available study spaces
     - filter by building, type, number of seats, quietness/loudness,
2. Reserve a study space for a certain time
     - limited to maximum time limit (2 hrs)
3. Modify / Delete reservations
4. Misconduct reporting system
5. User authentication
     - OAuth maybe? require hawk.iit.edu / iit.edu email
6. Check-in and check-out. Allow temporary leave for breaktime.
     - rules about length of break
     - use QR codes to scan
     - must arrive within certain time of reservation (~20min)
7. View busiest / least busy study times? -- metrics

## **Top Two to Three Scenarios**

### **Your Scenario #1**

Austin has an assignment due in a couple of days. He lives on campus, and his roommate has friends over to hang out. Austin opens the Study Reservation App to find available spots. He looks at spots in MTCC first because that is his favorite location to study. He finds an open study space and reserves it for 5:00pm. It is currently 4:45pm. He walks over and arrives a couple minutes early. There is no one in the study space. He sits down and waits until 5:00pm to check-in to his reservation.

### **Your Scenario #2**

Finals week is around the corner. Maria and her peers agree on meeting up at a certain date and time to study together for their physics final. They don&#39;t want to risk having to wait until that day comes so Maria takes initiative by downloading the Study Reservation App. She opens the app and views the busiest days/times that most study rooms are booked and uses that information to decide when to book a study room for her and her peers. As a result, Maria is confident that their study session will go as planned and that they will be prepared for their final exam. Finally, on the day of their study session, Maria simply walks up to their reserved study room and scans the nearby QR code so that they can check in. The scanning of the QR code reveals reservation details, such as their start/end time along with rules of using the study space.

### **Your Scenario #3**

James has a team project and needs to meet with his 4 teammates outside of class on campus. They need to find a quiet, collaborative space on campus with a whiteboard that can accommodate them. They walk to the Retaliatta building and find the common areas already occupied. They then head on over to the Kaplan Institute building, only to find all of the spaces already in use. They come across a QR code on a classroom door, and after scanning it they find a list of timings which the classroom is not being used for a class. They reserve a convenient time slot from the slots still available and proceed to have an effective collaboration session.

##

## **Team Members**

| **Name** | **Location** | **Time zone offset from Chicago (Chicago is 0 offset)** |
| --- | --- | --- |
| Eric Zacarias | Chicago,IL (Off Campus, Commuter) | 0 |
| Hannah Leland | Chicago, IL (Off Campus, Online) | 0 |
| Sameer Rangoonwala | Chicago, IL (Office Campus, Online) | 0 |
| Xiyuan Song | Shanghai China (Off Campus Online) | +13h |

## **Team Working Agreement**

We will use Github for version control. Team-members will push their finished code to a branch to ensure the main branch remains bug-free.

If we need to meet outside of class we have found a mutually agreeable time at:

[https://www.when2meet.com/?12788487-DxPin](https://www.when2meet.com/?12788487-DxPin)

If we need to meet outside of class we will use the following tool/tech for meetings:

- Google Cal &amp; Google Meet

When we are not meeting together we will use the following tool/tech for communications:

- Discord
- [https://discord.gg/TRfzzETB](https://discord.gg/TRfzzETB)

We will communicate respectfully in a professional manner. Discussions only. No arguing/name calling of any kind. Respect the ideas of each team member.

We will divide work fairly. Each member will be responsible for the work they choose to be assigned to (based on their skillset). Each member should be assigned to one or more stories on the Kanban board.
