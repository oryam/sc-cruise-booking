# Sample application

# Cruise trip

Let's go for a cruise! ... WAIT!
 

- there is a prebooking list `passengers.csv` and live booking.
- 


**passengers.csv format**

- Pre booking list preview

| booking id  | firstname | lastname | room id | floor |
| ------------|-----------|----------|---------|-------|
| 1001        | John      | Jason    | 24      | 1     |
| 1001        | Marie     | Jason    | 24      | 1     |
| 1002        | Eric      | Law      | 138     | 5     |

- the file contains the list of passengers who prebooked a room
- a booking id can be associated to one or more passengers depending on the capacity of the room


** Passengers**

- passengers in prebooking list
- a new passenger can book a room at the entrance
- the room must be available when no booking id is provided (means, not already booked by passengers in the prebooking list)
- it is possible to add a new passenger to a room if:
    - the capacity allows it 
    - and the new passenger gives the existing booking id and at least a lastname of a associated passenger


**Room**

- Room list preview

| room id  | floor | capacity | category        | smoking | pet |
| ---------|-------|----------|-----------------|---------|-----|
| 24       | 1     | 2        | DELUXE          | 0       | 1   |
| 138      | 5     | 1        | STANDARD        | 1       | 0   |

- room id contains the floor and the room number. Ex. 1-24 means floor 1 and room number 24.

# TODO

- count the number of booked room from prebooking list
- add a new passenger in a new available room
- add a new passenger in an existing room

