- **Getting and loading the data**

The data preparation phase was done using CRISP-DM (Cross-Industry Standard Process for Data Mining) method to Power Query in Power BI to modify and further analyze the data. 

**RETRIEVING THE DATA**

- From the Homepage, click on the “Get data” icon. A list of common data sources will be shown (Figure 1).
- Choose the file format based on the format of your file. In the case of this prototype, the secondary file was saved as “Excel Workbook” format.
- After retrieving the file from its source, the overview of the table is shown (Figure 2). It consists of demographic and academic data of the students. These data will be used to generate the visualization for student retention of the College of Information and Computing Sciences (CICS).

![Figure 1](https://github.com/NinyaJD/SoftwareImpacts/assets/158118047/70335fd3-4eef-4fbf-8ff2-d180b5c1e8c4)









![](Aspose.Words.b5db2409-3b7e-46da-b120-af1a21996eda.002.png)![](Aspose.Words.b5db2409-3b7e-46da-b120-af1a21996eda.003.png)












![](Aspose.Words.b5db2409-3b7e-46da-b120-af1a21996eda.004.png)

**MODIFYING THE DATA**

- If the data requires modification, simply click the “Transform Data” button to update and delete attributes for any entities. Otherwise, click the "Load” button to load the data in Power BI. In the case of this prototype, it is necessary to clean the data as it contains null/error values (shown in Figure 4). Also, the categorical data needs to be transformed into numerical data for the modeling phase in Jupyter environment.
- You will then be directed to Power Query to commence the data cleaning.



![](Aspose.Words.b5db2409-3b7e-46da-b120-af1a21996eda.005.png)![](Aspose.Words.b5db2409-3b7e-46da-b120-af1a21996eda.006.png)







![](Aspose.Words.b5db2409-3b7e-46da-b120-af1a21996eda.007.png)



![](Aspose.Words.b5db2409-3b7e-46da-b120-af1a21996eda.008.png)![](Aspose.Words.b5db2409-3b7e-46da-b120-af1a21996eda.009.png)





![](Aspose.Words.b5db2409-3b7e-46da-b120-af1a21996eda.010.png)





**LOADING THE DATA**

- Afterwards the data cleaning, click the “Close & Apply” button in the upper left corner of the system (Figure 5).
- The final dataset will then be loaded (shown in Figure 6) that will be used to conduct the exploratory analysis, and visualization of the data.



![](Aspose.Words.b5db2409-3b7e-46da-b120-af1a21996eda.011.png)![](Aspose.Words.b5db2409-3b7e-46da-b120-af1a21996eda.012.png)![](Aspose.Words.b5db2409-3b7e-46da-b120-af1a21996eda.013.png)










![](Aspose.Words.b5db2409-3b7e-46da-b120-af1a21996eda.014.png)![](Aspose.Words.b5db2409-3b7e-46da-b120-af1a21996eda.015.png)





- **Power BI environment**

There are three significant views in the Power BI environment. First is the report view where the student retention dashboard was created. On the right corner in Figure 7 shows the entities that were loaded. Moreover, this side also contains the available graphs and functions that was used to build the visuals of this prototype.



![](Aspose.Words.b5db2409-3b7e-46da-b120-af1a21996eda.016.png)![](Aspose.Words.b5db2409-3b7e-46da-b120-af1a21996eda.017.png)









Another is the table view (Figure 8) that displays the data in each entity/file. Furthermore, you can modify the data here such as renaming columns or tables, adding rows or columns, manage the relationship between entities, and changing data types. This was highly used in this prototype as there is a need to ensure the appropriateness of the relationship between entities, to correct the data type of each column, and add additional columns to sort the data for a more summarized information.



![](Aspose.Words.b5db2409-3b7e-46da-b120-af1a21996eda.018.png)![](Aspose.Words.b5db2409-3b7e-46da-b120-af1a21996eda.019.png) 










Lastly is the model view that illustrates the relationship between entities (shown in Figure 9). You can also easily connect, modify, and manage the relationship between entities in this view. 



![](Aspose.Words.b5db2409-3b7e-46da-b120-af1a21996eda.020.png)![](Aspose.Words.b5db2409-3b7e-46da-b120-af1a21996eda.021.png)















- **Using the Early Warning System for Student Retention Dashboard**

**FILTER FUNCTION IN THE EWS STUDENT RETENTION PROTOTYPE**

Each page allows the user to filter the information that he/she wants to view. There are 2 ways to do this:

- First is to click a specific category in a graph and it will eventually display the information related to it (like in Figure 10).
- ![](Aspose.Words.b5db2409-3b7e-46da-b120-af1a21996eda.022.png)Second is to use the Search function available in each dashboard (for instance in Figure 11).  



![](Aspose.Words.b5db2409-3b7e-46da-b120-af1a21996eda.023.png)







![](Aspose.Words.b5db2409-3b7e-46da-b120-af1a21996eda.024.png)









![](Aspose.Words.b5db2409-3b7e-46da-b120-af1a21996eda.025.png)

**MOVING TO OTHER PAGE IN THE EWS STUDENT RETENTION PROTOTYPE**

Power BI does not support single-click when going to another page. Thus, to do this:

- In the navigation pane, CTRL + click the icon or button to move to the selected page. Such as in Figure 12 wherein by using CTRL + click, the user was directed to the “Student Details” page.  



![](Aspose.Words.b5db2409-3b7e-46da-b120-af1a21996eda.026.png)![](Aspose.Words.b5db2409-3b7e-46da-b120-af1a21996eda.027.png)

