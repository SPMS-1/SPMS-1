# Smart Parking Management System (SPMS) — Browser Demo

## Run it
1. Extract this ZIP.
2. Open the `SPMS_Application` folder.
3. Double-click `index.html` to open in Chrome, Edge, or Firefox.
4. No installation or internet connection is required.

If needed, open a terminal in this folder and run `python -m http.server 8000`, then visit `http://localhost:8000`.

## Included features
- 8 parking slots with search and availability filters
- Reservation form and input validation
- One active reservation per vehicle (duplicate prevention)
- Fee calculation at ₹40/hour
- Simulated successful and failed payment
- Reservation records, vehicle entry, exit and slot release
- Browser local-storage persistence and reset function

## Important limitations
This is a front-end academic demo, not a production system. Payments are simulated, data is local to one browser, and there is no backend, database, authentication or real payment gateway. Do not enter real sensitive information.

## Suggested demo
1. Search for A01.
2. Reserve A01 with test name and vehicle `MH31AB1234` for 2 hours.
3. Confirm simulated payment; fee should be ₹80 and A01 becomes occupied.
4. Try to book another slot with the same vehicle; duplicate booking should be rejected.
5. In Records, record entry, then complete vehicle exit. A01 becomes available again.
6. Reset demo data for another run.

## Jira mapping
- SPMS-1: Parking Slot Management — dashboard, slot search/filter, availability and occupancy.
- SPMS-2: Reservation and Payment Management — reservations, duplicate checks, fee calculation, simulated payment and vehicle exit.
- SPMS-13 and SPMS-14: record actual test steps and observed outcomes.

Report test outcomes honestly. Do not mark features passed until you have executed them.
