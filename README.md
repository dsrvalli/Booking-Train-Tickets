# Booking-Train-Tickets
Concept: REST API will support multiple formats using CONTENT TYPE &amp; ACCEPT HEADER

# Why we are developing the use case?
   - [ ]  Here the  Usecase is Business to Business communication (B TO B) & (C 2 B):
   - [ ]  Usecase: How the REST API supports the multiple formats  

# What is the concept for implementing the multiple formats?
   - [ ] We can implement by using  content Type & Accept header

# Architecture 
   - [ ] The Architecture is one Resource that can have several clients, IRCTC is a web application and also is a distributed application 
   - [ ] C 2 B (customer can directly communicate with the business) & as well as B 2 B communication so we can write Rest API
# Example
   - [ ] To improve the business of IRCTC we have Applications like(MakeMyTrip, Yatra, Goibibo) 
   
  ********  USECASE ******** 
   - [ ] To develop a REST API to book train ticket using below details 


Input : passenger data(name.email,phno,from ,to,jdate,trainNum) (xml&JSON)
Output: ticket data(ticket id ,status,cost,pnr,from, to,jdate,name) (xml&JSON)

Endpoints:
/bookticket=>to book a new ticket
/ticket/{pnr}=>to get ticket which is already booked using PNR

