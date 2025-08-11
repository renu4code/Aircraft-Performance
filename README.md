# ✈️ Aircraft Performance Analysis

This Python script performs basic calculations to analyze the performance of an aircraft. It helps you determine important flight parameters like range, endurance, weight, lift, drag, acceleration.

---

## 🔧 What the Script Does

The script calculates the following:

- **Range**: How far the aircraft can fly based on fuel capacity and speed.
- **Endurance**: How long the aircraft can stay in the air.
- **Total Weight**: Sum of the payload (e.g., passengers or cargo) and fuel weight.
- **Center of Gravity (CG) Position**: Balance point of the aircraft, based on weight distribution.
- **Lift**: Upward force keeping the aircraft in the air.
- **Drag**: Air resistance pulling the aircraft back.
- **Weight (in Newtons)**: Force due to gravity on the aircraft's mass.
- **Acceleration**: How quickly the aircraft speeds up or slows down.
- **Velocity**: Final speed after acceleration.
- **Distance**: How far the aircraft travels in a given time.

📁 All results are saved into a file named:

aircraft_performance_analysis.txt

## 📥 Input Data

The script uses the following predefined input values:

```python
fuel_capacity = 1000               # gallons
fuel_consumption_rate = 50        # gallons per hour
true_air_speed = 150              # knots
payload = 5000                    # pounds
fuel_weight = 6000                # pounds
moment_list = [10000, 2500]       # pound-feet
total_weight = 1500               # pounds (used for CG position)
cl = 1.5                          # lift coefficient
cd = 0.02                         # drag coefficient
rho = 1.225                       # air density (kg/m³)
v = 100                           # velocity (m/s)
s = 20                            # wing area (m²)
mass = 5000                       # mass (kg)
g = 9.81                          # gravity (m/s²)
thrust = 6000                     # thrust (N)
drag = 5000                       # drag force (N)
velocity = 50                     # initial velocity (m/s)
acceleration = 2                 # m/s²
time = 10                         # seconds



                                                ----- Happy Coding -----


