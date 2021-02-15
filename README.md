# Metabolic-Crosstalk <br>
## Author <br>
Elias Siguenza <br>
Tennant Laboratory <br>
Institute of Metabolic and Systems Research <br>
College of Medical and Dental Sciences <br>
School of Mathematics <br>
University of Birmingham <br>
England, United Kingdom <br>
e.vera-siguenza@bham.ac.uk <br>
<br>

This repository contains the code for the preliminary mathematical model for investigating multicellular crosstalk. <br>
Briefly, it is a type of constraint-based model (CBM), which only accounts for reaction stoichiometry and reversibility <br>
under the assumption of steady-state whilst using an underdetermined formulation. <br>
<br>
This results in a continuous reaction flux distribution space, at the expense of losing all knowledge of transient behaviours or metabolite concentrations. However, additional conditions are imposed to determine unique solutions (e.g. flux distributions) and testable predictions. Through conical optimisation, and relying on a particular objective; such as cellular biomass growth, it is possible to restrict the model to a subset of feasible kinetic solutions, known as the "flux hyper-cone". <br>

The model is intended as an “in- silico” tool capable of producing testable predictions, on the nature of metabolite exchange between two types of cells and their ultimate fate. Through a series of “in-silico” genetic knockouts and knockdowns, along with the targeting of the system’s metabolic phenotype, we will be able to identify enzymes or transporters that represent important hubs, the inhibition of which would result in a complete breakdown of the cellular community. <br>

The code makes use of the MATLAB COBRA package available here: https://opencobra.github.io/cobratoolbox/stable/ <br>
The Gurobi Optimisation Package, whose license can be obtained at: https://www.gurobi.com/ <br>
The IBM Optimisation Package (CPLEX Studio), whose license can be obtained at: https://www.ibm.com/uk-en/products/ilog-cplex-optimization-studio <br>

Files:
This repository, as of its latest version contains:

Schematich diagram of the model.
Schematic diagram of the metabolic network in the Myeloma cell.
Schematic diagram of the metabolic network inn the BMMS cell.
A MATLAB .m file (script) with the model (where instructions are further provided).
About
Multiple Myeloma

