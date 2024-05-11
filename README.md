# DATA VISUALIZATION 
Data visualization is the representation of data through the use of common graphics, such as charts, plots, infographics, and even animations. These visual displays of information communicate complex data relationships and data-driven insights in a way that is easy to understand.
Matplotlib and Seaborn are Python libraries that are used for data visualization. They have built-in modules for plotting different graphs. While Matplotlib is used to embed graphs into applications, Seaborn is primarily used for statistical graphs.

## Basic Visualization
1. Bar Chart Vertical
   Compare among categories, few categories. Can be used over time
2. Bar Chart Horizontal
   Has a long item label. Compare among categories. Used for many categories
3. Line Chart
   Compare over time, one category
4. Stacked Bar Chart
   Show components in a category, that can be used over time(a few periods). Relative and absolute differences matter.
5. Stacked 100% Bar Chart
   Show components in a category. Composition in percentage, focus contribution on each component. Can be used over time (a few periods) and only relative differences matter.
6. Pie Chart
   Static Composition, Useful for less than 5 categories. A simple share of the total
7. TreeMap
   Static Composition, accumulation to total. Absolute difference matters

## Data Visualization Using Python
Python offers several plotting libraries namely Matplotlib and Seaborn for data visualization.
- Matplotlib
1. It used for basic graph plotting
2. It mainly works with dataset and array
3. Matplotlib acts productively with data arrays and frame
4. Matplotlib is more customizable and pairs well with Pandas and Numpy
     
- Seaborn
1. It mainly used for statistics and complex visualization
2. It works with the entire dataset
3. More organized and functional than Matplotlib, the dataset as a solitary unit
4. Seaborn has more themes and statistical analysis.

### Import matplotlib and seaborn
<div align="center"><img src="https://github.com/alresadeva/Data_Analytics_Data_Visualization/assets/166176480/d629bb01-1558-4697-b05e-379283879f14" /></div> 
                                                
### Creating variables
Creating two variables to display a chart
<div align="center"><img src="https://github.com/alresadeva/Data_Analytics_Data_Visualization/assets/166176480/70649220-c7b1-40cd-a410-71eeef11ac6e" /></div>
 
Displaying a chart from the previously created variables                                     
<div align="center"><img src="https://github.com/alresadeva/Data_Analytics_Data_Visualization/assets/166176480/723103ef-d39b-44f7-8de4-f7a027274844" /></div>
<div align="center"><img src="https://github.com/alresadeva/Data_Analytics_Data_Visualization/assets/166176480/eb29978e-511d-435b-b76e-7e5c8ba02955" /></div>                
 
### Creating labels
Adding one variable for the Y-axis, still with the same category, which is fruits
<div align="center"><img src="https://github.com/alresadeva/Data_Analytics_Data_Visualization/assets/166176480/570dd179-c7e4-4b17-a6de-525e098ce3b2" /></div>
 
Displaying a chart for the quantity of harvested grapes and kiwis in the specified year. Then, adding title labels to the X and Y axes.
<div align="center"><img src="https://github.com/alresadeva/Data_Analytics_Data_Visualization/assets/166176480/56c4cb94-1f16-408a-9d0d-276873e76384" /></div>
<div align="center"><img src="https://github.com/alresadeva/Data_Analytics_Data_Visualization/assets/166176480/482a6692-83be-4a97-8058-85f803d2cde8" /></div>
 
### Creating tittle and legend
Adding a title to the graph and a legend to indicate the graph based on color (Blue for grapes and Orange for kiwi)
<div align="center"><img src="https://github.com/alresadeva/Data_Analytics_Data_Visualization/assets/166176480/272d18ec-b32d-4ca8-a349-e29c67a8a2ce" /></div>
<div align="center"><img src="https://github.com/alresadeva/Data_Analytics_Data_Visualization/assets/166176480/e0b23da9-c95c-4875-b562-4cdc1e75dce9" /></div>
 
### Creating grid
An easy way to make your charts look beautiful is to use some default styles from the Seaborn library. These can be applied globally using the sns.set_style function.

Creating a visualization plot with a white background and grid.

- Whitegrid
<div align="center"><img src="https://github.com/alresadeva/Data_Analytics_Data_Visualization/assets/166176480/0838b8ae-d1aa-479f-b8d4-9eb0e007f643" /></div>
<div align="center"><img src="https://github.com/alresadeva/Data_Analytics_Data_Visualization/assets/166176480/61e33829-1ba7-4da2-b2af-a89f7f8bd6ea" /></div>
 
The syntax above is used to create a graph showing the yields of grapes and kiwi over the years. It sets the X-axis label as 'Year', the Y-axis label as 'Yield (tons per hectare)', and the title of the graph as 'Crop Yields in Kanto'. A legend is added to distinguish between the lines representing grapes and kiwi, with 'grapes' represented by circles (marker='o') and 'kiwi' represented by crosses (marker='x')

- Darkgrid
Creating a visualization plot with a dark background and grid.
<div align="center"><img src="https://github.com/alresadeva/Data_Analytics_Data_Visualization/assets/166176480/c59a4f0e-96c0-4208-8846-b67ed5c1bdb5" /></div>
<div align="center"><img src="https://github.com/alresadeva/Data_Analytics_Data_Visualization/assets/166176480/2d2a7779-1681-4f68-a432-9c773d68cd22" /></div>
 
### Creating a Bar Chart
Creating a bar chart showing the grape yields from year to year in Bandung
<div align="center"><img src="https://github.com/alresadeva/Data_Analytics_Data_Visualization/assets/166176480/5c14c98e-d5a3-4a42-85fd-841267988dac" /></div>
<div align="center"><img src="https://github.com/alresadeva/Data_Analytics_Data_Visualization/assets/166176480/82707e3d-1a26-4124-abbb-376c434f93d9" /></div>
 
### Creating a Stacked Bar Chart
Creating a stacked bar chart showing the grape and kiwi yields from year to year in Bandung. Grapes are represented by the first bar chart, while kiwi is represented by the second bar chart. The argument bottom=grapes sets the kiwi bar chart to start from the grape yields, thereby showing the comparison between the two yields for each year.
<div align="center"><img src="https://github.com/alresadeva/Data_Analytics_Data_Visualization/assets/166176480/b748bc95-41f0-44d0-b266-fe19bc5c0fb4" /></div>
<div align="center"><img src="https://github.com/alresadeva/Data_Analytics_Data_Visualization/assets/166176480/b3badaf7-ae59-4e60-8641-eaa230635cb5" /></div>
 
## Data Visualization From Seaborn Library
The Seaborn library is a Python package that focuses on statistical data visualization. It serves as a high-level interface built on top of Matplotlib, providing a simpler and more efficient interface for creating appealing and informative statistical graphics

### Creating Bar Chart
### Import dataset 'glue' from Seaborn
<div align="center"><img src="https://github.com/alresadeva/Data_Analytics_Data_Visualization/assets/166176480/456304c9-c7bb-444b-a61f-ee41388b9637" /></div>
<div align="center"><img src="https://github.com/alresadeva/Data_Analytics_Data_Visualization/assets/166176480/91f82b4b-f6bb-4835-8ee7-04cf98ed81d6" /></div>

### Creating a bar plot
Creating a bar plot to represent the 'Model' column against the 'Score' column in the 'glue' dataset
<div align="center"><img src="https://github.com/alresadeva/Data_Analytics_Data_Visualization/assets/166176480/412839ee-16b0-472e-9920-199b2b0dde75" /></div>
<div align="center"><img src="https://github.com/alresadeva/Data_Analytics_Data_Visualization/assets/166176480/d91b299f-b5d4-40e2-9466-c0637dbef166" /></div>
  
Creating a bar plot by dividing it based on the values in the 'Year' column, thus displaying different colors for each year

### Creating a bar chart vertical (pivot)
<div align="center"><img src="https://github.com/alresadeva/Data_Analytics_Data_Visualization/assets/166176480/aef70c85-7905-4781-af75-9dce91caacad" /></div>
<div align="center"><img src="https://github.com/alresadeva/Data_Analytics_Data_Visualization/assets/166176480/05a369b9-cd0c-4291-9a2d-668f9989b060" /></div>
   
### Creating a bar chart horizontal (pivot)
<div align="center"><img src="https://github.com/alresadeva/Data_Analytics_Data_Visualization/assets/166176480/46d1b0ed-1c6e-4d92-87da-da03cee61354" /></div>
<div align="center"><img src="https://github.com/alresadeva/Data_Analytics_Data_Visualization/assets/166176480/d887ff40-2c96-4bfa-8cb1-1bce4a29581a" /></div>
 
## Creating Histogram
### Import dataset 'flights' from Seaborn
<div align="center"><img src="https://github.com/alresadeva/Data_Analytics_Data_Visualization/assets/166176480/b443e82b-13dd-44d6-bce3-8fa995c8e36f" /></div>
<div align="center"><img src="https://github.com/alresadeva/Data_Analytics_Data_Visualization/assets/166176480/111151a3-8e5f-4b7e-b3f8-3cb7a75eaf5c" /></div>
<div align="center"><img src="https://github.com/alresadeva/Data_Analytics_Data_Visualization/assets/166176480/ad924c15-7a5a-4d6e-8994-8c4ad2936dd4" /></div>
 
### Creating histogram distribution With "Bins=7"
Create a histogram displaying the distribution of the number of passengers on flights, where the histogram result uses the number of passengers as input data and the argument bins=7 is used to determine the number of bins or data groups used in the histogram
<div align="center"><img src="https://github.com/alresadeva/Data_Analytics_Data_Visualization/assets/166176480/52e2ffce-7ad5-4495-bc59-5caeb5782f5e" /></div>
<div align="center"><img src="https://github.com/alresadeva/Data_Analytics_Data_Visualization/assets/166176480/05b5dcbe-0576-45bf-bc78-ae728600aa0f" /></div>
 
  
### Creating histogram distribution With "Bins=100, 500, 10"
Displaying a histogram of the distribution of the number of passengers on flights using the argument bins=np.arange(100,599,10), which is used to explicitly determine the bin boundaries, starting from 100 up to 500 with an interval of 10.
<div align="center"><img src="https://github.com/alresadeva/Data_Analytics_Data_Visualization/assets/166176480/c7a13414-8a43-4d64-a4ca-5a3aeb523940" /></div>
<div align="center"><img src="https://github.com/alresadeva/Data_Analytics_Data_Visualization/assets/166176480/16118025-cc42-44a2-a75f-cde61ddfcd31" /></div>
 
## Crisp DM
The Cross-Industry Standard Process for Data Mining, or CRISP-DM, is one of the data mining process models.
1. Business Understanding – What does the business need?
2. Data Understanding – What data do we have/need? Is it clean?
3. Data preparation – How do we organize the data for modeling?
4. Modeling – What modeling techniques should we apply?
5. Evaluation – Which model best meets the business objectives?
6. Deployment – How do stakeholders access the results?
