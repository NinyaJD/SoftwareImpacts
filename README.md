- **Getting and loading the data**

The data preparation phase was done using CRISP-DM (Cross-Industry Standard Process for Data Mining) method to Power Query in Power BI to modify and further analyze the data.

**RETRIEVING THE DATA**

  - From the Homepage, click on the "Get data" icon. A list of common data sources will be shown (Figure 1).
  - Choose the file format based on the format of your file. In the case of this prototype, the secondary file was saved as "Excel Workbook" format.
  - After retrieving the file from its source, the overview of the table is shown (Figure 2). It consists of demographic and academic data of the students. These data will be used to generate the visualization for student retention of the College of Information and Computing Sciences (CICS).

![](RackMultipart20240213-1-edvx5a_html_b8f7cbff928ca82.png)

Figure 1. Getting the data in Power BI

 ![](RackMultipart20240213-1-edvx5a_html_7c2d2298eddc9c7e.png)

Figure 2. Overview of the table in a sheet

**MODIFYING THE DATA**

  - If the data requires modification, simply click the "Transform Data" button to update and delete attributes for any entities. Otherwise, click the "Load" button to load the data in Power BI. In the case of this prototype, it is necessary to clean the data as it contains null/error values (shown in Figure 4). Also, the categorical data needs to be transformed into numerical data for the modeling phase in Jupyter environment.
  - You will then be directed to Power Query to commence the data cleaning.

![](RackMultipart20240213-1-edvx5a_html_7181dddb8a6e7f6b.png)

Figure 3. Position of the "Transform Data" button in Power BI

![Shape1](RackMultipart20240213-1-edvx5a_html_81a73fad224f61ab.gif)

![](RackMultipart20240213-1-edvx5a_html_29702be3bd909d03.png)

Figure 4. Some error values in the dataset

![Shape2](RackMultipart20240213-1-edvx5a_html_10efc670ee503ed0.gif)

**LOADING THE DATA**

  - Afterwards the data cleaning, click the "Close & Apply" button in the upper left corner of the system (Figure 5).
  - The final dataset will then be loaded (shown in Figure 6) that will be used to conduct the exploratory analysis, and visualization of the data.

Figure 5. Position of the "Close and Apply" button in Power Query

 ![](RackMultipart20240213-1-edvx5a_html_fa41f8a01819e89f.png) ![Shape3](RackMultipart20240213-1-edvx5a_html_9dcf850ac57a6c75.gif)

Figure 6. Loading the data in Power BI

 ![](RackMultipart20240213-1-edvx5a_html_8b2dffb58e42ae39.png)

- **Power BI environment**

There are three significant views in the Power BI environment. First is the report view where the student retention dashboard was created. On the right corner in Figure 7 shows the entities that were loaded. Moreover, this side also contains the available graphs and functions that was used to build the visuals of this prototype.

Figure 7. Report canvas in Power BI

 ![](RackMultipart20240213-1-edvx5a_html_39c8f37105f22bc9.png)

Another is the table view (Figure 8) that displays the data in each entity/file. Furthermore, you can modify the data here such as renaming columns or tables, adding rows or columns, manage the relationship between entities, and changing data types. This was highly used in this prototype as there is a need to ensure the appropriateness of the relationship between entities, to correct the data type of each column, and add additional columns to sort the data for a more summarized information.

Figure 8. Data warehouse in Power BI

 ![](RackMultipart20240213-1-edvx5a_html_e74d4bde1c6a932e.png)

Lastly is the model view that illustrates the relationship between entities (shown in Figure 9). You can also easily connect, modify, and manage the relationship between entities in this view.

Figure 9. Entity Relationship Diagram (ERD) of student's data in Power BI

 ![](RackMultipart20240213-1-edvx5a_html_daf8202f76977929.png)

- **Using the Early Warning System for Student Retention Dashboard**

**FILTER FUNCTION IN THE EWS STUDENT RETENTION PROTOTYPE**

Each page allows the user to filter the information that he/she wants to view. There are 2 ways to do this:

  - First is to click a specific category in a graph and it will eventually display the information related to it (like in Figure 10).
  - ![](RackMultipart20240213-1-edvx5a_html_f602e9aa9648d8b4.png)Second is to use the Search function available in each dashboard (for instance in Figure 11).

Figure 10. Filtering the data by clicking the graph

![](RackMultipart20240213-1-edvx5a_html_41633be3023d6c58.png)

Figure 11. Filtering the data using the Search function

**MOVING TO OTHER PAGE IN THE EWS STUDENT RETENTION PROTOTYPE**

Power BI does not support single-click when going to another page. Thus, to do this:

  - In the navigation pane, CTRL + click the icon or button to move to the selected page. Such as in Figure 12 wherein by using CTRL + click, the user was directed to the "Student Details" page.

![](RackMultipart20240213-1-edvx5a_html_1b157f6b0efd25ce.png)

Figure 12. Sample of using CTRL + click to move to another page
