# Confined Mechanism for Minimally Invasive Surgery

This repository contains all the design files of a novel RCM (Remote Center of Motion) mechanism for minimally invasive surgery. The mechanism enforces the RCM constraint mechanically (design‑based approach), reducing reliance on complex software, improving patient safety, and lowering manufacturing costs.

## Repository Structure
```
├── CAD
│ ├── Fusion 360                        # Main design file (Autodesk Fusion 360)
│ └── STL
│  ├── laser error analysis stl files   # STLs for error analysis prototype
│  └── prototype                        # STLs for physical prototype
├── Photos
│ ├── Geometry      # Angle definitions and geometric model (PDF)
│ ├── Prototype     # Photos of the assembled mechanism and experimental setup
│ └── Renderings    # 3D renderings of the RCM mechanism
└── README.md
```

## Key Features

- **Design‑based RCM** – No iterative numerical IK solvers needed.
- **Low‑cost & simple** – Standard revolute joints and rigid links.
- **Lightweight & compact** – Suitable for portable/handheld surgical robots.
- **Upgradable** – Can be extended to variable‑radius RCM with one extra actuator.

## Usage

1. **3D printing** – Use the STL files in `CAD/STL/prototype` for a physical prototype.
2. **Error analysis** – The `laser error analysis stl files` are designed for optical measurement setups.
3. **Documentation** – See `Photos/Geometry/` for kinematic definitions and model.

## Citation

If you use this design in your research, please cite the accompanying paper (to be added).

## License

[Specify your license, e.g., MIT, CC‑BY‑NC, or “All rights reserved”]