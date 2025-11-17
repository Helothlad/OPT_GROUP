🌿 Menorca Biodiversity Conservation Optimization
📋 Project Overview
This project applies Integer Linear Programming (ILP) and quantitative analysis to support the design of biodiversity conservation strategies in Menorca, a UNESCO Biosphere Reserve.

Acting as the Analytics Department of the Consell Insular de Menorca, the goal is to optimize decision-making regarding wildlife conservation in a landscape fragmented by anthropogenic pressures.

🎯 Objectives
The primary objective is to design an optimization model that allocates limited economic resources to improve the conservation prospects of four focal terrestrial species:

🦔 Atelerix algirus (Algerian Hedgehog)

🦦 Martes martes (Pine Marten)

🐭 Eliomys quercinus (Garden Dormouse)

🐇 Oryctolagus cuniculus (European Rabbit)

The optimization strategies focus on two key interventions:

Wildlife Corridors: Establishing connections between isolated population patches to ensure genetic connectivity and prevent inbreeding.

Habitat Expansion: Modifying adjacent lands (e.g., agricultural areas) to make them ecologically suitable for specific species.

🗂️ Data
The analysis uses a discretized grid map of Menorca provided in dataset.geojson. Each cell contains attributes such as:

Grid ID: Unique identifier.

Dominant Land Cover: e.g., Forests, Urban Fabric, Agriculture.

Species Presence: Boolean flags for the four focal species.

Costs: Adaptation costs for specific species and construction costs for corridors.

🛠️ Technologies & Tools
Language: Python

Optimization Solver: Google OR-Tools (CP-SAT)

Geospatial Analysis: GeoPandas, Shapely

Visualization: Folium, Matplotlib

🚀 Methodology
The project is divided into two main phases:

Analysis & Modeling:

Qualitative and quantitative analysis of the provided geospatial data.

Formal definition of the optimization problem using mathematical notation (Decision variables, Constraints, Objective Function).

Implementation:

Programming the ILP model using OR-Tools.

conducting computational experiments to assess solver performance and scalability.

📊 Scenario
Menorca's landscape is a mosaic of agricultural land, forests, and urban settlements. The project models the coexistence of species with varying ecological needs—for example, managing the predatory relationship between the Pine Marten (Martes martes) and smaller mammals like the Dormouse (Eliomys quercinus). The final model aims to be adaptable to other species and islands within the Balearic archipelago.
