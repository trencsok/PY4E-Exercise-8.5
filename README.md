# PY4E-Exercise-8.5
Exercise 8.5 in Python for Everyone<br/> 
Exercise 5: Minimalist Email Client.<br/>
Source: https://www.py4e.com/html3/08-lists

MBOX (mail box) is a popular file format to store and share a collection of emails. This was used by early email servers and desktop apps. Without getting into too many details, MBOX is a text file, which stores emails consecutively. Emails are separated by a special line which starts with From (notice the space). Importantly, lines starting with From: (notice the colon) describes the email itself and does not act as a separator. Imagine you wrote a minimalist email app, that lists the email of the senders in the user’s Inbox and counts the number of emails.

Write a program to read through the mail box data and when you find line that starts with “From”, you will split the line into words using the split function. We are interested in who sent the message, which is the second word on the From line.
