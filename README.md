# PROG101_ASSIGNMENT_JULIUS_ROGERS_905006607
this is assignment 1 for programming logic and design about a community flood early warning and alert system for freetown

## ABSTRACT
Freetown floods every rainy season, and the people who live in its low-lying and informal settlements
often receive no timely, location-specific warning before water enters their homes. This report
presents the logical design of SL-FloodWatch, a community-based flood early warning and alert
system that turns simple measurements (rainfall, river or drain level and the rate at which the level is
rising) into colour-coded SMS alerts that any mobile phone can receive. No source code is written.
Instead, the solution is designed through computational thinking (decomposition, pattern recognition,
abstraction and algorithm design), a step-by-step algorithm, pseudocode, three flowcharts, and a
modular structure of seven functions. The design applies constants, variables, data types, Boolean
logic, decision structures and repetition structures, and its behaviour is demonstrated with six sample
scenarios. The system supports Sustainable Development Goals 11, 13 and 9, and is proposed as an
Open Source Software project and a candidate Digital Public Good so that Sierra Leonean
communities, universities and agencies can adopt, translate and improve it freely. Version control
evidence for the project is provided through a GitHub repository.

## Keywords:
computational thinking, algorithm design, pseudocode, flowchart, flood early warning,
Open Source, Digital Public Goods, SDG 11, SDG 13, Sierra Leone.





























































# 1. RATIONALE
### 1.1 Problem Description 
The community problem. Freetown, the capital of Sierra Leone, experiences heavy rainfall from May to November, with annual totals that exceed 3,000 mm. Rainwater runs rapidly into streams and drainage channels that pass through densely populated settlements such as Kroo Bay, Susan’s Bay and Kolleh Town. Residents frequently discover the danger only when water is already in their homes. The core problem is therefore the absence of a timely, trusted and understandable flood warning that tells people what is happening in their own neighbourhood and what to do about it.
### Who is affected.
Residents of flood-prone and informal settlements are the most affected, particularly children, the elderly, people with disabilities, market traders and low-income households. Ward leaders, health facilities, the Freetown City Council and the National Disaster Management Agency (NDMA) are also affected because they must respond to emergencies with little advance information. 
### Why the problem exists.
Several causes combine: rapid urbanisation and building on floodplains and hillsides; blocked drains and solid waste; very few monitoring points at ward level; warnings that are general, late and mostly in English; and limited budgets for expensive proprietary systems. 
### How the proposed solution addresses it.
SL-FloodWatch collects simple readings from trained community volunteers or low-cost sensors, validates them, calculates how fast water is rising, classifies the risk using clear rules, and sends a colour-coded SMS to the registered residents of the affected ward. Because it relies on SMS, it works on basic phones without internet access.
## 1.2 Background 
On 14 August 2017 heavy rain triggered a mudslide and floods in the Western Area that killed more than one thousand people and destroyed homes and infrastructure (World Bank, GFDRR and Government of Sierra Leone, 2017). Flooding also increases waterborne diseases such as cholera. The Sendai Framework for Disaster Risk Reduction highlights multi-hazard early warning systems as a priority for reducing disaster losses (UNDRR, 2015), and the Sierra Leone National Innovation and Digital Strategy encourages digital solutions for national development (DSTI, 2019). Mobile phone use is widespread, which makes SMS an inclusive channel for public warnings.
 
