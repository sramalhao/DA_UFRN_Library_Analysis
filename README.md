# 📊 UFRN Library Loan Analysis (2010–2020)

This project presents a structured analysis of library loan data from the Federal University of Rio Grande do Norte (UFRN) between 2010 and 2020, with a forecast for 2022. The goal is to uncover user behavior, trends, and course-specific insights to support strategic decisions in academic services and resource allocation.

---
## 🔄 Analysis Workflow
## Data Import
- Loan data was imported semester-wise and concatenated into a single dataset (library_loans).
- Duplicates were removed using unique identifiers.
- Additional book-related metadata was merged into the dataset.

### Data Cleaning & Categorization
- Irrelevant columns were dropped.
- A UDC (Universal Decimal Classification) category was derived from the localizacao field.

## 3. Overall Loan Analysis
- Calculated total loans and books borrowed.
- Grouped loans by year, month, and hour to identify temporal patterns.
- Created line and bar plots to visualize trends.

### User Type Analysis
- Generated a frequency table for tipo_vinculo_usuario.
- Visualized loan distribution across user types using bar plots.

### Collection, Library & UDC Analysis
- Created frequency tables for collections, libraries, and UDC categories.
- Identified the most borrowed collections and most frequented libraries.
  
### Graduate Student Analysis
- Filtered graduate student loans.
- Analyzed trends by year and month using boxplots.

### Postgraduate Student Analysis
- Similar filtering and trend analysis as with graduate students.
- Visualized monthly and yearly loan behavior using boxplots.

### Student Enrollment Data
- Imported and merged enrollment data (pre- and post-2010).
- Extracted and combined registration data from JSON files.

### Loans by Selected Courses
- Focused on loans from specific undergraduate courses.
- Aggregated and compared data using a pivot table by year and course.

### Postgraduate Loans (After 2017)
- Filtered loans from postgraduate students after 2017.
- Merged with registration data and created a pivot table.

### 2022 Forecast
- Imported forecast data and appended it to the postgraduate pivot table.
- Reordered table to include forecasted values for comparison.

### Percentage Change Analysis
- Calculated year-over-year percentage differences in postgraduate loans.
- Visualized results with a bar chart by course and year.

### Summary & Insights
Generated a final report summarizing key findings.

## 📌 Conclusion
This analysis revealed several meaningful insights into library usage at UFRN. Between 2010 and 2020, over 2 million loans were recorded, with a marked decline in 2020 likely due to the COVID-19 pandemic. Borrowing behavior displayed clear seasonal and hourly patterns, and undergraduate students accounted for the majority of usage, while postgraduate students demonstrated more distributed and diverse borrowing habits. The "Acervo Circulante" collection alone made up over 99% of all loans, and the Biblioteca Central Zila Mamede emerged as the most frequented library, responsible for nearly 69% of all transactions. When analyzing by academic level, graduate students exhibited consistent use of specific collections, whereas postgraduate students showed strong borrowing activity in courses like Dental Sciences and Science, Technology and Innovation. Course-specific analysis revealed varying trends over time, with some undergraduate and postgraduate programs maintaining high engagement levels. A forecast for 2022 suggests partial recovery in loan activity, although it remains below pre-pandemic levels. These findings highlight the pandemic’s significant impact on library use, while also pointing to key areas—such as specific collections, user types, and courses—that warrant targeted academic support and resource planning.

## ✅ Recommendations
- Resource Allocation: Focus on high-demand collections and libraries to optimize resource usage.
- Support Strategies: Tailor academic support for courses with high borrowing rates.
- Pandemic Recovery: Implement strategies to encourage library usage post-pandemic.
- This analysis provides actionable insights to enhance library services and better meet user needs.
