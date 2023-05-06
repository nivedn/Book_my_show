# Book_my_show

Requirement Gathering-:
```
This project contains the code which enables the user to perform actions like book,cancel tickets using LLD concepts.
```

Actors-:
```
1. client/customer
2. Buisness Owner
3. system
```

Client / Customer-:
```
1. Search events based on city / date / event / movie
2. Check availability for ticket / seat
3. Proceed to Payment 
4. Pay via UPI / wallet
5. Add event to callender.
6. Buy more than 1 ticket / Book for others
7. Recieve E-ticket / collect ticket
8. Cancel the booked ticket.
9. Recieve refund if any (if algible as per the booking instruction)
```

Buisness Owners-:
```
1. Add Events
2. Update Information regarding the event run by the buisness such as Time / Event / Seat Availability(if more than one 3rd party is selling tickets)
3. Recieve Payment
4. Pay Refund if needed
```

System-:
```
1. Display city/movie/seat availability upon search
2. Generate ticket for the event
3. Notify customer upon ticket confirmation
4. Remove Events once Date is Expired
5. Retain Commision & Send rest to buisness owners on every transcations made 
6. Revert the availability Status of seat / ticket once cancelled by customer
```

Common-:
```
1. Registration in App
2. Onboarding
3. Rating
```
