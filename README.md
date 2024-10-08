# Project Timeline Gantt Chart

![image](https://github.com/user-attachments/assets/9a758a1c-32be-46c9-ae0d-6c1b84fb378f)


## Overview

This project demonstrates how to create a Gantt chart for visualizing a project timeline using Python's Matplotlib and Pandas libraries. A Gantt chart is a useful tool for project management, helping teams to plan and track progress over time.

## Project Timeline

The Gantt chart represents the following project timeline:

- **Weeks 0-1**: Requirement Gathering and Project Planning
- **Weeks 1-2**: Designing Wireframes and Prototypes
- **Weeks 2-5**: Backend Development and Setup
- **Weeks 5-8**: Frontend Development and UI Enhancements
- **Weeks 8-10**: Comprehensive Testing and Debugging
- **Weeks 10-11**: Deployment, Final Review, and Project Handover
- **Ongoing**: Maintenance, Performance Monitoring, and Updates

## Technologies Used

- **Python**: The primary programming language used for this project.
- **Matplotlib**: A powerful plotting library for creating static, animated, and interactive visualizations in Python.
- **Pandas**: A data analysis library that provides data structures and functions needed for manipulating and analyzing data.

## Getting Started

To run this project locally, follow these steps:

### Prerequisites

Make sure you have Python installed on your machine. You can download it from [python.org](https://www.python.org/downloads/).

### Installation

1. Clone the repository or download the code files.

   ```bash
   git clone https://github.com/JAmanOG/GanttChart.git
   cd GanttChart
   ```

2. Install the required libraries using pip:

   ```bash
   pip install matplotlib pandas
   ```

### Usage

1. Open your terminal or command prompt.
2. Navigate to the directory containing the Python script.
3. Run the script:

   ```bash
   python gantt_chart.py
   ```

   Replace `gantt_chart.py` with the name of your Python script if it differs.

4. The Gantt chart will be displayed in a new window.

## Code Structure

- **gantt_chart.py**: The main Python script that contains the code to generate the Gantt chart.

### Code Explanation

1. **Data Preparation**: The script defines the project tasks, their start weeks, and durations.
2. **DataFrame Creation**: A Pandas DataFrame is created to organize the task data for easy manipulation and plotting.
3. **Gantt Chart Plotting**: The tasks are plotted as horizontal bars, representing their duration along a timeline measured in weeks.
4. **Visualization**: The x-axis is labeled with week numbers for clarity, and a grid is added to enhance readability.

## Contributing

Contributions are welcome! If you'd like to enhance this project, please follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/YourFeature`).
3. Make your changes and commit them (`git commit -m 'Add some feature'`).
4. Push to the branch (`git push origin feature/YourFeature`).
5. Open a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Acknowledgments

- [Matplotlib Documentation](https://matplotlib.org/stable/contents.html) for plotting guidance.
- [Pandas Documentation](https://pandas.pydata.org/pandas-docs/stable/) for data manipulation techniques.
