# Climate, Economic Inequality, and Malaria Incidence: A Comparative Analysis

![Python](https://img.shields.io/badge/Python-3.9-blue.svg)  
![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)  
![Made with Colab](https://img.shields.io/badge/Made%20with-Google%20Colab-orange)  
![Data Sources](https://img.shields.io/badge/Data-WHO%20%7C%20World%20Bank%20%7C%20Climate%20Portal-lightgrey)

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1xk-ssvVu6Xt12-ILYX2zNBDjWJW-qs8o?usp=sharing)

---

## Overview

This project explores the relationship between **economic inequality**, **climate change**, and **malaria incidence** across two countries: **Nigeria** and **Madagascar**. It investigates how economic and environmental variables interact to influence the burden of malaria and healthcare outcomes.

---

## Research Questions

- To what extent does economic inequality affect vulnerability to climate change-induced malaria outbreaks?  
- How do economic and climate factors jointly influence malaria incidence and healthcare costs across regions?

---

## Data Sources

- **Malaria Incidence**: World Health Organization (WHO)  
- **Economic Data (GDP)**: World Bank  
- **Climate Data (Temperature)**: Climate Change Knowledge Portal

---

## Tools & Libraries

- **Google Colab** (Python 3.9)  
  - `pandas`  
  - `NumPy`  
  - `SciPy` (`scipy.stats`)  
  - `Matplotlib`  
  - `Seaborn`

---

## Methods

- Collected 20+ years of data on malaria incidence, GDP, and average annual temperature for **Nigeria** and **Madagascar**  
- Conducted **correlation analysis** and **hypothesis testing** using `scipy.stats`  
- Visualized data with **heatmaps** and **line plots** using `Matplotlib` and `Seaborn`

---

## Key Findings

- **Malaria incidence increased more in Madagascar** than in Nigeria from 2002 to 2022  
- No statistically significant correlation was found between **GDP** changes and malaria incidence  
- **Temperature trends** did not significantly predict malaria cases across either country

---

## Conclusion

Although this study does not establish a definitive link between economic inequality and climate change-induced malaria outbreaks, it does show that **Madagascar has experienced a greater increase in malaria incidence** over the past 20 years compared to Nigeria. This suggests that localized factors—potentially including healthcare infrastructure, climate variability, or vector control efforts—may play a critical role.

**Key Observations:**
- Heatmaps revealed country-specific trends in malaria incidence.  
- GDP may not be a sufficient standalone metric for economic inequality—future studies should explore alternative measures.

---

## Future Studies

To build on this analysis, future research could explore:
- Expanding the dataset to include **more country pairs** with contrasting GDP levels and similar climates  
- Studying the **availability and effectiveness of malaria prevention strategies** (e.g., bed nets, indoor spraying, vaccines)  
- Using **machine learning or deep learning models** to predict malaria incidence based on socioeconomic and climate features  
- Analyzing the **biological impact of rising temperatures on mosquito ecology**, including breeding sites, transmission rates, and life cycles

---

## References

1. **DataBank: World Development Indicators.** March 10, 2023. [World Bank](https://databank.worldbank.org/source/world-development-indicators#)

2. **Jordan, Rob.** "How Does Climate Change Affect Disease?" *Stanford Earth*, March 15, 2019. [Link](https://earth.stanford.edu/news/how-does-climate-change-affect-disease)

3. **Mabaso, Musawenkosi L. H., et al.** "El Niño Southern Oscillation (ENSO) and Annual Malaria Incidence in Southern Africa." *Transactions of the Royal Society of Tropical Medicine and Hygiene*, vol. 101, no. 4, 2007, pp. 326–330. [DOI:10.1016/j.trstmh.2006.07.009](https://dx.doi.org/10.1016/j.trstmh.2006.07.009)

4. **World Health Organization.** "Malaria Burden Data: Cases and Deaths." April 13, 2023. [WHO](https://www.who.int/data/gho/data/themes/topics/topic-details/GHO/malaria-cases-deaths)

5. **Matundura Ogega, Obed, et al.** *Impact of 1.5°C and 2°C Global Warming Scenarios on Malaria Transmission in East Africa* [Version 3; Peer Review: 2 Approved], 2020.

6. **Sachs, Jeffrey, and Pia Malaney.** "The Economic and Social Burden of Malaria." *Insight Review Articles*, vol. 415, 2002.

7. **World Bank Climate Change Knowledge Portal.** [Link](https://climateknowledgeportal.worldbank.org/download-data)

---

## Presentation

You can view the project presentation here:  
[📎 Project Slide Deck (Google Slides)](https://docs.google.com/presentation/d/15e9HRNgzEHzPqRU5rjCFQB5xtJHsbjZv/edit?usp=sharing&ouid=102535417028323473788&rtpof=true&sd=true)

