# python-fibonacci-lfsr
Control LFSR for the High Altitude Balloon Random Number Generator Senior Capstone Project


## Function
Outputs the results from the FPGA random number generator and </br >
the results from the control linear feedback shift register </br >
concurrently over the terminal or command line. 
* Enter the serial COM port that the FPGA is connected to
	* This can be found in Windows device manager
* Waits for a serial connection to be established
* when a connection is established, the results are displayed
	* Python LFSR is on the left
	* FPGA based LFSR is on the right


## Expected LFSR Output:
ACE1 </br >
5670 </br >
AB38 </br >
559C </br >
2ACE </br >
1567 </br >
8AB3 </br >
4559 </br >
22AC </br >
9156 </br >
C8AB </br >
E455 </br >
722A </br >
3915 </br >
1C8A </br >
8E45 </br >
....
