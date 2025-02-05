# [Face-Attendance](https://github.com/MrAnon89/FaceAttendance-Project/edit/main/README.md)
Start: 08/01/24  |  Finish: 23/04/24

The face attendance system uses facial recognition to automatically track attendance. When a person approaches the system, it captures their face, matches it against a stored database, and records their attendance without the need for manual input.

## The story behind the project:
When our school final project approach was announced, we were given four months to create something from scratch. My group decided to seize the opportunity and spent the first month planning the workflow. In the second and third months, we focused on turning our plan into a functional application. During the final month, I took the opportunity to debug, double-check everything, and prepare the proposal report for submission to the school. The idea for the project came from my frustration with the time-consuming attendance process, where the teacher had to shout our names to check attendance every class. I remembered that the foundation of coding is to solve real-life problems, so I decided to create the face attendance system as a solution to this issue. As a result, our group received the second-highest score in the school.

## The framework and libraies I work with:
1. OpenCV
   - Image and video capture and processing.
   - Drawing shapes and person's name oround the detected face.
   - Real time video proccesing
2. FaceRecognition
   - Face detection and recognition.
   - Identifying and comparing faces for matching.
   - Extracting face landmarks (eyes, nose, mouth, etc.).
   - Encoding faces for identification and storing them for future comparison.
   - Handling multiple face detection in a single image or video frame.
3. Os
   - File and directory management (creating directories, checking file existence).
   - Handling file paths to save or load images and videos.
   - Managing temporary files or directories for processed images.
   - Accessing environment variables for configuration purposes.
4. DateTime
   -  Managing and manipulating date and time.
   -  Show time for every attendance and track.
5. OpenPyxl
   - Storing the attendance data to excel file(xlsx)
   - Keeping the data in excel clear and readable
6. Pyinstaller
   - Make the code into .exe file
   - make it easier to share the program into other windows
   - make it easier to use
  
## What I learn:
- Team work make dream work
- Better time management better result
- Finish the project before deadline 
