# Lab 3 - Python
#### In this lab, I explored a series of Python scripts that demonstrate how to work with real-world data such as time, dates, geographic locations, and system resources. Using external libraries like jdcal, astral, and geopy, I learned how to calculate sunrise/sunset times, determine moon phases, geocode addresses, and monitor CPU and battery usage. These foundational skills are essential for building smart, context-aware IoT systems and understanding how software can interact with time and environment-based inputs.

### cd ~/iot
#### This command allows me to naviagte to the IoT folder.
![alt text](cd-iot.jpg)

### cd *3
#### This command puts me into the lesson 3 folder.
![alt text](cd-3.jpg)

### python3 julian.py
#### This script converts today’s Gregorian date into the Julian date format using the jdcal library. Julian dates are useful in astronomy and scientific calculations.
![alt text](julian.jpg)

### python3 date_example.py
#### Demonstrates basic date handling in Python using the datetime module. It prints the current date and shows how to add or subtract days.
![alt text](date_example.jpg)

### python3 datetime_example.py
#### Combines both date and time into a single object and displays the full current timestamp. The script also shows how to format and manipulate datetime values.
![alt text](datetime_example.jpg)

### python3 time_example.py
#### Uses Python’s built-in time module to measure durations, view the current time in seconds, and compare UTC vs local time. It also includes examples of introducing pauses in a program.
![alt text](time_example.jpg)

### python3 sun.py "New York"
#### Calculates the local sunrise and sunset times for New York City using the astral module. This is useful for location-based scheduling or automation.
![alt text](sun.jpg)

### python3 moon.py
#### Outputs the current moon phase using astral.moon. The result is a number from 0 to 29, where 0 indicates a new moon and 14 represents a full moon.
![alt text](moon.jpg)

### python3 coordinates.py "Samuel C. Williams Library"
#### This script uses geopy to convert a named location into its GPS coordinates (latitude and longitude).
![alt text](coordinates.jpg)

### python3 address.py "40.74480675, -74.02532861159351"
#### This performs the opposite of coordinates.py, it takes a pair of latitude and longitude values and returns a readable address.
![alt text](address.jpg)

### python3 cpu.py
#### Uses the psutil module to measure and display the current CPU usage percentage. It helps understand system performance in real-time.
![alt text](cpu.jpg)

### python3 battery.py
#### Also using psutil, this script retrieves the battery status of the device, including the percentage of charge remaining and whether the system is currently charging.
![alt text](battery.jpg)

### python3 documentstats.py document.txt
#### Analyzes a text file (document.txt) and prints statistics such as the number of words, characters, and lines. This can be useful for text analytics or file processing.
![alt text](documentstats.jpg)
