# NI-USB6008-analog-digital-outputs
This script allows to control analog (any value between 0 and 5V) and digital (0 or 5V) outputs of the USB-6008 DAQ from National Instrument using the PyDAQmx module. 
Additional outputs can be added following the same model.
Tested on Python 2.7 64-bit on a windows machine

- First make sure that the DAQ is recognised by the computer, and that you can use the program provided by National Instrument (NI-MAX) to set the voltages.

- The script NI-USB-6008.py assigns a task to digital/analog pin of the device. Once a task is assigned you can use the task to set the voltage of the pin using one of the function of the code.

- To use the script, eventually modify the code to assign the task to your pin of interest, then run the code in your favorite editor like Spyder. After that, you can use the interactive command line to call the functions to set voltages.
