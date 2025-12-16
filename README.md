# HusqvarnaW435x
Can analysis of an Automower W435x

Tools:SavvyCan
      PCAN-USB:IPEH-002022
      Speed:1 Mbps


Info: just downlaod SavvyCan and Load the Log file to get an better view.

Files:
      
      -mowing.csv is a log file that shows the Automower in its mowing state.
      -test-without-parts-only_mcu_and_motorcontroller.csv is a file that shows the Automower in a state where all sensors are disconnected, leaving only the motor controllers,BMS and the main MCU active.
      -withoutBMS.csv is a measurement in which the BMS is fully disconnected from the Automower and electrically isolated.
      -charging_with6.38A_19.9V.csv is a measurement taken during charging with a current of 6.38 A and a battery voltage of approximately 19.9 V.
      -on-off(timeout).csv contains measurements recorded from startup until the system shuts down into sleep mode due to a timeout.
      -parking.csv records the mower during the parking stage while it is searching for and driving toward the charging station.
      
