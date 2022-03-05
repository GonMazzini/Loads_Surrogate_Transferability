# Transferability of turbine-based surrogate loads models to industrial siting applications. 

The project aims to explore the suitability of transfer learning for adapting loads surrogate models 
developed in academia for industrial siting applications. Transfer learning implies re-using of a pre-trained model on a new problem, for which less data is available wrt. to the database used for training
the original model. The sense behind transfer learning is to exploit knowledge gained from a previous 
task to improve generalization about another.


For this project, the starting model is based on the DTU 10 MW Reference Wind Turbine (trained 
with a high-fidelity database), and the main goal is re-training it to predict loads (focus on fatigue 
loads) on a new turbine type from Siemens Gamesa Renewable Energy (SGRE). 
