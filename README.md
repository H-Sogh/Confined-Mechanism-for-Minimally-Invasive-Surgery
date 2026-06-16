# Confined Mechanism for Minimally Invasive Surgery

This repository contains all the design files of a novel RCM (Remote Center of Motion) mechanism for minimally invasive surgery. The mechanism enforces the RCM constraint mechanically (design‑based approach), reducing reliance on complex software, improving patient safety, and lowering manufacturing costs.

<!-- <div style="display: flex; gap: 10px;">
  <img src="Photos\Renderings\Rendering 3DOF RCM.png" alt="3 DOF RCM prototype" width="350">
  <img src="Photos\Prototype\Experimental setup for error analysis.JPG" alt="Error analysis setup" width="350">
</div> -->

## Repository Structure

```
├── CAD
│ ├── Fusion 360    # Main design file (Autodesk Fusion 360)
│ └── STL
│  ├── laser error analysis stl files   # STLs for error analysis design
│  └── prototype                        # STLs for 3DOF design
└── README.md
```

<!-- 
├── Photos
│ ├── Geometry      # Angle definitions and geometric model (PDF)
│ ├── Prototype     # Photos of the assembled mechanism and experimental setup
│ └── Renderings    # 3D renderings of the RCM mechanism
 -->

## Key Features

- **Design‑based RCM** – No iterative numerical IK solvers needed.
- **Low‑cost & simple** – Standard revolute joints and rigid links. 3 actuators and easy control.
- **Lightweight & compact** – Suitable for portable/handheld surgical robots.
- **Upgradable** – Can be extended to variable‑radius RCM with one extra actuator.

## Usage

1. **3D printable 3-DOF prototype** – Use the STL files in `CAD/STL/prototype` for a physical prototype.
2. **3D printable error analysis mechanism** – The `CAD/STL/laser error analysis stl files` are designed for error measurement setups.
3. **Editable 3D models** - Check the Fusion 360 archive file at `CAD/Fusion360/Prototypes of Confined Mechanism for Minimally Invasive Surgery.f3z`
<!-- 4. **Documentation** – See `Photos/Geometry/` for kinematic definitions and model. -->

## Citation

If you use this design in your research, please consider citing the accompanying paper (to be added).