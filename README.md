Accounting Ledger CLI Application 

Overview 

  The Accounting Ledger CLI Application is a Java-based tool designed for tracking financial transactions. It provides a command-line interface (CLI) for users to manage deposits, payments, and view transaction history efficiently. 

Features 

  Transaction Management: 

  - Add deposits with details such as date, time, description, vendor, and amount. 

  - Record payments with similar detailed information. 

Ledger Display 

  - View the entire transaction history. 

  - Filter to view only deposits or payments. 

  - Improved display for a more user-friendly experience. 

Financial Reports 

  Generate predefined reports for 

  - Month-to-date 

  - Previous month 

  - Year-to-date 

  - Previous year

  - Vendor name

  - Custom search

Error Handling 

- Updated error catch mechanisms to ensure smooth and accurate transaction management. 

- Clear error messages to guide users in correcting issues. 

Code Highlights 

- Comparable Interface 

- The implements keyword in Java allows access to an interface, such as Comparable. 

Comparable Interface 

  - Similar to a class but contains empty methods to be defined with @Override. 

  - The compareTo method, part of the Comparable interface, enables object comparison. 

compareTo Method 

- The compareTo method is used for sorting Transactions objects by date. 

- Utilizes the compareTo method from LocalDate for date comparison. 

- Compares the current object's date with the next object's date: 

- Returns -1 if the current object's date is before the next object's date. 

- Returns 0 if the dates are equal. 

- Returns 1 if the current object's date is after the next object's date. 

- This method ensures that Transactions objects are sorted in chronological order. 

Getting Started 

  Prerequisites 

   - Java Development Kit (JDK) installed 

Usage 

- Clone the repository. 

- Navigate to the project directory. 

- Compile and run the application. 

- Use the CLI to add deposits, record payments, and view the ledger. 

License 

This project is licensed under the MIT License. 

<img width="503" alt="9" src="https://github.com/Erikarod27/AccountingLedger/assets/113813867/ebda585d-73cd-4c74-8f25-2cc78251b905">
<img width="512" alt="10" src="https://github.com/Erikarod27/AccountingLedger/assets/113813867/a2620d3e-d600-4fc7-ae46-02f7daa26345">


Images of Application Screens:

<img width="234" alt="UpdatedLedgerDisplay" src="https://github.com/user-attachments/assets/f71708a6-366d-46c3-a094-6d7dcddc9219">
<img width="629" alt="AccountLedgerError" src="https://github.com/user-attachments/assets/9ec2b2ed-fde4-428c-adc9-086f8a13106c">
<img width="243" alt="Payment" src="https://github.com/user-attachments/assets/c08d5956-0582-4332-901b-eb36c95ddcd8">
<img width="345" alt="Ledger" src="https://github.com/user-attachments/assets/37a74d3f-9ec9-4e92-8f8e-397477f85d9f">
<img width="369" alt="Reports" src="https://github.com/user-attachments/assets/7f8a99a0-02a4-4264-8114-bec548b80d92">
<img width="235" alt="Goodbye" src="https://github.com/user-attachments/assets/fd608046-e520-402d-ad01-f6a5d1e24807">



