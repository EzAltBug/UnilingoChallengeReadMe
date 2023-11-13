# Unilingo Challenge - Ezequiel Altamirano

## UPDATE - 13/11
Challenge is fully operational, with all its functionalities ready to test!
I stay alert for any news

## First deploy - 10/11

Hi! Here i will explain what i have done until today in this little proyect.
Here's the [URL](https://lucky-pixie-a4b93c.netlify.app) to the proyect.

I have made a Frontend app in React using Material-UI, Hooks, Axios (to communicate with backend APIs), deployed it on Netlify, a Java Spring Boot backend API that uses Youtube API v3 for the initial 1-2 checkpoints, deployed on Google Cloud Platform, and a Python API for handling youtube video download, also deployed in Google Cloud Platform.

Until now i just reached to complete until checkpoint 2. 

## Why only checkpoint 2? 
I've made some decisions on the run for the development, some of them couldn't give the performance i've wanting to and had to make big refactorings in little time.

Some of them where specifically for checkpoint 3, i've started trying to handle the video on a iframe in the front, then realized that was better to handle the file in backend to ease future developments (checkpoint 4 and 5).
I started developing a Youtube video downloader in Java (in the main backend API i developed). Then, testing the API, I realized that it had a very poor performance, since it took approximately 40-50 seconds per request.

Then started to develop an Python API that responses in approximately 2 seconds, but had some trouble deploying it and integrating it.

I already have the Python API deployed, just need to handle the audio file in the UI and play it, but im out of time right now.
I'll keep working on the project over the weekend to complete every checkpoint, and updating this README.MD with any news that i have on this proyect.

I apologize for don't having the mini proyect on time, as i wanted to deliver to you, and thank you for the opportunity.

Best Wishes, Eze.



