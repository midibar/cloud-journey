# Future System Requirements

## Purpose

The goal of the future system is to reduce manual administrative work in the yoga studio and centralize reservations, attendance, passes, and operational visibility in one system.

## Business goals

- Students should be able to reserve classes without manual intervention through WhatsApp or email.
- The system should automatically validate whether a class has available capacity.
- The system should automatically validate whether a student is allowed to attend a class.
- Reservations should be stored automatically in a centralized system.
- Attendance should be recorded digitally.
- The studio owner should be able to view operational information through dashboards or reports.
- The system should reduce human error and dependence on manual spreadsheet updates.

## Functional requirements

- Students can log into the system.
- Students can view available classes.
- Students can reserve a class.
- The system can verify whether seats are available before confirming a reservation.
- The system can place students on a waiting list when a class is full.
- The system can validate student passes automatically.
- The system can support different types of passes based on number of classes purchased.
- The system can support different pass rules depending on class category.
- The system can support special handling for training classes.
- The system can support passes with time-based validity, including at least one pass valid for 5 weeks.
- The system can allow single-class bookings.
- Single-class bookings may differ depending on whether the student is a resident or non-resident.
- Teachers can record attendance digitally.
- The owner can record payments.
- The owner can view reservation, attendance, pass, and payment information.
- The system should keep a history of reservations, attendance, passes, and payments.

## Administrative flexibility requirements

- The owner should be able to manually extend a student pass.
- The owner should be able to manually freeze a student pass.
- The owner should be able to manually adapt or override pass conditions in exceptional cases.
- Administrative permissions should remain available because the studio is small and exceptions are sometimes handled personally.

## Payment requirements

- Payment tracking should be included in the system.
- In the first stage, the system does not need to process online payments directly.
- The system should allow the owner to record payments made in person or after class.
- The system should support multiple payment methods as recorded data, even if online payment is not yet implemented.

## Non-functional considerations

- The system should be simple and practical for a small yoga studio.
- The system should centralize data that is currently spread across Excel, Airtable, and paper.
- The system should be easy to use for students, teachers, and the owner.
- The system should support future improvements such as online payments or expanded reporting.