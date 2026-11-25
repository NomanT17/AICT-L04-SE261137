# Project plan: Lab Equipment Booking System

## Project objective
Create a straightforward booking process that allows students to request shared laboratory equipment and enables lab staff to manage availability and prevent conflicting reservations.

## Scope
- Maintain a list of equipment and its availability.
- Allow students to submit booking requests with date, time, and purpose.
- Allow lab staff to approve or reject requests.
- Record booking status and avoid overlapping approved bookings.

## Phases
1. **Plan and purchase**
   - Confirm equipment list, user roles, booking rules, and required software.
   - Identify any hardware or hosting needs.
2. **Install**
   - Prepare the application environment and database.
   - Add equipment records and booking-request forms.
3. **Test and train users**
   - Test valid, incomplete, and conflicting booking requests.
   - Demonstrate the process to students and lab staff.
   - Collect feedback and correct issues.

## Roles
- Students: view equipment and submit booking requests.
- Lab staff: review requests and maintain equipment availability.
- Project owner: document requirements, coordinate implementation, and test the workflow.

## Key requirements
- A booking request must include equipment, date, time slot, and purpose.
- Required fields must be validated.
- The system should flag a time slot that is already booked.
- Booking status should be visible to the requester and lab staff.

## Risks and controls
- **Double booking:** check availability before approval.
- **Incorrect request details:** validate required fields.
- **Equipment unavailable for maintenance:** allow staff to mark equipment unavailable.

## Budget limit
To be confirmed after the equipment and hosting requirements are reviewed.

## Venue
CS Meeting Room
