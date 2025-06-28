# CLI-Based Project Tracker 
**Problem Statement:** 
Freelancers and developers often manage multiple client projects with varying hourly rates, 
making it difficult to track work hours, calculate billing, and maintain logs manually. This 
project addresses that problem with a simple, automated solution that handles project 
creation, time logging, billing, and CSV export — all via an intuitive GUI. 
### Project Overview: 
This is a desktop-based Project Tracking System built using Python and the Tkinter library. 
The tool allows users (like freelancers or developers) to manage multiple projects, track time 
spent on each task, calculate billing automatically based on hourly rates, and export logs for 
invoicing or reporting. 
### Key Features: 
* Add Projects : Add multiple projects with unique names and hourly billing rates
* Log Time Entries : Record start time, end time, and notes for each project task 
* Auto Billing calculation : Automatically calculates billable hours and multiplies with hourly 
rate 
* Export Logs to CSV : Save all logs to a CSV file with detailed project/task records 
* Project Summary : View total hours and earnings per project in a dedicated summary 
section 
* GUI-Based Interaction : User-friendly layout with dropdown menus, table view, and 
feedback alerts 


### Technologies Used: 
* Python 3 : Core programming language 
* Tkinter : GUI development for desktop interface
* Datetime module : Time parsing and duration calculation 
* CSV module : Exporting logs to external files 
* ttk.Treeview : Rendering project logs in table form 

Core Logic: 
* Projects are stored in a dictionary: 
    -python 
    -CopyEdit 
    -projects = { "project_name": {"rate": 500, "logs": [ ... ]} } 
* Each time log stores: 
    - Start time (HH:MM) 
    - End time (HH:MM) 
    - Duration (calculated in hours) 
    - Optional note 
* GUI fields collect user input, validate formats (e.g., correct time, numbers), and 
update the data in real time. 
* Treeview widget is used to display logs with billing info. 
* A summary section totals hours and earnings per project. 
* CSV export function generates a structured log file for external use (billing/invoicing). 
## What I Learned: 
* Designing user-friendly GUI layouts using Tkinter 
* Implementing time calculations with datetime.strptime() 
* Using Treeview for dynamic table rendering in GUI 
* Validating user input and showing error/info messages 
* Storing structured data in Python dictionaries 
* File handling and exporting logs using csv.writer 
* Event-driven programming in desktop applications 
