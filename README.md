# Carbon-project

With this project i was tasked with analysing a file for carbon dioxide emission(in metric tonnes)

The research questions were;

a)The industry type that had the most amount of CO2 emission in metric tonnes

b)The sector with highest amount of CO2 emission in metric tonnes.

c)Country and region with the most CO2 emission.

d)Region and country with the highest GDP in billion USD as aresult of the evolution of industries.

e)Region and country with the highest percentage of renewable energy.

-Firsty step was loading up the data for analysis;
#IMPORTING THE DATASET
import pandas as pd

import numpy as np

import matplotlib.pyplot as plt

import seaborn as sns

df = pd.read_csv('/content/Co2_Emissions_by_Sectors.csv')

df.head()

-From loading the data consequent analysis was done to ensure proper stucture of data and  null values were unavailable.

-After that visuals for the data were done to ensure that the users had a clear view of what was happening.

FINDINGS

From the research and analysis done the following findings were discovered;

1) Manufacturing industry had the largest amount of CO2 emmission in metric tonnes followed by cnstruction, energy and mining industries.

2) Brazil had the highest CO2 emmission in metric tonnes followed by Germany, Canada,India, USA,China and South Africa.

3) Oceania, Europe, South America, Africa, North America and Asian regions had the highest CO2 emmissions in terms of regions respectively.

4) Brazil, Australia, SA, Canada, Germany, India, USA and China had the highest GDP in billion USD as a result of evolution of industries.

5) Oceania region had the highest percentage of renewabe energy as compared to North America which had the least.

RECOMMENDATIONS

1) Transition to Renewable Energy: Given that Oceania has the highest percentage of renewable energy, other regions should prioritize transitioning to renewable energy sources like solar and wind power. This will help reduce CO2 emissions from manufacturing, construction, energy, and mining industries, which are major contributors to CO2 emissions.

Reasoning: Renewable energy sources produce little to no greenhouse gases, offering a sustainable alternative to fossil fuels.

2) Sustainable Manufacturing Practices: Manufacturing industries, being the largest CO2 emitters, need to adopt sustainable practices. This includes improving energy efficiency, using recycled materials, and reducing waste.

Reasoning: Implementing these practices will help minimize the environmental impact of manufacturing processes and contribute to lowering CO2 emissions.

3) Promote Public Transportation: Countries with high transport growth percentages, such as those in Oceania, should further promote and invest in public transportation systems. This can encourage a shift from private vehicles, reducing traffic congestion and CO2 emissions from transportation.

Reasoning: Public transportation is generally more energy-efficient per passenger than individual vehicles, thus reducing the overall carbon footprint.

4) Sustainable Construction: Construction industries should explore and adopt sustainable building materials and techniques. This includes using eco-friendly materials, optimizing building designs for energy efficiency, and minimizing construction waste.

Reasoning: Sustainable construction practices can significantly reduce the environmental impact of buildings, which are major consumers of energy and resources.

5) Carbon Capture and Storage: Research and development into carbon capture and storage technologies should be encouraged and supported. This can help mitigate CO2 emissions from industrial processes by capturing and storing CO2 emissions before they are released into the atmosphere.

Reasoning: Carbon capture and storage can play a crucial role in reducing emissions from industries that are difficult to decarbonize, such as cement production.

6) International Collaboration: Countries and regions should collaborate on sharing best practices, technologies, and policies related to CO2 emissions reduction. This can accelerate the global transition to a low-carbon economy.

THANK YOU

THE END

