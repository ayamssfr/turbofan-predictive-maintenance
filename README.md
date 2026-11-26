# ✈️ Turbofan Predictive Maintenance

Predicting the Remaining Useful Life (RUL) of aircraft turbofan engines using machine learning.

🚧 **Work in progress**

## Goal
Forecast engine degradation from sensor data, then recommend when maintenance should happen, before failure.

## Dataset
[NASA C-MAPSS](https://data.nasa.gov/) — simulated run-to-failure data from turbofan engines (21 sensors, 3 operating settings).

## Roadmap
- [ ] Data exploration and visualisation
- [ ] Baseline model (linear regression / random forest)
- [ ] Advanced model (LSTM)
- [ ] Evaluation on unseen test engines (RMSE)
- [ ] Maintenance recommendation from predicted RUL
- [ ] C++ inference module (ONNX Runtime) — closer to embedded avionics constraints

## Tech
Python · pandas · scikit-learn · PyTorch · C++ · ONNX
