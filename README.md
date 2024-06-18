This is an HTML-based code that converts voltage (mV) to temperature (K) and temperature (K) to voltage (mV) for T-type and K-type thermocouples. 
It primarily uses coefficients provided by NIST. 
However, in NIST, coefficients below 65 K are not available in certain instances.
Extensive fitting was done to calculate the missing coefficients and their accuracy was estimated to be 0.05 K.
This code contains the original NIST coefficients and the missing coefficients at lower temperatures. 
For the T-type thermocouple, the range of input temperatures is 3.15 - 673.15 K, and the range of input voltage is -6.248 - 15.455 mV.
For K-type thermocouple, the range of input temperatures is 273.15 - 1645.15 K, and the range of input voltage is 0 - 20.644 mV.
To calculate voltage/temperature first select the type of Thermocouple and then input the value in the input field and press the enter key. 
The result will be shown in the result field.
![convert](https://github.com/saif-phy/Thermocouple-Voltage-Temperature-Converter/assets/170793998/b4e10121-02a5-4a2c-a5d8-547b514c90e7)
