Hey everybody!!

**EXCEL**

### **Table of Contents**
- [**Table of Contents**](#table-of-contents)
- [**Excel Fundamentals**](#excel-fundamentals)
  - [**Introduction to Excel**](#introduction-to-excel)
    - [**Excel**](#excel)
    - [**Uses of Excel**](#uses-of-excel)
    - [**Workbook vs Worksheet**](#workbook-vs-worksheet)
    - [**Rows, Columns and Cells**](#rows-columns-and-cells)
    - [**Active Cell**](#active-cell)

### **Excel Fundamentals**

#### **Introduction to Excel**

##### **Excel**

**What is Excel?**

*Microsoft Excel is a spreadsheet software developed by Microsoft that is used to:*
- *Store data*
- *Organize data*
- *Perform Calculations*
- *Analyze data*
- *Create reports*
- *Build dashboards*
- *Visualize data using charts*

**Example:** *Suppose you own a small shop*

| Product | Quantity | Price |
| ------- | -------- | ----- |
| Pen     | 10       | 5     |
| Book    | 20       | 50    |

*If you want total sales:*
- *Pen sales = 10 * 5 = 50*
- *Book sales = 20 * 50 = 1000*

*Excel can calculate this automatically using formulas.*

---

**Real-World uses of Excel**

1. **Business**
    - *Used for Sales Reports, Revenue Tracking, Expense Tracking, Profit Analysis.*
    - **Example:** *A company tracks monthly sales in Excel.*
  
2. **HR Department**
    - *Used for Employee Records, Attendance Tracking, Salary Sheets, Leave Management.*
    - **Example:** *HR maintains employee attendance for 500 employees.*

3. **Finance Department**
    - *Used for Budget Planning, Loan Calculations, Financial Statements.*
    - **Example:** *Accountants prepare profit and loss reports.*

4. **Data Analyst**
    - *Used for Data Cleaning, Data Validation, Pivot Tables, Dashboards, KPI Reporting.*
    - **Example:** *Analyzing customer purchase data.*


5. **Students**
    - *Used for Marks Calculation, Project Tracking, Attendance.*
    - **Example:** *Calculating semester percentages.*

---

**Why Excel is important for Data Analyst?**

- *Because raw data usually comes in:*
  - *Excel files (.xlsx)*
  - *CSV files (.csv)*
- *Before SQL, Python or Power BI, analysts often clean and inspect data in Excel.*
- *Common analyst tasks:*
  - *Remove duplicates*
  - *Find missing values.*
  - *Create pivot tables*
  - *Generate reports*
  - *Build dashboards*

---

**Advantages of Excel**

- **Easy to learn:** *No programming needed.*
- **Fast Calculations:** *Can calculate thousands of rows instantly.*
- **Powerful Analysis:** *Pivot tables and formulas simplify analysis.*
- **Visualization:** *Can create charts and dashboards.*
- **Industry Standard:** *Almost every company uses excel.*

---

**Limitations of Excel:**

- **Large Data Problems:** 
   - *Excel is not ideal for millions of rows.*
   - *For huge datasets:*
     - *SQL*
     - *Python*
     - *Power BI*
   *are better* 

---

##### **Uses of Excel**

**What are the uses of Excel?**

*Excel is used to:*
  1. **Store data:** *Excel can store large amounts of information in rows and columns.*
    
  **Example:** *Student records*

  | Student ID | Name  | Marks |
  | ---------- | ----- | ----- |
  | 101        | Ravi  | 85    |
  | 102        | Priya | 92    |
  | 103        | Kiran | 78    |

 *Instead of maintaining records on papers, they can be stored digitally.*

 **Example:** 
 - *A college stores details of thousands of students in Excel.*
 - *Information may include:*
   - *Student ID*
   - *Name*
   - *Phone Number*
   - *Marks*
   - *Attendance*

  2. **Organize data:** *Excel helps arrange data in a structured format.*
     
  **Unorganized Data:**

      Ravi 85

      Priya 92

      Kiran 78

  **Organized Data:**

  | Name  | Marks |
  | ----- | ----- |
  | Ravi  | 85    |
  | Priya | 92    |
  | Kiran | 78    |
   
  *Organized data is easier to read and analyze.*

  **Example:** *An HR department organizes employee information:*
  | Emp ID | Name | Department |
  | ------ | ---- | ---------- |
  | E101   | Ram  | HR         |
  | E102   | Sita | Finance    |

  3. **Perform Calculations:** *Excel can perform calculations automatically using formulas.*
    
   **Example:**
   | Product | Qty | Price |
   | ------- | --- | ----- |
   | Pen     | 10  | 5     |

   **Formula:** 
   ```excel
   =10*5        Result: 50
   ```

   **Example:**

   - *A shop owner calculates:*
     - *Total Sales*
     - *Profit*
     - *Expenses*
     - *Monthly Revenue*
    
  *using Excel formulas.*

  4. **Data Analysis:** *Analyzing data means finding useful information from raw data.*

   **Example:** *Sales data*

   | Month | Sales |
   | ----- | ----- |
   | Jan   | 50000 |
   | Feb   | 70000 |
   | Mar   | 90000 |

   **Questions:** 

   - *Which month had highest sales?*
   - *Average sales?*
   - *Growth Percentage?*
   
   *Excel can answer these using functions and Pivot tables.*

   **Example:** 

   - *A Data Analyst receives customer sales data and finds:*
     - *Best-selling products*
     - *Top customers*
     - *Monthly growth* 

  5. **Reporting:** *Reports summarize information for management.*

   **Example:** *Monthly Sales Report*
   | Month | Revenue |
   | ----- | ------- |
   | Jan   | 50000   |
   | Feb   | 70000   |
   | Mar   | 90000   |

   *Management uses reports to make decisions.*

   **Example:**

   - *Every month companies generate:*
     - *Sales Reports*
     - *Employee Reports*
     - *Expense Reports*
     - *Inventory Reports* 

   *using Excel.*

   6. **Dashboard Creation:** *A dashboard is a visual summary of business performance.*
   
   **Dashboard may contain**
   - *Revenue*
   - *Profit*
   - *Growth*
   - *Charts*
   - *KPIs*

   **Example:** *CEO Dashboard*
   
   *Shows*
   - *Total Revenue*
   - *Total Customers*
   - *Profit Margin*
   - *Monthly Growth*

   *on one screen.*

   7. **Budget Planning:** *Excel helps plan income and expenses.*

   **Example:**
   | Category | Amount |
   | -------- | ------ |
   | Salary   | 50000  |
   | Rent     | 10000  |
   | Food     | 5000   |
   | Savings  | 15000  |
   
   **Example:** *Finance departments create annual budgets in Excel.*

   8. **Financial Analysis:** *Analyzing money-related information.*

   **Examples:**
   - *Profit*
   - *Loss*
   - *ROI*
   - *Investments*
   - *Loans*

   **Example:** *An accountant calculates*
   - *Net Profit*
   - *Tax*
   - *Cash Flow*

   *using Excel.*

   9. **Inventory Management:** *Tracking stock available in a business.*

   **Example:**
   | Product | Stock |
   | ------- | ----- |
   | Pen     | 100   |
   | Book    | 50    |
   
   *Excel helps identify:*
   - *Low stock*
   - *High stock*
   - *Reorder quantity*

   **Example:** *A supermarket tracks thousands of products using Excel.*

   10. **Employee Management:** *Managing employee information.*
   
   **Example:**
   | Emp ID | Name | Salary |
   | ------ | ---- | ------ |
   | E101   | Ravi | 40000  |

   **Example:** *HR uses excel for:*
   - *Attendance*
   - *Payroll*
   - *Employee Database*
   - *Leave Tracking*

   11. **Education Sector:** 
   
   *Uses*

   - *Marks Calculation*
   - *Attendance Tracking*
   - *Timetable Management*
   - *Result Analysis*

   **Example:**
   | Subject | Marks |
   | ------- | ----- |
   | Math    | 90    |
   | Science | 85    |

   *Excel automatically calculates:*
   - *Total Marks*
   - *Average*
   - *Percentage*

   12. **Data Cleaning:** *Fixing messy data.*

   **Example:** *Before Cleaning*
   | Name |
   | ---- |
   | Ravi |
   | ravi |
   | RAVI |
  
   *After Cleaning*
   | Name |
   | ---- |
   | Ravi |

   **Example:** *Data Analysts spend a large portion of their time cleaning data before analysis.*

   13. **Automation:** *Automating repetitive work.*

   **Example:** *Instead of calculating salary for 1000 employees manually, Excel formulas can calculate all salaries instantly.*

   **Advanced Automation:**
   - *Macros*
   - *VBA*
   - *Power Query*

---

##### **Workbook vs Worksheet**

**What is a Workbook?**

- *A workbook is an Excel file that contains one or more worksheets.*
- *Think of a workbook as a book. Just like a physical book contains many pages, an excel workbook contains one or more worksheets.*

**File Extension:**

*Common workbook file extensions are:*
- *`.xlsx`(Standard Excel Workbook)*
- *`.xls`(Older Excel Workbook)*
- *`.xlsm`(Macro-enabled Workbook)*

**Example:**

- *Imagine you work in a company. The company maintains a file name Sales_Report_2026.xlsx. This Single file is a Workbook.*
- *Inside this workbook there may be:*
  - *January Sales*
  - *February Sales*
  - *March Sales*
  - *April Sales*
  - *May Sales*
  - *Summary Report*

*Each of these is a separate worksheet.*

---

**What is a Worksheet?**

- *A Worksheet is a single spreadsheet(sheet) inside a workbook.*
- *It is made up of:*
  - *Rows*
  - *Columns*
  - *Cells*

*This is where you actually enter, edit and analyze data.*

**Example:**
- *Suppose your workbook is Employee_Data.xlsx.*
- *Inside it, you have:*
  - *Employees*
  - *Attendance*
  - *Salary*
  - *Leaves*
  - *Performance*

*Each one is a Worksheet.*

---

**Workbook vs Worksheet**

| Workbook                             | Worksheet                                     |
| ------------------------------------ | --------------------------------------------- |
| Excel file                           | A sheet inside the workbook                   |
| Can contain multiple worksheets      | Contains rows, columns, and cells             |
| Saved as `.xlsx`, `.xls`, or `.xlsm` | Cannot exist independently outside a workbook |
| Example: `Sales_Report.xlsx`         | Example: January, February                    |

---

**Why use multiple worksheets?**

*Instead of putting everything on one sheet, we separate related information.*
 - *If one worksheet contains employees, sales, attendance, salary, customers this become difficult to read and maintain.*
 - *If we maintain separately in a workbook with worksheets it is organized and easy to manage.*

---

**Advantages of using multiple worksheets**

- **Better Organization:** *Each sheet stores one type of information.*
- **Easier Navigation:** *Instead of scrolling through thousands of rows, switch directly to the required worksheet.*
- **Better reporting:** *One worksheet stores raw data. Another worksheet stores pivot tables.. Another worksheet stores charts. Another worksheet stores dashboards.*
- **Better security:** *Specific worksheets can be protected while leaving others editable.*

---

##### **Rows, Columns and Cells**

**What is a Row?**

- *A Row is a horizontal line of cells in an Excel worksheet.*
- *Rows run from left to right.*
- *Each row is identified by a number.*

**Example:**
|      |   A  |   B   |   C   |
|------|------|-------|-------|
|   1  |      |       |       |
|   2  |      |       |       |
|   3  |      |       |       |
|   4  |      |       |       |
|   5  |      |       |       |


*The numbers 1, 2, 3, 4, 5 represents Rows.*

**Example:** *Imagine a company with 5000 employees. Each employee's information occupies one row.*

| Row  | Employee      |
| ---- | ------------- |
| 2    | Ravi          |
| 3    | Priya         |
| 4    | Kiran         |
| ...  | ...           |
| 5001 | Last Employee |

*This makes it easy to store and manage employee records.*

---

**Characteristics of Rows**

- *Horizontal*
- *Numbered*
- *Store one complete record*
- *Start from Row 1*

---

**Maximum number of Rows**

- *Modern Excel (Excel 2007 and later supports) 1,048,576 rows.*
- *This means you can store over 1 million records in a single worksheet.*

**Why is this important?**

*Suppose an e-commerce company has 800,000 customer orders. Since excel supports over 1 million rows, all these orders can fit in one worksheet. If the data exceeds this limit, tools like SQL or databases are more suitable.*

---

**What is a Column?**

- *A Column is a vertical line of cells in an Excel worksheet.*
- *Columns run from top to bottom.*
- *Each column is identified by letters.*

**Example:**
|      |   A  |   B   |   C   |
|------|------|-------|-------|
|   1  |      |       |       |
|   2  |      |       |       |
|   3  |      |       |       |
|   4  |      |       |       |
|   5  |      |       |       |

*Columns are labeled: A B C D ..... After Z excel continues with AA AB AC .... AZ BA BB ...*

**Example:** *In a company's employee database*
| Column | Stores       |
| ------ | ------------ |
| A      | Employee ID  |
| B      | Name         |
| C      | Department   |
| D      | Salary       |
| E      | Joining Date |

*Each column represents a specific field or attribute.*

---

**Characteristics of Columns**

- *Vertical*
- *Lettered*
- *Store one category of information*
- *Start from column A*

---

**Maximum number of columns**

- *Modern excel supports 16,384 columns. The last column is XFD. So excel columns go from A B C D ....XFD.*

**Why is this important?**

*Imagine a hospital database with many details Patient ID, Name, Age, Gender, Blood Group, Address, Phone Number, Diagnosis, Doctor, Admission Date, Discharge Date. Each detail gets its own column.*

---

**What is a Cell?**

- *A Cell is the intersection of a Row and a Column.*
- *A Cell is the smallest unit in an excel worksheet where you enter data.*

**Example:**
|      |   A  |   B   |   C   |
|------|------|-------|-------|
|   1  |      |       |       |
|   2  |      |   ●   |       |
|   3  |      |       |       |
|   4  |      |       |       |
|   5  |      |       |       |

*The highlighted point is where Column B and Row 2 meet. That cell is called B2.*

**Example:**
| A           | B    | C      |
| ----------- | ---- | ------ |
| Employee ID | Name | Salary |
| E101        | Ravi | 35000  |

- *The cell containing Ravi is B2.*
- *The cell containing 35000 is C2.*

---

**What can a cell contain?**

*A Cell can contain Text(Ravi), Numbers(6789), Dates(28-06-2026), Time(10:30 AM), Formulas(=A1+B1), Functions(=SUM(A1:A10))*

---

**Cell Address(Cell Reference)**

- *Every cell has a unique address.*
- *A cell address is formed by combining Column Letter + Row Number.*

**Example:**
| Cell Address | Meaning          |
| ------------ | ---------------- |
| A1           | Column A, Row 1  |
| B2           | Column B, Row 2  |
| C5           | Column C, Row 5  |
| D10          | Column D, Row 10 |

**Example:**
      A       B        C

1   Name    Age     City

2   Ravi    22    Hyderabad

- *Ravi is A2*
- *22 is B2*
- *Hyderabad is C2*

**Why are cell addresses important?**

- *Excel formulas use cell addresses.*
  - **Example:** *=A1+B2* *Instead of =100+200*
- *Using cell addresses makes formulas dynamic. If the values in A2 or B2 change, the result updates automatically.*

---

**Difference between Rows, Columns and Cells**

| Feature    | Row        | Column   | Cell                           |
| ---------- | ---------- | -------- | ------------------------------ |
| Direction  | Horizontal | Vertical | Intersection of row and column |
| Identifier | Numbers    | Letters  | Letter + Number                |
| Example    | Row 5      | Column C | C5                             |

**Example:**

| A          | B     | C     | D       |
| ---------- | ----- | ----- | ------- |
| Student ID | Name  | Maths | Science |
| 101        | Ravi  | 90    | 85      |
| 102        | Priya | 95    | 92      |

---

##### **Active Cell**





