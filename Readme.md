# Venturi Meter Simulator

An interactive web application built with Streamlit to simulate ideal and real fluid flow in a Venturi meter. 

## 🛠️ Technologies Utilized
- **Language:** Python
- **Framework:** Streamlit
- **Libraries:** NumPy, Pandas, Matplotlib, Thermo, Fluids

## 🎮 Features
- **Simulation Modes:** Ideal (no friction) and Realistic (Darcy-Weisbach friction analysis).
- **Real-time Visualization:** Schematic diagrams, pressure profiles, and energy line plots.
- **Fluid Database:** Pre-configured properties for water, air, ethanol, etc.
- **Dynamic Calculations:** Automatic computation of Reynolds number, friction factor, and head loss.

## ⚙️ How to Run

**1. Prerequisites**
Ensure you have Python 3.8+ installed on your machine.

**2. Installation**
Navigate to the source folder and install the required dependencies:
```console
cd src
pip install -r requirements.txt
```

**3. Execution**
Start the application server:
```console
streamlit run app.py
```

## 📚 Context
Developed for the Fenômenos de Transporte (Transport Phenomena) course at UFSC (Universidade Federal de Santa Catarina).

**Collaborators:**
- [Eduardo Zambotto da Silva](https://github.com/Edu17z)
- [Júlio Amaral Pereira](https://github.com/JulioAmaral007) 