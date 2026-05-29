# Smart India Hackathon Workshop

## Date: 29.05.2026

## Register Number: 212223220046

## Name: KEERTHIVASAN S

## Problem Title
SIH 1710: Enhancing Navigation for Railway Station Facilities and Locations

## Problem Description

Background: Railway stations are complex environments with numerous facilities and locations such as ticket counters, platforms, restrooms, food courts, and waiting areas. Passengers often face difficulties in navigating these spaces, especially in large or unfamiliar stations. Efficient and user-friendly navigation systems are crucial for improving passenger experience, reducing congestion, and ensuring timely travel connections. Description: The problem involves developing a comprehensive navigation solution for railway stations that assists passengers in locating various facilities and destinations within the station premises. This includes creating detailed maps, providing real-time directions, and integrating features such as accessibility options for individuals with disabilities. The solution should be intuitive, easy to use, and accessible via multiple platforms, including mobile devices and digital kiosks. Key challenges include updating navigation information in real-time, ensuring accuracy, and accommodating the diverse needs of all passengers. Expected Solution: The expected solution is a multi-platform navigation system that provides detailed, real-time directions to all facilities and locations within a railway station. This system should include: A mobile application with 3D interactive maps and step-by-step navigation. Digital kiosks located throughout the station with touch-screen interfaces. Voice-guided navigation for visually impaired passengers. Regular updates to reflect changes in station layout and facility locations. Integration with existing railway apps and services for seamless user experience. The solution should enhance the overall passenger experience by reducing confusion, saving time, and improving accessibility within the station.

## Problem Creater's Organization
Ministry of Railway

## Idea

1. The idea of this project is to create a smart indoor navigation system for railway stations. In many large railway stations, passengers find it difficult to locate platforms, ticket counters, restrooms, waiting halls, food courts, lifts, escalators and exits.

2. Normal GPS is not accurate inside stations because of roofs, multiple floors and crowded areas. So this project uses QR code based location points inside the station. Passengers can scan the nearest QR code and get directions to their required place.

3. The system will be useful for new passengers, senior citizens, visually impaired people and passengers who are in a hurry to catch trains.

## Proposed Solution

1. The proposed solution is a mobile and kiosk based navigation system. QR codes will be placed at important points inside the station such as entrance gates, platforms, bridges, waiting halls and exits.

2. When the passenger scans a QR code, the system identifies the current location. Then the passenger can search for a destination such as Platform 5, restroom, ticket counter or food court.

3. The system calculates the shortest path and shows step-by-step directions. Voice guidance is also provided for visually impaired passengers.

## Architecture Diagram

<img width="1536" height="1024" alt="architecture diagram" src="https://github.com/user-attachments/assets/cf24f2d3-ba93-463c-b183-c2d8177feaa2" />

## Use Cases

1. The main users of this system are passengers and station administrators.

2. Passengers can use the system to search for facilities, scan QR codes, get directions and use voice navigation.

3. Station administrators can update the station map when there are changes in facility locations or routes.

## Technology Stack

| Module             | Technology Used         |
| ------------------ | ----------------------- |
| Mobile Application | Flutter                 |
| Kiosk Interface    | HTML, CSS, JavaScript   |
| Backend            | Node.js, Express.js     |
| Database           | Firebase / MongoDB      |
| Map Display        | 2D/3D Station Map       |
| Navigation Logic   | Shortest Path Algorithm |
| Voice Guidance     | Text-to-Speech          |
| QR Scanning        | QR Code Scanner         |
| Admin Panel        | React.js                |

## Dependencies

• Flutter SDK

• Node.js

• Express.js

• Firebase or MongoDB

• QR Code Scanner package

• Text-to-Speech package

• React.js

• HTML, CSS, JavaScript

• Internet connection for real-time updates

• Station map data

• QR codes placed inside the stationt
