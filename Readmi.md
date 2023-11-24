<h1>Student Maltiple Gate Attendance System Using NodeMCU and RFID</h1>

This repository contains the source code and documentation for a student attendance system implemented using Internet of Things (IoT) technology. The project utilizes NodeMCU, an open-source IoT platform based on the ESP8266 WiFi module, and RFID (Radio-Frequency Identification) technology to automate and streamline the attendance tracking process.

<h3>Features:</h3>
<ul>
<li>RFID Integration: The system employs RFID technology to uniquely identify and track students, allowing for efficient and accurate attendance recording.</li>
<li>NodeMCU Implementation: NodeMCU, powered by the ESP8266 WiFi module, serves as the IoT platform to connect the RFID module to the internet.</li>
<li>Multiple Gates: The system allows multiple gate entries and saves data indicating which gate a student entered.</li>
<li>Entry Exit Time: Displays the 1st scan entry time and 2nd scan exit time..</li>
<li>Google Sheets Integration: Attendance data is seamlessly integrated with Google Sheets, providing a centralized and easily accessible record of student attendance.</li>
<li>Real-time Updates: The system provides real-time updates to the Google Sheets document, ensuring that attendance records are always up-to-date.</li>
</ul>

<h3>How It Works:</h3>

   <ul>
    <li>RFID Tag Scanning: Students scan their RFID tags upon entering a designated area.</li>
    <li>NodeMCU Processing: The NodeMCU processes the RFID data and connects to the Google Sheets API.</li>
    <li>Google Sheets Logging: The attendance data is logged in a Google Sheets document in real time, creating a comprehensive attendance record.</li>
   </ul>

<h3>Future Updatable:</h3>
   <ul>
    <li>Fixed Time Entry: Implement fixed time entry; if a student scans their card late, the system does not give attendance.</li>
    <li>Auto Exit Time: Automatically update exit time when the class time is over.</li>
    <li>Possible Integration with Web/Mobile App:** Explore the possibility of integrating a web app or mobile app for more convenient attendance tracking</li>
   </ul>
