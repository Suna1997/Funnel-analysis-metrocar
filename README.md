# Funnel-analysis-metrocar

This project aims to analyze the customer funnel of Metrocar, a ride-sharing app (similar to Uber/Lyft), to identify areas for improvement and optimization. We will use SQL for data analysis and Tableau or Google Sheets for data visualization. The stakeholders have asked several business questions that can uncover valuable insights for improving specific areas of the customer funnel. Your task is to conduct a funnel analysis and present your analysis and recommendation. Explain your reason for your recommendation based on insights retrieved from the data.



# Project Logistics

DA203.1 Explore the Metrocar Data with SQL
The first week will mainly focus on understanding the dataset using SQL. Unlike previous projects, the DA203 dataset will require less cleaning and preparation. Still, it contains more tables and properties and requires more understanding of the business (ride-sharing) and the company’s funnel.
DA203.2 Developing Metrocar Funnel Metrics
The second sprint will be focused on analyzing the data and reaching conclusions regarding the given business questions.
DA203.3 Present the Funnel Results to Stakeholders
The third sprint will be mostly reserved for preparing and recording the final submission based on your insights and recommendations.
DA203.4 Practice Week
The end of the last sprint (practice week) is the submission deadline for students who want to get feedback. Most students will use this week to finalize the last pieces of their project and to record and submit their presentations.
Students who submit the project before the deadline at the end of the unit will receive personalized feedback on their work.


# Project Background
🚗 About Metrocar

Metrocar's business model is based on a platform that connects riders with drivers through a mobile application. Metrocar acts as an intermediary between riders and drivers, providing a user-friendly platform to connect them and facilitate the ride-hailing process.





# Metrocar’s Funnel

The customer funnel for Metrocar typically includes the following stages:

App Download: A user downloads the Metrocar app from the App Store or Google Play Store.
Signup: The user creates an account in the Metrocar app, including their name, email, phone number, and payment information.
Request Ride: The user opens the app and requests a ride by entering their pickup location, destination, and ride capacity (2 to 6 riders).
Driver Acceptance: A nearby driver receives the ride request and accepts the ride.
Ride: The driver arrives at the pickup location, and the user gets in the car and rides to their destination.
Payment: After the ride, the user is charged automatically through the app, and a receipt is sent to their email.
Review: The user is prompted to rate their driver and leave a review of their ride experience.
Similar to other customer funnels, there will be drop-offs at every stage of the funnel, which is why funnel analysis can be helpful in identifying areas for improvement and optimization. For example, Metrocar may analyze the percentage of users who download the app but do not complete the registration process, or the percentage of users who request a ride but cancel before the driver arrives.


# Business questions

You will need to analyze the data and make recommendations based on the following business questions:

What steps of the funnel should we research and improve? Are there any specific drop-off points preventing users from completing their first ride?
Metrocar currently supports 3 different platforms: ios, android, and web. To recommend where to focus our marketing budget for the upcoming year, what insights can we make based on the platform?
What age groups perform best at each stage of our funnel? Which age group(s) likely contain our target customers?
Surge pricing is the practice of increasing the price of goods or services when there is the greatest demand for them. If we want to adopt a price-surging strategy, what does the distribution of ride requests look like throughout the day?
What part of our funnel has the lowest conversion rate? What can we do to improve this part of the funnel?

# The Dataset
This dataset is inspired by publicly available datasets for Uber/Lyft. The data for this dataset was generated specifically for this project.

Introducing Beekeeper Studio


Paste the following URL using the “Import from URL” option mentioned in the instructions linked above:

postgres://Test:bQNxVzJL4g6u@ep-noisy-flower-846766-pooler.us-east-2.aws.neon.tech/Metrocar
