# DiffAmp_ACD
A differential amplifier (also known as a difference amplifier or op-amp subtractor) is a type of electronic amplifier that amplifies the difference between two input voltages but suppresses any voltage common to the two inputs. A differential amplifier is an analog circuit with two inputs (V1 and V2) which are differential signals.

## PROBLEM STATEMENT
<br>
<strong>Design a common source stage with current source load (implement using current mirror) for the following specifications:</strong> <br>
  <br>
  &emsp;Gain (A<sub>v</sub>) = 5 <br>
  &emsp;Power budget < 100 uW <br>
  &emsp;Supply voltage (V<sub>dd</sub>) = 1.8 V <br>
  &emsp;Threshold Voltage (V<sub>th</sub>) = 0.4 <br>
  &emsp;U<sub>n</sub>C<sub>ox</sub> = 300 uA/V<sup>2</sup>  <br>
  &emsp;Assuming Overdrive Voltage = 200 mV

## SCHEMATIC
![diffampschem](https://github.com/SahilPrabhu/DiffAmp_ACD/assets/92974277/a9c753f9-d361-4773-8d95-c0670ac43e0a)

## DC ANALYSIS
![dcanalysis](https://github.com/SahilPrabhu/DiffAmp_ACD/assets/92974277/5c64d597-ea45-4f2a-beb3-79021e2e338e)
![dcgraph](https://github.com/SahilPrabhu/DiffAmp_ACD/assets/92974277/6fc17933-2575-4d6c-a071-3ac7e14cd357)

## TRANSIENT ANALYSIS
![transanalysis](https://github.com/SahilPrabhu/DiffAmp_ACD/assets/92974277/3abe9796-3a6c-4e67-841e-8aed9f7a1187)

## INPUT WAVEFORMS
![inputtop](https://github.com/SahilPrabhu/DiffAmp_ACD/assets/92974277/3575b68d-0a74-4c65-a50d-5e0b1505451c)
![inputbottom](https://github.com/SahilPrabhu/DiffAmp_ACD/assets/92974277/0615b4db-89d9-4882-ba1c-a66b9ceea43b)

## OUTPUT WAVEFORMS
![outputtop](https://github.com/SahilPrabhu/DiffAmp_ACD/assets/92974277/86f816ca-3c05-4875-a507-d2c9934072d5)
![outputbottom](https://github.com/SahilPrabhu/DiffAmp_ACD/assets/92974277/ee07ae7b-ca63-474f-ac19-90f80ff573e6)


We get a gain of 4.45 for this circuit.
