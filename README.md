# 2401PTDS_Regression_Project

![](https://img.shields.io/badge/Python-3776AB.svg?style=for-the-badge&logo=Python&logoColor=white)

<div id="main image" align="center">
  <img src="https://github.com/marcmarais/2401FTDS_Regression_Project/blob/main/agri_image.png" width="450" height="300" alt=""/>
</div>

## Table of contents

* [1. Project Overview](#project-description)
* [2. Dataset](#dataset)
* [3. Packages](#packages)
* [4. Environment](#environment)
* [5. Team Members](#team-members)

## 1. Project Overview <a class="anchor" id="project-description"></a>

The purpose of this project is to analyze the dataset from the agri-food sector, using data from the Food and Agriculture Organization (FAO) and the Intergovernmental Panel on Climate Change (IPCC). The dataset focuses on greenhouse gas (GHG) emissions from the agri-food sector, which includes all activities involved in the production, processing, distribution, and consumption of food. This sector is a significant contributor to global GHG emissions, and understanding its impact is crucial for developing strategies to mitigate climate change.

## 2. Dataset <a class="anchor" id="dataset"></a>

The dataset focuses on greenhouse gas (GHG) emissions from the agri-food sector, which includes all activities involved in the production, processing, distribution, and consumption of food. This sector is a significant contributor to global GHG emissions, and understanding its impact is crucial for developing strategies to mitigate climate change.

**Dataset Features:**

- Savanna fires: Emissions from fires in savanna ecosystems.
- Forest fires: Emissions from fires in forested areas.
- Crop Residues: Emissions from burning or decomposing leftover plant material after crop harvesting.
- Rice Cultivation: Emissions from methane released during rice cultivation.
- Drained organic soils (CO2): Emissions from carbon dioxide released when draining organic soils.
- Pesticides Manufacturing: Emissions from the production of pesticides.
- Food Transport: Emissions from transporting food products.
- Forestland: Land covered by forests.
- Net Forest conversion: Change in forest area due to deforestation and afforestation.
- Food Household Consumption: Emissions from food consumption at the household level.
- Food Retail: Emissions from the operation of retail establishments selling food.
- On-farm Electricity Use: Electricity consumption on farms.
- Food Packaging: Emissions from the production and disposal of food packaging materials.
- Agrifood Systems Waste Disposal: Emissions from waste disposal in the agrifood system.
- Food Processing: Emissions from processing food products.
- Fertilizers Manufacturing: Emissions from the production of fertilizers.
- IPPU: Emissions from industrial processes and product use.
- Manure applied to Soils: Emissions from applying animal manure to agricultural soils.
- Manure left on Pasture: Emissions from animal manure on pasture or grazing land.
- Manure Management: Emissions from managing and treating animal manure.
- Fires in organic soils: Emissions from fires in organic soils.
- Fires in humid tropical forests: Emissions from fires in humid tropical forests.
- On-farm energy use: Energy consumption on farms.
- Rural population: Number of people living in rural areas.
- Urban population: Number of people living in urban areas.
- Total Population - Male: Total number of male individuals in the population.
- Total Population - Female: Total number of female individuals in the population.
- total_emission: Total greenhouse gas emissions from various sources.
- Average Temperature °C: The average increasing of temperature (by year) in degrees Celsius,

CO2 is recorded in kilotonnes (kt): 1 kt represents 1000 kg of CO2.

The feature "Average Temperature C°", represents the average yearly temperature increase. For example, if it is 0.12, it means that the temperature in that specific location increased by 0.12 degrees Celsius.

Forestland is the only feature that exhibits negative emissions due to its role as a carbon sink. Through photosynthesis, forests absorb and store carbon dioxide, effectively removing it from the atmosphere. Sustainable forest management, along with afforestation and reforestation efforts, further contribute to negative emissions by increasing carbon sequestration capacity.

## 3. Packages <a class="anchor" id="packages"></a>

To carry out all the objectives for this repo, the following necessary dependencies were loaded:

+ `pandas 2.1.4`
+ `numpy 1.26.4`
+ `matplotlib 3.9.1`
+ `seaborn 0.13.2`
+ `scikit-learn 1.5.1`
+ `statsmodels 0.14.2`
+ `xgboost 2.0.3`

The libraries and their dependencies are listed in [requirements.txt](./requirements.txt)

## 4. Environment <a class="anchor" id="environment"></a>

If you do not already have a virtual environment for python, install Anaconda, a powerful package and environment management system:
[Download Anaconda](https://www.anaconda.com/download)


Follow these instructions to set up your python virtual environment using conda and install all the dependencies easily:

### Create the new environment:

```bash
# create the conda environment
conda create --name <env>
```

### Activate the virtual environment in a terminal and install the project dependencies:

```bash
# activate the virtual environment
conda activate <env>

# install the pip package
conda install pip

# install the requirements for this project
pip install -r requirements.txt
```

## 5. Team Members <a class="anchor" id="team-members"></a>

- [Muhammad Seedat](https://github.com/maseedatM5)
- [Sharon Rangwato](https://github.com/Noni1030)
- [Tim Fleur](https://github.com/timfleur)
- [Tyrelle Brandt](https://github.com/TyrelleBrandt)
- [Glen Adams](https://github.com/glenad)

