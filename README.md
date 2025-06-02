<!-- Improved compatibility of back to top link -->
<a name="readme-top"></a>

<!-- PROJECT SHIELDS -->


<!-- PROJECT LOGO -->
<br />
<div align="center">
  <h3 align="center">Course Scheduler</h3>

  <p align="center">
    Interactive course scheduling via interval graphs and graph coloring<br />
    <br />
    <a href="https://github.com/your-username/course-scheduler"><strong>Explore the Repo »</strong></a>
    <br />
    <br />
    <a href="https://github.com/your-username/course-scheduler/issues">Report Bug</a>
    ·
    <a href="https://github.com/your-username/course-scheduler/pulls">Request Feature</a>
  </p>
</div>

<!-- ABOUT THE PROJECT -->

## About The Project

**Course Scheduler** is a Python-based terminal application that automates the creation of conflict-free course timetables.  
It models courses as nodes in an **interval/conflict graph**, then applies a **graph-coloring algorithm** to assign time slots and classrooms, ensuring no student or instructor overlap.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Features

- 🎓 **Interval & Conflict Graph Modeling**  
  Build a graph where each course is a node; edges represent shared resources (students or instructors).

- 🖌 **Graph-Coloring Scheduler**  
  Use a greedy coloring algorithm (via NetworkX) to assign each course a unique “color” (time slot) whenever conflicts exist.

- 🖥 **Textual TUI**  
  User-friendly terminal interface built with [Textual](https://github.com/Textualize/textual) for:
  - Adding/Editing courses, instructors, student groups, time slots, and classrooms
  - Generating and viewing the schedule in a scrollable table
  - Exporting the conflict graph as a PNG

- 💾 **Local Data Persistence**  
  Store all entities and the generated schedule locally (JSON by default; optional SQLite support).

- 📊 **Visualization**  
  Export a visual representation of the conflict graph (NetworkX + Matplotlib or Graphviz).

- 🛡 **License & Community**  
  MIT-licensed so you can freely adapt and extend. Contributions are welcome!

<p align="right">(<a href="#readme-top">back to top</a>)</p>

### Built With


<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- GETTING STARTED -->

## 🚀 Getting Started

To get a local copy up and running, follow these steps.

### Prerequisites

- **Python 3.11+** installed on your machine.  
- (Optional) [Git](https://git-scm.com/) for cloning the repository.

### Installation

1. **Clone the repo**  
   ```bash
   git clone https://github.com/your-username/course-scheduler.git
   cd course-scheduler

