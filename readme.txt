# Blood Bank System Setup Guide

## Prerequisites

- **XAMPP** (for running the server and MySQL database)
- **Text Editor** (like Notepad++, Sublime Text, or any other)
- **Blood Bank System** source code

---

## Steps to Install:

### 1. Download and Install XAMPP:
   Make sure to download and install XAMPP, as it will run the Apache server and MySQL.

### 2. Download the Source Code:
   Download the **Blood Bank System** zip file from the provided source.
   
   *(Ensure you have WinRAR or any unzip tool to extract the file.)*

### 3. Extract the Zip File:
   After downloading, extract the **Blood Bank System** folder.

### 4. Move the Folder to XAMPP Root Directory:
   Copy the extracted folder and paste it into the XAMPP `htdocs` directory.
   
   **For Example:**
   - On Windows: `C:/xampp/htdocs`
   - On other drives: `D:/xampp/htdocs`, etc.

### 5. Set Up the Database:

   - Open your browser and navigate to [http://localhost/phpmyadmin](http://localhost/phpmyadmin).
   - Create a new database named: `bloodbank_db`.
   - Import the **bloodbank_db.sql** file from the extracted folder’s **SQL file** subfolder.

### 6. Run the Application:
   Open your browser and navigate to:
   ```bash
   http://localhost/bloodbank
