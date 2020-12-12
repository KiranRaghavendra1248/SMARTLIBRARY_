# DSCWOW_SMARTLIBRARY
Library system automation using Real-Time Face Recognition and Optical Character Recogntion

# OBJECTIVE
Automation of  libraries in schools and colleges , for effective storage of records of students who frequent the libraries to borrow books.
Our main aim is to remove the current drawbacks i.e the requirement of a physical presence in the library who takes down records of people borrowing books.
We completely automate the process of borrowing a book so the person who borrows the book has zero or minimal contact with other people.

# IMPLEMENTATION
We use the infamous MTCNN algorithm to detect extract and align faces .
The software requires a real time video of the person which spans for 20 seconds as the ground truth value, which is used to train our model.
The student then enters his USN/roll number or anything that uniquely identifies them in their place of study.
The network verifies the person using One Shot Learning using a Siamese Network  when he enters his USN.
We then use OCR (Optical Character Recognition) to automate the process of identifying the name of the book borrowed, 
and in this manner we can store the record of the person borrowing the book.
The record includes the USN of the person borrowing the book , the name of the book and the date and time of when the book was borrowed. 
