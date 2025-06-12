# AUTOMATED-REPORT-GENERATION_TASK2

*COMPANY*: CODTECH IT SOLUTIONS

*NAME*: ATHARVA PARESH CHALKE

*INTERN ID*: CT04DL947

*DOMAIN*:  PYTHON PROGRAMMING

*DURATION*: 4 WEEKS

*MENTOR*: NEELA SANTOSH

*DESCRIPTION*:

# Student Report Card Generator

This Python project automates the creation of student's report cards by transforming grades data from Excel into visual PDF reports.The system processes academic performance data to generate individual student reports complete with grades,average and performance charts also a class-wide summary.In project,I have used several key Python libraries like FPDF handles the PDF generation,providing precise control over every element of the report cards.FPDF allows us to position text,tables and images exactly where we want them to be.We use it to create the structured layout of each report card.The library's cell-based system lets us build clean tables for displaying subject grades while maintaining consistent formatting across all reports.

For data processing and calculations,we use Pandas.This powerful library reads the Excel grade data and converts it into a format we can work with it.It handles all the grade calculations behind the scenes like computing subject averages, validating scores and preparing the data for visualization.Pandas makes it easy to filter out missing or invalid grades while processing only the valid data points.Data visualization is handled by Matplotlib.We use it to create the bar charts that show each student's performance across subjects. Matplotlib gives us control over every chart element.The library's flexibility allows us to maintain consistent formatting across all charts while ensuring they're optimized for PDF output.

The project implements a complete grading system that converts numerical scores (0-100) into standard letter grades (i.e. from A+ till F). This conversion happens in the get_grade method,which includes careful error handling to manage missing or invalid data.The system automatically calculates overall averages for each student while properly weighting all subjects.For output management,we use Python's built-in zipfile library to package all individual reports along with the class summary into a single downloadable ZIP file.This makes distribution easy as teachers can generate and share all reports with just one file download.Error handling is built into every stage of the process.The code gracefully handles missing grades,invalid scores and file operation errors.If a student is missing a grade for one subject,the system will note this in the report without failing.The chart generation similarly checks for valid data before attempting to create visualizations.

The report cards follow a clean, professional design with the school's colors like blue and white as the primary scheme.Each PDF includes proper page numbers in the footer.The layout is optimized for readability, with clear section headers and consistent spacing throughout.Performance charts use color strategically like blue bars for subject scores make the data immediately understandable.The class comparison chart uses a lighter sky blue for easy differentiation while maintaining visual consistency with the individual reports.All charts include value labels so readers don't need to estimate scores from the axes making it easy.

This solution saves teacher's and other staff's significant time during grading periods while providing students and parents with clearer,more visual academic feedback.By automating the most time-consuming parts of report card generation,it allows teachers to focus on instruction while still providing detailed performance insights.The complete system runs efficiently,processing an entire class's worth of reports in seconds.The modular design makes it easy to adapt for different grading systems or report formats. Schools can customize the template by modifying the ReportCardPDF class while keeping all the core functionality intact.


For seeing the output of task2.ipynb u can either download the *GradeReports.ZIP* or you can view each individual reports and summary report I have uploaded in repo

*OUTPUT_FOR_SUMMARY_REPORT:*

![Image](https://github.com/user-attachments/assets/c921fd52-3383-4b6d-be9c-28de4111e555)
