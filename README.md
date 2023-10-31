# Academia Junior College Document Generation Desktop Application

- This desktop application is built with Python and the tkinter framework.
- It enables junior college teachers to perform the following tasks:
  1. Import student data into a database using SQL.
  2. Select courses for students.
  3. Input and calculate subject marks, totals, percentages, grades, ranks, and grace marks.
  4. Automatically generate multi-page PDF documents, including Consolidated Sheets, Mark Lists, and Student Results.
  5. Create organized PDFs with tables of recorded marks for each student.
  6. Export data as CSV files for yearly student records.

To check it out, follow these steps:
1. cd .\Academia-Junior-College-Doc-Generation-Desktop-Application\
2. pip install -r requirements.txt( python -m pip install Pillow, python -m pip install PyPDF2 , python -m pip install reportlab)
3. Run the `mainSSA` file in PyCharm.(python mainSSA.py)

Important: Please check out the csv formate(bkq.csv) of students data which is supported by this application, in the home page first you import students data then all the GRNo, of studnets will reflect at the time of adding students,course..
   

To create an executable (EXE) file:
1. Install `auto-py-to-exe` or use `pyinstaller`.
