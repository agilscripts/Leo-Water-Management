# Pre-Requisite
1. Install Node-Red on your computer locally. Use this address for more information if needed https://nodered.org/docs/getting-started/local
2. Import the Flows.json file or copy and paste it later.
# Getting Started
1. Run the command node-red in your terminal. This will start the server in your localhost 1880. Navigate to localhost:1880 in your web browser and you will see an empty view.
2. In the menu in the top right, select import. Here you will either import the file of Flows.json or copy the file contents completely and paste them into the input box. This will give you the project skeleton.
3. Next you must install the palettes required, in the top right menu select Manage Palette. Install the following using the install button.
   -@flowfuse/node-red-dashboard
   -node-red-dashboard
   -node-red-node-mysql
   -node-red-node-openweathermap
   -node-red-node-ui-table
   -node-red (should be installed already)
4. Now you should be able to successfully see the application without any data loaded. Navigate to localhost:1880/ui in a new tab.
5. To see the sample data select the blue button on all the left-side blue inject nodes.
-----
# Overview
The UI will show you three columns, one for a person's inventory and water quantity, one for general contaminants and things to monitor, and the last is the daily weather information. 
The user should be able to quickly gain an overview of the daily supply of the different water tanks with both the pie and bar chart, check for any unusual amount of contaminants in the water, and a weather chart to track the temperature and weather status for the day.
There is also an overview for individual customers to view basic information like family size and initial date signed up, as well as how much water allowance they have used and available for the month. There is also a button for them to request feedback.
## Next Steps
The flow and UI are only using sample data and numbers I have entered into the view. Our team was not able to connect it to the database but the palette should be installed with everything needed to inject your data by replacing the blue left-side nodes with mysql nodes.
The layout of the first column should be cleaned up so that the two water charts are not separated by the individual summary. You may also find it more beneficial to change the values listed in the charts or gauges if you find certain information more suited than others. Everything built should be able to be used as a template.
