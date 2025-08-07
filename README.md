# 🐜 Social Insects and Collective Computation

## 📝 Overview
This project simulates the collective behavior of ants using a state-machine-based approach to model decision-making, recruitment, and foraging. Inspired by the principles of bio-inspired computing, it explores how simple local rules can lead to intelligent global behavior without centralized control. 

This simulation models **tandem running** and **commitment dynamics** in an ant colony choosing between two food sources of different quality. It is based on Project 5 of ASU's CSE598 Bio-Inspired Computing course and aligns with current research in **swarm intelligence**, **emergent behavior**, and **collective decision-making**.

## ✨ Key Features
- Models **uncommitted**, **committed**, and **recruiting** ant states
- Incorporates probabilistic behavior using alpha, beta, and lambda parameters
- Visualizes state transitions and feeder preferences
- Explores how swarm behavior results in optimal food source selection
- Uses biologically inspired algorithms rather than traditional AI

## 🖼️ Screenshots

**Ant Feeder Setup**  
<img src="./assets/ant_feeder.png" alt="Ants choosing between feeders" width="500"/>

**Full Behavioral State Diagram**  
<img src="./assets/flow_chart.png" alt="State transition overview" width="500"/>

**Phase 1 – Initial State**  
<img src="./assets/flow_chart_pt1.png" alt="Uncommitted state flow" width="500"/>

**Phase 2 – Commitment & Recruitment**  
<img src="./assets/flow_chart_pt2.png" alt="Committed state flow" width="500"/>

**Phase 3 – Recruitment Dynamics**  
<img src="./assets/flow_chart_pt3.png" alt="Recruitment logic" width="500"/>

**Grid Layout of Nest and Feeders**  
<img src="./assets/grid_feeders.png" alt="Grid simulation of nest and feeders" width="500"/>

**Simplified Transition Diagram**  
<img src="./assets/transition_diagram.png" alt="Simplified transition model" width="500"/>

## 🧪 Technologies Used
- Python 3.10+
- HTML/CSS for data visualization
- Jupyter Notebook (optional, for experimentation)

## ⚙️ How to Build and Run
1. Clone the repository:
   ```bash
   git clone https://github.com/ChadNetwig/social-insect-collective-comp.git
   cd social-insect-collective-comp
   ```

2. Open the simulation:

- Either run cse598-proj5-code-FINAL.html in your browser

- Or analyze/edit the simulation logic in a text or HTML editor

Note: You may open it locally (no server required).

## 📌 Important Notes
- This project models concepts from Project 5: Modeling Collective Behavior in Ants from ASU’s CSE598 Bio-Inspired Computing course.

- The biological inspiration for this project is derived from Deborah Gordon’s work on ant decision-making and collective computation.

- Related to current research in swarm robotics, biologically inspired algorithms, and self-organization.

## 📚 License
This project is licensed under the MIT License.