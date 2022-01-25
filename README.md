# Booking-Train-Tickets
Concept: REST API will support multiple formats using CONTENT TYPE &amp; ACCEPT HEADER

- [ ]Here the  Usecase is Business to Business communication (B TO B) & (C 2 B):
- [ ]Usecase: How the REST API supports the multiple formats  

- [ ]	To know the concept of where?how?when? to use content Type & Accept header
- [ ] To improve the business of IRCTC we have Applications like(MakeMyTrip, Yatra, Goibibo)
- [ ]	The Architecture is one Resource that can have several clients, IRCTC is a web application and also is a distributed application 
- [ ]	C 2 B (customer can directly communicate with the business) & as well as B 2 B communication so we can write Rest API

- [ ]To develop a REST API to book train ticket using below details 

Input : passenger data(name.email,phno,from ,to,jdate,trainNum) (xml&JSON)
Output: ticket data(ticket id ,status,cost,pnr,from, to,jdate,name) (xml&JSON)

Endpoints:
/bookticket=>to book a new ticket
/ticket/{pnr}=>to get ticket which is already booked using PNR

