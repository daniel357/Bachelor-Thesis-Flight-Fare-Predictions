# Bachelor Thesis - Flight Fare Predictions

## Overview
This repository contains the implementation of my Bachelor thesis project titled "Flight Fare Predictions." The project aims to predict the optimal time to purchase flight tickets to get the lowest prices using advanced machine learning techniques.

## Project Description
The primary goal of this project is to develop a machine learning model that accurately forecasts the best time for customers to purchase flight tickets at the lowest possible prices. This is achieved by leveraging a comprehensive dataset from Kaggle and employing a Random Forest algorithm to predict fare trends.

## Key Features
- **Machine Learning Model:** Developed a Random Forest model to predict the optimal timing for purchasing flight tickets, achieving a mean error margin of approximately 2 days.
- **Web Application:** Created a user-friendly web application with Next.js for the front-end and NestJS for the back-end.
- **Email Notifications:** Integrated email notifications for users to receive fare predictions.
- **Data Visualization:** Designed dynamic charts for visualizing fare trends and optimal purchase times.

## Technologies Used
- **Front-end:** Next.js (React-based)
- **Back-end:** NestJS (Node.js-based)
- **Database:** Firebase Firestore
- **Programming Languages:** TypeScript
- **Machine Learning:** Random Forest Algorithm

## Installation

### Prerequisites
- Node.js
- npm (Node Package Manager)
- Firebase account for Firestore

### Steps
1. **Clone the Repository**
    ```bash
    git clone https://github.com/daniel357/Bachelor-Thesis-Flight-Fare-Predictions.git
    cd Bachelor-Thesis-Flight-Fare-Predictions
    ```

2. **Install Dependencies**
    ```bash
    npm install
    ```

3. **Set Up Firebase Firestore**
    - Create a Firebase project and Firestore database.
    - Update the Firebase configuration in the project.

4. **Run the Application Locally**
    ```bash
    npm run dev
    ```

## Usage
1. Navigate to the home page of the application.
2. Enter your travel details including search and departure dates.
3. Submit the form to receive the optimal time to purchase your flight tickets.
4. Optionally, enter your email address to receive the prediction information.

## Dataset
The dataset used in this project is sourced from Kaggle, specifically the "Flight Prices" dataset. It contains comprehensive historical flight fare data.
## Owner: https://www.kaggle.com/datasets/dilwong/flightprices
