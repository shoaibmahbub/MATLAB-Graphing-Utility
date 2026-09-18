# MATLAB Graphing & Numerical Analysis Utility

A standalone, multi-equation 2D/3D graphing and numerical analysis GUI built with **MATLAB App Designer**.

Developed as part of the academic project for **EEE-4416** by **Shoaib Mahbub** (ID: 230021325, Section C1).

---

## Features

- **2D & 3D Function Plotting:** Handles explicit (`y = f(x)`) and implicit (`x^2 + y^2 = 16`) equations using dynamic string parsing.
- **Numerical Solvers:** Evaluates single-function $x$-intercepts via `fzero`/`vpasolve` and locates dual-curve intersection points.
- **Theme Engine:** Instant toggling between Light and Dark visual modes with full contrast synchronization across panels and legends.
- **Error Guarding:** Active input validation to prevent axis range bounds errors and silent execution crashes.

---

## Quick Start

### Option A: Standalone Executable (No MATLAB Required)
Download the latest standalone installer from the [GitHub Releases](../../releases/latest) page and run the setup wizard.

### Option B: Run Source Code in MATLAB
1. Clone or download this repository.
2. Open MATLAB (R2020b or newer).
3. Navigate to the `src/` folder and launch `app1.mlapp` in App Designer.
4. Click **Run**.

---

## Project Structure

```text
.
├── src/
│   └── app1.mlapp               # Primary MATLAB App Designer source file
├── docs/
│   └── Project_Description.pdf  # Initial project guidelines & prompt specifications
├── README.md                    # Project documentation
└── .gitignore                   # Git build ignore rules
```
