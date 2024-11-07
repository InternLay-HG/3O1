## **Software Requirements Specification (SRS) for Caron Urban Mobility Platform**
## **Version 1.0**

### **1. Introduction**
1.1 Purpose
The purpose of this document is to outline the software requirements for Caron, a next-generation urban mobility platform that enables streamlined taxi bookings, user-driver interactions, and real-time, eco-friendly travel options. Caron aims to improve commuting efficiency in urban settings by integrating multi-modal transportation choices and providing real-time route suggestions.

###### 1.2 Intended Audience and Reading Suggestions
This document is intended for:  
Developers responsible for building and maintaining the Caron platform.  
Project Managers who oversee project progress and timelines.  
City Planners looking to leverage Caron’s transportation data for urban planning.  
Stakeholders with an interest in the strategic development and growth of Caron.

###### 1.3 Scope
Caron is a web and mobile platform providing users with features such as:
Seamless cab bookings and live tracking.
Direct communication between users and drivers.
Integrated multi-modal options including public transit, ride-sharing, and bike-sharing.
Eco-conscious travel incentives, encouraging sustainable choices.

###### 1.4 Definitions, Acronyms, and Abbreviations
API - Application Programming Interface  
GPS - Global Positioning System  
GDPR - General Data Protection Regulation  
Multi-modal Transportation - Use of multiple forms of transportation within a single journey.  

### **2. Overall Description**

###### 2.1 Product Perspective
The Caron platform comprises three main components:  
Mobile Application (iOS and Android): Enables on-the-go cab booking and route tracking.
Responsive Web Application: Provides detailed trip planning, account management, and tracking of eco-friendly incentives.  
Backend System: Handles data processing, third-party integrations (e.g., public transit, ride-sharing, and traffic data), and analytics for optimizing route and traffic predictions.

###### 2.2 Product Features
Real-time Cab Booking: Users can book and track cabs in real-time.  
Driver Communication: In-app chat and call options for immediate interaction.  
Multi-modal Route Suggestions: Integrates various transportation options, including public transit and bike-sharing.  
Traffic and Weather-aware Route Planning: Provides optimized routes considering real-time traffic and weather conditions.  
Eco-friendly Incentives: Rewards users for eco-conscious travel choices, tracking their environmental impact.  
Community Reporting: Users can report road conditions, which improve route recommendations.

###### 2.3 User Classes and Characteristics
Regular Commuters: Individuals looking for optimized daily routes for work or school.  
Eco-conscious Users: Users prioritizing sustainable travel options.  
City Planners: Authorized users analyzing aggregated data to make informed decisions.

### **3. System Requirements**
Mobile Application: Available for iOS and Android platforms.  
Web Application: Compatible with major browsers (Chrome, Firefox, Safari, Edge).  
Backend Server: Node.js, with necessary integrations for external APIs.  
Database: MongoDB or similar for data storage.

### **4. Installation**
Prerequisites
Node.js and npm for server setup.  
MongoDB for data storage.  
Android Studio or Xcode for mobile app development.

### **5. Specific Requirements**
###### 5.1 External Interface Requirements
*User Interfaces*
Mobile App (iOS and Android): Provides features like real-time maps with traffic overlays, booking interface, driver interaction options, and a dashboard displaying eco-travel points and rewards.  
Web Application: Features a trip planning interface, eco-footprint tracking, rewards, and account management.  

*Hardware Interfaces*  
GPS Integration: For accurate real-time location tracking.  
Smartphone Sensors: Utilizes accelerometer and gyroscope for mode detection.  

*Software Interfaces*  
Integration with various APIs:  
Public Transit APIs for schedule updates.  
Ride-sharing and bike-sharing APIs (e.g., Uber, Lyft) for additional travel options.  
Traffic and weather APIs for real-time adjustments to travel recommendations.

###### 5.2 Functional Requirements
*User Registration and Authentication*  
REQ-1: Users can register using email, phone, or social media accounts.  
REQ-2: Includes secure authentication with options like two-factor authentication.  

*Real-time Traffic Monitoring*  
REQ-3: Real-time traffic conditions displayed on an interactive map.  
REQ-4: Traffic forecasts based on historical and live data for enhanced route planning.  

*Route Planning and Recommendations*  
REQ-5: Multi-modal route options combining cab, public transit, and bike-sharing.  
REQ-6: Personalized recommendations based on user preferences (time, cost, eco-impact).  

*Eco-friendly Incentives*  
REQ-7: Tracks the environmental impact of user travel choices, rewarding eco-conscious behaviors.  

*Community Reporting*  
REQ-8: Users can report road conditions and incidents, which will enhance real-time recommendations.

###### 5.3 Non-functional Requirements
*Performance*  
REQ-9: The mobile app should respond to user inputs within 2 seconds for seamless interaction.  
REQ-10: The system shall handle up to 100,000 concurrent users.  

*Security*  
REQ-11: All data exchanges should use industry-standard encryption protocols.  
REQ-12: User data storage should be GDPR-compliant to maintain user privacy.  

*Reliability*  
REQ-13: The platform should maintain a 99.9% uptime.  
REQ-14: Data backups should occur hourly to ensure data reliability.  

*Usability*  
REQ-15: Mobile UI designed for single-hand usability with intuitive access to core features.  
REQ-16: Main features should be accessible within three taps to streamline the user experience.

### **6. Appendices**

###### 6.1 Glossary
API: A set of routines and protocols for building and integrating software.  
Multi-modal Transportation: Combining multiple transportation types within a single journey to reach a destination.

###### 6.2 Assumptions and Dependencies
Users access Caron via GPS-enabled smartphones.  
Public transit, ride-sharing, and bike-sharing services are active within the city.  
External APIs (transit, traffic, weather) are reliably accessible for optimal platform functionality.

### **7. Team Members and Domains**
->Jeet Jay Mulani(Team Leader) - Andriod Development  
->Pragati Ghosh - UI/UX Design  
->Aditya Meena - UI/UX Design  
->Aditya Verma - Andriod Development  
->Kartikey Thakur - Web Development  
->Piyush Arora - Andriod Development  
->Harsh Kumar - Web Development  
->Zayan Khan - AI/ML  

### **8. Figma file and Notion site**
caron 1.0(figma): https://www.figma.com/design/oSVoQLaHRWQDI1dVTWHsfq/caron-internlay-3O1?node-id=0-1&t=c8dZD3vnPyXSlqNJ-1
notion site: https://spectacled-wasabi-b60.notion.site/CARON-1-0-134cf5ac2a5880e1b612d7fe8d79bc44
