# BalconyPowerPlant
+-------------------+
|  PowerPlant       |
+-------------------+
| - pvModule: PVModule |
| - inverter: Inverter |
| - plug: Plug        |
| - assembly: Assembly |
+-------------------+
| + displayInfo()    |
+-------------------+

       |
       V

+-------------------+
|  PVModule         |
+-------------------+
| - height: double  |
| - width: double   |
+-------------------+
| + getDimensions() |
+-------------------+

       |
       V

+-------------------+
|  Inverter         |
+-------------------+
| - dcVoltage: double |
+-------------------+
| + getDCVoltage()  |
+-------------------+

       |
       V

+-------------------+
|  Plug             |
+-------------------+
| - type: String    |
+-------------------+
| + getPlugType()   |
+-------------------+

       |
       V

+-------------------+
|  Assembly         |
+-------------------+
| - material: String|
+-------------------+
| + getMaterial()   |
+-------------------+
