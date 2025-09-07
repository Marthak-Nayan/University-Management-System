# 🎓 University Management System


---

## 🛠 Tools Required
- **NetBeans IDE**
- **XAMPP (MySQL + Apache)**

---

## 📚 Libraries Used
- `jcalendar-tz-1.3.3-4.jar` → For date picker/calendar functions
- `mysql-connector-j-8.0.32.jar` → To connect Java with MySQL database
- `rs2xml.jar` → To display database records in JTable (ResultSet to TableModel)

---

## 🚀 Steps to Run the Project

### Step 1: Import Libraries
- Open the project in **NetBeans**
- Right-click on the project → **Properties → Libraries → Add JARs**
- Import:
  - `jcalendar-tz-1.3.3-4.jar`
  - `mysql-connector-j-8.0.32.jar`
  - `rs2xml.jar`

---

### Step 2: User Login
- Run the application
- Choose login type:
  - **Admin**
  - **Employee**
  - **Student**

---

### Step 3: Open Home Page
- After login, the system opens the **respective panel**:
  - Admin Panel
  - Employee Panel
  - Student Panel

---

### Step 4: Perform Operations
Based on user role, you can perform tasks such as:
- ➕ Add new information  
- ✏️ Update data  
- 🔍 Search details  
- 📘 Manage course details  
- 📝 Examination details  
- 📑 Other required operations  

---

### Step 5: Exit / Logout
- User can either **logout** to switch accounts
- Or **exit** to close the application

---

## 📌 Notes
- Make sure **XAMPP (MySQL)** server is running before login
- Configure the **database connection** in code with your MySQL username & password
- Import the project database (`.sql` file) before running the project
