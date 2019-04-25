# App to Control and receive data from the FPGA
This is a Matlab app which allows control and access to the FPGA as part of the DOA receiver system. It's main functions are to visualise and export data.

## Prerequisites
 - Matlab 2018b (Untested in other versions)
 - Instrument control toolbox (Only for instrreset function)
 
## How to use
 1. Select the serial port and click "Connect"
 2. Navigate the the "Raw Data Viewer" tab
 3. Type the number of samples you require and click "Get Data"
 4. Follow the instructions in the popup, currently this is to press the "Sample" button the FPGA Board
 5. The data will then be plotted and it is possible to navigate around using the buttons in the top right
 6. If you have any problems restart the GUI 

## Theory of operation

 - 115200 Serial interface to FPGA
 - Sample number is set over serial when "Get Data" button is pressed
 - The data is read in from the FPGA after the "Sample" button is pressed

 

