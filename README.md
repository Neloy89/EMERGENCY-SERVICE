# EMERGENCY-SERVICE
The Emergency Service System is a user-friendly application designed to reduce response times and improve coordination between fire, police, and ambulance services.

## Background

The Emergency Service System is designed to streamline and optimize the efficiency of emergency response services (fire, ambulance, law enforcement) through the use of technology. With a focus on minimizing response time, the system integrates emergency services into a user-friendly platform, accessible via mobile devices. The application leverages GPS, real-time tracking, AI, and data analytics to enable faster dispatch and ensure public safety.

## Problem Statement

Emergency services in Bangladesh face significant delays between service requests and the actual help arriving. The current system can process a limited number of simultaneous calls, leading to long wait times during high demand periods, endangering public safety.

## Proposed Solution

The project aims to create an automated system using AI and data analytics to enhance emergency response efficiency. By integrating real-time GPS tracking, service request management, and data-driven decisions, the solution reduces delays, improves service delivery, and ultimately saves lives.

## Features

- **Login & Signup**: Secure user authentication with OTP verification, fingerprint support, and location permission requests.
- **Real-Time Tracking**: Provides users and emergency responders with live location data during service delivery.
- **Request Services**: Allows users to request fire, health care, and law enforcement services with real-time tracking of the dispatch.
- **Service Review & Feedback**: Users can review services, improving accountability and service quality.
- **Generate Probable Causes**: Uses AI to suggest possible causes for emergency requests based on historical data and user input.
- **Penalties for False Requests**: Implements a penalty system for false requests to ensure service availability for real emergencies.

## Technologies Used

- **Programming Languages**: C#, SQL
- **Frameworks**: Microsoft Visual Studio 2022, NUnit for testing
- **Database**: Microsoft SQL Server
- **Diagrams**: UML diagrams for system architecture, including use case, class, sequence, and activity diagrams.

## System Architecture

The system follows the Incremental Development Model, focusing on iterative development and delivery of features, with continuous testing and feedback loops.

## Installation

1. Clone the repository:  
   `git clone git@github.com:Neloy89/EMERGENCY-SERVICES.git`

2. Open the project in **Microsoft Visual Studio 2022**.

3. Set up the database with **Microsoft SQL Server** using the provided schema.

4. Build and run the application.

## Testing

The system includes several test cases to ensure the proper functionality of features, such as:

- **Test Case ID: FR_2** - Health Care Session: Ensure the user can request an emergency consultant.
- **Test Case ID: FR_3** - Ambulance Notification System: Validate real-time notification for nearby ambulances.
- **Test Case ID: FR_4** - Law Enforcement Dispatch: Ensure law enforcement units are dispatched based on severity and location.

## Future Improvements

- Implement AI-based prediction models for quicker emergency cause detection.
- Integrate more advanced real-time tracking features.
- Improve system scalability for high-demand events.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
