# Use Case: Borrow Equipment

## Primary Actor
Student

## Supporting Actor
Laboratory Technician

## Goal
Borrow laboratory equipment using the system.

## Preconditions
- Student has a registered RFID card.
- Equipment is available.

## Trigger
Student taps the RFID card.

## Main Flow

1. Student taps RFID.
2. Dashboard opens.
3. Student searches equipment.
4. Student views equipment details.
5. AI recommends related equipment.
6. Student adds items to the borrow list.
7. Student submits the request.
8. Laboratory technician reviews the request.
9. Technician approves the request.
10. Inventory is updated.

## Alternative Flow

- Invalid RFID → Access denied.
- Equipment unavailable → Borrow request cannot continue.

## Postconditions

- Borrow request is saved.
- Inventory is updated.
- Borrow history is recorded.