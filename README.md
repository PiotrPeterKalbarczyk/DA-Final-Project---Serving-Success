# Serving Success: A Data-Driven Approach to Identifying Prime Restaurant Locations in Berlin

## Objective:

The objective of this project is to apply data analytics and geospatial insights to identify Berlin districts with the strongest potential for launching a new restaurant and support location-based business decisions in the hospitality industry.



The analysis began with a broad exploration of restaurant density and demographics across all 12 Berlin districts. To bring the findings into a business context, I introduced a hypothetical use case: a prospective entrepreneur is considering opening a **Greek restaurant**. The project then focused on identifying areas where this specific cuisine could thrive, based on saturation, cultural fit, and local demand.

---

## Summary of Insights

### District Filtering
- Analyzed over **3,500 restaurants** and population data across **12 Berlin districts**.
- Found that restaurant count is not always proportional to population size — some densely populated areas have relatively few restaurants.
- To address this, calculated **restaurant density per km²** and **per capita**, revealing more nuanced hotspots.
- Combining population, restaurant density, and area size, the top-performing districts were: **Mitte, Charlottenburg, Kreuzberg**, and **Schöneberg**, with **Pankow** also showing potential for growth.

![Anna1](./04_Reveal_js/assets/09_Anna_Scatter.jpg)

### Cultural Cuisine Patterns

- Compared restaurant locations with migrant population data across Berlin.
- Found that ethnic restaurants don’t always appear in districts with the highest migrant presence.
- However, migrant populations tend to influence **directional clustering** of their cuisines — certain areas become hotspots even without a direct population match.
- This suggests that cultural presence acts as a **spatial signal**, while other factors like tourism and gentrification shape final restaurant placement.


*The upper row represents number of restaurants and lower row the population of certain migrant group.*  
![Maps](./04_Reveal_js/assets/08_Maps.jpg)

### Greek Cuisine Case Study

- Using prior filtering, reduced the initial shortlist of five districts to four, excluding **Pankow** due to a lack of alignment with the Greek population distribution.
- Analyzed the share of **Greek cuisine**, which represents **~3%** of all restaurants in Berlin — indicating a niche but notable presence.
- **Charlottenburg (4.5%)** and **Schöneberg (3.0%)** have the highest concentration of Greek restaurants, suggesting these areas are already saturated and may present higher competition.
- **Kreuzberg (1.7%)** and **Mitte (1.9%)**, on the other hand, show significantly lower saturation, offering potential for **market entry and growth**.
- These districts also align partially with areas of higher **Greek population density**, which may support authenticity, community presence, and cultural relevance.


## Recommendations

- **Avoid Schöneberg and Charlottenburg** for Greek cuisine due to high market saturation.
- **Prioritize Mitte and Kreuzberg**, where demand exists and competition is lower.
- Mitte is also Berlin’s **top tourist district**, which may boost foot traffic but also implies **higher rent**, an important trade-off to consider.
- Factor in **access to transport hubs and population density** when selecting the final location.

---

## Tech Stack

- **QGIS** – mapping and polygon analysis
- **PostgreSQL (PostGIS)** – spatial data cleaning and querying
- **SQLAlchemy** – PostgreSQL connection for dynamic querying
- **Tableau** – demographic and cuisine-level visualization

---

📄 *For a more detailed walkthrough of the analysis process, see* [README_longer_analysis.md](./README_longer_analysis.md).

