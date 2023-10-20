# Lindner-Airlines: Design Document
---
Team Members : Subuhi,Chandra Sekhar Cherukuri,Nikhil Sai Kumar Runku,Veda Supraja Adapa,Bhargav Sreepathi

## Logo
![image](https://github.com/subuhifu/Lindner-Airlines/assets/143138483/ea7835c4-fe27-4752-aeb4-5ab94a879417)


## Introduction



## Story Board
![image](https://github.com/subuhifu/Lindner-Airlines/assets/143138483/92c1d223-0ff3-454a-a9ed-12e17e26ba33)
![image](https://github.com/subuhifu/Lindner-Airlines/assets/143138483/9e52b6ad-e19a-4ca2-8452-f26b2f35b133)

![image](https://github.com/subuhifu/Lindner-Airlines/assets/143138483/2e542f5f-bf22-40c8-ab40-8854bc466526)

![image](https://github.com/subuhifu/Lindner-Airlines/assets/143138483/700edcf9-0eff-48cb-aeab-121838765bd0)

![image](https://github.com/subuhifu/Lindner-Airlines/assets/143138483/1b6857c0-2f5b-499e-a98d-41b451faa6ec)

![image](https://github.com/subuhifu/Lindner-Airlines/assets/143138483/c03a436b-ae82-470d-8aab-6a4c66c7db70)




##  Data Feeds

[U.S. International Air Traffic Data](https://www.kaggle.com/datasets/parulpandey/us-international-air-traffic-data/)

[U.S. Historical Flight Delay and Weather Data](https://www.kaggle.com/datasets/ioanagheorghiu/historical-flight-and-weather-data)


## Functional Requirement

### Requirement 1.0: User Registration and Login

#### Scenario

As a user, I want to register an account and be able to log in so that I can access the airline's booking system.

#### Dependencies
The application provides registration and login functionality.

#### Assumptions
Users will provide valid registration information.

#### Examples
### 1.1

**Given**: I am a new user.

**When**: I navigate to the registration page and provide valid registration details.

**Then**: I should receive a confirmation message and be able to log in with my new account.

### 1.2
**Given**: I am a registered user.

**When**: I navigate to the login page and provide my valid credentials.

**Then**: I should be logged in and have access to the airline's booking system.

### Requirement 2.0: Flight Search and Booking
#### Scenario
As a user, I want to search for available flights and make bookings to plan my travel.

#### Dependencies
The system provides access to a flight database and booking functionality.

#### Assumptions
Flights are available for booking.

### Examples
### 2.1
**Given**: I want to book a flight.

**When**: I search for flights from "Cincinnati" to "Dallas" on a specific date.

**Then**: I should see a list of available flights and be able to select and book one.

### 2.2
**Given**: I am booking a flight.

**When**: I select a flight and provide passenger details.

**Then**: I should receive a booking confirmation with all the travel details.

### Requirement 3.0: User Profile Management
#### Scenario
As a user, I want to manage my profile information and preferences.

#### Dependencies
The application allows users to create and update profiles.

#### Assumptions
Users have profiles with editable information.

### Examples
### 3.1
**Given**: I want to update my profile.

**When**: I navigate to my profile and change my contact information.

**Then**: My profile is updated, and the changes are saved.

### 3.2
**Given**: I want to update my demographic information.

**When**: I access the demographic information update feature and provide new details, such as my address, phone number, or date of birth.

**Then**: My demographic information is updated, and the changes are saved securely.

### Requirement 4.0: Flight Management
#### Scenario
As an airline administrator, I want to manage flight details and availability.

#### Dependencies
The system allows administrators to add, update, or remove flight information.

#### Assumptions
Administrators have the necessary permissions.

#### Examples
### 4.1
**Given**: I need to add a new flight.

**When**: I access the flight management panel and provide flight details.

**Then**: A new flight is added to the system.

### 4.2
**Given**: A flight schedule needs to be updated.

***When***: I select a flight and modify its departure time.

***Then***: The flight schedule is updated, and passengers are informed of the change.

### Requirement 5.0: Reporting and Statistics
#### Scenario
As an airline administrator, I want to access reports and statistics related to bookings and flight performance.

#### Dependencies
The system provides access to booking and flight data.

#### Assumptions
Data is available for analysis.

#### Examples
### 5.1
**Given**: I want to view the total number of bookings this month.

**When**: I access the reporting dashboard.

**Then**: I see a summary of monthly bookings.

### 5.2
**Given**: I want to analyze the most popular flight routes.

**When**: I access the statistics section.

**Then**: I receive data on the top routes based on bookings.

### Requirement 6.0: Assistance Requests

#### Scenario
As a user with special needs, I want to request assistance during my travel.

#### Dependencies
The system allows users to request assistance and assign staff to assist them.

#### Assumptions
Users can specify their assistance requirements.

#### Examples
### 6.1
**Given**: I require wheelchair assistance.

**When**: I make a booking and specify my assistance needs.

**Then**: Wheelchair assistance is arranged for my travel.

### 6.2
**Given**: I have a medical condition and need in-flight assistance.

**When**: I request assistance during the booking process.

**Then**: Medical assistance was provided during my flight.









## Scrum Roles

- Frontend Developer: Chandra Sekhar Cherukuri
- Integration Developer: Veda Supraja Adapa
- Scrum Master: Subuhi
- DevOps: Bhargav Sreepathi
- Product Developer: Nikhil Sai Kumar Runku
  




## Weekly Meetings


Sunday at 9 PM on Teams


