- **Getting and loading the data**

The data preparation phase was done using CRISP-DM (Cross-Industry Standard Process for Data Mining) method to Power Query in Power BI to modify and further analyze the data. 

**RETRIEVING THE DATA**

- From the Homepage, click on the “Get data” icon. A list of common data sources will be shown (Figure 1).
- Choose the file format based on the format of your file. In the case of this prototype, the secondary file was saved as “Excel Workbook” format.
- After retrieving the file from its source, the overview of the table is shown (Figure 2). It consists of demographic and academic data of the students. These data will be used to generate the visualization for student retention of the College of Information and Computing Sciences (CICS).

![Figure 1](https://github.com/NinyaJD/SoftwareImpacts/assets/158118047/70335fd3-4eef-4fbf-8ff2-d180b5c1e8c4)

Figure 1. Getting the data in Power BI








![Figure 2](https://github.com/NinyaJD/SoftwareImpacts/assets/158118047/3e831300-f167-4081-8db1-514291df3c08)

Figure 2. Overview of the table in a sheet









**MODIFYING THE DATA**

- If the data requires modification, simply click the “Transform Data” button to update and delete attributes for any entities. Otherwise, click the "Load” button to load the data in Power BI. In the case of this prototype, it is necessary to clean the data as it contains null/error values (shown in Figure 4). Also, the categorical data needs to be transformed into numerical data for the modeling phase in Jupyter environment.
- You will then be directed to Power Query to commence the data cleaning.


<img width="593" alt="Figure 3" src="https://github.com/NinyaJD/SoftwareImpacts/assets/158118047/d92b2ea8-50ee-4ab5-932e-10959657d1b3">

Figure 3. Position of the "Transform Data" button in Power BI


<img width="960" alt="Figure 4" src="https://github.com/NinyaJD/SoftwareImpacts/assets/158118047/2e6a363e-5083-4a5c-bc7d-c38a21afbb1d">

Figure 4. Some error values in the dataset






**LOADING THE DATA**

- Afterwards the data cleaning, click the “Close & Apply” button in the upper left corner of the system (Figure 5).
- The final dataset will then be loaded (shown in Figure 6) that will be used to conduct the exploratory analysis, and visualization of the data.


<img width="504" alt="Figure 5" src="https://github.com/NinyaJD/SoftwareImpacts/assets/158118047/b2ee065a-06af-4d0f-b7d3-f2593ca11e61">

Figure 5. Position of the "Close and Apply" button in Power Query




![Figure 6](https://github.com/NinyaJD/SoftwareImpacts/assets/158118047/fae51317-1290-47bc-82de-97cf2bae83a5)

Figure 6. Loading the data in Power BI





- **Power BI environment**

There are three significant views in the Power BI environment. First is the report view where the student retention dashboard was created. On the right corner in Figure 7 shows the entities that were loaded. Moreover, this side also contains the available graphs and functions that was used to build the visuals of this prototype.




![Figure 7](https://github.com/NinyaJD/SoftwareImpacts/assets/158118047/4a14d6ca-0377-4e7c-a615-5fb1cb93798b)

Figure 7. Report canvas in Power BI




Another is the table view (Figure 8) that displays the data in each entity/file. Furthermore, you can modify the data here such as renaming columns or tables, adding rows or columns, manage the relationship between entities, and changing data types. This was highly used in this prototype as there is a need to ensure the appropriateness of the relationship between entities, to correct the data type of each column, and add additional columns to sort the data for a more summarized information.



![Figure 8](https://github.com/NinyaJD/SoftwareImpacts/assets/158118047/f3da4488-0dfc-474c-9239-7bda7e7f3e47)

Figure 8. Data warehouse in Power BI







Lastly is the model view that illustrates the relationship between entities (shown in Figure 9). You can also easily connect, modify, and manage the relationship between entities in this view. 



![Figure 9](https://github.com/NinyaJD/SoftwareImpacts/assets/158118047/76b9d6b8-6344-4fab-bf71-906c5ee01a90)

Figure 9. Entity Relationship Diagram (ERD) of student's data in Power BI





- **Using the Early Warning System for Student Retention Dashboard**

**FILTER FUNCTION IN THE EWS STUDENT RETENTION PROTOTYPE**

Each page allows the user to filter the information that he/she wants to view. There are 2 ways to do this:

- First is to click a specific category in a graph and it will eventually display the information related to it (like in Figure 10).
- Second is to use the Search function available in each dashboard (for instance in Figure 11).  



![Figure 10](https://github.com/NinyaJD/SoftwareImpacts/assets/158118047/98d6368e-2e80-41a7-984e-27e6f98e2862)

Figure 10. Filtering the data by clicking the graph




![Figure 11](https://github.com/NinyaJD/SoftwareImpacts/assets/158118047/6fa99f5c-33cc-4858-84d4-9cac0a07bdb3)

Figure 11. Filtering the data using the Search function




**MOVING TO OTHER PAGE IN THE EWS STUDENT RETENTION PROTOTYPE**

Power BI does not support single-click when going to another page. Thus, to do this:

- In the navigation pane, CTRL + click the icon or button to move to the selected page. Such as in Figure 12 wherein by using CTRL + click, the user was directed to the “Student Details” page.  



![Figure 12](https://github.com/NinyaJD/SoftwareImpacts/assets/158118047/b2899692-73fc-4dba-bc68-5d2a25ca080a)

Figure 12. Sample of using CTRL + click to move to another page
