# Differential Amplifier with active load using PDM
Designing a differential amplifier with an active load using the potential division method in Cadence Virtuoso gpdk 180nm technology to achieve a gain of 40 dB and a slew rate of 5 V/μs and gain bandwidth product 5MHz.
The differential pair consists of two NMOS transistors (M1, M2) as the input stage.
The active load is typically implemented using PMOS transistors (M3, M4) in a current mirror configuration.
A tail current source (using an NMOS transistor, M0) is used to set the differential pair's bias current.
The potential division method helps set the bias point of the differential pair and the active load. You can use resistor dividers or voltage sources to adjust the gate voltages of the transistors to set the proper operating point.
Perform DC, AC, and transient analysis in Cadence Virtuoso to verify the gain, slew rate, and operating points.
Adjust the transistor sizes, bias currents, and load capacitance based on simulation results to meet the design specifications.
Fine-tune the parameters to ensure the amplifier meets the required gain and slew rate. Ensure that all transistors remain in saturation for proper operation.

