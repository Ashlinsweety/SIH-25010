# Smart India Hackathon Workshop
# Date:30.09.2025
## Register Number:25011333
## Name:R.Ashlin 
## Problem Title
SIH 25010: Smart Crop Advisory System for Small and Marginal Farmers
## Problem Description
A majority of small and marginal farmers in India rely on traditional knowledge, local shopkeepers, or guesswork for crop selection, pest control, and fertilizer use. They lack access to personalized, real-time advisory services that account for soil type, weather conditions, and crop history. This often leads to poor yield, excessive input costs, and environmental degradation due to overuse of chemicals. Language barriers, low digital literacy, and absence of localized tools further limit their access to modern agri-tech resources.

Impact / Why this problem needs to be solved

Helping small farmers make informed decisions can significantly increase productivity, reduce costs, and improve livelihoods. It also contributes to sustainable farming practices, food security, and environmental conservation. A smart advisory solution can empower farmers with scientific insights in their native language and reduce dependency on unreliable third-party advice.

Expected Outcomes

• A multilingual, AI-based mobile app or chatbot that provides real-time, location-specific crop advisory.
• Soil health recommendations and fertilizer guidance.
• Weather-based alerts and predictive insights.
• Pest/disease detection via image uploads.
• Market price tracking.
• Voice support for low-literate users.
• Feedback and usage data collection for continuous improvement.

Relevant Stakeholders / Beneficiaries

• Small and marginal farmers
• Agricultural extension officers
• Government agriculture departments
• NGOs and cooperatives
• Agri-tech startups

Supporting Data

• 86% of Indian farmers are small or marginal (NABARD Report, 2022).
• Studies show ICT-based advisories can increase crop yield by 20–30%.

## Problem Creater's Organization
Government of Punjab

## Theme
Agriculture, FoodTech & Rural Development

## Proposed Solution
- Uses satellite data and IoT sensors (where feasible) for precision.
- Uses NDVI, EVI, and soil moisture maps to monitor crop health and land conditions.
- Provides weather forecasts and agro-climatic insights.
- IoT Sensor Deployment (Where Feasible)
- Soil sensors measure moisture, pH, and temperature.
- Weather stations track rainfall, humidity, and wind speed.
- Data feeds into advisory engine for hyperlocal precision.


## Technical Approach
- Satellite Data:
- NDVI, EVI for crop health
- Soil moisture and temperature maps
- Rainfall and weather forecasts
- IoT Sensors (where feasible):
- Soil moisture, pH, temperature, NPK levels
- Microclimate data (humidity, wind speed)
- Pest detection via image sensors
- IoT devices send data via GSM, LoRaWAN, or Wi-Fi
- Satellite data accessed via APIs (e.g., ISRO BHUVAN, Sentinel Hub)
Flowchart:
        +------------------------+
        |  Farmer Registration   |
        +------------------------+
                  ↓
        +------------------------+
        |  Data Collection Layer |
        |  - Satellite APIs      |
        |  - IoT Sensors         |
        +------------------------+
                  ↓
        +------------------------+
        |  Data Transmission     |
        |  - GSM/LoRa/Wi-Fi      |
        +------------------------+
                  ↓
        +------------------------+
        |  Cloud Storage & ETL   |
        |  - Real-time ingestion |
        +------------------------+
                  ↓
        +------------------------+
        |  Analytics Engine      |
        |  - ML Models           |
        |  - Rule-Based Logic    |
        +------------------------+
                  ↓
        +------------------------+
        |  Advisory Generation   |
        |  - Crop Suggestion     |
        |  - Input Scheduling    |
        |  - Pest Alerts         |
        +------------------------+
                  ↓
        +------------------------+
        |  Delivery Channels     |
        |  - App / SMS / IVR     |
        |  - Chatbot / Kiosk     |
        +------------------------+


## Feasibility and Viability
feasibility
- Satellite data is freely available from ISRO, NASA, and Copernicus platforms.
- IoT sensors (soil moisture, temperature, pH) are increasingly affordable and solar-powered.
- GSM, LoRaWAN, and Wi-Fi enable sensor connectivity in rural areas.
- Cloud platforms (AWS, Azure) support scalable data processing and storage.
- Mobile apps and SMS/IVR systems ensure delivery to farmers with varying tech access.
Operational Feasibility
- Sensors can be deployed at village level for shared use, reducing cost per farmer.
- Extension workers and NGOs can assist with training and maintenance.
- Multilingual, voice-enabled interfaces improve usability for low-literacy users.
- Advisory content can be localized based on agro-climatic zones.
 Economic Feasibility
- Satellite data is free; IoT sensors can be subsidized or shared.
- Government schemes (e.g., Digital India, PM-Fasal Bima Yojana) support tech adoption.
- Freemium models and partnerships with agri-input firms can sustain operations.

 Viability
 Social Viability
- Targets smallholders who form over 85% of India’s farming population.
- Reduces dependency on middlemen and empowers farmers with timely decisions.
- Encourages inclusion of women and marginalized communities.
   Environmental Viability
- Promotes precision irrigation and fertilization, reducing resource waste.
- Supports climate-resilient farming through real-time alerts and adaptive cropping.
- Encourages sustainable practices like organic inputs and soil conservation.
   Scalability & Sustainability
- Modular system design allows regional customization and expansion.
- Feedback loop enables continuous learning and model improvement.
- Proven success of similar agri-tech platforms (e.g., Kisan Suvidha, AgriApp) shows strong adoption potential.





## Impact and Benefits
Impacts
- Improved Crop Productivity
Precision recommendations based on real-time data lead to better yields.
- Reduced Input Costs
Optimized use of water, fertilizers, and pesticides lowers expenses.
- Climate Resilience
Early warnings and adaptive advice help farmers manage droughts, floods, and erratic weather.
- Informed Decision-Making
Farmers gain access to scientific insights previously unavailable to them.
- Digital Inclusion
Empowers low-literacy and remote farmers through voice-enable
Benefits
- Hyperlocal Advisory
Tailored to each farm’s soil, weather, and crop conditions.
- Timely Alerts
Real-time notifications for irrigation, pest outbreaks, and weather changes.
- Sustainable Farming
Promotes eco-friendly practices and reduces environmental impact.
- Market Optimization
Suggests best harvest times and connects farmers to buyers for better prices.
- Scalability
Can be expanded across regions with minimal infrastructure.



## Research and References
 Satellite Data
- ISRO BHUVAN Portal
- Provides free satellite imagery and agro-climatic data for Indian agriculture.
- Useful for crop health monitoring, rainfall analysis, and land use mapping.
- Copernicus Sentinel (European Space Agency)
- Offers high-resolution multispectral data for vegetation indices like NDVI and EVI.
- Supports crop stress detection and soil moisture estimation.
- NASA MODIS & Landsat Programs
- Widely used for remote sensing in agriculture.
- Enables large-scale monitoring of crop growth and environmental conditions.
- "Application of Remote Sensing in Precision Agriculture" – Journal of Remote Sensing & GIS
- Highlights how satellite data improves decision-making in crop planning and input management.

IoT Sensors
- "IoT-Based Smart Farming System for Indian Agriculture" – IJERT
- Discusses deployment of soil and weather sensors for real-time advisory.
- Emphasizes affordability and scalability for small farms.
- "Smart Agriculture Using IoT and Machine Learning" – JETIR, 2024
- Demonstrates how IoT sensors combined with ML models enhance crop prediction and input efficiency.
- FAO Report: Digital Agriculture in India
- Explores the role of IoT and satellite data in improving productivity and resilience for smallholders.
- Recommends community-based sensor models for cost-effective deployment.

