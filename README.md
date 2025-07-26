# Laminar Fluid Flow in Split Pipe  | COMSOL Multiphysics

## 🔍 Objective

To simulate steady-state laminar flow through a split circular pipe to:
- Visualize velocity and pressure gradients.
- Evaluate parabolic flow profile.
- Study effects of wall shear and symmetry.

## 🛠️ Tools Used
- **COMSOL Multiphysics** (Physics: Laminar Flow, Stationary Study)
- **COMSOL's CFD Module**
- **Post-processing**: COMSOL Visualization + Python (optional for automation)

## 🧪 Simulation Setup

| Parameter         | Value                  |
|------------------|------------------------|
| Geometry          | Horizontally split circular pipe (3D) |
| Fluid             | Water (ρ = 1000 kg/m³, μ = 0.001 Pa·s) |
| Pipe Length       | 15.0 mm                  |
| Pipe Diameter     | 1 mm                 |
| Flow Regime       | Laminar (Re < 1000)    |
| Study Type        | Stationary             |

## 🔄 Boundary Conditions

- **Inlet**: Uniform velocity profile
- **Outlet**: Zero pressure (reference)
- **Walls**: No-slip condition
- **Symmetry**: Used on centerline of split pipe

## 📊 Results

### 🔹 Velocity Profile
- Parabolic profile confirming laminar nature.
- Max velocity at centerline

![Velocity Profile](velocity_profile.png)

### 🔹 Pressure Distribution
- Linear drop along length of the pipe.
- Minimal turbulence at split zone.

![Pressure Distribution](pressure_distribution.png)

### 🔹 Streamlines
- Smooth, continuous, no vortices.
- Confirms absence of recirculation zones.

![Streamlines](Results/streamlines_video.gif)

## 📎 Files Included

| Folder           | Contents |
|------------------|----------|
| `/COMSOL_Model`  | `.mph` COMSOL simulation file |
| `/Results`       | PNG plots and streamline animation |
| `/Reports`       | PDF summary of the simulation |
| `/README.md`     | Project description |

## 📌 Learning Outcome

This project demonstrates:
- Laminar fluid flow setup in COMSOL
- Interpreting fluid mechanics results
- visual reporting

## 📄 License

This project is licensed under the MIT License. Feel free to fork and build on it.

---

**Developed by [Shahana P](https://github.com/the-frozen-light)**  
[🔗 Portfolio](https://motokid181.wixsite.com/shahana-portfolio)
