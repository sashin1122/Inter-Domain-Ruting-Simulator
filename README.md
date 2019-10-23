
![Test Image 4](https://github.com/tograh/testrepository/3DTest.png)



Overview

This program was designed as a simple ruting simulator that enables users to build a network configuration (iether through the user interface or through a .csv file with speciefied formats, see network.csv for example). After a network is configured the user can then perform routing simulations from one node to another. The program will calculate shortest paths using dijikstras algorythm and will produce calculated performance data aswell as light up the path when requested. Use the "Animate" button to stabalize or fix the anamation at any point in the programs use. The program has a localy built database for storing in app data so performance data and network topology can be recovered if app is accidentally closed. 







Network.csv is an input test file that can be used to configure a network for simulation perposes.

The program can be launched by opening the src file and running the PrototypeLayout file in a browser.

please refere to user manual for more information:

User Manual
Open the web application. The simulation configurations are displayed on the left and on the right will be a blank screen where the network will be displayed. 
Select the instructions button to view the instructions. Select the instructions button to close the instructions (optional). 
Select the “Choose File” button to select an input .csv file. The corresponding network will be displayed on the right. 
Select the “Animate” button to change the layout. Select the “Animate” button again to pause the display - this will allow you to interact with the graph and move the nodes. Select the “Animate” button again to restore the previous layout.
The network can be edited by adding or deleting nodes.
To add a node, select the “Add a node” button. Complete the form and click the “Add” button. The node will now be displayed on the network.
To delete a node, select the “Delete a node” button. Select the node from the dropdown box and click the “Delete” button. The graph will revert to its initial state. Select the “Animate” button to change the view. The footprint of node will remain on the display but it will be severed from the rest of the graph and all its corresponding links will be removed.
After configuring your desired network it is time to configure a routing simulation. Select a start and end node - if not selected, the default for both categories is the first node in the input .csv file. Select a routing algorithm - Djikstra or Bellman Ford. Select packet size. Select the “Submit” button to run the simulation. The shortest path on the graph will light up and the program will generate performance data.
The performance data will be displayed below the heading “performance data”. Performance data can be downloaded by selecting the “Download Performance Data” button.
Additionally the network topology may also be downloaded by selecting the “Download Network Topology Data” button.
If connection is lost or the browser is refreshed, the previous sessions’ network can be reloaded and the previous sessions’ performance data and network topology data will be available for download by selecting the “Download Performance Data” button or the “Download Network Topology Data” button.
Additional Information is provided at the bottom of the network configuration bar for the user’s convenience.
