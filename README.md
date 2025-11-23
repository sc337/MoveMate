# MoveMate — Student Moving Assistant App  
### Android Development Project (Module 6 – Week 4 Update)

MoveMate is a mobile app designed to help students stay organized during the moving process. The app allows users to manage tasks, maintain an inventory list, and track their moving expenses. Data is stored locally using SQLite for fast performance and offline access.

---

## 📱 Features
- ✔️ Task list with add, edit, delete  
- ✔️ Inventory list using RecyclerView  
- ✔️ SQLite local database storage  
- ✔️ Navigation between multiple screens  
- ✔️ Basic UI layouts and icons  
- ✔️ Budget tracking screen (in progress)

---

## 🏗️ Project Structure

app/
├── java/
│ └── com.movemate/
│ ├── HomeActivity.java
│ ├── TaskActivity.java
│ ├── InventoryActivity.java
│ ├── BudgetActivity.java
│ ├── DatabaseHelper.java
│ └── models/
│ ├── Task.java
│ └── InventoryItem.java
├── res/
│ ├── layout/
│ ├── drawable/
│ └── values/


---

## Database Schema
### **Tasks Table**
| Column | Type |
|--------|-------|
| id | INTEGER PRIMARY KEY |
| title | TEXT |
| description | TEXT |
| due_date | TEXT |
| status | TEXT |

### **Inventory Table**
| Column | Type |
|--------|-------|
| id | INTEGER PRIMARY KEY |
| item_name | TEXT |
| category | TEXT |
| condition | TEXT |
| quantity | INTEGER |

### **Expenses Table**
| Column | Type |
|--------|-------|
| id | INTEGER PRIMARY KEY |
| amount | REAL |
| category | TEXT |
| date | TEXT |

---

## Installation & Running the App
1. Clone the repository  
2. Open the project in **Android Studio**  
3. Let Gradle sync  
4. Run app on emulator or physical device  

---

## Version Changelog
See Version Log in `/docs/version_log.md`  
(Current Version: **1.2 – Week 4**)

---

## Upcoming Work (Weeks 5–7)
- Implement reminders  
- Improve UI theme  
- Add onboarding screen  
- Add export/share feature  
- Finalize and test all features  

---

## Developer  
Shawn Caesar  
Saint Leo University — Android App Development  
