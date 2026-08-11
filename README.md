## Power BI LEGO Explorer
 
 ### Project Overview/ Objective:
For an enthusiastic LEGO collector, there are many different sets to choose from. Selecting the right set based on factors such as theme, age range, number of pieces, and price can therefore be challenging.

#### Objective:
Build an interactive LEGO Set Explorer that allows users to quickly search, explore, and narrow down LEGO sets based on their preferred criteria, such as theme, age range, number of pieces, and price.

#### Project Note:
This is an exploratory Power BI project focused on building an interactive tool for LEGO set discovery and filtering. The primary focus is on user experience, interactive exploration, filtering, and data visualization, rather than complex business analysis or advanced DAX.

### Dataset:
•	Dataset source: Lego_sets  Dataset  - MavenAnalytics
•	Number of tables: Single table
•	Number of rows and columns:  18457 rows , 14 columns


### Tools & Technologies:
• Power BI 
• power Query
• DAX

### Data Preparation:
#### Power Query Transformation:
• Removed unnecessary columns that were not required for analysis or visualization.<br>
• Checked and handled missing values and duplicate records.<br>
• Corrected data types where required.<br>
• Created an Age Range field for easier filtering.<br>
• Created Price Range categories for interactive exploration.<br>
• Validated image and web URL fields for displaying LEGO set images and links<br>

#### DAX / Measures:
•	Total Sets – Counts the total number of LEGO sets.<br> 
•	Average Pieces – Calculates the average number of pieces per set.<br>
•	Average Retail Price – Calculates the average US retail price.<br>
•	Selected Set Details – Uses SELECTEDVALUE() to dynamically display the selected set's name, year, pieces, age range, and image.<br>
•	Dynamic Price Filtering – Uses a numeric range parameter and DAX to dynamically filter LEGO sets based on the maximum price selected by the user.<br>

### Dashboard:
The LEGO Set Explorer provides an interactive interface for users to filter and explore LEGO sets based on theme, age range, and price. Users can select a specific set to view its details, including release year, number of pieces, age range, and set image.

#### Key Features:
<b> • Interactive Set Explorer</b> – Browse and explore LEGO sets with detailed set-level information.<br>
<b> • Dynamic Filtering</b> – Filter sets by Theme Group, Theme, Age Range, and Price Range.<br>
<b> • Custom Price Range Selection</b> – Use the numeric range parameter to dynamically filter sets based on retail price.<br>
<b> • Dynamic KPIs</b> – View Total Sets, Average Pieces, and Average Retail Price based on the selected filters.<br> 
<b> • Set-Level Details</b> – Select a set to view its year, piece count, age range, and LEGO image.<br> 
<b> • Price Range Categorization</b> – Easily compare sets across predefined price bands.<br>
<b> • Interactive Navigation</b> – Use Clear Slicers and Explore Sets controls for a smoother exploration experience.<br>

#### Dashboard preview:
##### Screenshots:
![Default mainpage](https://github.com/anagha-more/Power_BI_LEGO_Explorer/blob/main/Deafult%20Main%20page.png)
![image tooltip](https://github.com/anagha-more/Power_BI_LEGO_Explorer/blob/main/Image%20Tooltip%20on%20table.png)
![filter set](https://github.com/anagha-more/Power_BI_LEGO_Explorer/blob/main/Filter%20Set%20using%20theme.png)

#### How to use:
1. Download .pbix file or click on the link provided to view the report.
2. Select a Theme Group, Theme, or Age Range. 
3. Adjust the Price Range slider. 
4. Browse the filtered set list.
5. Hover on the set name in the table to get the view of set.
6. Select a set from the table to view detailed information(release year, number of pieces, age group suitable for etc.)
7. Use "Clear Slicers" to reset the selections.

[Lego Set Explorer - view Dashboard](https://app.powerbi.com/view?r=eyJrIjoiYjM1OTY2M2UtMzI4ZS00YjRkLWFkMzItOWFkYWY0N2JmZjcwIiwidCI6IjE4NWI4MjQ5LTNmYTItNGI1Zi05MzhhLTllNTRiMWEwOWEwNSJ9)

### Learnings:
This project focused primarily on building an interactive and user-friendly Power BI explorer. It provided hands-on experience in designing intuitive report navigation, implementing interactive filters and slicers, using a numeric range parameter for dynamic filtering, and presenting set-level information through an interactive dashboard.

              


