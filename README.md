# Canvas-LMS_Module_Title_Updater
This file generates cURL commands to update Canvas LMS module titles. 

Follow Canvas' API documentation for clarification on formatting. https://canvas.instructure.com/doc/api/modules.html

Steps to use the quiz generator:

  1. Generate your API key in Canvas, then paste this into cell A3
  2. Type your institutions url into cell A6
  3. Type your course ID into cell A9
  4. Fill in cells with your data
  5. Input Module ID in column E. This can get had by running a GET call to the course
  6. cURL commands are generated in column J.
  7. Select your REST API option (GET, POST, DELETE, PUT) through the dropdown menu in column I
  8. Copy and paste this code into your text editor of choice using the bash (.sh) "language."
  9. Save this file, then make it an executable file using terminal/command prompt
  10. Execute the file by double clicking it
