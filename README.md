# INTERNSHALA LEADS ANALYSIS: CASE STUDY


## I OBJECTIVE

  To analyze a dataset that contains information about how leads are acquired, categorized, and converted, and also
  highlighting trends, patterns, or any other meaningful observations that could help the organization understand
  how leads are generated and how they interact with courses.

## PREREQUISITE

  Imagine you are working for an organization that offers advanced certifications in various courses.

## DATA SOURCE:
  Data is publicly available open-source data. I have downloaded and attached [here](https://github.com/SujalDubey/Internshala_Leads_Analysis-CaseStudy/blob/main/raw_data.csv).
  
## II DATASET OVERVIEW:
  1. Channel_group: Acquisition channel of the lead.
  2. Course: The course of interest to the lead.
  3. lead_id: Unique identifier for each lead.
  4. Lead_type: Type of interaction for lead generation.
  5. lead_date: Date of lead creation.
  6. graduation_year: Year of graduation.
  7. amount_paid: Amount paid by the lead (if applicable).
  8. paid_at: Date of payment (if applicable).


## DATA SUMMARY:
  1. Total Leads: 16,460.
  2. Total Unique Leads: 16,460 (No duplicates in lead_id).
  3. Total Leads Converted: 648 leads have payment information.
  4. Total Channel Groups: 13
  5. Total Courses: 7

https://github.com/user-attachments/assets/dc739988-adff-43c7-9f11-c51fe7faea6c
[Live Dashboard](https://public.tableau.com/app/profile/lunistic/viz/Internshala_data_analysis/Analysis_dashboard?publish=yes):


## III KEY PERFORMANCE INDICATORS(KPIs) & INSIGHTS 
  1. ### Top Channels performance:
     1. A: 7,932 leads
     2. M: 1,647 leads
     3. F: 1,586 leads
     4. D: 1,294 leads
     5. E: 1,080 leads
     
  _Channel A dominates lead generation and conversion (313 successful payments)._

  2. ### Most Popular Courses:
![pie_chart](https://github.com/user-attachments/assets/a2b3121c-f57a-4bda-b900-29158b8f11cb)

     1. Python: 4,323 leads
     2. Java: 4,250 leads
     3. CRM: 2,565 leads
     4. Guitar: 2,164 leads
     5. Google Analytics: 1,358 leads

  4. ### Top Courses Converted:
     1. Java: 181 payments
     2. Python: 132 payments
     3. CRM: 125 payments
     4. Guitar: 99 payments
     5. Google Analytics: 44 payments
  
  _Python and Java are the most popular courses among leads, bringing more than
50% of Total Leads._

  4. ### Payment Trends:
     1. Out of 16,460 leads, only 648 paid, with Java and Python being the most
          purchased courses(313).
     2. Leads generated through interacting with EFG gripped over 50% of the total
          payments.
     3. Only 3.9% of overall leads purchased the courses.
     4. Leads generated through interacting with EFG gripped over 50% of the total
          payments.

  6. ### CONVERSION RATIOS:
![Screenshot (82)](https://github.com/user-attachments/assets/91b0eea4-62f5-4a2b-9b3b-5037f117d883)

      1. Channel B has a conversion rate of over 15% for leads turning into paid leads.
      2. CRM has the highest conversion ratio of 5% w.r.t. Leads acquired.
  
![Screenshot (84)](https://github.com/user-attachments/assets/65178635-41f7-4c23-9ef7-09fcb4f5449d)

  8. A slight peak was observed for 2024 graduates (569 leads).
  9. As per the data, on average, leads purchase the course within 8 to 10 days from the
      'Lead Date'.(Min. 1 day or Max. 28 days)


## RECOMMENDATIONS:
  1. The Python Course should be included in Channel Group J, as it has proven highest lead generation.
  2. Promote Python, Java, and CRM courses, as they show high lead interest and conversion potential.
  3. Prioritize Channel A for both lead generation and conversion.
  4. Customize marketing strategies for 2024 graduates, as they represent a slightly larger share.
  5. Analyze low-performing channels and adjust strategies to optimize them.
  6. If we had dates for when the channel_group was created, we could compare the performances of the groups.

## Conclusion:
  This report demonstrates a data-driven approach to lead analysis, providing actionable insights into acquisition channels, course preferences, and conversion rates. By leveraging these findings, businesses can refine their marketing efforts, optimize lead nurturing,     and improve overall sales performance. The analysis highlights significant patterns in lead acquisition, interest, and conversion. By leveraging these insights, the organization can enhance its marketing efforts, optimize resource allocation, and improve overall lead    conversion rates.

**Disclaimer: This data does not represent the exact values




