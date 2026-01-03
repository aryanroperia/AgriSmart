# The AgriSmart App

## Overview
The AgriSmart app is a comprehensive solution aimed at optimizing the daily agricultural activities of farmers in the Indian subcontinent region. India has one of the largest agricultural workforces in the world, employing 42% of the country's workforce. Android's share of the mobile operating system market in India is 95% as of 2023. This inherently leads to a large target customer pool for this application. The app offers a suite of features such as real-time weather tracking, detailed crop information, disease management resources, skill development content, and task management tools, all of which act in conjunction to ensure better farming practices are followed. It integrates several APIs and is built using the industry vetted and recommended MVVM architecture for enhanced performance and scalability. This app was made by a team consisting of myself, Aryan Roperia, Arjen Fuller, and Max Bitterman. We were mentored to make this app under Yash Khatri, a current student at IIIT Delhi.

## A list of functions this app contains
- **Weather Tracking:** Keep the user updated with real-time local weather conditions and weather forecast
- **Crop Information:** Access a vast repository of plant data to help farmers follow optimal practices.
- **Disease Control:** Identify common plant diseases with detailed descriptions of symptoms and treatment options.
- **Skill Development:** Explore educational content and resources to improve farming techniques and stay modern with practices.
- **Task Management:** Organize farming tasks efficiently. Prioritize tasks with the alarm feature for timely plant care.


## Technology
- Firebase: Utilized for authentication, firebase is used to manage both login and signup processes.
- Databases are implemented for efficient local data storage.
- News: WebView is used to display farmer news from the Krishi Jagran website.
- API:
  - A Weather API is integrated for tracking weather conditions.
  - SheetDB is used to handle additional data requirements.
- The app follows the MVVM (Model-View-ViewModel) architecture to maintain clean and organized code.
- UI:
  - RecyclerView is used for displaying lists within the user interface.
  - Fragments ensure a faster and more responsive user experience.
  - Splash screen is added for an engaging start-up
