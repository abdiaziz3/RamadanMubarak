# RamadanMubarak
This is a simple website created using HTML, CSS, and JavaScript to celebrate the holy month of Ramadan.The website displays a greeting message, an image related to Ramadan, an audio file playing Quran, and a countdown timer to show the remaining days of Ramadan.

# Usage
To view the website, simply download or clone the repository and open the index.html file in your web browser. The audio file and image used in the website are included in the audio and images folders respectively.

# Contributing
If you want to contribute to this project, feel free to fork the repository and create a pull request with your changes.

# Credits
This project was motivated by doing Ramadan on Scrimba, an online learning platform.

# License
This project is licensed under the MIT License.

# © By Abdirahman Abdiaziz

# JavaScript used to execute the countdown

The JavaScript code in the script.js file is responsible for the countdown timer functionality on the website. It sets a specific date (April 21, 2023) as the target date to count down to, and updates the countdown every 1 second.

The setInterval() method is used to execute a function repeatedly, which calculates the remaining time until the target date and updates the countdown timer accordingly. The remaining time is calculated by finding the difference between the current date and the target date, and then converting that time into days, hours, minutes, and seconds.

The days, hours, minutes, and seconds variables are then used to display the countdown timer on the webpage by updating the text of the element with the ID demoClock.

Finally, if the countdown timer reaches zero, the text "EXPIRED" is displayed on the webpage, indicating that the target date has passed.
