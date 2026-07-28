# ⚡ Vidyut Sanchalak (विद्युत संचालक)

> *A comprehensive codebase and computational toolkit dedicated to modern power system analysis, electrical machine modeling, and smart grid automation.*

---

## 📌 About The Project
**Vidyut Sanchalak** is engineered to bridge core electrical engineering concepts with practical software implementation. Designed with a focus on rigorous analytical modeling, power flow optimization, and control systems, this repository serves as a functional framework for electrical engineers, researchers, and core engineering aspirants interested in power systems and automation.

---

## 🛠️ Core Engineering Domains & Features

* **⚡ Power Systems Analysis:** Implementation of algorithms for Load Flow (Newton-Raphson, Gauss-Seidel), Economic Load Dispatch, and Fault Analysis (Symmetrical & Unsymmetrical).
* **🔄 Electrical Machines Modeling:** Dynamic simulation parameters and mathematical modeling for Transformers, Synchronous Generators, and Induction Motors.
* **📊 Control & Automation:** Feedback loop stability analysis, Bode/Nyquist plots, and root locus derivations for linear time-invariant (LTI) systems.
* **🔌 Substation & Grid Control Logic:** Scripts and logic modeling mirroring real-world grid operations, protection schemes, and SCADA monitoring concepts.

---

## ⚙️ Tech Stack & Dependencies

* **Language:** Python / MATLAB *(update based on your exact implementation)*
* **Key Libraries:** 
  * `NumPy` & `SciPy` (for matrix computations and numerical differential equation solving)
  * `Matplotlib` / `Control` (for system response and stability visualization)
  * `Pandas` (for handling grid load profile datasets)

---

## 📂 Repository Structure

```tree
vidyut-sanchalak/
│
├── power-systems/       # Load flow, fault calculations, and transmission line parameters
├── machines/            # Equivalent circuit simulations and torque-speed characteristics
├── control-systems/     # Stability criteria, compensators, and frequency response
├── assets/              # Circuit diagrams, single-line diagrams (SLDs), and plots
└── README.md            # Project Documentation
```

## 🚀 Getting Started

### Prerequisites

Ensure you have Python installed along with the essential engineering packages:

```bash
pip install numpy scipy matplotlib control pandas
```

### Installation & Execution

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/govinda-1403/vidyut-sanchalak.git](https://github.com/govinda-1403/vidyut-sanchalak.git)
   ```

2. **Navigate into the project directory:**
   ```bash
   cd vidyut-sanchalak
   ```

3. **Run any specific module (e.g., power flow or machine analysis script):**
   ```bash
   python power-systems/load_flow.py
   ```

---

## 💡 Future Roadmap

- [ ] Add real-time load forecasting models using historical grid data.
- [ ] Expand fault analysis modules for microgrid configurations.
- [ ] Implement automated single-line diagram (SLD) generation tools.

---

## 🤝 Contributing

Contributions, suggestions, and peer reviews from fellow electrical engineering enthusiasts and core tech developers are always welcome! Feel free to open an issue or submit a pull request.

---

## 📜 License

Distributed under the MIT License.

---

*Crafted with ⚡ for the core engineering community.*
