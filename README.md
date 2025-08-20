Electric Drivetrain Efficiency Model 

This project is a 1D simulation of an electric drivetrain system, developed as part of a technical challenge for a Automotive OEM company. The goal was to evaluate battery-to-wheel efficiency under a given drive cycle and study how key parameters affect overall performance.

This project builds a MATLAB/Simulink model of a dual-axle electric drive unit (EDU) with motors, inverters, and gearboxes. Simulates power flows and losses to calculate system efficiency across a drive profile. Runs a sensitivity analysis on Gear ratio, Inverter switching frequency, Motor temperature. It also Identifies optimization strategies for improving efficiency while managing trade-offs.

📊 Key Insights

1) Lower gear ratios keep the motor in its sweet spot → lower energy consumption.
2) Moderate switching frequencies (10–12 kHz) balance inverter losses and performance.
3) Strong thermal management is essential — cooling efficiency drops of ~10% can cut overall system efficiency by up to 9%.

🛠 Tools & Methods

1) MATLAB/Simulink for modeling and simulation
2) Quadratic + empirical models for motor, inverter, and cooling efficiencies
3) Sensitivity analysis with comparative plots and data tables
