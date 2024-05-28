# Protected-Li-ion-Battery-Charging-Module
<img width="897" alt="image" src="https://github.com/siwar-gharbi/Protected-Li-ion-Battery-Charging-Module/assets/109144779/70d43512-e56b-4644-b5ea-a7a147462bf1">


Manage the constant current to constant voltage charging of a connected lithium battery
Over-discharge protection -
keeps your battery from being discharged below 2.4V, a healthy minimum voltage level for your battery If a connected battery has been discharged below 2.4V the module will cut output power from the battery until the battery voltage has been re-charged above 3.0V (the over-discharge release voltage), which at that time the module will again allow discharge of power from the battery to a connected load. Although the module cuts output power from the battery during an over-discharge situation, it still allows charging of the battery to occur through the parasitic diode of the discharge control MOSFET (FS8205A Dual MOSFET).

Overcharge protection - the module will safely charge your battery to 4.2V
Overcurrent and short-circuit protection - the module will cut the output from the battery if the discharge rate exceeds 3A or if a short-circuit condition occurs
Soft-start protection limits inrush current
Trickle charge (battery reconditioning) - if the voltage level of the connected battery is less than 2.9V, the module will use a trickle charge current of 130mA until the battery voltage reaches 2.9V, at which point the charge current will be linearly increased to the configured charge current.

Can be powered, for charging, from a USB cable (USB C) or the VCC and GND connections. The power source needs to be able to provide at least 1A for the charger to correctly charge a connected battery. 

Includes two indicator LEDs that indicates charging and charge complete.

Product Contents:

1 pc - TP4056 / TC4056 Lithium Battery Charger and Protection Module
Specifications:

Charge Controller	TP4056 / TC4056
Protection IC	DW01A
Charge/Discharge Control MOSFET	FS8205A
Input Supply Voltage	4.5~6.0 V
Constant Charge Current	1 A
Charge Complete (Float) Voltage	4.2 V ±1.5%
Overcharge Protection
Overcharge Detection Voltage	4.3 V ±50 mV
Overcharge Release Voltage	4.1 V ±50 mV
Over-Discharge Protection
Over-Discharge Detection Voltage	2.4 V ±100 mV
Over-Discharge Release Voltage	3.0 V ±100 mV
