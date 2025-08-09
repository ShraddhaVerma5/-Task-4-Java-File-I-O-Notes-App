# -Task-4-Java-File-I-O-Notes-App

# 📓 Java Notes App

A simple **Java File I/O** based notes manager that allows you to **add** and **view** notes through the terminal.  
It demonstrates file persistence using `FileWriter` and `BufferedReader`.

---

## 📌 Features
- Add notes without overwriting existing ones (append mode).
- View all saved notes from `notes.txt`.
- Menu-driven console interface.
- Handles missing file and I/O errors gracefully.

---

## 🛠️ Technologies Used
- **Java** (Core)
- **FileWriter** for writing notes
- **BufferedReader** + **FileReader** for reading notes
- **VS Code** / any Java IDE
- **Terminal** for execution

---

## 📂 Project Structure
1. **Start the program** → Show menu options.
2. **User chooses**:
   - **Add Note** → Take input and save it to `notes.txt`.
   - **View Notes** → Display all saved notes.
   - **Exit** → Close the program.
3. Loop until the user exits.

---

## ▶️ How to Run
### 1️⃣ Clone the repository
```bash
git clone https://github.com/ShraddhaVerma5/-Task-4-Java-File-I-O-Notes-App
cd Task-4-Java-File-I-O-Notes-App

---

💻 Example Output
=== Notes App ===
1. Add Note
2. View Notes
3. Exit
Enter your choice: 1
Enter your note: Complete Java File I/O Task
Note saved successfully!

=== Notes App ===
1. Add Note
2. View Notes
3. Exit
Enter your choice: 2

--- All Notes ---
- Complete Java File I/O Task

