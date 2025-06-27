# Course Scheduler

This project is a Python-based timetable scheduler for academic divisions (batches), designed to automatically generate weekly timetables for multiple divisions while respecting various academic and logistical constraints.
Build focusing on Data Structures and Algorithms. Implemented graph-coloring algorithm and hashing techniques.

## Features
- Schedules both theory and lab sessions for multiple divisions.
- Ensures no faculty or batch is double-booked.
- Enforces constraints such as:
  - No subject repeated in a day for a batch.
  - Only one lab per day per batch.
  - Minimum two theory lectures per day.
  - Maximum seven theory lectures per day.
  - Labs require consecutive slots and are globally tracked to avoid overlap.
- Outputs readable timetables using PrettyTable.

## Requirements
- Python 3.x
- [prettytable](https://pypi.org/project/prettytable/)

Install dependencies with:
```sh
pip install prettytable
```

## Usage
1. Clone the repository and navigate to the project directory.
2. Run the scheduler:
   ```sh
   python time-table.py
   ```
3. The script will print the generated timetables for each division in the console.

## Customization
- You can modify the subjects, faculties, and number of divisions in `time-table.py` to fit your institution's requirements.
- The scheduling logic can be extended to add more constraints or features as needed.

## Project Structure
- `time-table.py`: Main script containing all scheduling logic and data definitions.
- `README.md`: Project documentation.

## License
This project is open source and available under the [MIT License](LICENSE). 
