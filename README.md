# Pharmacy Management Software

This GitHub repository hosts the project was prepared for SEN2212/Data Structures and Algorithms II.

## Project Details

- Developed in Java using the Eclipse IDE.
- Achieves O(1) time complexity for insertion and deletion through the use of Linked list and LinkedHashMap data structures.
- Maintains insertion order with the use of LinkedHashMap.
- Ensures uniqueness of elements with the use of LinkedHashMap.

## Getting Started

To get started with the Pharmacy Management System, you will need to have Java and the Eclipse IDE installed on your machine.

1. Clone the repository to your local machine.
2. Open the project in Eclipse.
3. Run the program to start the login system.

## Software Language/Project Environment

- **Language:** The project is developed using the Java programming language within the Eclipse IDE.
- **GUI Development:** We utilized WindowBuilder to build the graphical user interface (GUI).
- **fficient data structures for organization:** Linked list and LinkedHashMap.


## Data Structures

In our project, we manage three main objects: pharmacies, employees, and patients. To establish connections between employees and their respective pharmacies, we implemented a linked list data structure. This choice was made due to its O(1) time complexity for insertion and deletion, offering efficiency compared to arrays. Additionally, we connected patient information to pharmacies using a LinkedHashMap. This data structure maintains insertion order, provides O(1) time complexity for insertion and deletion, and stores unique elements.

## Application Features

### 1. Login to Pharmacy
   - Validate pharmacy name and password.
   - If credentials are correct, proceed to employee login.

### 2. Login to Employee/Patient
   - Validate employee name and password.
   - Successful login adds the employee to the linked list of their respective pharmacy.
   - Access to patient information management.

### 3. Add Patient
   - Input validation for ID, phone number, and age (numeric only).
   - Name and surname accept alphabetical characters only.
   - Ensures all required patient information is provided.
   - Adds patients to the JTable and the pharmacy's LinkedHashMap.

### 4. Update Patient
   - Input validation for ID, phone number, and age (numeric only).
   - Name and surname accept alphabetical characters only.
   - Ensures all required patient information is provided.
   - Updates patient records in the JTable and the pharmacy's LinkedHashMap.

### 5. Search Patient
   - Search patients by their unique ID.
   - Utilizes filtering for efficient searching.

### 6. Delete Patient
   - Select a patient in the JTable and delete them.
   - Removes the patient from the JTable and the pharmacy's LinkedHashMap.

## Conclusion / Summary

Our project's main objective is to implement what we have learned in the SEN2212/Data Structures and Algorithms II course into a real-world example.
