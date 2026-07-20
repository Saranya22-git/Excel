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
    - [**Cell Address**](#cell-address)
    - [**Range**](#range)
    - [**Name Box**](#name-box)
    - [**Formula Bar**](#formula-bar)
  - [**Excel Interface**](#excel-interface)
    - [**Ribbon**](#ribbon)
    - [**Tabs**](#tabs)
    - [**Groups**](#groups)
    - [**Quick Access Toolbar**](#quick-access-toolbar)
    - [**Status Bar**](#status-bar)
    - [**Sheet Tabs**](#sheet-tabs)
    - [**Zoom Controls**](#zoom-controls)
  - [**Working with Worksheets**](#working-with-worksheets)
    - [**Create Workbook**](#create-workbook)
    - [**Save Workbook**](#save-workbook)

### **Excel Fundamentals**

#### **Introduction to Excel**

##### **Excel**

**What is Microsoft Excel?**

*Microsoft Excel is a Spreadsheet software developed by Microsoft. It is used to store, organize, calculate, analyze and visualize data using rows, columns, formulas, functions, charts, and Pivot Tables. It is widely used in businesses for reporting, data analysis, budgeting and dashboard creation.*

---

**Why do we need Excel?**

*Suppose you own a small mobile shop. Everyday you sell phones. On paper, your records look like this:*

| Phone   | Qty |   Price |
| ------- | --: | ------: |
| Samsung |   5 | ₹20,000 |
| iPhone  |   2 | ₹80,000 |

*After 30 days, you'll have hundreds of records.*

*Questions like:*
- *How much did I earn this month?*
- *Which phone sold the most?*
- *Which brand made the most profit?*

*Doing this manually would take hours. Excel solves this problem. It can calculate, organize, and summarize thousands of records in seconds.*

---

**Real-World Example**

**Example-1:** *HR Department*
| Employee |  Salary |
| -------- | ------: |
| Ravi     | ₹30,000 |
| Priya    | ₹45,000 |

*HR uses Excel to:*
- *Store employee details*
- *Calculate salaries*
- *Track attendance*

**Example-2:** *Sales Department*
| Product | Sales |
| ------- | ----: |
| Laptop  |   120 |
| Mouse   |   350 |

*Sales teams use Excel to identify:*
- *Best-selling products*
- *Monthly revenue*
- *Sales trends*

**Example-3:** *Data Analyst*
- *A Data Analyst receives a file with 50,000 customer records.*
- *Before using SQL or Python, they often:*
  - *Remove duplicates*
  - *Fix missing values*
  - *Create Pivot Tables*
  - *Build reports*
- *This is why Excel is still one of the most-used tools in data analysis.*

---

**Example:** *Suppose you own a small shop*

| Product | Quantity | Price |
| ------- | -------- | ----- |
| Pen     | 10       | 5     |
| Book    | 20       | 50    |

*If you want total sales:*
- *Pen sales = 10 * 5 = 50*
- *Book sales = 20 * 50 = 1000*

*Instead of calculating manually, Excel can calculate this automatically using formulas.*

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

##### **Workbook vs Worksheet**

**What is a Workbook?**

- *A workbook is an Excel file that contains one or more worksheets. It is used to store and organized related data in a single file.*
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

- *A Worksheet is a single spreadsheet(sheet) inside a workbook where users enter, edit, organize and analyze data using rows, columns and cells.*

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
- *A Cell is the smallest unit in an excel worksheet where data is entered, edited and stored.*

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

*A Cell can contain*
- *Text(Ravi)*
- *Numbers(6789)*
- *Dates(28-06-2026)*
- *Time(10:30 AM)*
- *Formulas(=A1+B1)*
- *Functions(=SUM(A1:A10))*

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

|   |   A   |    B   |     C     |
|---|-------|--------|-----------|
|1  | Name  |  Age   |  City     |
|2  | Ravi  |  22    | Hyderabad |

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

**What is an Active Cell?**

- *An Active Cell is the currently selected cell in a worksheet where you can enter, edit or delete data.*
- *Only one cell can be active at a time.*

**Example:**
| A     | B   | C         |
| ----- | --- | --------- |
| Name  | Age | City      |
| Ravi  | 22  | Hyderabad |
| Priya | 21  | Chennai   |

*If you click on B2, it becomes the Active Cell.*

---

**How to identify an Active Cell?**

- *An Active Cell has a thick border (outline) around it.*

---

**Characteristics of Active Cell**

*An Active Cell:*

- *Is currently selected*
- *Has a thick border*
- *Can receive data*
- *Can contain text, numbers, dates, formulas or functions*
- *Only one cell is active at a time*

---

**Difference between Cell and Active Cell**

| Cell                        | Active Cell                           |
| --------------------------- | ------------------------------------- |
| Any box in the worksheet    | The currently selected cell           |
| May or may not contain data | Ready for data entry                  |
| Millions of cells exist     | Only one Active Cell exists at a time |

---

**How to move the Active Cell?**

*There are several ways*

**Method-1:** *Mouse*
- *Click any cell*
- *That cell becomes active.*

**Method-2:** *Arrow Keys*
*Use*
- *Up Arrow*
- *Down Arrow*
- *Left Arrow*
- *Right Arrow*

*Each key moves the Active cell by one cell.*

**Method-3:** *Tab Key*
- *Press Tab*
- *The Active Cell moves one column to the right.*

**Method-4:** *Enter Key*
- *Press Enter*
- *The Active Cell moves one row down.*

---

**Keyboard Shortcuts**
| Shortcut      | Action                              |
| ------------- | ----------------------------------- |
| Arrow Keys    | Move one cell                       |
| Tab           | Move right                          |
| Shift + Tab   | Move left                           |
| Enter         | Move down                           |
| Shift + Enter | Move up                             |
| Home          | Move to Column A of the current row |
| Ctrl + Home   | Move to A1                          |
| Ctrl + End    | Move to the last used cell          |

---

**Why is the Active Cell important?**

- **Data Entry:** *When you type Ravi. It goes into the Active Cell.*
- **Formula Entry:** *If C2 is active and you type =A2+B2. The formula is stored is C2*
- **Formatting:** *If you make the Active Cell Bold, only that selected cell(or selected range) is formatted.*
- **Deleting Data:** *Pressing the Delete key clears the contents of the Active Cell.*

---

**Active Cell vs Cell Address**

**Active Cell:** *The cell you are currently working on.*

**Example:** *You clicked B5. So the Active Cell is B5.*

**Cell Address:** *The name of that cell.*

**Example:** *B5 is the cell address.*

*The Active Cell is the selected cell and B5 is the cell address.*

---

**Name Box and Active Cell**

- *Look at the top-left corner of excel. There is a Name Box.*
- *Whenever you select a cell, the Name Box displays its address.*

---

##### **Cell Address**

**What is a Cell Address?**

- *A Cell Address (also called a Cell Reference) is the unique location or identifier of a cell in an Excel worksheet.*
- *It tells excel exactly which cell you want to read from or write to.*
- *A Cell Address is formed by combining Column Letter + Row Number.*

**Example:**

| Cell Address | Meaning                               |
| ------------ | ------------------------------------- |
| A1           | Column A, Row 1                       |
| B5           | Column B, Row 5                       |
| C10          | Column C, Row 10                      |
| H25          | Column H, Row 25                      |
| XFD1048576   | Last cell in a modern Excel worksheet |

---

**Why does excel need cell addresses?**

- *If a teacher says "Give this paper to the student". No one knows which student. But if the teacher says "Give this paper to Roll No. 25". Everyone knows exactly who the teacher means.*
- *Instead of saying "Use that cell". Excel needs something precide like B5 so it knows exactly which cell you mean.*

---

**How Excel uses Cell Addresses?**

*Excel uses cell addresses in:*

- *Formulas*
- *Functions*
- *Charts*
- *Pivot Tables*
- *Conditional Formatting*
- *Data Validation*
- *Lookups*
- *Dashboards*

*Almost every advanced excel feature depends on cell reference.*

**Example:**
| A  | B  |
| -- | -- |
| 10 | 20 |

**Formula:** =A1+B1

*Excel read A1-10 B1-20 Result=30. Notice that we are referring to cell addresses not typing 10+20.*

---

**Why is this better?**

*Suppose A1 changes from 10 to 50. The formula automatically updates =A1+B1 50+20=70. If you had written =10+20. The result would always stay 30. This is why cell reference make excel dynamic.*

---

**Types of References**

*There are 3 types.*

| Type               | Example    |
| ------------------ | ---------- |
| Relative Reference | A1         |
| Absolute Reference | $A$1       |
| Mixed Reference    | A$1 or $A1 |

---

##### **Range**

**What is a Range?**

- *A Range is a group of one or more cells in an Excel worksheet.*
- *It is used to perform operations such as calculations, formatting, sorting, filtering, and applying functions to multiple cells at once.*

---

**Example:** *Imagine you're working as HR*

| Employee | Salary |
| -------- | -----: |
| Ravi     |  40000 |
| Priya    |  50000 |
| Kiran    |  45000 |
| Arun     |  42000 |

*You want the total salary. Instead of selecting each salary one by one, you use the range B2:B5 then =SUM(B2:B5). Excel calculates the total instantly.*

---

**Types of Ranges**

1. **Single Cell Range:** *Only one cell.*

**Example:** *A1*

2. **Continuous (Contiguous) Range:** *Cells are connected.*

**Example:** *A1:A5*

3. **Non-Continuous (Non-Contiguous) Range:** *Cells are not connected.*

**Example:** *A1, C1, E1*

---

**How do we write a Range?**

*Starting Cell : Ending Cell*

**Examples:**

| Range  | Meaning              |
| ------ | -------------------- |
| A1:A10 | Cells from A1 to A10 |
| B2:B8  | Cells from B2 to B8  |
| C3:F8  | Rectangle of cells   |

---

**Where are Ranges used?**

*Ranges are used in SUM, AVERAGE, MAX, MIN, COUNT, Pivot Tables, Charts, Conditional Formatting, Data Validation, Sorting, Filtering.*

---

##### **Name Box**

**What is a Name Box?**

*The Name Box is a feature in Microsoft Excel located to the left of the Formula Bar. It displays the address of the currently active cell and allows users to quickly navigate to a specific cell or range.*

---

**Why do we need the Name Box?**

- *Imagine you have an Excel sheet with 50,000 rows. You need to go directly to cell H35000. Would you scroll all the way down? Very Slow.*
- *Instead type H35000 in the Name Box and press Enter. Excel instantly jumps to that cell.*

---

**Where is the Name Box?**

*It is located above the worksheet to the left of the Formula Bar.*

---

**What does the Name Box do?**

1. **Shows the Actice Cell Address:** *Click cell C2. Name box displays C2.*
2. **Navigate to any cell:** *Type B500 in the Name Box. Press Enter. Excel jumps directly to B500.*
3. **Navigate to a range:** *Type A1:C10 in the Name Box. Press Enter. Excel selects the entire range A1:C10.*
4. **Create Named ranges(advanced):** *Instead of =SUM(B2:B20). You can name the range 'Sales' and use =SUM(Sales).*

---

**Advantages**

*The Name Box helps you:*
- *Navigate quickly*
- *Save Time*
- *Avoid excessive scrolling*
- *Display the Active cell address*
- *Select ranges quickly*

---

##### **Formula Bar**

**What is a Formula Bar?**

*The Formula Bar is located above the worksheet and to the right of the Name Box. It displays the contents of the active cell, including text, numbers, formulas, and allows users to enter or edit them.*

---

**Why do we need the Formula Bar?**

- *Imagine a cell contains **=SUM(B2:B10)**. The worksheet displays only the result 4500.*
- *But how do you know which formula produced 4500?*
- *Click the cell. The Formula Bar shows **=SUM(B2:B10)**. This helps you understand, edit, and correct formulas.*

---

**What does the Formula Bar do?**

1. **Displays Cell Contents:** *Suppose cell A2 contains Ravi. Click A2. Formula Bar shows Ravi.*
2. **Display Formulas:** *Suppose cell D10 contains =SUM(B2:B9). The worksheet may display 35000. But the Formula Bar shows =SUM(B2:B9).*
3. **Edit Data:** *Suppose cell A2 contains Ravi. You want Ravi Kumar. Instead of typing again, Click A2. Edit directly in the Formula Bar.*
4. **Edit Long Formulas:** *Imagine =IF(B2>50000,ROUND(B2*0.10,2),ROUND(B2*0.05,2)). This is difficult to edit inside a small cell. The Formula Bar gives much more space.*

---

**Advantages**

*The Formula Bar helps you:*
- *View formulas*
- *Edit formulas*
- *Edit long text*
- *Reduce mistakes*
- *Understand calculations*

---

#### **Excel Interface**

##### **Ribbon**

**What is the Ribbon?**

*The Ribbon is the main command center of Microsoft Excel. It is located at the top of the Excel window and contains Tabs, Groups, and Commands that help users perform tasks such as formatting, inserting charts, creating formulas, and managing data.*

---

**What does the Ribbon contain?**

*The Ribbon is made up of three levels.*

- *Ribbon*
- *Tabs* 
  -  *Groups*
  -  *Commands*

**Ribbon**

**Home Tab** 
- *Clipboard Group*
  - *Cut*
  - *Copy*
  - *Paste* 
- *Font Group*
  - *Bold*
  - *Italic*
  - *Font Size* 
- *Alignment Group*
  - *Center*
  - *Left*
  - *Right* 

---

**Why is the Ribbon important?**

*The Ribbon helps users:*
- *Access Excel features quickly*
- *Organize commands logically*
- *Improve productivity*
- *Reduce the time spent searching for tools*

*Instead of memorizing hundreds of shortcuts, users can easily find commands on the Ribbon.*

---

**Advantages**

*The Ribbon:*
- *Makes Excel user-friendly*
- *Organizes commands*
- *Speeds up work*
- *Reduces confusion*
- *Improves efficiency*

---

##### **Tabs**

**What are Tabs?**

*Tabs are the main categories available on the Ribbon in Microsoft Excel. Each Tab contains related Groups and Commands that help users perform specific tasks efficiently.*

---

**Default Tabs in Excel**

*The most common Tabs are:*

| Tab             | Purpose                                          |
| --------------- | ------------------------------------------------ |
| **Home**        | Formatting, Clipboard, Font, Alignment           |
| **Insert**      | Tables, Charts, Pictures, Shapes                 |
| **Page Layout** | Themes, Margins, Orientation                     |
| **Formulas**    | Functions, Formula Auditing                      |
| **Data**        | Sort, Filter, Data Validation, Remove Duplicates |
| **Review**      | Spelling, Comments, Protect Sheet                |
| **View**        | Zoom, Freeze Panes, Window Options               |

*Some versions of Excel also include:*
- *Draw*
- *Help*
- *Developer(Optional)*

---

**Purpose of Each Tab**

**Home Tab:** *Most frequently used Tab. Used for:*
- *Copy*
- *Paste*
- *Font Formatting*
- *Alignment*
- *Number Formatting*
- *Cell Styles*

**Example:** *Making headings Bold.*

**Insert Tab:** *Used to insert:*
- *Tables*
- *Charts*
- *Pictures*
- *Shapes*
- *Pivot Tables*

**Example:** *Creating a Pie Chart*

**Page Layout Tab:** *Used for:*
- *Margins*
- *Page Size*
- *Orientation*
- *Print Area*

**Example:** *Preparing a report for printing.*

**Formulas Tab:** *Used for:*
- *Functions*
- *Formula Auditing*
- *Name Manager*

**Example:** *Using SUM(), IF(), AVERAGE()*

**Data Tab:** *Used for:*
- *Sorting*
- *Filtering*
- *Remove Duplicates*
- *Data Validation*
- *Text to Columns*

**Example:** *Sorting employee salaries from highest to lowest.*

**Review Tab:** *Used for:*
- *Spelling Check*
- *Comments*
- *Notes*
- *Protect Sheet*

**Example:** *Protecting a worksheet from accidental edits.*

**View Tab:** *Used for:*
- *Zoom*
- *Freeze Panes*
- *Gridlines*
- *Window Management*

**Example:** *Freezing the first row while scrolling.*

---

**Advantages**

*Tabs help users:*
- *Organize commands*
- *Find tools quickly*
- *Improve productivity*
- *Reduce confusion*
- *Work efficiently*

---

##### **Groups**

**What are Groups?**

*A Group is a section within a Ribbon Tab that contains related commands used to perform similar tasks. Groups help organize commands, making them easier to locate and use.*

---

**Where are groups located?**

*Groups are found inside Tabs.*

```text
Ribbon
│
├── Home Tab
│      │
│      ├── Clipboard Group
│      ├── Font Group
│      ├── Alignment Group
│      ├── Number Group
│      ├── Styles Group
│      ├── Cells Group
│      └── Editing Group
```

*Every Tab contains one or more Groups*

---

**Commom Groups in the Home Tab**

**Clipboard Group:** *Used for:*
- *Cut*
- *Copy*
- *Paste*
- *Format Painter*

**Example:** *Copying employee data from one worksheet to another.*

**Font Group:** *Used for:*
- *Font Style*
- *Font Size*
- *Bold*
- *Italic*
- *Underline*
- *Font Color*
- *Fill Color*

**Example:** *Making report headings bold and increasing the font size.*

**Alignment Group:** *Used for:*
- *Left Align*
- *Right Align*
- *Center Align*
- *Wrap Text*
- *Merge & Center*

**Example:** *Center-aligning a report title.*

**Number Group:** *Used for:*
- *Currency*
- *Percentage*
- *Decimal Places*
- *Date Format*
- *Time Format*

**Example:** *Displaying salaries in currency format.*

**Styles Group:** *Used for:*
- *Cell Styles*
- *Conditional Formatting*
- *Format as Table*

**Example:** *Highlighting top-performing employees.*

**Cells Group:** *Used for:*
- *Insert Cells*
- *Delete Cells*
- *Format Cells*

**Example:** *Adding a new column for employee bonuses.*

**Editing Group:** *Used for:*
- *AutoSum*
- *Fill*
- *Clear*
- *Sort & Filter*
- *Find & Select*

**Example:** *Finding a specific employee quickly.*

---

**Advantages**

*Groups help users:*
- *Organize commands logically*
- *Find tools quickly*
- *Improve productivity*
- *Reduce confusion*
- *Make excel easier to learn*

---

##### **Quick Access Toolbar**

**What is the Quick Access Toolbar?**

*The Quick Access Toolbar is a customizable toolbar located at the top-left corner of the Excel window. It provides quick access to frequently used commands such as Save, Undo, and Redo, regardless of the active Ribbon Tab*

---

**Where is the Quick Access Toolbar located?**

*The Quick Access Toolbar is located:*
- *At the top-left corner of the Excel window.*
- *Above or below the Ribbon (depending on user settings)*

---

**Default commands in the Quick Access Toolbar**

*By default, the Quick Access Toolbar usually contains:*

| Command | Purpose                    |
| ------- | -------------------------- |
| 💾 Save | Saves the workbook         |
| ↩ Undo  | Reverses the last action   |
| ↪ Redo  | Restores the undone action |

---

**Can we customize it?**

*Yes! You can add your favorite commands such as:*
- *Print*
- *New Workbook*
- *Open*
- *Quick Print*
- *Sort*
- *Filter*
- *Spelling Check*
- *Email*

**Example:** *Suppose you use Print many times every day. Instead of opening the File menu every time, you can add Print to the Quick Access Toolbar. This saves time.*

---

**Difference between Ribbon and Quick Access Toolbar**

| Ribbon                         | Quick Access Toolbar                   |
| ------------------------------ | -------------------------------------- |
| Contains all Excel commands    | Contains only frequently used commands |
| Organized into Tabs and Groups | Small customizable toolbar             |
| Changes based on selected Tab  | Always visible                         |
| Large command area             | Small command area                     |

---

**Advantages**

*The Quick Access Toolbar:*
- *Saves Time*
- *Reduces repeated clicks*
- *Improves productivity*
- *Provides quick access to commonly used commands*
- *Can be customized according to user needs*

---

##### **Status Bar**

**What is the Status Bar?**

*The Status Bar is located at the bottom of the Excel window. It displays information about the current worksheet, selected cells, and workbook status. It also provides quick calculations such as Sum, Average, Count, and zoom controls.*

---

**Where is the Status Bar located?**

*The Status Bar is located:*
- *At the bottom of the Excel window*
- *Below the worksheet*

---

**What information does the Status Bar show?**

*The Status Bar can display:*
- *Ready*
- *Enter*
- *Edit*
- *Sum*
- *Average*
- *Count*
- *Numerical Count*
- *Minimum*
- *Maximum*
- *Zoom Percentage*
- *View Shortcuts*

---

**Can we customize the Status Bar?**

*Yes. Right-click on the Status Bar. You can choose to display:*
- *Sum*
- *Average*
- *Count*
- *Maximum*
- *Minimum*
- *Numerical Count*
- *Zoom slider*
- *View shortcuts*

*Only the options you select will appear.*

---

**Advantages**

*The Status Bar:*
- *Saves Time*
- *Shows quick calculations*
- *Displays worksheet status*
- *Provides zoom controls*
- *Improves productivity*

---

##### **Sheet Tabs**

**What are Sheet Tabs?**

*Sheet Tabs are located at the bottom of an Excel workbook. They represent individual worksheets and allow users to navigate, organize, and manage multiple worksheets within a single workbook.*

---

**Where are Sheet Tabs located?**

*Sheet Tabs are located:*
- *At the bottom-left corner of the Excel window.*
- *Just above the Status Bar.*

---

**What can you do with Sheet Tabs?**

*You can:*
- *Switch between worksheets*
- *Add a new worksheet*
- *Rename a worksheet*
- *Delete a worksheet*
- *Move worksheets*
- *Copy worksheets*
- *Change tab color*
- *Hide/Unhide worksheets*

---

**Why are Sheet Tabs important?**

*Sheet Tabs help you:*
- *Organize related data*
- *Separate information logically*
- *Navigate between worksheets quickly*
- *Manage large projects efficiently*

---

**Advantages**

*Sheet Tabs help you:*
- *Organize data*
- *Navigate quickly*
- *Manage related information*
- *Reduce file clutter*
- *Improve productivity*

---

##### **Zoom Controls**

**What are Zoom Controls?**

*Zoom Controls are located at the bottom-right corner of the Excel window on the Status Bar. They allow users to zoom in or zoom out to change the worksheet's viewing size without affecting the actual data or formatting.*

---

**Where are Zoom Controls located?**

*Zoom Controls are located:*
- *At the bottom-right corner of the Excel Window.*
- *On the Status Bar*

---

**What can you do with Zoom Controls?**

**Zoom In:** *Makes everything appear larger on your screen.*

**Example:** *100% -> 150%*

*Useful when:*
- *Reading small text*
- *Presenting data*
- *Editing detailed reports*

**Zoom Out:** *Makes everything appear smaller.*

**Example:** *100% -> 80%*

*Useful when:*
- *Viewing large worksheets*
- *Seeing more rows and columns at once*

**Zoom Percentage:** *Excel shows the current zoom level.*

**Example:** *50%, 75%, 100%, 125%, 150%, 200%*

*100% is the default zoom level in most Excel workbooks.*

---

**Does Zoom affect the actual data?**

- *No. Zoom Controls only change how the worksheet appears on your screen.*
- *They do not change:*
  - *Font Size*
  - *Cell Size*
  - *Data*
  - *Formatting*
  - *Print output*

---

**Advantages**

*Zoom Controls help you:*
- *Read small text easily*
- *View large worksheets*
- *Present reports clearly*
- *Improve user comfort*
- *Switch between detailed and overview views quickly*

---

#### **Working with Worksheets**

##### **Create Workbook**

*Creating a Workbook means creating a new Microsoft Excel file that contain one or more worksheets for storing, organizing, and analyzing data.*

---

**How to Create a Workbook?**

**Method-1:** *Open Excel*

1. *Open Microsoft Excel*
2. *Click Blank Workbook*
3. *A new workbook is created.*

**Method-2:** *Keyboard Shortcut*

- *In Excel press **Ctrl + N*** 
- *A new workbook opens instantly.*

**Method-3:** *From File Menu*

1. *Click File*
2. *Click New*
3. *Select Blank Workbook*

---

##### **Save Workbook**

*Saving a Workbook is the process of storing an Excel file with its data, formulas, formatting, and worksheets in a chosen location for future use.*

---

**How to Save a Workbook?**

**Method-1:** *Keyboard Shortcut*

- *Press Ctrl + S*
- *If the workbook has never been saved before:*
  - *A **Save As** window opens.*
  - *Choose a location*
  - *Enter a file name*
  - *Click Save* 
- *If the workbook is already saved:*
  - *Pressing Ctrl + S simply updates the existing file.*

---

**Method-2:** *Save Button*

*Click the Save (💾) icon on the Quick Access Toolbar.*

**Method-3:** *File Menu*

1. *Click File*
2. *Click Save*
3. *Choose a location (only the first time)*
4. *Enter the file name*
5. *Click Save*

---

**Difference Between Save vs Save As**

| Save                      | Save As                                 |
| ------------------------- | --------------------------------------- |
| Updates the existing file | Creates a new copy of the file          |
| Keeps the same file name  | Allows a new file name                  |
| Keeps the same location   | Can choose a different location         |
| Shortcut: **Ctrl + S**    | Shortcut: **F12** *(or File → Save As)* |

---









