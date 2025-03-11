BGR : The voltage refernce should be independent of PVT variations.
1. PROCESS by which the circuit is implemented
2. VOLTAGE variations of supply voltage
3. TEMPERATURE variations from -40°C to +125°C

The voltage reference consists of:
1. PTAT circuit: voltage variation is proportional to absolute temperature
2. CTAT circuit: voltage variation is complementary to absolute temperature
3. α1 * PTAT + α2 * CTAT = constant voltage

PROCEDURE:
1. The circuit is designed in CADENCE VIRTUOSO. 
2. DC analysis is performed by sweeping temperature parameter from -40°C to +125°C.
3. The graphs of CTAT, PTAT and BGR voltage are plotted.
