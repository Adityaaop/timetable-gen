# timetable-generator

An automated timetable generator designed to schedule courses, instructors, and classrooms while resolving scheduling conflicts and constraints.

## Features

- **Conflict Detection:** Prevents room double-booking, instructor overlaps, and student section clashes.
- **Configurable Constraints:** Supports time slots, working days, instructor availability, and room capacities.
- **Export Formats:** Generates human-readable schedules (exportable to CSV / PDF / JSON).

## Project Structure

```text
timetable-gen/
├── src/            # Core scheduling logic & constraint algorithms
├── data/           # Input files (teachers, subjects, classrooms, time slots)
├── output/         # Generated timetables
├── SECURITY.md     # Security & vulnerability reporting policy
└── README.md       # Project documentation
