# AI_Desktop_Voice_Assistant

A Python program that functions as a voice-controlled personal assistant, similar to Jarvis from the Iron Man movies. It uses various libraries and modules to perform tasks such as responding to voice commands, searching Wikipedia, opening web browsers, playing music, and sending emails.

Key Features:

Voice Recognition and Text-to-Speech: The program utilizes the speech_recognition and pyttsx3 libraries to recognize voice commands from the user and respond with spoken text.

Greetings: It greets the user based on the current time of day (morning, afternoon, or evening) when the program starts.

Wikipedia Search: It can search for and read a summary from Wikipedia based on user queries.

Web Browsing: The program can open web pages for YouTube, Google, and Stack Overflow based on user commands.

Music Player: It can play music from a specified directory using the os module. The music directory is predefined in the code.

Time Query: When asked, it can tell the current time.

Email Functionality: It can send emails to a predefined recipient. The sender's email and password must be provided in the code for this functionality to work.

Usage:

When the program is executed, it greets the user and awaits voice commands.

The user can give voice commands such as "Open YouTube," "Tell me about [topic]," "Play music," and "Email to [recipient]." The program responds accordingly.

To send an email, the user must provide the content of the email, and the recipient's email address must be predefined in the code.
