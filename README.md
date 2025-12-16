# FOP_Assignment_Store_Operations_Management_System
This is a team project for FOP assignment that the title is Store Operations Management System
File Structure for OOP
Suggested by gemini, can add or remove based on your peference
src/
├── Main.java (The only shared file - keep it minimal!)
│              
│
├── model/                    (Data Objects - Agree on these FIRST)
│   ├── Employee.java         (sx)
│   ├── Product.java          (yy)
│   ├── SaleRecord.java       (yy)
│   └── AttendanceLog.java    (sx)
│
├── data/                     (File Handling - Reading/Writing CSVs)
│   └── DataStorage.java      (jk - handles all CSV reading/writing) [cite: 10]
│
├── service/                  (The "Brain" - Where you write your Logic)
│   ├── AuthService.java      (sx - Login, Register logic) [cite: 26]
│   ├── AttendanceService.java(sx - Clock in/out logic) [cite: 47]
│   ├── StockService.java     (yy - Morning count, Stock In/Out) [cite: 67]
│   ├── SalesService.java     (yy - Recording sales) [cite: 118]
│   ├── SearchService.java    (sx - Search algorithms) [cite: 144]
│   ├── EditService.java      (jk - Editing records) 
│   └── ReportService.java    (yc - Analytics, Filtering, Sorting) [cite: 227, 233]
│
├── utils/                    (Extra Tools)
│   ├── EmailSender.java      (yc - Auto Email) 
│   └── PerformanceMetric.java(yc - Employee performance) [cite: 239]
│
└── gui/                      (Graphical User Interface)
│   └── AppInterface.java     (xj - The JavaFX/Swing Interface)
├── employees.csv             <-- PUT HERE (sx, check [cite: 22])
├── models.csv                <-- PUT HERE (yy needs this for Stock)
└── outlets.csv               <-- PUT HERE (jk needs this for transfers)
