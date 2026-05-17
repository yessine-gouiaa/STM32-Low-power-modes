as much as low power modes seems simple and easy to do
there are many tricks that may happen and holds cpu from entering specific low power mode correctly
this example show one of these cases
project demonstrate the effect of debug bits on power consumption
this examples shows the necessity of clearing manually debug bits before entering standby mode
if it happen and you debugged the project before running it
debug bits set and they get stuck there even if you disable them using STM32CubeIDE GUI interface you need to clear them by code
this will result to a drop in power consumption from 1.4mA to 900nA 