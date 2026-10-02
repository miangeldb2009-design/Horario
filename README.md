# Horario
[![Ask DeepWiki](https://devin.ai/assets/askdeepwiki.png)](https://deepwiki.com/miangeldb2009-design/Horario)

This repository contains a dynamic and interactive web application for viewing the academic schedule of the 2º SMR (Sistemas Microinformáticos y Redes) course at IES Donoso Cortés. It is a single, self-contained HTML file that provides a rich, user-friendly interface for managing the school week.

## Key Features

- **Full Weekly Schedule**: Displays the entire week's class schedule in a clear, easy-to-read grid. Each subject has a unique color and font for quick identification.
- **"Today" View**: A dedicated panel that dynamically shows the current class in real-time, what's coming up next, or the status for the day (e.g., "No more classes today").
- **Interactive Subject Details**: Click on any class block to open a detailed modal with:
    - A list of all sessions for that subject throughout the week.
    - The total number of classes per week.
    - Convenient links to educational platforms like Rayuela, EducarEx, and searches on Google and YouTube.
- **Teacher Highlighting**: Click on a teacher's name in the legend to highlight all of their classes in the schedule, making it easy to track a specific instructor's timetable.
- **Light & Dark Mode**: Includes a toggle to switch between a light and dark theme to suit your preference.

## Usage

No server or build process is required. To use the application, simply download the `Horario de Miguel Ángel Hurtado · 2º SMR.html` file and open it in any modern web browser.

## Customization

This schedule can be easily adapted for a different student or course. All data for teachers, subjects, and the weekly timetable is hardcoded in JavaScript objects at the bottom of the HTML file.

To modify the schedule, edit the following variables within the `<script>` tag:

- **`PROFES`**: An object containing teacher names and their assigned highlight color.
- **`ASIGNATURAS`**: An object defining the subjects and linking them to a teacher from the `PROFES` object.
- **`HORARIO`**: An array of objects that defines the structure of the weekly schedule, including class times, subjects for each day, and recess periods.