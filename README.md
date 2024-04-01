
# Product Line Dashboard

### Dashboard Link : https://app.powerbi.com/links/VecWz3FKtJ?ctid=3f66430c-920e-49dc-9dd6-8223afea3b81&pbi_source=linkShare&bookmarkGuid=de627bc8-6425-48b6-969b-6136983eab0b

## Problem Statement

Here, a product problem statement may be pivotal in streamlining the process and guiding your team in the right direction from start to finish. The product problem statement aims to identify and clarify issues affecting your customers in simple terms. By the time you complete the statement, you should have a tight grasp on the customer experience you plan to deliver, whatever that may be.
So, here we have created a dashboard on a purpose so we can get a idea of each sector total gross & quantity in each sector.

## Chart used 
(a) Card :
          It was used to display values like sum of 'Gross of Income','Quantity','Total'. 

  (b) Slicer :
        It was used for the branch which was bifurcated as'A','B','C'.

  (c) Gauge :
        Used for the 'Sum of Gross Income' with respect to 'First product line'.
  
  (d) Donut Chart :
        Used to display the 'Sum of Rating'by Gender.
  
  (e) Stacked Column Chart :
        It was used to show the'Sum of Tax' by each Product line.

  (f) Pie Chart :
        Used to display the 'Gross Income' & 'Product line'.
  
  (g) Area Map :
        It was used to show the sum of each product line.
  
  (h) Stacked Bar Chart :
        This visual was used to show 'Unit Price' by each product line.

### Steps followed 

- Step 1 : Load data into Power BI Desktop, dataset is a csv file.
- Step 2 : Open power query editor & in view tab under Data preview section, check "column distribution", "column quality" & "column profile" options.
- Step 3 : All data types of column were validated in power query editor.
- Step 4 : All duplicate values were removed from the data.
- Step 5 : All the columns were reordered and arranged firmly.
- Step 6 : Further a dedicated header tab was added in a data as a first row.
- Step 5 : All data types were reviewed and corrected as per the column values.
- Step 5 : After going in view tab in power query editor,clicked on'column quality'&'show whitespaces' for the data quality.
- Step 6 : After editing all the data ,I have clicked 'Close & Apply' and loaded data into report view.
- Step 7 : In the report view, under the view tab, theme was selected. 
- Step 8 : Visual filters (Slicers) were added for three fields named "A", "B" & "C".
- Step 9 : Four card visuals were added to the canvas,representing 'Product category','Sum of Gross Income','Sum of Quantity','Sum of Total'representing Product Line.
           Using visual level filter from the filters pane, basic filtering was used & null values were unselected for consideration into average & sum calculation.
- Step 10 :Some of the values were summarized as sum of whole column including 'cogs','Gross Income','Gross margin percentage','Quantity','Rating','Tax','Total' & 'Unit Price'.

### Snapshot of Card

![Snap_1](https://github.com/Chandan-Sav/Dashboard---Product-line/assets/121309914/1eb0b26a-e102-4ba5-9370-35ecd4d582a4)

 - Step 14 : The report was then published to Power BI Service.
 
 
![Publish_Message](https://github.com/Chandan-Sav/Dashboard---Product-line/assets/121309914/7974c9b9-5a10-46bd-97c2-b6486cca4e5d)

# Snapshot of Dashboard (Power BI Service)

![dashboard_snapo](https://github.com/Chandan-Sav/Dashboard---Product-line/assets/121309914/9c7e11ec-bcf6-4814-a134-0ce9720a1496)

 
 # Report Snapshot (Power BI DESKTOP)

 
![Dashboard_upload](https://github.com/Chandan-Sav/Dashboard---Product-line/assets/121309914/dfc9a278-e72a-42d0-b8f5-3dd456796264)

# Insights

A single page report was created on Power BI Desktop & it was then published to Power BI Service.

Following inferences can be drawn from the dashboard;

 ### [4] Some other insights
 
 ### Unit Price
 
 1.1) 431 Unit by Health & beauty.
 
 1.2) 310 Unit by Sports & Travel.
 
 1.3) 211 Unit by Electronic Accessories.

 1.4) 99 Unit by Home & Lifestyle.

 1.5) 98 Unit by Food & Beverages.

 1.6) 88 Unit by Fashion Accessories. 
         thus, maximum unit price by Product Line is from Health & beauty.
 
 ### Gross Income
 
 2.1)  37.26% Sales belong to 'Health & Beauty'  group.
 
 2.2)  8.3% Sales belong to 'Food & Beverages' group.
 
 2.3)  10.38% Sales belong to 'Home & Lifestyle' group.
 
 2.4)  19.0% employees belong to 'Electronic Accessories' group.

 2.5)  22.55% employees belong to 'Sports & Travel' group.

 
         thus, maximum Sales belong to 'Healthy & beauty' age group.
         
### [Tax 5%]

 3.1) 196 Unit by Health & beauty.
 
 3.2) 202 Unit by Sports & Travel.
 
 3.3) 153 Unit by Electronic Accessories.

 3.4) 103 Unit by Home & Lifestyle.

 3.5) 128 Unit by Food & Beverages.

 3.6) 37 Unit by Fashion Accessories. 
 
         thus, maximum Tax of Product line belong to 'Sports & Travel' group.
         

