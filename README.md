# EV-Charging-Demand-Prediction
As electric vehicle (EV) adoption continues to accelerate, urban planners must proactively assess and enhance infrastructure—especially the availability of charging stations. Insufficient preparation risks creating congestion and reducing user satisfaction, ultimately jeopardizing environmental targets.

📌 Problem Statement
Leverage historical data on EV registrations—including vehicle types, regional trends, and usage patterns—to develop a predictive model that forecasts future electric vehicle demand. This model will support strategic infrastructure decisions and sustainable growth planning.

🎯 Project Goal
Create a regression-based forecasting model that predicts future EV adoption by analyzing:

Monthly registration trends

Vehicle categories (passenger vs. truck)

Battery Electric Vehicles (BEVs) and Plug-in Hybrid Electric Vehicles (PHEVs)

County-level variations and regional factors

📊 Dataset Description
Source: Washington State Department of Licensing (DOL) Timeframe: January 31, 2017 – February 29, 2024 Granularity: Monthly counts by county

Key Variables:
Date: End-of-month timestamp for vehicle registration data

County: Residential location of vehicle owner

Vehicle Primary Use: Passenger (83%) and Truck (17%)

BEVs: Vehicles fully powered by onboard electric batteries

PHEVs: Vehicles partially powered by electric batteries

EV Total: Combined count of BEVs and PHEVs

Non-EV Total: Vehicles not classified as electric

Total Vehicles: All vehicles registered in each county

Percent EVs: Share of EVs relative to total registered vehicles
