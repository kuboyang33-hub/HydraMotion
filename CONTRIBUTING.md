Contributing to HydraMotion
Thanks for your interest in contributing to HydraMotion — an open‑hardware, multi‑mode CoreXY platform designed for 3D printing, CNC machining, drag‑knife cutting, and pen plotting.
This project is built to be modular, transparent, and community‑driven. Contributions of all kinds are welcome.

🧭 Project Structure
HydraMotion uses a clean branch‑based structure:

Branch	Purpose
Main	Documentation, roadmap, overview, contributor guides
Hardware	CAD, STEP files, frame, toolheads, MotorSwitcher
Firmware	Klipper configs for PrintMode, CNCMode, CutMode, PlotMode
Please make sure your contributions go to the correct branch.

🛠️ How to Contribute
1. Fork the repository
Click Fork on GitHub to create your own copy.

2. Create a feature branch
Use a descriptive name:

Code
feature/frame-v1
feature/printhead-mount
fix/typo-readme
firmware/cnc-macros
3. Make your changes
Follow the guidelines below for CAD, firmware, and documentation.

4. Commit with clear messages
Examples:

Add v1 frame STEP placeholder

Create initial PrintMode printer.cfg

Document toolhead interface concept

Fix typo in README

5. Open a Pull Request
Target the correct branch:

Hardware → Hardware

Firmware → Firmware

Docs → Main

Include a short description of what you changed and why.

🧩 Contribution Areas
Hardware (CAD / Mechanical)
Use STEP as the primary exchange format

Fusion 360, SolidWorks, Onshape, and FreeCAD are all acceptable

Keep assemblies modular

Name files clearly:

Code
frame_v1.step
print_head_v1.step
motor_switcher_v1.step
pen_lift_v1.step
Firmware (Klipper)
Each mode has its own folder:

Code
Firmware/Klipper/PrintMode/
Firmware/Klipper/CNCMode/
Firmware/Klipper/CutMode/
Firmware/Klipper/PlotMode/
Please:

Keep configs modular

Use comments generously

Avoid machine‑specific values unless necessary

Add macros in separate files when possible

Documentation
Good documentation is as valuable as hardware:

README improvements

Diagrams

Mode explanations

Toolhead interface descriptions

Build instructions

Roadmap updates

🧪 Coding & CAD Standards
General
Keep contributions modular

Avoid hard‑coding machine‑specific values

Prefer clarity over cleverness

Document assumptions and limitations

CAD
Use real‑world units (mm)

Keep sketches fully constrained

Avoid proprietary file formats as the only source

Include exploded views when helpful

Klipper
Use descriptive section names

Group macros logically

Comment every non‑obvious line

Keep mode‑specific configs isolated

🗣️ Communication
If you want to propose a feature or discuss an idea:

Open a Discussion

Or create an Issue labeled proposal or question

If you’re unsure where something belongs, just ask — we’re happy to help.

🏁 Getting Started Tasks
If you want to help but don’t know where to start, check out issues labeled:

good first issue

help wanted

hardware

firmware

documentation

These are beginner‑friendly and important.

Enter your email to get approval to edit my OnShape file.

❤️Code Of Conduct:
Be respectful, constructive, and collaborative.
HydraMotion is an open‑hardware project built on shared curiosity and engineering creativity.

Thank You For Supporting This Project!😊❤️
