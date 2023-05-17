# LenStudent

LenStudent is an application designed to enhance the learning experience by providing students with a clear and distraction-free way to view the information displayed on the board during lectures.
By utilizing image recognition technology and capturing images of the board, LenStudent eliminates the need for students to take their own pictures,
allowing them to fully engage in the lecture while saving valuable time and keeping the privacy of the lecturers

## Our vision
The primary goal of LenStudent is to empower students to focus on the content presented on the board during lectures without distractions.
By automatically capturing images of the board and removing background elements,
LenStudent ensures that students have a clear and uninterrupted view of the information. This not only saves time for students, as they no longer need to take their own pictures,
but also respects the privacy of the lecturers by removing them from the captured images.

LenStudent aims to revolutionize the way students interact with board content by providing a seamless integration between the computer and mobile applications.
The intuitive user interface and easy access to the most up-to-date board image make LenStudent an indispensable tool for enhancing the learning process while maintaining the privacy of the lecturers.

## Features
### Backend - Python Code
- Connects to an external camera to recognize and capture images of the board.
- Automatically takes pictures of the board at regular intervals.
- Removes background distractions, such as the lecturer or other objects, from the captured images.
- Assembling together multiple images to create a complete and unobstructed view of the board if needed.
- Interfacing with FireBase real-time storage to save the photos

### Frondend - Android application
- Allows students to view the most recently updated image of the board captured by the computer application.
- Appears as a floating window above other apps for convenient and quick access.
- Users can access the mobile app at any time by clicking on the app icon.
- Provides the option to download the latest image of the board to the user's device for offline access or further review.
