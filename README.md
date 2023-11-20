# Melcloud2DomoticzV3
Melcloud2Domoticz updated by Giljam Val
# the data below is copy paste from a post Gival made on https://gathering.tweakers.net/forum/list_messages/2112892/5

 I have made a version 3.0 of this script. (also stated in Albert's GIT). Unfortunately, this version 3.0 is not yet finished (I haven't gotten around to it yet). That's why I'm now running both scripts side by side. Version 2.0 for the updates to Melcloud and version 3.0 for reading out additional parameters. That works fine; just a little more processing, so I want to finish version 3.0 soon (I've already made some progress).

With version 3.0 you can now read out some more parameters (see below), you can also add new ones more easily, it reads out everything you add in the config file .mcdevices.

(below from the config file, first letter is Read/Write/eXclude (ignore), second letter is General/2eZone/Hotwater (skipped if not applicable). 3rd column is the Melcloud data type, then another type for Domoticz and another default value and an IDX). R#G # OperationMode # Text

R#G#OperationMode#Text#-#4483
X#G#HasHotWaterTank#Switch#On#0
X#G#HasZone2#Switch#Switch#Off#0
X#G#CanHeat#Switch#On#0
X#G#CanCool#Switch#Off#0
X#G#HeatpumpStatus#Text#-#4021
R#G#HeatpumpActive#Switch#Off#4025
R#G#HeatPumpPower#Switch#On#4024
X#G#CurrentEnergyConsumed#Power#0#0
X#G#CurrentEnergyProduced#Power#0#0
R#G#WaterPump1Status#Switch#Off#4032
R#G#WaterPump2Status#Switch#Off#4033
R#G#WaterPump3Status#Switch#Off#4034
R#G#WaterPump4Status#Switch#Off#4037
R#G#ValveStatus3Way#Switch#Off#4035
R#G#ValveStatus2Way#Switch#Off#4036
R#G#ValveStatus2Way2a#Switch#Off#4038
R#G#ValveStatus2Way2b#Switch#Off#4039
R#G#BoosterHeater1Status#Switch#Off#4040
R#G#BoosterHeater2Status#Switch#Off#4041
U#G#SetHeatFlowTemperatureZone1#SetPoint#40#4011
U#2#SetHeatFlowTemperatureZone2#SetPoint#40#4012
U#C#SetCoolFlowTemperatureZone1#SetPoint#18#4013
U#C2#SetCoolFlowTemperatureZone2#SetPoint#18#4014
R#G#OutdoorTemperature#Temp#18#4006
U#G#SetTemperatureZone1#SetPoint#20#4015
U#2#SetTemperatureZone2#SetPoint#20#4016
U#H#SetTankWaterTemperature#SetPoint#50#4018
R#G#RoomTemperatureZone1#Temp#0#4007
R#2#RoomTemperatureZone2#Temp#0#4008
R#H#TankWaterTemperature#Temp#0#4010
U#G#OperationModeZone1#Selector#20#4027
U#2#OperationModeZone2#Selector#20#4028
R#G#ProhibitHeatingZone1#Text#-#4019
R#2#ProhibitHeatingZone2#Text#-#4020
X#G#ProhibitCoolingZone1#Text#-#0
X#2#ProhibitCoolingZone2#Text#-#0
R#H#EcoHotWater#Text#-#4022
R#H#ProhibitHotWater#Text#-#4023
R#H#ForcedHotWaterMode#Switch#Off#4026
R#H#MaxTankTemperature#Temp#0#4009
R#G#DefrostMode#Switch#-#4920
R#G#DefrostMode#Text#-#4925
X#G#MinSetTemperature#SetPoint#30#0
X#G#MaxSetTemperature#SetPoint#50#0
R#G#FlowTemperature#Temp#0#4624
R#G#FlowTemperatureZone1#Temp#0#4622
R#2#FlowTemperatureZone2#Temp#0#4623
R#G#ReturnTemperature#Temp#0#4625
R#G#ReturnTemperatureZone1#Temp#0#4626
R#2#ReturnTemperatureZone2#Temp#0#4627
R#H#ReturnTemperatureBoiler#Temp#0#4630
X#H#BoilerStatus#Text##0
R#G#MixingTankWaterTemperature#Temp#0#4628
R#G#CondensingTemperature#Temp#0#4629
X#G#DemandPercentage#Percentage#0#4878
R#G#DailyHeatingEnergyConsumed#Power#0#4632
X#C#DailyCoolingEnergyConsumed#Power#0#0
X#G#DailyHeatingEnergyProduced#Power#0#4877
X#C#DailyCoolingEnergyProduced#Power#0#0
X#G#DailyHotWaterEnergyProduced#Power#0#0
X#G#DailyHotWaterEnergyConsumed#Power#0#0
X#G#HolidayMode#Text##0
X#G#TargetHCTemperatureZone1#Temp#0#0
X#2#TargetHCTemperatureZone2#Temp#0#0
X#G#SetHeatFlowTemperatureZone1#SetPoint#30#0
X#2#SetHeatFlowTemperatureZone2#SetPoint#30#0
X#C#SetCoolFlowTemperatureZone1#SetPoint#18#0
X#C2#SetCoolFlowTemperatureZone2#SetPoint#18#0
X#2#HasSimplifiedZone2#Switch#Off#0
R#G#ErrorMessage#Text#-#4924
