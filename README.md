# Job Application App

## Overview

The Job Application App is a mobile application developed using React Native. It provides a user-friendly interface that allows users to search for specific types of jobs based on technologies or types of work. The app integrates with the Jsearch API from RapidAPI to fetch job details, and it offers features such as job search, popular jobs, recent/nearby jobs, and detailed job information.

## Features


The Job Application App offers the following key features:

1. **Job Search:** Users can search for jobs based on technologies or types of work. The app provides a search functionality that allows users to enter specific keywords related to their desired job and retrieves relevant results.

2. **Popular Jobs:** The app displays a section showcasing popular jobs. These jobs are determined based on factors such as the number of views, user ratings, and overall demand.

3. **Recent/Nearby Jobs:** Users can explore recently posted job opportunities or search for jobs in their vicinity. The app utilizes location data to suggest nearby jobs or allows users to filter job listings based on proximity.

4. **Job Details:** When users click on a specific job, the app displays a detailed job page. This page includes comprehensive information about the job, such as required qualifications, responsibilities, company details, and any additional relevant information.

5. **RapidAPI Integration:** The app integrates with the RapidAPI platform and utilizes the Jsearch API to fetch job details. This API provides access to a vast database of job listings, ensuring that users have access to up-to-date and relevant job information.

6. **User Interface and User Experience:** The Job Application App is designed with a focus on providing an intuitive and visually appealing user interface (UI) and user experience (UX). The interface is optimized for mobile devices and follows best practices for mobile app design.

## Getting Started

To run the Job Application App locally or deploy it to a mobile device, follow these steps:

1. Clone the repository from GitHub: https://github.com/SAIKmar-1729/Job_App_React_Native.git.

2. Install the necessary dependencies by running the following command:
  ```sh 
  npm install
```
  
1. Obtain an API key from RapidAPI by signing up on their website: https://rapidapi.com/

2. LogIn into rapidapi and search for ### Jsearch API.

3. Replace the placeholder API key in the .env file with your actual RapidAPI key.
```js
RAPID_API_KEY = [YOUR_RAPID_API_KEY]
```
1. Build and run the app using the appropriate command for your target platform:

For iOS:
```sh
npm run ios
```

For Andriod:
```sh
npm run andriod
```

1. The app should launch on the iOS Simulator or an Android emulator/device.

## Technologies Used
The Job Application App is built using the following technologies:

* React Native: A JavaScript framework for building mobile applications.
* RapidAPI: An API marketplace that provides access to various APIs, including the Jsearch API for job data.
* JavaScript: The programming language used for developing the mobile application.
