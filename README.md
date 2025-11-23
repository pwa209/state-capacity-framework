# **State vs. Capacity Toy Model**

This repository contains the interactive companion code for the paper:  
"State and Capacity in Neural Models of Cognition and Consciousness: A Two-Axis, Testable Framework"  
This toy model demonstrates the core theoretical dissociation proposed in the framework:

1. **Structural Capacity (The Hardware):** Slow, architectural changes (e.g., layer depth, hidden size) that determine the "ontological limit" of the system.  
2. **Computational State (The Software):** Fast, reversible modulation (e.g., gain, noise) that determines the operating regime within those limits.

## **The Interactive App**

The included Streamlit app allows users to:

* **Train** a Recurrent Neural Network (RNN) with varying structural capacities (Depth/Width) on a non-linear wave task.  
* **Modulate** the trained network's state (Gain/Noise) in real-time to observe performance shifts without retraining.  
* **Visualize** how high capacity is necessary but not sufficient for performance (i.e., a "high capacity" brain can fail in a "low gain" state).

## **Installation**

1. Clone this repository:  
   git clone \https://github.com/pwa209/state-capacity-framework
   cd state-capacity-framework

2. Install dependencies:  
   pip install \-r requirements.txt

## **Usage**

Run the application locally:

streamlit run app.py

*(Note: If you renamed the script, use that filename instead, e.g., streamlit run state\_vs\_capacity\_explorer.py)*

## **Scientific Interpretation**

The app mimics the two axes described in the paper:

* **Capacity Axis:** Corresponds to developmental or evolutionary timescales. Changing the slider for "Hidden Units" requires pressing "Train" again, simulating the cost of structural growth.  
* **State Axis:** Corresponds to neuromodulatory or attentional timescales. Changing "Global Gain" updates the plot instantly, simulating the rapid reconfiguration of dynamics.

## **Citation**

If you use this framework or code, please cite:

\[Insert Paper Citation Here\]

## **License**

MIT License
