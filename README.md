# Smart India Hackathon Workshop
# Date: 26/09/2025
## Register Number: 25017264
## Name: SANDYA S
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

The idea is to create a multilingual mobile app that acts as a digital assistant for small farmers. Instead of being overloaded with complex data, the farmer will just open the app or talk to it and receive simple, practical advice in their own language.


The app can:

Suggest which crops are suitable for their soil and season.

Provide fertilizer and soil health tips in a farmer-friendly way.

Alert about weather changes before they happen.

Identify pests or diseases from photos uploaded by the farmer and suggest remedies.

Give market price updates from nearby markets to avoid exploitation by middlemen.

Since many farmers struggle with reading, the app will also provide voice support and large icons for easy navigation.


Features that make this idea unique:

Acts as a personal guide, not just a data source.

Gives predictive suggestions. For example, Rain expected next week, delay irrigation today.

Has a feedback loop - farmer responses help improve the app continuously.

Works offline - storing the last updated advice when internet isn’t available.

## Technical Approach

Mobile App Framework: React Native / Flutter (runs on Android & iOS).

Django – for storing farmer data, crop info and pest reports.

HTML and CSS – for designing web-based dashboards or admin panels.

Databases: SQLite for storing farmer records and app data.

AI/ML : Crop recommendation and pest/disease detection from images.


Methodology and Process:

Understand Farmer Needs – Surveys or case studies to know common problems.

App and UI Design – Multilingual, large icons, simple navigation. Initial prototype could be web-based in Django, later converted to mobile.

Data Collection and Storage – Crop, soil, pest data in SQLite. Weather and market data via public APIs.

Smart Features – Crop recommendation, pest detection, offline support.

Feedback Loop – Farmer inputs improve future suggestions.

Unique Ideas that bring innovation:

Farmer Voice Diary: Personal farm notes via audio recordings.

Community Q&A: Local farmer interaction through a discussion board.

Offline Predictive Advice: Stored advice usable without internet.

![alt text](<Crop Advisory Design.jpg>)
![alt text](<flowchart diagram.png>)



## Feasibility and Viability

Technical Feasibility:

Mobile app works on Android/iOS, Django + SQLite backend is simple and lightweight.

Public APIs for weather, market prices, and soil/crop data are accessible.

Offline caching ensures usability without constant internet.


Economic Feasibility:

Farmers already have low cost smartphones.

Minimal infrastructure cost as open-source frameworks reduce expenses.


Operational Feasibility:

Simple UI, voice support, and local language make adoption easier.

Community and personalized advice encourage engagement.


Potential Challenges & Risks:

Low digital literacy.

Limited internet access.

Early AI models may be inaccurate.

Data privacy concerns.



Strategies to Overcome Challenges:

Intuitive design and step-by-step onboarding.

Offline mode with cached data.

Gradual AI integration that start with manual advice.

Minimal data storage with basic authentication.


## Impact and Benefits

Potential Impact:

Empowers farmers with better decision making.

Reduces dependency on middlemen via real time price info.

Provides personalized, local and seasonal guidance.

Builds a community for knowledge sharing.


Benefits:

Social:

Digital inclusion, community engagement, awareness of sustainable practices.

Economic:

Higher productivity, income stability, cost savings via optimized resources.

Environmental:

Sustainable fertilizer/pesticide use, water conservation, reduced crop wastage.

Educational:

Farmers learn modern techniques like keeping farm diaries via voice.


## Research and References

Research Papers & Studies

Mobile Applications for Smallholder Farmers: A Review” – ScienceDirect

Effectiveness of ICT in Agriculture” – ICT in Agriculture

Indian Government Open Data Portals – Data.gov.in

Market Prices – Agmarknet

Weather APIs – OpenWeatherMap

