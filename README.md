# Python Swiss Army Knife
Welcome to the Python Swiss Army Knife, a versatile collection of Python scripts and applications that can help you perform various tasks and operations. This repository contains a menu-driven graphical user interface (GUI) built using Tkinter to access different functionalities.

# Preview

![tkinter_menu](https://github.com/neelay-16/Python-Menu-using-tkinter/assets/135517502/34a88aea-d9d4-4f0e-87e3-65ceb28e4ebe)


# Features

System Apps:

- Open Notepad, Calculator, and File Explorer directly from the GUI.

AWS Operations:

- Perform AWS operations like creating EC2 instances, S3 buckets, listing EC2 instances, and uploading files to S3.

 Multimedia:

- Capture video from your webcam.
- Generate QR codes for text or URLs.
- Swap faces in images.
- Control system volume with hand gestures.

Internet and Search:
- Open YouTube and search for your favorite songs.
- Perform Google searches right from the GUI.
- Interact with search engines using Langchain.

Weather Update:

- Get the latest weather information for a specific city.

Communication:

- Communicate with deaf individuals using hand gestures and speech synthesis.

Fun and Games

- Play Tic-Tac-Toe with a simple text-based interface.
- Perform object detection in images.
- Manipulate pixels in images for fun effects.

Geographic Information

- Obtain your current GPS coordinates.

Messaging

- Send WhatsApp messages programmatically.

# Description

Let's break down the code section by section:

Import Statements:
The code starts by importing several Python libraries and modules such as tkinter, pyttsx3 (for text-to-speech), speech_recognition (for speech recognition), and more. These libraries are used for various purposes within the application.

![image](https://github.com/neelay-16/Python-Menu-using-tkinter/assets/135517502/6178d754-c04c-41e4-8d53-2ae545528858)


Function Definitions:
The code defines several functions that correspond to different actions or functionalities of the application. These functions include opening system applications, performing AWS operations, capturing video, getting weather information, sending WhatsApp messages, and more.

do_something Function:
This function displays an information dialog box with the title "Info" and the message "Team 9 - Stambh" when called.

![image](https://github.com/neelay-16/Python-Menu-using-tkinter/assets/135517502/1a3ebb7e-aaad-41cb-b95e-970b12f6a0c9)


system_app Function:
This function opens a new window (Toplevel) with the title "System Apps" and provides options to open Notepad, Calculator, and File Explorer. Users can also close the window.

![image](https://github.com/neelay-16/Python-Menu-using-tkinter/assets/135517502/f474bf7c-1ede-4957-899c-55b0095c5be7)


aws_operations_window Function:
This function opens a new window (Toplevel) with the title "AWS Operations" and provides options to create an EC2 instance, create an S3 bucket, upload files to S3, and list EC2 instances. Users can also close the window.

![image](https://github.com/neelay-16/Python-Menu-using-tkinter/assets/135517502/0eabebc7-cf64-45f1-ae76-1c398f7ab681)


on_exit Function:
This function prompts the user with a confirmation dialog to exit the application when the "Exit" button is clicked.

![image](https://github.com/neelay-16/Python-Menu-using-tkinter/assets/135517502/7546ae01-cb55-4b40-833c-d6027c8000bf)


System Application Functions (open_notepad, open_calculator, open_explorer):
These functions use the subprocess module to open Notepad, Calculator, and File Explorer, respectively.

![image](https://github.com/neelay-16/Python-Menu-using-tkinter/assets/135517502/84817940-73bf-42b1-8554-2c3343ce61f2)


AWS Operations Functions (list_ec2_instances, open_ec2_instance, create_s3_bucket, upload_to_s3):
These functions perform AWS-related operations using the boto3 library. They allow users to list EC2 instances, create an EC2 instance, create an S3 bucket, and upload files to an S3 bucket.

![image](https://github.com/neelay-16/Python-Menu-using-tkinter/assets/135517502/8613c03e-a7b7-4da2-888f-f9d2bdffd974)

![image](https://github.com/neelay-16/Python-Menu-using-tkinter/assets/135517502/2042d614-2b92-40c1-aa80-8d86c5c214c5)

open_youtube and google_search Functions:
These functions open a web browser to search on YouTube or Google, respectively. Users are prompted to enter their search queries.

![image](https://github.com/neelay-16/Python-Menu-using-tkinter/assets/135517502/f71765f8-696f-4419-b328-dcd82f6d551f)


deaf_people_help Function:
This function uses hand gesture recognition to communicate with deaf people. It captures video from the camera, detects hand gestures, and plays corresponding pre-recorded audio messages.

![image](https://github.com/neelay-16/Python-Menu-using-tkinter/assets/135517502/3e69805f-2eef-4443-9676-3620c7dc82b4)


capture_video Function:
This function captures video from the camera and saves it as "captured_video.avi."

![image](https://github.com/neelay-16/Python-Menu-using-tkinter/assets/135517502/a4d120d4-d1dd-4314-a85e-604f190377a0)


get_weather Function:
This function allows users to enter a city name and fetches weather information for that city using an API. The weather details are displayed in an information dialog.

![image](https://github.com/neelay-16/Python-Menu-using-tkinter/assets/135517502/9464186a-142d-436d-a13d-b69918c6979c)


Image_swaping Function:
This function loads two images and swaps a part of one image with another. It displays the resulting image.

![image](https://github.com/neelay-16/Python-Menu-using-tkinter/assets/135517502/6bc64e91-dd76-4829-af24-2efc9ed65962)


Volume_by_hand_gesture Function:
This function uses hand gesture recognition to control system volume. It adjusts the volume based on the distance between two fingers.

![image](https://github.com/neelay-16/Python-Menu-using-tkinter/assets/135517502/900dd212-ad75-49fa-b41b-4ea6b47a4f03)


generate_qr_code Function:
This function generates a QR code from user-provided text or URLs and displays it.

![image](https://github.com/neelay-16/Python-Menu-using-tkinter/assets/135517502/6a6a1cc9-0191-4339-a2f9-e37acbf397f9)


langchain_SERP_Search and langchain_Brave_Search Functions:
These functions perform web searches using language models and external search tools.

![image](https://github.com/neelay-16/Python-Menu-using-tkinter/assets/135517502/04ffecab-d634-46e6-8c81-66192f4439b7)

![image](https://github.com/neelay-16/Python-Menu-using-tkinter/assets/135517502/47710058-bc44-45bd-9ad8-41eebc1637b3)



playing_with_pixels Function:
This function manipulates pixel colors in an image to create a simple graphical scene.

![image](https://github.com/neelay-16/Python-Menu-using-tkinter/assets/135517502/b546ec34-e357-4e68-88e7-61a665a85b9e)


object_detection Function:
This function uses Amazon Rekognition to detect labels in an image.

![image](https://github.com/neelay-16/Python-Menu-using-tkinter/assets/135517502/0cb58abf-a0df-42c6-99ec-0d6decb3efce)


Tik_Tac_TOE Function:
This function implements a text-based Tic Tac Toe game where two players can take turns to play.

![image](https://github.com/neelay-16/Python-Menu-using-tkinter/assets/135517502/7f72d4dd-daee-4958-9e21-fa56b4923c7a)


geo_coordinates Function:
This function retrieves the GPS coordinates (latitude and longitude) of the user's IP address using the geopy library.

![image](https://github.com/neelay-16/Python-Menu-using-tkinter/assets/135517502/d727d2a9-76dc-4b48-b3e5-c27514457f71)


whatsapp_message Function:
This function sends an instant WhatsApp message using the pywhatkit library.

Main Application Window (root):
The main GUI window is created using tkinter and includes buttons to access different functionalities. Menu options for "File" (Exit) and "About" (Team Info) are also provided.

Menu Bar:
The application includes a menu bar with options to exit the program and access information about the development team.
Event Loop:

The root.mainloop() call starts the Tkinter event loop, allowing the user to interact with the GUI and trigger various functions.

A graphical user interface (GUI) will open, allowing you to select and execute various tasks and operations.





