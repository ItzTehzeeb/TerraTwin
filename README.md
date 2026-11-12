<img src="assets\TerraTwin transparent logo.png" height="140px" width="140px"></img>
# TerraTwin

### _Turning Earth into a training map for space exploration. TerraTwin is a data-driven web application that calculates the similarity between locations on Earth and target destinations on the Moon and Mars. Built for the NASA Space Apps Challenge 2026, TerraTwin helps mission planners identify the best terrestrial analogs for testing space hardware, preventing mission failures caused by inadequate Earth-based testing._

## Table of Contents
- The Challenge
- Our Solution
- Features
- NASA Data Sources Used
- AI Usage Disclosure
- The Team

## The Challenge
Selecting future landing sites and lunar base locations depends on many factors.
Future missions to Mars and the Moon rely on testing equipment in environments on Earth that mimic extraterrestrial conditions. However, NASA's current database of analog sites is incomplete, fragmented, and hasn't been updated since 2011. Mission planners lack a unified, data-driven tool to rigorously compare Earth sites to planetary targets.

## Our Solution
TerraTwin is an interactive dashboard that scores Earth locations against planetary targets.

By selecting a target, users can see a ranked leaderboard of Earth analogs. The app calculates a Percentage Similarity Score across five key metrics:

1. Aridity
2. Temperature Swing
3. Elevation
4. Terrain Type
5. Mineralogy
Instead of just displaying numbers, TerraTwin breaks down the score to show why a site is a strong match, what it lacks, and how it can be used to test specific hardware.

## Featured Earth Analogs
While TerraTwin includes well-known sites like the Atacama Desert, Death Valley, and McMurdo Dry Valleys, our team also identified and characterized a lesser-known, highly promising analog: the Danakil Depression (Ethiopia).

## Features
- **Target Selection:** Choose from multiple planetary targets (Mars/Moon).
- **Dynamic Leaderboard:** Instantly ranks Earth analogs from most similar to least.
- **Metric Breakdown:** View percentage matches for specific criteria (e.g : how closely the Atacama's aridity matches Jezero Crater).
- **Insights & Gaps:** Highlights an analog's strong matches alongside its limitations (what it lacks).

## NASA Data Sources Used
TerraTwin is built entirely on open, verifiable data. The following datasets were used to calculate our similarity metrics:

- **NASA Earthdata:** Used for Earth-based elevation models and land surface temperature.
- **NASA Planetary Data System (PDS):** Used for Martian and Lunar target comparisons (Jezero Crater, Lunar South Pole).
- **USGS Astrogeology:** Used for terrestrial analog mineralogy mapping.

## AI Usage Disclosure
In accordance with NASA Space Apps guidelines, we disclose the use of AI in our project:

- **Tool Used:** Claude AI (by Anthropic)
- **Reason for Use:** We used Claude AI to accelerate our development, because our team's focus was on the scientific research, data validation, and NASA dataset integration, we used AI to handle the repetitive boilerplate code and establish the initial structural foundation of the web app.
- **Prompts Used:** We prompted Claude with requests such as: "Generate a responsive HTML/CSS template for a dashboard with a sidebar for planetary target selection and a main grid for analog results," and "Write the foundational HTML structure for a web app with an interactive leaderboard."
- **Where it was used:** Claude was used to generate the initial UI layout, foundational HTML code, and the outer structure of the application.

- **Our Own Original Work:** The AI did not write our core scientific logic, the TerraTwin similarity scoring algorithms, or the data processing scripts. All NASA data integration, the geological research for the Danakil Depression, the mathematical calculations for the percentage similarity scores, and the final custom styling and debugging were done entirely by our team members.


## The Team (AURORA:002)
We are a team of six students from Dhaka, Bangladesh, participating in the NASA Space Apps Challenge 2026.

- Nawaaf Mahbeer Nibras
- Tehzeeb Kabir
- Rukaiya Tasneem
- Arham Majid
- Mahadi Fatema Adrita
- Rayna Janan

Built with ❤️ for the NASA Space Apps Challenge 2026. Turning Earth into a training map for the cosmos.

