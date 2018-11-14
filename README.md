# AIMLOS

A.I.M.L.O.S. stands for Artificially Intelligent and Machine Learnable Operating Systems. 

AIMLOS is a project targetting to revolutionise the housing and real estate sector with Artificial Intelligence. 

Aim 1:
  1) Collect monthly housing power consumption data from Google Dataset Search Toolbox.
  2) Collect weather data of a particular state or city from Google Dataset Search Toolbox.
  3) Analyse the data
  4) Build a model for predicting the power consumption and monthly electricity bill for a particular household depending on the number of appliances, usage duration of particaular appliances (low or high), outside weather consitions and time of day so as to give a prediction of power usage to the household and help them cut on electricity and avoid unnaturally high bills.

If Aim 1 is completed:
  1) Build a hybrid network for speech recognition, intent classification and entity recognition so as to understand user commands such as 'Turn on the AC at 20'
  2) Build another connecting network for automatic AC/heater/fan/etc... levels depending on outside temperature, time of day, user commands (specific), power consumption limitations
  3) A Reinforcement / Active Learning model on the above for user feedbacks.
 
For Full Stack/UI/UX developers:
  1) Build the backend of the whole software to make it an end to end product and also create a web page.
  
Link to datasets: https://drive.google.com/open?id=16QnG-QWRPRI9uexQL42fhNxVJLMAxNCe

For household_energy_consumption.csv:

    Attribute Information: 1.date: Date in format dd/mm/yyyy

    2.time: time in format hh:mm:ss

    3.global_active_power: household global minute-averaged active power (in kilowatt)

    4.global_reactive_power: household global minute-averaged reactive power (in kilowatt)

    5.voltage: minute-averaged voltage (in volt)

    6.global_intensity: household global minute-averaged current intensity (in ampere)

    7.sub_metering_1: energy sub-metering No. 1 (in watt-hour of active energy). It corresponds to the kitchen, containing mainly a dishwasher, an oven and a microwave (hot plates are not electric but gas powered).

    8.sub_metering_2: energy sub-metering No. 2 (in watt-hour of active energy). It corresponds to the laundry room, containing a washing-machine, a tumble-drier, a refrigerator and a light.

    9.sub_metering_3: energy sub-metering No. 3 (in watt-hour of active energy). It corresponds to an electric water-heater and an air-conditioner.
