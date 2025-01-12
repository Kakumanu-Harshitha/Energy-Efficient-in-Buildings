# Energy-Efficient-Buildings

The ENB (Energy Efficiency Building) dataset is designed for studies involving the energy efficiency of buildings. It includes data related to the heating and cooling loads of buildings based on various architectural and material properties.

# Description:
The dataset is often used in regression tasks where the goal is to predict the heating load (Y1) or cooling load (Y2) of a building based on its features.
It contains 768 samples.
Each sample corresponds to a building with specific architectural and design properties.
# Features :
The dataset consists of 8 input features and 2 target variables:

Input Features
X1: Relative Compactness 

A measure of how compact the building is (dimensionless).
Higher values typically indicate more compact structures.
X2: Surface Area

Total external surface area of the building 
X3: Wall Area

Total area covered by walls (in 
𝑚
2
m 
2
 ).
X4: Roof Area

Total roof area of the building (in 
𝑚
2
m 
2
 ).
X5: Overall Height

The height of the building (in 
𝑚
m).
X6: Orientation

Represents the direction the building faces:
Encoded as 2, 3, 4, or 5.
X7: Glazing Area

The proportion of the building's surface covered by glazing (e.g., windows) (dimensionless).
X8: Glazing Area Distribution

Describes how the glazing area is distributed across different orientations:
Encoded as 0 (no glazing), 1 (equally distributed), 2 (north), 3 (east), 4 (south), or 5 (west).
Target Variables
Y1: Heating Load

Energy required to maintain the building's internal temperature during colder months (in 
𝑘
𝑊
ℎ
/
𝑚
2
kWh/m 
2
 ).
Y2: Cooling Load

Energy required to maintain the building's internal temperature during warmer months (in 
𝑘
𝑊
ℎ
/
𝑚
2
kWh/m 
2
 ).
