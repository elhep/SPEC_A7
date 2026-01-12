"# SPEC_A7" 

Reguiered: https://github.com/elhep/SPEC_A7/milestone/1

Done:
- Upper side of PCB with 2.5mm keepout to prevent collision with crate slides. JTAG and all parts moved down.
- Obsolete parts replaced: 
        - NB3L553DG -> NB3U1548C
        - S27KS0642GABHB020 -> S27KS0642GABHV020
-  Corrected to appropriate part SIT9121AI-1C2-33E125.000000 -> SIT9121AI-2C2-33E125.000000 (https://github.com/elhep/SPEC_A7/issues/9)
- Front panel LEDs redistributed. Front SMA set in one line. Moved front panel mounting holes (rounded to reasonable position).
- PCB origin set to front panel lower nmounting hole
- The output capacitors on IC19, IC46, IC47 were replaced with 10uF 16V tantalum capacitors
- Info to do not cut PCB tabs
- corrected stackup to 0,035mm copper on every layer
- AD5683R replaced by AD5683 with external 3V reference (check if current limiting resistor R205 not too big) (https://github.com/elhep/SPEC_A7/issues/14)
- TVS diodes with small capacitance used: PESD5V0S1UA,115 -> D1213A-02SR-7
- Bottom silk ordered
- Impedance profile corrected, D90 added.
- S50 signals defined: SMA connectors, RGMI,
- replaced obsolete Nexperia parts
- PCB stackup table move to M1
