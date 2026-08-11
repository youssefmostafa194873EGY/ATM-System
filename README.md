💻 ATM System Simulation Project in C++
A comprehensive C++ project simulating an ATM Main Menu System that manages everyday financial transactions with dynamic file I/O capabilities for persistent data management.

Key Features:
Authentication & Security: Secure login system that verifies account numbers and corresponding PIN codes.

Quick Withdraw: Preset withdrawal amounts (from 100 to 20,000) with real-time balance validation.

Normal Withdraw: Custom amount withdrawal requiring multiples of 5 and a minimum of 100, integrated with insufficient funds checks.

Deposit & Balance Check: Instant deposit functionality and real-time account balance inquiry.

Data Persistence (File I/O):

Loads customer data from external files (the bank.txt) using custom string delimiters (#//#).

Updates and saves modified customer balance data back to the file upon logout.

Technical Stack & Concepts:
Data Structures (std::vector & struct): Efficient in-memory handling of customer records.

File Handling (std::fstream): Automated reading and writing of database records.

String Manipulation: Custom parsing and serialization algorithms for delimited strings.

Clean Code Architecture: Modular functional design utilizing enum for state management and user validation logic.
