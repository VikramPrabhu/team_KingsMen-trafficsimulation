# Team_KingsMen-TRAFFIC SIMULATOR

## Installation of NetLogo

Step I: Download NetLogo from  http://ccl.northwestern.edu/netlogo/5.3.1/ 

Step II: Select the OS on which you want to run this simulator 

Step III: Once the software has been downloaded, Install the application on your system by following the instructions


## Creating required options in GUI

I. Before running the simulation, User has to create the following on the 'Interface' Tab from the drop-down list.

        1. number-of-ticks (slider)
        2. Traffic-Lights-timer? (slider)
        3. setup (button)
        4. go (forever-button)
        5. Emergency-Vehicles (button)
        6. go-emergency (button)
        7. number-of-cars (slider) 
        8. snow (switch)
        9. create-snow (button)
        10. for-snow (forever-button)
        
II. The minimum value for the "Traffic-Lights-timer?" is 20

III. Maximum density of vehicles on each lane should be 30%

## Process of creating buttons and sliders

  1. Go to 'Interface'
  2. Click on the drop-down list (normally seen next to the 'Add' symbol.
  3. Select the desired option from the list and click anywhere outside the NetLogo world (black screen) to set parameters for the         chosen option.
  4. If the chosen button has to run repeatedly, ensure that the 'Forever' checkbox is ticked while assigning a name to that button.

## Using NetLogo to run the Simulation

  1. After creating all the controls on the Interface Tab as mentioned above, click on the 'setup' button.
  2. A dialog box will open asking to create a file and store it at a user-desired location.
  3. Only files with .txt extensions should be created. (Note: It is mandatory to create this file to start the simulation)
  4. After creating the file cars, lanes, traffic lights and pedestrians are created.
  5. Click the 'go' button to run the simulation and generate a report.
  6. Emergency Vehicles can be added to the simulation by clicking on the 'Emergency-Vehicle' button.
  7. Click on 'go-emergency' button to move the emergency vehicle.
  8. The emergency vehicles should be run only with the other vehicles and not alone.
  9. Simulation will run exactly for the number of ticks given as an input at 'number-of-ticks' slider by the user.
  10. Click on 'create-snow' button to change the weather into a snowy weather.
  11. To change weather from snowy to normal, turn the snow switch off.
  12. The 'for-snow' button gives a snowfall effect as and when the simulation is running. 
  13. Once the simulation is completed, an end report would be genrated to the .txt file created at the start of the simulation.
