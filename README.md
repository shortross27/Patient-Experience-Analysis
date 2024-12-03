# Patient-Experience-Analysis

## Project Overview
This project demonstrates data analysis and visualization skills using Power BI. It involves exploring patient experience data to uncover actionable insights and trends, focusing on factors that impact patient satisfaction.

## Dataset Details
- **Source:** The dataset was provided as part of a school project to analyze patient experience survey data. It includes anonymized responses collected from patients regarding their satisfaction with various aspects of healthcare services. This project focuses on leveraging Power BI to uncover trends and actionable insights from the data.
- **Description:** Includes variables like demographics, wait times, treatment satisfaction, and survey responses.
- **File Format:** Excel (.xlsx).
- **Preprocessing:** The dataset was cleaned prior to analysis to ensure accuracy.

## Objective
The primary objective of this project is to:

1. Showcase Power BI capabilities, including interactive dashboards and custom visualizations.
2. Conduct a detailed analysis of patient experience to identify trends and improvement areas.

## Dashboard Features
- **Overview Tab:** Key performance indicators (KPIs) summarizing patient satisfaction.
- **Demographic Analysis:** Filters and charts to explore satisfaction by age, gender, or region.
- **Wait Time Impact:** Visualizations showing correlations between wait times and satisfaction scores.
- **Custom Drill-Throughs:** Explore details for specific patient categories or surveys.

## Insights and Analysis
This **bar chart** presents a clear picture of the patient count across different departments within a healthcare setting. We can see that Urgent Care sees the highest number of patients, followed by Primary Care, with Specialist Visits having the lowest patient count. This visualization helps us understand the distribution of patient volume among these departments, which can be crucial for resource allocation, staffing decisions, and overall operational efficiency.

![Patient Count by Department](https://github.com/user-attachments/assets/bbd71ccb-6ff4-4434-a500-b655b0a8c18b)

&nbsp;
&nbsp;

This **line graph** compares two metrics over time: average wait time (left axis, orange line) and average overall satisfaction (right axis, blue line). The inverse relationship between the two is evident, with higher wait times often corresponding to lower satisfaction levels. For example, peaks in the orange line (e.g., around June 10 and June 16) coincide with dips in the blue line, emphasizing the impact of wait time on customer satisfaction. This visualization effectively uses dual y-axes to compare two distinct but related measures, highlighting a key factor (wait time) affecting satisfaction trends.

![Wait and Satisfaction by Date](https://github.com/user-attachments/assets/b287f0bc-365b-47b9-9a11-2f3740a3d2e0)

&nbsp;
&nbsp;

This **pie chart** titled Patient Count by Insurance Type illustrates the distribution of patients based on their insurance coverage. The chart shows that Uninsured patients make up the largest segment at 40% (light blue), followed by Private Insurance at 32% (dark blue), and Public Insurance at 28% (orange).

I chose a pie chart because it effectively demonstrates proportions as parts of a whole, making it easy to visualize the relative size of each category. This visualization highlights a significant insight: a substantial portion of patients lack insurance coverage, which could pose challenges for access to care and financial sustainability. Understanding this distribution helps inform resource allocation and strategies for addressing uninsured patients. This chart simplifies the data for quick comprehension, ensuring the audience can easily grasp the disparities between insurance types.

![Count by Insurance](https://github.com/user-attachments/assets/0ab34f16-49ff-49fd-9254-94c5f5aefc2d)

&nbsp;
&nbsp;

This **scatter plot** titled Patient Overall Satisfaction by Wait Time and Type of Appointment examines the relationship between wait time (x-axis) and overall satisfaction (y-axis) while categorizing data by type of appointment: Primary Care (light blue), Specialist Visit (dark blue), and Urgent Care (orange). A trendline is included to show a slight negative correlation between longer wait times and lower satisfaction levels.

I chose a scatter plot for this visualization because it effectively displays individual data points and highlights variability across appointment types. This format allows us to identify patterns or outliers, such as how satisfaction scores remain relatively high for shorter wait times, regardless of the appointment type. The inclusion of the trendline emphasizes the broader insight that reducing wait times could improve patient satisfaction, providing a foundation for actionable recommendations. The categorized points further help pinpoint which appointment types might experience more significant declines in satisfaction.

![Satisfaction by Wait Time and Appointment](https://github.com/user-attachments/assets/92b8a797-cfa1-4d6e-bade-b53e619b577d)

&nbsp;
&nbsp;

This **bar chart** provides a visual representation of patient satisfaction with provider communication across different appointment types and insurance categories. By comparing the average ratings for each group, we can easily identify trends and disparities. For example, we can see that specialist visits tend to have higher communication ratings compared to primary care and urgent care, regardless of insurance type. Additionally, patients with private insurance generally have higher ratings than those with public insurance or no insurance. By understanding these patterns, healthcare organizations can pinpoint areas where communication can be improved, leading to enhanced patient satisfaction and potentially better health outcomes.

![Comunication Rating by Appointment and Insurance](https://github.com/user-attachments/assets/63ca2be0-e0b7-4afa-a851-b8b5fde59d86)

&nbsp;
&nbsp;

**Average Age by Reason and Insurance Type**
This grouped bar chart visualizes the average age of patients based on the reason for visit (Follow-up, Annual Checkup, New Medical Issue, Prescription Refill) and categorizes data by type of appointment (Primary Care, Specialist Visit, Urgent Care). The chart highlights differences in the average patient age for each type of visit across appointment types.
This chart is essential for understanding age-related patterns in healthcare utilization. For instance, older patients may prioritize annual checkups or follow-up visits, which could guide resource allocation and targeted outreach efforts. Grouped bars facilitate comparison between appointment types and reasons for visits simultaneously.

**Overall Satisfaction vs. Communication by Insurance**
This horizontal bar chart compares provider communication ratings to overall patient satisfaction across three insurance types: Private, Public, and Uninsured.
This chart demonstrates the relationship between communication quality and satisfaction levels, with variations based on insurance type. It emphasizes that uninsured patients tend to have lower satisfaction and communication ratings, which could highlight disparities in care. Horizontal bars make it easier to compare averages across multiple dimensions.

**Number of Appointments by Age and Reason**
This stacked bar chart shows the appointment count for different age ranges and breaks down the data by reason for visit (Annual Checkup, Follow-up, New Medical Issue, Prescription Refill).
This visualization captures how appointment frequency varies by age group and visit purpose, highlighting patterns like increased follow-ups in older patients or new medical issues in younger ones. Stacked bars allow detailed insight into the contribution of each reason within age categories, supporting age-specific healthcare strategies.

![Age and Satisfaction Graphs](https://github.com/user-attachments/assets/0451bfe5-0777-43fa-aa80-07f1c437fee1)

&nbsp;
&nbsp;

This dashboard provides a comprehensive overview of patient satisfaction and wait times within the healthcare organization dataset. We can see that while overall patient satisfaction is relatively high, there is room for improvement in reducing wait times and enhancing provider communication.

The scatter plot in Panel 2 highlights a clear negative correlation between wait time and satisfaction, emphasizing the importance of efficient scheduling and timely appointments. Additionally, the bar chart in Panel 3 reveals slight differences in satisfaction and communication ratings across different insurance types, suggesting potential areas for targeted interventions.

To further investigate these trends, we can interact with the dashboard by clicking on different insurance types to filter the data. This allows us to drill down into specific patient populations and identify potential disparities. For instance, if you wanted to know the statistics for only the patients with a specific type of insurance. Simply click on the specific insurance type in the legend of the bar chart. This will change the values for that specific insurance type throughout the entire dashboard. Same can be done with the type of appointment and even on specific days.

By leveraging this dashboard, we can make data-driven decisions to improve patient experience, optimize resource allocation, and enhance overall operational efficiency.

![Satisfaction and Wait Times Dashboard](https://github.com/user-attachments/assets/b8d2ceaf-f21c-4e21-886a-92a795ba904e)

&nbsp;
&nbsp;

This dashboard provides a comprehensive overview of patient demographics and reasons for visits within our healthcare organization. We can see that the average patient age is 59.20 years, indicating a predominantly older patient population.

The bar chart titled **Average Age by Reason and Insurance Type** shows that specialist visits tend to have older patients compared to urgent care and primary care. Additionally, patients with private insurance are slightly older on average compared to those with public insurance or no insurance.

The pie chart **Count of Patient Age by Insurance Type** reveals that the majority of patients are uninsured (40%), followed by those with public insurance (28%) and private insurance (32%).

The stacked bar chart **Number of Appointments by Age and Reason** provides insights into the distribution of appointments across different age groups and reasons for visits. We can observe that annual checkups and follow-ups are the most common reasons for visits, with a higher concentration in the older age groups.

Clicking on bars, lines, or pie slices can filter the data to show information for the selected category. For example, clicking on a specific insurance type in the pie chart will filter the other visualizations to show data only for that insurance type.

By analyzing these visualizations, we can gain valuable insights into our patient population and identify potential areas for targeted interventions. For example, we might consider offering specialized services for older patients or implementing outreach programs to encourage uninsured individuals to seek care.

![Patient Demographics and Reasons Dashboard](https://github.com/user-attachments/assets/1fc2bef1-8161-4eba-94aa-b9cfb0d4f402)

## Recommendations 
Based on the insights derived from the analysis, the following strategies are recommended to enhance patient satisfaction:

**1. Reduce Wait Times**
   - Implement efficient scheduling systems to minimize delays.
   - Use technology to streamline patient check-ins and appointment management.
   - Optimize staffing to ensure adequate coverage during peak hours.

**2. Improve Provider Communication**
   - Conduct training programs for healthcare providers on effective communication skills.
   - Introduce feedback mechanisms to continuously gather and act on patient concerns.
   - Promote personalized care approaches to build trust and improve patient-provider relationships.

**3. Customize Approaches for Diverse Patient Groups**
   - Create age-specific communication and care strategies tailored to patient needs.
   - Address discrepancies in satisfaction across different insurance types with targeted interventions.
   - Provide cultural competency training to enhance interactions with patients from diverse backgrounds.

## Expected Outcomes
Adopting these recommendations can lead to:
- Higher patient satisfaction scores.
- Improved patient outcomes and healthcare experiences.
- A stronger reputation and increased trust in the healthcare organization.

## How to View
1. Download the .pbix file from this repository.
2. Open the file in Power BI Desktop.
3. Explore the dashboards using the pre-configured slicers and filters.
