# 📚 DBMSL Practicals  
_All DBMSL Practicals for SPPU (2019 Pattern) — Computer Engineering_  

---

## 🧩 Practical 1: College Library Management System  
**Objective:**  
Design and develop a database schema that demonstrates the use of **SQL DDL statements**.  

**Tasks:**  
- Create SQL objects such as **Tables**, **Views**, **Indexes**, **Sequences**, and **Synonyms**.  
- Apply appropriate **constraints** like `PRIMARY KEY`, `FOREIGN KEY`, `UNIQUE`, `CHECK`, and `NOT NULL`.  
- Ensure efficient storage of information about **students**, **books**, and **transactions**.  

---

## 🧮 Practical 2: Student Result Management System  
**Objective:**  
Implement at least **10 SQL DML queries** for a Student Result Management System.  

**Tasks:**  
- Perform operations such as `INSERT`, `UPDATE`, `DELETE`, and `SELECT`.  
- Use **arithmetic**, **comparison**, **logical**, and **set operators**.  
- Apply **built-in SQL functions**.  
- Work with tables like **Student**, **Marks**, and **Result**.  

---

## 🏢 Practical 3: Company Employee Database Application  
**Objective:**  
Develop 10 SQL queries using **Joins**, **Subqueries**, and **Views**.  

**Tasks:**  
- Extract meaningful business insights such as:  
  - Department-wise employee lists  
  - Highest-paid employees  
  - Performance-based selections  
- Demonstrate **advanced SQL techniques**.  

---

## ⚙️ Practical 4: PL/SQL Code Block (Control Structures & Exception Handling)  
**Schema:**  
- `Borrower(Rollin, Name, DateofIssue, NameofBook, Status)`  
- `Fine(Roll_no, Date, Amt)`  

**Requirements:**  
- Accept `roll_no` and `name of book` from the user.  
- Calculate fine:  
  - If days between 15–30 → ₹5 per day  
  - If days > 30 → ₹50 per day  
- Update book status from **‘I’ (Issued)** to **‘R’ (Returned)** after submission.  
- If fine applies, insert details into the **Fine** table.  

---

## 🎓 Practical 5: Stored Procedure — Student Categorization  
**Procedure:** `proc_Grade`  

**Logic:**  
- If `marks >= 990 and <= 1500` → **Distinction**  
- If `marks between 900 and 989` → **First Class**  
- If `marks between 825 and 899` → **Higher Second Class**  

**Tables:**  
- `Stud_Marks(name, total_marks)`  
- `Result(Roll, Name, Class)`  

**Task:**  
Write a PL/SQL block to use the above stored procedure.  

---

## 🧾 Practical 6: Parameterized Cursor & Trigger  
**Tasks:**  
1. Write a PL/SQL block using a **parameterized cursor** to merge data from:  
   - `N_RollCall` (new)  
   - `O_RollCall` (old)  
   Skip records that already exist in `O_RollCall`.  
2. Write a **database trigger** on the `Library` table to:  
   - Track **updated** or **deleted** records.  
   - Store old values in the **Library_Audit** table.  

---

## ☕ Practical 7: Java Database Connectivity (JDBC)  
**Objective:**  
Implement **MySQL/Oracle** database connectivity using Java.  

**Features:**  
- Perform database navigation operations:  
  - Add  
  - Delete  
  - Edit  
  - View  

---

## 🛒 Practical 8: MongoDB — Online Shopping Application  
**Objective:**  
Design and develop a **MongoDB** database with full **CRUD** functionality.  

**Tasks:**  
- Implement `Create`, `Read`, `Update`, and `Delete` operations.  
- Use logical operators and the `save()` method.  
- Manage collections for shopping data.  

---

## 📊 Practical 9: MongoDB Aggregation & MapReduce  
**Tasks:**  
- Implement **aggregation** and **indexing** with suitable examples.  
- Demonstrate **MapReduce** operations using MongoDB.  

---

## 💻 Practical 10: MongoDB Java Connectivity  
**Objective:**  
Write a Java program to implement **MongoDB connectivity** and perform:  
- Add  
- Delete  
- Edit  
- Navigation operations  

