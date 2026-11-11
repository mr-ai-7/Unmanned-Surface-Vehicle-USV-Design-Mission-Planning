# Unmanned Surface Vehicle Design & Mission Planning

A team project for ME5073 Marine Robotics at the ASTRAM Lab, IIT Hyderabad. We designed a 1.22 × 1.32 m surface vehicle in Fusion 360, fabricated its hull from 3D-printed PETG-HS sections, and integrated a Pixhawk controller for radio control and GPS waypoint mission planning.

[Watch the 47-second demo](usv%20working%20demo.mp4) · [Read the project report](Marine%20Robotics%20-%20USV%20Project%20Report.docx) · [View the ArduPilot parameters](USV_NEW.param)

## Hull and fabrication

The assembled vehicle measures 1,221 mm long by 1,318 mm wide and has a kerb weight of 16 kg. We printed the hull sections on a Bambu Lab H2S using four perimeters and 20% gyroid infill. Lip-and-groove joints aligned the sections during assembly. We sealed the seams with Dowsil 789 silicone and allowed 24 hours for curing.

## Propulsion and control

Two Blue Robotics T200 thrusters provide propulsion. The control system combines a Pixhawk X7 Pro+, GPS, electronic speed controllers, and a FrSky Taranis Q X7 radio. We used ArduPilot Mission Planner for GPS waypoint planning. The included parameter file records the controller settings for this build.

## Estimated performance

We estimated a top speed of approximately **2 m/s** by balancing available thrust against hull drag. The calculation used a CAD-derived wetted surface area of 1.0 m², a thrust rating of 4.55 kgf per thruster at 14 V, and an estimated drag coefficient of 0.043. The report uses the Blue Robotics BlueBoat as a reference and adjusts the drag coefficient for our boxier hull. The 2 m/s figure is a design estimate. The report does not include a measured top-speed trial.

## Project team

Built at the ASTRAM Lab, Department of Mechanical and Aerospace Engineering, IIT Hyderabad. The project report credits all nine team members.
