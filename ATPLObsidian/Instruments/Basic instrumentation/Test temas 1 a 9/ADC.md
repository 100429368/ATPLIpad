Transforms air data measurements into impulsive electric signals driving servo motors in instruments.


**Inputs are 
Total Air Temperature
Static pressure
Total pressure**
Sometimes AoA

Outputs are:
IAS
TAS
SAT/OAT
TAT
M
AOA
Altitude
Vertical speed
Position of VMO/MMO pointer



Systems connected to ADC:
TCAS
EFIS
AFCS(automatic flight Control System)
Transponders
Fms
Flight data recorder 
Warning systems
EFIS(electronic flight information system)

Failure in ADC affects:
Speed(IAS CAS TAS M)
Altitude
AoA
Vertical Speed
OAT
TAT

No necesita OAT

Parapasar de IAS a CAS utiliza
Compressibility errors
Density errors
Instrument errors
Position errors 


It receives The static pressure and total pressure, it supplies the TAS to the conputer of the INS , determines the match number, the outside air temperature.


