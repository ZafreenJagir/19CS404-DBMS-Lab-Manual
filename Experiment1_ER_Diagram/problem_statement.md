# ER Diagram Workshop – Submission Template

## Objective
To understand and apply ER modeling concepts by creating ER diagrams for real-world applications.

## Purpose
Gain hands-on experience in designing ER diagrams that represent database structure including entities, relationships, attributes, and constraints.

---

# Scenario A: City Fitness Club Management

**Business Context:**  
FlexiFit Gym wants a database to manage its members, trainers, and fitness programs.

**Requirements:**  
- Members register with name, membership type, and start date.  
- Each member can join multiple programs (Yoga, Zumba, Weight Training).  
- Trainers assigned to programs; a program may have multiple trainers.  
- Members may book personal training sessions with trainers.  
- Attendance recorded for each session.  
- Payments tracked for memberships and sessions.

### ER Diagram:
*Paste or attach your diagram here*  

<img width="1311" height="902" alt="image" src="https://github.com/user-attachments/assets/5ca7b363-b52c-47c3-9b7c-49c56efd6ab9" />


### Entities and Attributes


<img width="895" height="450" alt="image" src="https://github.com/user-attachments/assets/53002831-950c-4612-b1d4-e81c32db1509" />


### Relationships and Constraints


<img width="895" height="626" alt="image" src="https://github.com/user-attachments/assets/1997df41-747f-4892-932a-27f440e22ad7" />


### Assumptions

1.Each member, trainer, and program has a unique ID.
2.A member can join multiple programs, but not the same program twice at the same time.
3.A program can have multiple trainers.
4.Members can book personal training sessions with trainers in advance.
5.Attendance is recorded for each session.
6.Payments are recorded separately for memberships and personal training sessions.
7.Expired members cannot book new sessions.

# Scenario B: City Library Event & Book Lending System

**Business Context:**  
The Central Library wants to manage book lending and cultural events.

**Requirements:**  
- Members borrow books, with loan and return dates tracked.  
- Each book has title, author, and category.  
- Library organizes events; members can register.  
- Each event has one or more speakers/authors.  
- Rooms are booked for events and study.  
- Overdue fines apply for late returns.

### ER Diagram:


<img width="982" height="702" alt="image" src="https://github.com/user-attachments/assets/709bee55-8f7c-41cc-857b-75ae1494ee66" />


### Entities and Attributes

<img width="895" height="543" alt="image" src="https://github.com/user-attachments/assets/32ed18e9-95f7-45d2-882c-41a49fcefee0" />


### Relationships and Constraints


<img width="875" height="541" alt="image" src="https://github.com/user-attachments/assets/f5481b9a-5ce2-4f26-9a0e-f8f08b4d3b29" />


### Assumptions

1.Each member, book, event, speaker, and room has a unique ID.
2.A member can borrow multiple books, but a book can be issued to only one member at a time.
3.Loan date and return date are recorded for every borrowed book.
4.Fine is calculated based on the number of overdue days.
5.A member can register for multiple events.
6.An event can have multiple speakers/authors.
7.A room can be booked for events or study, but only one booking per time slot.
8.A book belongs to only one category.

# Scenario C: Restaurant Table Reservation & Ordering

**Business Context:**  
A popular restaurant wants to manage reservations, orders, and billing.

**Requirements:**  
- Customers can reserve tables or walk in.  
- Each reservation includes date, time, and number of guests.  
- Customers place food orders linked to reservations.  
- Each order contains multiple dishes; dishes belong to categories (starter, main, dessert).  
- Bills generated per reservation, including food and service charges.  
- Waiters assigned to serve reservations.

### ER Diagram:


<img width="961" height="1291" alt="image" src="https://github.com/user-attachments/assets/29393c2d-2d03-48dc-9aa1-6640022a1727" />


### Entities and Attributes


<img width="885" height="614" alt="image" src="https://github.com/user-attachments/assets/22f341bf-b53b-4cdd-b3d5-12432a02dfcd" />


### Relationships and Constraints


<img width="876" height="586" alt="image" src="https://github.com/user-attachments/assets/d8e5fe52-6d8f-4f2f-926d-a8a6be527290" />


### Assumptions

1.Each customer, reservation, waiter, dish, and bill has a unique ID.
2.A reservation is made for a specific date and time with a fixed number of guests.
3.Walk-in customers are also recorded as reservations.
4.One reservation is assigned to one waiter, but a waiter can handle multiple reservations.
5.Each order is linked to one reservation.
6.An order can contain multiple dishes, and each dish belongs to one category.
7.Only one final bill is generated per reservation.
8.The bill includes food charges + service charges.

## RESULT:
Thus the ER Diagram for each scenario has been drawn and explained successfully.


