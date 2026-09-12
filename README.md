# Plan&Go

> **By Team TungTungSahur**  
> **Problem Statement:** Travel Planner  
> **Team Members:** Lee Xhi Rou, Bernice Tan Jiawen, Kam Xin Le, Yap En Yu  
> 
> 🔗 **Quick Links:**
> - 🎥 **Video Presentation:** [Watch Unlisted YouTube Video]([Unlisted Youtube Link])
> - 📊 **Presentation Slides:** [View Slides]([Public Link])
> - 🌐 **Live Prototype:** [plan-and-go-v1.vercel.app](https://plan-and-go-v1.vercel.app/)

---

## 1. Project Overview

### 1.1 The Problem
We chose to focus on group travel because travelling with multiple people often creates more challenges. Different travellers may have different budgets, interests, schedules, and preferred travel paces, making it difficult to create a plan that works for everyone. Unexpected changes such as bad weather, transportation delays, budget changes, or changing preferences can further disrupt the original itinerary.

Existing travel applications address some of these problems, but they often focus on specific parts of the travel experience. For example, **Wanderlog** supports collaborative itinerary planning, budgeting, expense splitting, and travel organization, while **TripIt** focuses on consolidating bookings and managing travel itineraries. However, existing solutions rarely bring group preference coordination, real-time adaptive planning, comprehensive traveller safety, and integrated expense tracking together into a single platform.

This creates an opportunity for **Plan&Go** to provide a more adaptive and integrated travel experience — helping groups make decisions together, automatically adjust plans when situations change, and providing additional safety support for women and other travellers.

### 1.2 The Solution
**Plan&Go** is an AI-powered travel companion designed to make group trips seamless, safe, and truly memorable. Before you even set off, it takes the hassle out of preparation with smart packing lists and weather-matched outfit recommendations.

On the road, Plan&Go balances everyone’s budget, pace, and interests into a flexible itinerary that adapts automatically to unexpected changes like bad weather or transit delays. More than just a logistics tool, it acts as an interactive travel journal with built-in safety support and smart expense sharing—keeping everyone protected while preserving your shared memories for years to come.

### 1.3 Feature Set

| Feature | Description |
| :--- | :--- |
| **AI-Powered Smart Planning** | Turn “Where should we go?” into a ready-to-go adventure. Plan&Go creates personalized itineraries based on your budget, available time, starting location, travel style, transport preferences, and who you’re travelling with. For group trips, everyone’s preferences are considered to create a plan that works for the whole group. |
| **One-Click Adaptive Itinerary** | Your itinerary isn’t set in stone. Regenerate your plan instantly when something doesn’t feel right. Tell Plan&Go why you want to change it, remove places you dislike, add your own bucket-list destinations, or discover nearby alternatives—so every regeneration gets closer to your ideal trip. |
| **Weather-Aware Planning** | Plan for the trip you’ll actually experience. Integrated weather forecasts help travellers anticipate changing conditions and prepare accordingly, making it easier to adjust activities and avoid unpleasant surprises. |
| **Integrated Flight & Stay Booking** | From planning to booking, without jumping between apps. Search and book flights and accommodations directly within Plan&Go, bringing essential travel planning activities together in one seamless experience. |
| **Smart Expense Tracking** | Know where your group’s money is going. Record shared expenses, track who paid, calculate settlements, and monitor your remaining trip budget in real time. Plan&Go can also alert the group when spending approaches or exceeds the planned budget. |
| **AI Bill Splitting** | Turn a messy receipt into a fair split in seconds. Upload a receipt and Plan&Go extracts the individual items, allowing each traveller to select what they purchased before automatically calculating how much everyone owes. Manual entry is also available when there’s no receipt. |
| **One-Tap Travel Guardian** | When something goes wrong, help is only one tap away. Travellers can trigger an SOS that shares their live location with relevant local authorities, helping reduce the friction of getting assistance during an emergency. |
| **Live Location Circle** | Stay connected without constantly asking “Where are you?” Share your live location with trusted group members or emergency contacts and view relevant locations on an interactive map—helping groups stay together and making it easier to find one another. |
| **AI Travel Stylist** | Let AI answer the “What should I wear?” question. Plan&Go recommends outfits based on the destination and expected weather, helping travellers choose what to wear without overthinking every day of the trip. |
| **Smart Packing List** | Pack smarter, not heavier. Plan&Go generates a practical packing checklist based on your trip, helping you remember the essentials. Tick items off as you pack and enjoy a more effortless preparation process. |
| **Travel Footprint** | Turn your journey into a map of memories. Capture the places you’ve visited by attaching your own photos to locations on the map, creating a personalized visual footprint of your journey over time. |
| **Daily Travel Journal** | Don’t just plan your trip—live and remember it. At the end of each day, travellers can check in with their emotions, write personal notes, and capture what made the day exciting, meaningful, difficult, or memorable. |
| **Trip Harmony Score** | Measure how the journey felt—not just where you went. Plan&Go transforms daily check-ins and trip reflections into a personalized Harmony Score, giving groups a unique reflection of their overall travel experience. The final summary can be exported as a shareable PNG for social media. |

---

## 2. Ideation & Process (Evaluation Weightage: 25%)

### 2.1 Ideas We Considered

| Idea | Status | Why it was dropped / kept |
| :--- | :---: | :--- |
| **AI-Powered Smart Planning** | **Chosen** | Selected as the main planning idea because it provides a personalised starting point for different types of travellers. |
| **One-Click Adaptive Itinerary** | **Chosen** | Travel plans may change during a trip. It makes the system flexible instead of locking users into one rigid plan. |
| **Weather-Aware Planning** | **Chosen** | Kept because weather directly affects outdoor activities and the overall travel experience. |
| **Integrated Flight & Stay Booking** | **Chosen** | Reduces the need for users to switch between multiple disjointed platforms when arranging their trip. |
| **In-App Share Wallet** | **Dropped** | We initially planned an e-wallet for funds pooling. However, implementing financial transactions within a short timeline was infeasible. Guaranteeing financial security with our limited time and resources was also a major concern. |
| **Smart Expense Tracking** | **Chosen** | Managing group spending is difficult, especially when multiple people pay for different group items. |
| **AI Bill Splitting** | **Chosen** | Splitting expenses manually is slow, error-prone, and can lead to misunderstandings among group members. |
| **One-Tap Travel Guardian** | **Chosen** | Safety is paramount, especially when travellers need immediate, low-friction help during emergencies. |
| **Live Location Navigation** | **Dropped** | Initially planned to guide users along routes using live location. Dropped due to privacy/security risks with continuous background tracking and the engineering overhead of building real-time turn-by-turn navigation within our timeframe. |
| **Real-Time Public Transportation Tracker** | **Dropped** | Aimed to provide real-time bus, MRT, and LRT tracking. Dropped due to the lack of reliable real-time transit APIs. Inaccurate cancellation/delay data could lead users to miss their transit. |
| **Live Location Circle** | **Chosen** | Keeps travelling groups connected passively, eliminating the need to constantly message “where are you?”. |
| **AI Travel Stylist** | **Chosen** | Resolves the dilemma of choosing suitable clothing across varying destination climates and dress codes. |
| **Smart Packing List** | **Chosen** | Prevents travellers from forgetting essentials during trip preparation. |
| **Travel Footprint** | **Chosen** | Adds an interactive, sentimental dimension by pinning photos to visited locations on a map. |
| **Daily Travel Journal** | **Chosen** | Enables travellers to record daily emotions and highlights instead of treating travel solely as a logistical task. |
| **Trip Harmony Score** | **Chosen** | Provides an analytical and fun post-trip reflection of group dynamics and overall trip sentiment. |

### 2.2 Ideation Boards

#### Mindmap 1 – Initial Concept
![Mindmap 1 - Initial Concept](./assets/mindmap1.png)

#### Mindmap 2 – Idea Development
![Mindmap 2 - Idea Development](./assets/mindmap2.png)

#### Mindmap 3 – Refined Concept After Mentor Consultation
![Mindmap 3 - Refined Concept](./assets/mindmap3.png)

### 2.3 Mentor Consultation

| Date | Mentor | Feedback Received | What Was Changed |
| :--- | :--- | :--- | :--- |
| **9/9/2026** | **Zach Thong** | 1. **Focus on Safety:** Centre the app on user safety (especially women, kids, and teens) rather than generic group travel planning.<br>2. **Consolidate UI on One Page:** Put all key entry points on a single dashboard using small widgets so users can easily follow.<br>3. **Adaptive SOS Widget:** Add an SOS button widget with auto-location detection adaptable anywhere.<br>4. **Direct Booking via APIs & Agents:** Move beyond passive recommendations—call agents and integrate APIs (e.g., Trip.com) to book flights directly, linked with the wallet. | 1. **Repositioned Core Concept:** Shifted to a safety-first platform with built-in safeguards for solo and female travellers across 6 core features.<br>2. **Single-Page Widget Dashboard:** Redesigned the homepage into a unified dashboard featuring compact widgets to showcase all key features and live recommendations at once.<br>3. **Real-Time SOS Widget:** Added a persistent SOS button that auto-detects current coordinates to access local emergency help globally. |

---

## 3. Design & Prototype

> 🌐 **Interactive Prototype URL:** [https://plan-and-go-v1.vercel.app/](https://plan-and-go-v1.vercel.app/)

### Figure 1: Preferences
![Figure 1: Preferences](./assets/fig1.png)  
*Users customize their travel preferences by selecting from diverse travel vibes such as relaxed, foodie, or packed. These inputs directly feed into the recommendation engine to tailor hyper-personalized itineraries and activities.*

### Figure 2: Itinerary Planning
![Figure 2: Itinerary Planning](./assets/fig2.png)  
*The platform generates a fully customized daily itinerary structured with real-time weather, curated stops, estimated costs, and timing. Users can easily fine-tune their schedule by bookmarking, removing stops, or triggering a one-click "Regenerate Plan" to refresh recommendations.*

### Figure 3: AI Smart Receipt Split & Expense Management
![Figure 3: AI Smart Receipt Split & Expense Management](./assets/fig3.png)  
*Users can upload receipt images using the "Smart Receipt Split" feature, which uses AI to automatically parse items, prices, dates, and currencies. From this modal, users can assign individual line items to specific members and designate who paid for streamlined group expense tracking.*

### Figure 4: One-Tap SOS & Real-Time Safety Hub
![Figure 4: One-Tap SOS & Real-Time Safety Hub](./assets/fig4.png)  
*The Guardian dashboard provides immediate emergency support through a "One Tap SOS" feature that broadcasts live GPS telemetry to local authorities and allows users to alert group members instantly. It also aggregates localized safety guidelines, emergency hotlines, and quick-access cards for nearby critical amenities such as clinics, ATMs, and police stations.*

### Figure 5: Guardian Real-Time Group Location Tracker
![Figure 5: Guardian Real-Time Group Location Tracker](./assets/fig5.png)  
*The Live Location map tracks group members in real time via an interactive Google Maps interface, showing each member’s precise pin, current spot, and device battery status. Users can toggle between map layers, centre on their own GPS, or open external navigation to stay connected and ensure group safety during travel.*

### Figure 6: Smart Wardrobe & AI Travel Stylist
![Figure 6: Smart Wardrobe & AI Travel Stylist](./assets/fig6.png)  
*The Stylist feature provides personalized outfit suggestions by analyzing the user's travel date, preferred aesthetic, gender, and local climate. Under the "Smart Wardrobe" section, it pairs tops and bottoms with tailored colour-palette advice that matches the destination’s scenery and ensures photogenic, weather-appropriate outfits.*

---

## 4. What Makes It Different

Compared with existing travel-planning applications, **Plan&Go** differentiates itself through key integrated capabilities:

| Feature | Description |
| :--- | :--- |
| **Dynamic Contextual Adaptation** | AI automatically adjusts the itinerary when weather, delays, or other real-time conditions change, instead of requiring users to rearrange plans manually. |
| **AI Track Bills** | Scan a receipt with OCR and let each traveller select the items they consumed. |
| **Safety Hub** | Combines one-tap SOS, live group location sharing, and nearby verified 24/7 clinics, police posts, and convenience stores in one place. |
| **Receipt-Itemized Bill Splitting** | AI scans receipts and identifies individual items, allowing each traveller to simply select what they consumed instead of manually entering expenses. |
| **AI Stylist & Smart Packing** | Generates outfit and packing recommendations based on both the destination’s weather and the day’s specific activities and dress requirements. |
| **Reflective Travel Story** | Converts daily check-ins, moods, notes, and completed activities into an automated personalized travel story, rather than just a list of visited places. |

### Competitive Matrix

| Capability | Wanderlog | TripIt | Plan&Go |
| :--- | :---: | :---: | :---: |
| **Trip Planning** | ✅ | ✅ | ✅ |
| **Group Collaboration** | ✅ | ✅ | ✅ |
| **Flight/Travel Recommendations** | ✅ | ✅ | ✅ |
| **AI Dynamic Rescheduling** | ❌ | ❌ | ✅ |
| **Integrated Safety Hub** | ❌ | ❌ | ✅ |
| **Weather + AI Styling** | ❌ | ❌ | ✅ |
| **AI Travel Recap** | ❌ | ❌ | ✅ |
| **Bill Tracking & Splitting** | Basic tracking only | ❌ | ✅ (AI Itemized OCR) |

---

## 5. Technical Architecture & Feasibility

### 5.1 Tech Stack

| Category | Technology / Service | Purpose / Reason |
| :--- | :--- | :--- |
| **Frontend** | React + Vite, Tailwind CSS, Leaflet.js | Lightweight, fast-loading travel-planning interface with interactive itinerary mapping and component styling. |
| **Backend** | Python + FastAPI, Docker | High-performance asynchronous API for AI orchestration, OCR pipeline, trip logic, and third-party integrations. |
| **Database** | Supabase PostgreSQL | Stores user profiles, trips, itineraries, expenses, and daily check-ins; provides authentication and scalable relational data storage. |
| **AI Services** | Gemini / OpenAI API | Personalised itinerary generation and AI-powered trip recaps. |
| **Maps & Services** | Google Maps Platform | Map visualizations, geocoding, route queries, and nearby place discovery. |
| **Exchange Rate API** | ExchangeRate API | Real-time currency conversion for multi-currency expense tracking and budget calculations. |
| **OCR Pipeline** | Google Cloud Vision / Gemini Vision | Extracts structured tabular information from uploaded receipt images. |
| **Weather Integration** | OpenWeather API | Provides real-time weather forecasts for dynamic trip scheduling. |
| **Deployment & Hosting** | Vercel (Frontend) + Render / Railway (Backend) | Production-ready, zero-downtime deployment pipelines suited for rapid hackathon iteration. |

> **Technical Constraints & Mitigations:**
> - **API Quotas:** Mitigated via response caching for static/repeated queries (e.g., weather forecasts and currency rates).
> - **Cold Starts & Latency:** Addressed through asynchronous FastAPI endpoints and client-side skeleton states.
> - **Security:** All sensitive third-party API keys are strictly maintained within server-side environment variables (`.env`) and never exposed to the frontend.

### 5.2 3-Week Development Timeline

| Week | Focus | Key Tasks |
| :---: | :--- | :--- |
| **Week 1** | **Backend & Core Functions** | - Set up FastAPI backend boilerplate and Docker environments<br>- Connect Supabase PostgreSQL & configure authentication<br>- Connect frontend and backend client layers<br>- Implement user profiles, trip creation, and itinerary schemas<br>- Implement basic AI itinerary generation endpoint |
| **Week 2** | **AI & API Integration** | - Integrate Google Maps & Places API<br>- Integrate OpenWeather API<br>- Implement dynamic itinerary updates based on real-time triggers<br>- Implement shared wallet & transaction tracking<br>- Implement receipt OCR pipeline & itemized bill splitting<br>- Integrate ExchangeRate API |
| **Week 3** | **Recap, Integration & Deployment** | - Implement daily check-ins & photo upload services<br>- Implement AI-generated travel score & recap generator<br>- Complete full end-to-end integration and edge-case handling<br>- Perform error handling and accuracy testing on OCR/AI prompts<br>- Deploy frontend to Vercel and backend to Render/Railway<br>- Final smoke testing, bug fixing, and presentation recording |
