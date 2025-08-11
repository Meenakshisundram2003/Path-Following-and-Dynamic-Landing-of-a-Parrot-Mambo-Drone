# Path-Following-and-Dynamic-Landing-of-a-Parrot-Mambo-Drone

This repository contains two key autonomous drone control systems for the Parrot Mambo drone:

- **Dynamic Landing on a Moving Platform**: The drone performs a controlled landing on a moving RGB-marked platform (mounted on a line-following robot).
- **Path Following**: The drone autonomously follows a pre-defined path using position estimation and control logic.

Both projects are implemented in MATLAB & Simulink with custom logic, vision modules, and demonstration videos.

---

## Repository Structure

```
/
├── dynamic_landing.zip          # All code/models for dynamic landing experiment
├── path_following.zip           # All code/models for path following experiment
├── docs/
│   ├── Landing_Report.pdf       # Report for dynamic landing
│   └── Path_Following_Report.pdf # Report for path following
├── demo/
│   ├── dynamic_landing_demo.mp4 # Demo video for dynamic landing
│   ├── path_following_demo.mp4  # Demo video for path following
│   └── ...                      # Other videos or examples
```
---

## Project 1: Dynamic Landing on a Moving Platform

- **Description**: Implements vision-based detection and Stateflow logic for the drone to track and land on a moving platform.
- **How to Use**:
  1. Unzip `dynamic_landing.zip`.
  2. Open MATLAB, load the provided project file(s).
  3. Follow instructions in `/docs/Landing_Report.pdf`.
  4. Run Simulink models and deploy code to drone as described.
- **Documentation**: See [`docs/Landing_Report.pdf`](docs/Landing_Report.pdf).
- **Demo**: Watch `demo/dynamic_landing_demo.mp4`.

---

## Project 2: Path Following

- **Description**: Enables the drone to autonomously follow a defined path using onboard sensors and control logic.
- **How to Use**:
  1. Unzip `path_following.zip`.
  2. Open MATLAB, load the provided project file(s).
  3. Follow instructions in `/docs/Path_Following_Report.pdf`.
  4. Run Simulink models and deploy code to drone as described.
- **Documentation**: See [`docs/Path_Following_Report.pdf`](docs/Path_Following_Report.pdf).
- **Demo**: Watch `demo/path_following_demo.mp4`.

---

## Demonstration Videos

- All experiment demonstration videos are located in the [`demo/`](demo/) folder.
- These showcase real drone performance for both dynamic landing and path following scenarios.

---

## Requirements

- MATLAB, Simulink, Stateflow Toolboxes
- Parrot Mambo Drone hardware
- Bluetooth connectivity

---

```

