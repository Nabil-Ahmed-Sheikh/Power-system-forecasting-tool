Traditional software for power system planning perform power flow analysis using user-defined generation dispatches and
demands. However, these software lack the capability to forecast generation and demand and optimize power flow while
respecting transmission system constraints within the same tool. Many jurisdictions around the world are seeking tools with these
integrated robust capabilities to plan the transmission system more efficiently and optimally. The objective of this project is to
develop a software tool that forecasts generation and demand and optimizes power flow to minimize total system production cost
while respecting transmission system constraints.

The outcome or end-product of this project will be an integrated software tool that can forecast generation and system demand
and perform security-constrained optimal power flow (SCOPF) for a power system model.
For the forecasting portion, generation dispatch of renewable generators, such as wind and solar generation, and system demand
will be forecasted using Python. The project will consider different machine learning techniques such as random forest, gradient
boosting, neural network, etc. and will pick the algorithm that has the lowest forecast error.
For the security-constrained optimal power flow (SCOPF) portion, an optimization model will be developed using Python and
Gurobi optimizer. The objective of this optimization will be to minimize total system production cost, and the model will be
subject to constraints, such as DC power flow equation constraints and line thermal rating constraints. The forecasting algorithm
will be integrated with the optimization tool so that the optimization model can directly use the forecasted renewable generation
and system demand data while solving the model.
The optimization tool will provide a dynamic method for identifying transmission system deficiencies by indicating the limiting
transmission lines causing congestion in the power system. Furthermore, the tool will generate a quantitative summary of the cost
impacts due to congestion so that the transmission system can be planned economically. A single-line diagram of the model will
be prepared using commercially or publicly available tools to visualize the results from the developed forecasting and optimization
tool.
