# Python for Mobile Robotics (MORO)

Welcome to the **Python for Mobile Robotics** repository. This repository contains practical exercises, Jupyter notebooks, and assignments focused on applying Python programming concepts to mobile robotics fundamentals, kinematics, simulation, and algorithms.

---

## 📂 Repository Structure

```text
python for mobile robotics/
├── Exercise1/
│   └── Untitled4.ipynb    # Python fundamentals: Lists, dictionaries, and iteration
└── README.md              # Project documentation and guide
```

---

## 📚 Exercises Overview

| Exercise | Topic | Description | Status |
| :--- | :--- | :--- | :--- |
| **Exercise 1** | Python Fundamentals | Core data structures (`list`, `dict`), indexing, manipulation, slicing, and loops | Completed / In Progress |
| **Upcoming** | Kinematics & Motion | Differential drive models, forward/inverse kinematics | Planned |
| **Upcoming** | Sensor Simulation & Processing | Odometry, ultrasonic/lidar range data handling | Planned |
| **Upcoming** | Navigation & Path Planning | Obstacle avoidance, potential fields, grid search (A*, Dijkstra) | Planned |

---

## 🛠️ Prerequisites

Ensure you have the following installed on your system:

- **Python 3.8+** (recommended: Python 3.10 or later)
- **Jupyter Notebook** or **JupyterLab** (or use Google Colab / VS Code with Python & Jupyter extensions)
- Common scientific packages:
  - `numpy`
  - `matplotlib`
  - `scipy`

---

## 🚀 Getting Started

### 1. Clone or Open the Workspace

Open the repository folder in VS Code or your preferred IDE:

```bash
cd "python for mobile robotics"
```

### 2. Set Up a Virtual Environment (Recommended)

#### On Windows (PowerShell):
```powershell
python -m venv .venv
.venv\Scripts\Activate.ps1
```

#### On Linux / macOS:
```bash
python3 -m venv .venv
source .venv/bin/activate
```

### 3. Install Dependencies

```bash
pip install --upgrade pip
pip install notebook ipykernel numpy matplotlib scipy
```

### 4. Running the Notebooks

Launch Jupyter Notebook or JupyterLab:

```bash
jupyter notebook
```

Navigate to the exercise folder (e.g., `Exercise1/`) and open the notebook file (`.ipynb`).

---

## 📝 Best Practices

- Keep code clean, modular, and well-commented.
- Save and commit your work regularly after completing each section.
- Use descriptive variable and function names corresponding to physical units (e.g., `velocity_m_s`, `theta_rad`).

---

## 📄 License

This repository is intended for academic and educational purposes under the **Mobile Robotics (MORO)** course curriculum.
