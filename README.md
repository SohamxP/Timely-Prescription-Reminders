# Timely Prescription Reminder 
It is a super helpful app that makes it easy for elderly patients to manage their medication schedules. It’s like having a personal assistant that helps you remember to take your medicines at the right time and in the right dose. Whether you’re the patient or your caregiver, you can input all the details about your prescriptions, and the app will send you timely reminders. This way, you can avoid missing or taking the wrong dose, which is especially important for older adults who might have memory problems or complicated medication routines.

# Programming Concepts Used 
  1. Structured Programming : Uses the functions to divide the logic into manageable parts (e.g inputData(), addMedicine(), removeMedicine(), displayPatient(), displayContacts(),  etc). This improves readability and reusability.
  2. File Handling : The program reads from and writes to files like : i. patientInfo.txt ii. Medication.txt iii. Schedule.txt iv. Emergencycontact.txt v. pharmacyInfo.txt; Concepts Used : i. fopen(), fclose() ii.  fprint(), fscanf(), fgets(), fread() iii. File modes: “r”, “w”, “a”.
  3. Structs (User-Defined Data Types) : This allows complex data organization, e.g storing patient or medication details. i. typedef struct Patient ii. typedef struct Medication iii. typedef struct Emergency iv. typedef struct Pharmacy v. typedef struct Address.
  4. Arrays and Strings : Arrays are used for storing medication schedules, user inputs, and string buffers; char arrays (char name[10]) are used to simulate strings; Multi-dimensional char arrays are used to simulate arrays of strings for handling file data (char x[100][100]).
  5. Time Function : The time.h library is used for date/time functionalities: - time(), localtime() to get current day, month, and year.
  6. Pointers Usage : Pointers are used for struct manipulation (e.g., Medication *mptr); Indirect access to struct members; File pointers (FILE *fptr).
