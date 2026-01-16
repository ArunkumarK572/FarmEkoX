# Smart Crop Advisory System for Small and Marginal Farmers
Problem Statement Number: SIH25010

Domain: Agriculture, FoodTech & Rural Development  
Mapped SDG: SDG 2 – Zero Hunger  
Organization: Government of Punjab

---

Capstone Project – Review 1

Course: CSE Capstone Project  
Department: Computer Science & Engineering

Submitted By:  
- Student Name 1 – Roll No  
- Student Name 2 – Roll No

Under the Supervision of:  
- Guide Name

Institution Name  
Academic Year: 2025–26

---

## Project Overview
Small and marginal farmers often rely on traditional practices or local advice for crop selection, pest control, and fertilizer use. This leads to suboptimal yields, higher input costs, and environmental harm. The Smart Crop Advisory System (FarmEkoX) provides a unified, mobile-first solution delivering personalized, localized, and accessible crop advisory services using real-time data, rule-based logic, and AI-driven assistance in local languages.

---

## Problem Statement
Many small and marginal farmers lack access to personalized, real-time advisory services that account for soil type, weather, and crop history. Barriers include language, low digital literacy, and the absence of localized tools. This leads to poor yields, overuse of chemicals, and higher costs.

Problem Statement Number: SIH25010  
Domain: Agriculture, FoodTech & Rural Development  
Mapped SDG: SDG 2 – Zero Hunger  
Organization: Government of Punjab

---

## Objectives
- Easy Registration: Simple, farmer-friendly sign-up with minimal digital skills required.  
- Season-wise Crop Recommendation: Intelligent recommendations accounting for season, location, and climate.  
- Crop Calendar View: Guidance on sowing, irrigation, fertilization, and harvesting schedules.  
- 7-Day Local Weather Forecast: Location-specific short-term forecasts for planning.  
- Rain Alerts – Skip Irrigation: Notifications about upcoming rainfall to conserve water.  
- Fertilizer Dose Calculator: Barcode-based fertilizer identification to determine nutrient composition and correct dosing.  
- Today’s News and Mandi Prices: Real-time agricultural news and mandi (market) price updates.  
- AI Voice and Chat Advisory in Local Language: Voice/chat assistant supporting local languages for accessibility.  
- Ask Expert Button: Direct connection to agricultural experts for personalized advice.  
- Nearby Resources Locator: Locate seed stores, fertilizer shops, mandis, and other resources via location services.  
- Multi-Language Interface: Support for regional languages to ensure inclusivity.

---

## Background & Related Work
- Existing apps such as Plantix, AgriApp, and IFFCO Kisan provide crop information, weather updates, and basic advisories.  
- Research and deployments show machine learning and AI can drive crop recommendation and fertilizer planning, but many tools lack deep localization, voice support, or precision fertilizer tooling.  
- There is a need for an integrated platform tailored for small and marginal farmers combining advisory, market information, fertilizer precision, and accessible AI voice/chat in local languages.

---

## Proposed Methodology
The methodology is an integrated approach combining real-time data, domain rules, and AI-driven assistance delivered via a mobile application.

Workflow:
1. User Access: Easy registration with profile and location capture.  
2. Input Data Collection: Season, crop, land area, weather, and fertilizer details (barcode scan).  
3. Processing & Advisory Logic: Analyze inputs to produce crop recommendations, fertilizer dosage, irrigation advice, and alerts.  
4. AI Advisory Support: Voice and chat assistant delivers localized, personalized guidance.  
5. Expert & Resource Support: In-app option to consult experts and locate nearby resources.  
6. Market & Update Services: Real-time mandi prices and agricultural news for decision support.

---

## Software Requirements
- Mobile Application (Frontend): React Native or Flutter for responsive, multi-language mobile UI.  
- Backend Server: Node.js for server-side logic, APIs, and authentication.  
- Database: MongoDB / Cloud database for storing user profiles, crop/fertilizer data, and history.  
- AI Voice Assistant Module: Integrate speech-to-text and text-to-speech in local languages for voice advisory.  
- Barcode Scanning Module: Mobile camera + barcode libraries to identify fertilizers and fetch nutrient data.  
- APIs/Services: Weather API, market price feeds (e.g., e-NAM), and news feeds.

---

## Innovation & Contribution
- AI Voice Assistant: Local language voice advisory for farmers with low literacy.  
- Barcode Fertilizer Calculator: Scan fertilizers to auto-identify composition and calculate dose.  
- Smart Irrigation Alerts: Rain forecasting to skip unnecessary irrigation and conserve water.  
- Integrated Advisory Platform: Crop advisories, fertilizer management, market information, and expert contact in one app.  
- Farmer-Friendly Interface: Simple, multi-language UI optimized for small and marginal farmers.

---

## Features (Quick Look)
- Register & manage farm profile  
- Season- and location-based crop suggestions  
- Interactive crop calendar and reminders  
- 7-day weather forecast and rain alerts  
- Fertilizer barcode scanner + dosage calculator  
- Local-language AI voice/chat assistant  
- Ask Expert (connect with agronomists)  
- Nearby resources locator (stores, mandis)  
- Real-time mandi prices and agri-news

---

## Repository & Demo
GitHub Repository: [FarmEkoX](https://github.com/ArunkumarK572/FarmEkoX)

(Insert app screenshots, timeline image, and Gantt chart in the repo when available — see /docs or /assets)

---

## Timeline & Gantt
- Timeline and Gantt chart images to be added in /docs or /assets.  
- Example phases: Requirements → Design → Implementation → Testing → Deployment → Evaluation.

---

## How to Run (Developer notes)
1. Clone the repository: `git clone https://github.com/ArunkumarK572/FarmEkoX.git`  
2. Follow platform-specific instructions (React Native / Flutter) in the repo's docs once the frontend is added.  
3. Configure backend (Node.js) and database (MongoDB) connection strings in environment variables.  
4. Obtain API keys for weather, news, and any third-party services used.  
5. For barcode and voice features, enable camera and microphone permissions on the device.

(Expand this section with concrete commands and env examples when codebase modules are added.)

---

## Contributors
- Student Name 1 – Roll No  
- Student Name 2 – Roll No  
Under the supervision of Guide Name

---

## References
1. A. Wolfert, L. Ge, C. Verdouw, and M.-J. Bogaardt, “Big data in smart farming – A review,” Agricultural Systems, vol. 153, pp. 69–80, May 2017.  
2. J. Liakos, P. Busato, D. Moshou, S. Pearson, and D. Bochtis, “Machine learning in agriculture: A review,” Sensors, vol. 18, no. 8, pp. 1–29, Aug. 2018.  
3. S. Kamilaris and F. X. Prenafeta-Boldú, “Deep learning in agriculture: A survey,” Computers and Electronics in Agriculture, vol. 147, pp. 70–90, Apr. 2018.  
4. Food and Agriculture Organization of the United Nations, “Digital agriculture and sustainable food systems,” FAO, Rome, Italy, Tech. Rep., 2019.  
5. Ministry of Agriculture and Farmers Welfare, Government of India, “National Agriculture Market (e-NAM),” [Online]. Available: https://www.enam.gov.in

---

## License
(Choose and add appropriate license file, e.g., MIT / CC BY. Add LICENSE in repo).