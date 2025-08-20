Electric Drivetrain Efficiency Model 

This project is a 1D simulation of an electric drivetrain system, developed as part of a technical challenge for a Performance Simulations Engineer position. The goal was to evaluate battery-to-wheel efficiency under a given drive cycle and study how key parameters affect overall performance.

This project builds a MATLAB/Simulink model of a dual-axle electric drive unit (EDU) with motors, inverters, and gearboxes. Simulates power flows and losses to calculate system efficiency across a drive profile. Runs a sensitivity analysis on:

Gear ratio → balance between energy efficiency and torque delivery
Inverter switching frequency → trade-off between ripple reduction and switching losses
Motor temperature → effect of cooling efficiency on drivetrain performance

It also Identifies optimization strategies for improving efficiency while managing trade-offs. Highlights plausibility issues in the provided drive cycle (e.g., unrealistic regen power spike >2 MW).

📊 Key Insights
Lower gear ratios (e.g., 6) keep the motor in its sweet spot → lower energy consumption.
Moderate switching frequencies (10–12 kHz) balance inverter losses and performance.
Strong thermal management is essential — cooling efficiency drops of ~10% can cut overall system efficiency by up to 9%.

🛠 Tools & Methods
MATLAB/Simulink for modeling and simulation
Quadratic + empirical models for motor, inverter, and cooling efficiencies
Sensitivity analysis with comparative plots and data tables
