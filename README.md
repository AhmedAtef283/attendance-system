# Attendance and Grade Management System

This project aims to create a web-based platform for attendance submission, grade management, and communication within an educational institution. The system leverages RFID technology, NodeMCU, and a web server to provide a seamless and efficient experience for students and professors.

Each student is assigned a unique RFID card, which they will use to scan their attendance. When a card is scanned, the RFID component reads the card's ID and
sends it to the NodeMCU. The NodeMCU acts as an intermediary between the RFID component and the web server. It establishes a connection with the web server using Wi-Fi and sends the student's ID to the server.

Simultaneously, an LCD is used to provide feedback to the student. Initially, it displays a welcome message. Upon a successful scan, the LCD displays "Access granted." However, if the card has been previously scanned, it displays "Card scanned previously.

Overall, this project offers a convenient and efficient method for students to submit their attendance using RFID technology. By combining the capabilities of NodeMCU, RFID, and LCD, the system automates the process and provides real-time feedback, simplifying attendance management for educational institutions
## Features

- **Attendance Submission**: Students can conveniently submit their attendance using their unique RFID cards. The RFID component reads the card's ID, which is then sent to the server through NodeMCU. Real-time feedback is provided to students via an LCD display.

- **Comparison of Attendance Percentages**: Professors have the ability to compare attendance percentages for each subject, allowing them to analyze student attendance patterns and make informed decisions.![Admin_Page](https://github.com/AhmedAtef283/attendance-system/assets/90651336/646dedc3-1b95-48bb-a81d-72654b18ee6f)


- **Export Students' Data into CSV File**: Professor have the ability to download the students' Data into csv file and download it into his device either Mobile phone or on labtop
![export-pop-up](https://github.com/AhmedAtef283/attendance-system/assets/90651336/86aa12b3-a638-450f-a861-28166724fac0)
![Screenshot 2023-05-24 003209](https://github.com/AhmedAtef283/attendance-system/assets/90651336/94294c96-e874-4ed9-9a86-f0aad43a67ab)

- **Progress Tracking**: Develop a tool for students to track their academic progress, including cumulative grades and attendance records.![WhatsApp Image 2023-05-23 at 19 01 52](https://github.com/AhmedAtef283/attendance-system/assets/90651336/82737577-eaca-486d-820b-554b48203807)

- **Lectures Schedule**: The project allows to student to see the schedule of lectures and see if there is any changes happened.![WhatsApp Image 2023-05-23 at 19 02 54](https://github.com/AhmedAtef283/attendance-system/assets/90651336/764d3592-bf34-4109-9645-226e523ef686)




## Technologies Used

- **RFID**: RFID technology is used to track and identify unique RFID cards assigned to each student. The RFID reader communicates with the cards and retrieves their ID information when scanned.

- **NodeMCU**: NodeMCU serves as an intermediary between the RFID reader and the web server. It establishes a connection with the server using Wi-Fi and transmits the scanned ID data.

- **Web Server**: The web server receives and processes attendance data sent by NodeMCU. It records attendance information in a database, associates it with student names, and provides access to grades and meeting schedules.

- **LCD Display**: An LCD display provides real-time feedback to students, displaying messages such as "Access granted" or "Card scanned previously" based on the success of their scan.

## Hardware Connections
![Picture1](https://github.com/AhmedAtef283/attendance-system/assets/90651336/d4762fc5-10b8-4c79-8e81-d5fd13bfff83)

## Installation and Setup

1. Clone the project repository from GitHub.

2. Set up the web server by following the installation instructions provided in the server's README file.

3. Connect the NodeMCU board to the RFID reader and LCD display as per the wiring instructions given in the hardware documentation.

4. Configure the NodeMCU's Wi-Fi settings to connect to the web server.

5. Upload the necessary code to the NodeMCU board, ensuring proper communication between the RFID reader, LCD display, and web server.

6. Launch the website by running the server application and accessing the appropriate URL.

## Future Enhancements

- **Discussion Forum**: Implement a discussion forum for students and professors to engage in academic discussions and seek clarification.

- **Assignment Submission**: Integrate a feature for students to submit assignments online, allowing professors to provide feedback and grades electronically.


- **Mobile Application**: Create a mobile application companion for the website, providing convenient access to features and notifications on smartphones and tablets.

## Demo Video


https://github.com/AhmedAtef283/attendance-system/assets/90651336/c131a09b-1acb-4460-b230-16ab813c5871



## Contributors
This code was developed by Attendance Seekers:
- [Ahmed Atef](https://github.com/AhmedAtef283)
- [Muhammed Emadeddine](https://github.com/m-emadeddin)
- [Kamilia Ahmed](https://github.com/Kamilia98)
- [Hesham Khaled](https://github.com/HeshamKhaled1)
- [Moaaz Ahmed]
- [Hazem Abdelnaser]
- [Mohamed Salah]

