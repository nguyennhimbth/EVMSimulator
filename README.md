# EVMSimulator

EVMSimulator is a lightweight and user-friendly electronic voting machine application built using Python's Tkinter library. Designed for simplicity and ease of use, it provides a basic framework for casting and managing votes with both a public voter interface and a secure administrator panel.
This project was developed with the aim of demonstrating a fundamental voting system structure, including features like candidate management, real-time vote counting, and secure administrative controls.

# Features

**Voter Interface:**
- Intuitive display of candidates.
- Ability to cast a single vote for a selected candidate.
- Real-time indication of voting period status (open/closed).
- Administrator Panel (Secure):
- Voting Control: Manually open and close the voting period.
- Live Statistics: View total votes cast in real-time.
  
**Secure Administration (Password Protected):**
- View detailed vote results and percentages.
- Reset all votes (requires re-authentication).
- Manage candidates (add, edit, remove, up to 32 candidates).
- Change administrator password.
- Data Persistence: Voting data (candidates, votes, voting status) and administrator password hash are saved to local JSON files, ensuring data is retained between sessions.
- Event Logging: All significant actions (e.g., voting opened/closed) are logged with timestamps for auditing.
- Password Security: Administrator password is stored as a SHA-256 hash.
