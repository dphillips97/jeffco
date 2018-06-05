## Work Sample for Jeffco Open Spaces GIS Analyst

### Deliverables:
1. [**Web Map App**](http://arcg.is/Pb55S0)
2. final_output.xlsx shows park name, then trail difficulty, then trail names
3. table_to_join.xlsx shows the same data in a way that can be imported into GIS software

### Basic Workflow
1. Use spatial join in ArcGIS Desktop 10.5 to find all trails in each park
2. Export resulting table as .csv and open in Jupyter Notebook
3. Clean data: rename columns, remove unlisted trails (trails with no name info)
4. Use pivot tables to summarize all data: show trails by difficulty in each park
5. Export table to Excel and clean data (removed numbered trails in Crown Hill Park, for example)
6. Perform table join in ArcGIS Desktop with original park layer
7. Share map as feature service on ArcGIS Online
8. Customize popups and stylize online
