# Smart India Hackathon Workshop
## Name: HARI PRASATH E
## Reg No: 25007799
# Date: 24-09-2025
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
The proposed solution is a **Smart Crop Advisory System** that helps farmers make better decisions using digital tools.  
It brings together crop advisory, soil and weather analysis, pest detection, and market insights into one platform.

- Provides **personalized crop guidance** using soil data and weather updates.  
- Helps address common issues faced by farmers such as unpredictable weather, pest attacks, and unstable market prices.  
- **Unique feature**: combines AI-driven pest detection with multilingual support, making it farmer-friendly and easy to use.  
- Ensures that even rural farmers with limited digital literacy can benefit from the service via mobile apps and USSD.  

---

## Technical Approach
The system uses a modular design with different services connected through an API Gateway.

- **Technologies**  
  - Backend: Python (Django/Flask)  
  - Frontend: JavaScript (React)  
  - Databases: PostgreSQL, MongoDB, Redis/Cloud Storage  
  - AI/ML: For pest and disease detection from images  
  - APIs: Weather updates, market price feeds  

- **Methodology**  
  1. Farmers use the **mobile app or USSD service** to raise queries.  
  2. Requests go through an **API Gateway** for routing and authentication.  
  3. The request is sent to the right **backend service** (crop advisory, pest detection, weather/soil, market monitoring).  
  4. Each service connects to its own **database** for storing and retrieving information.  
  5. The processed result is sent 
## Feasibility and Viability

### Feasibility
The system is realistic since it uses already available technologies, cloud platforms, and APIs.  
It requires moderate infrastructure and can be scaled as needed.

---

### Challenges
- Poor internet connectivity in rural regions.  
- Farmers not fully comfortable with smartphone apps.  
- High accuracy needed for AI-based pest detection.  

---

### Solutions
- **USSD support** for non-smartphone users.  
- **Multilingual simple UI** for ease of use.  
- **Collaboration with agricultural research institutions** for reliable datasets.  

---

## Impact and Benefits

### Impact on Farmers
Farmers gain quick access to reliable crop advice and market updates.  

### Social Benefits
Builds confidence among farmers by giving them direct access to information, reducing dependence on intermediaries.  

### Economic Benefits
- Higher crop yields due to better planning.  
- Better income by selling at favorable times and markets.  

### Environmental Benefits
- Reduced overuse of pesticides and fertilizers.  
- Prevents large-scale crop loss through early disease detection.  
## flowchart
<img width="1123" height="347" alt="smart_crop_advisory_flowchart_clear" src="https://github.com/user-attachments/assets/e84f1f4d-94b6-472a-be6d-686bee202d36" />

---

## Research and References
- [NABARD Annual Report 2022](https://www.nabard.org/)  
- [Indian Agricultural Research Institute (ICAR)](https://www.icar.org.in/)  
- [FAO – ICT in Agriculture](https://www.fao.org/ict4ag/en/)  
- [Government of India – Agri-Tech Initiatives](https://agricoop.gov.in/)  
