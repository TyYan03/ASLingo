# ASLingo
[![Watch the demo](https://img.youtube.com/vi/bdNJBdGzC-I/0.jpg)](https://www.youtube.com/watch?v=bdNJBdGzC-I)

## Inspiration

We developed this app to empower individuals with the gift of communication through sign language and bridge the gap between the hearing and deaf communities. Our inspiration is the belief that everyone deserves a voice, and we're committed to making communication more accessible and inclusive for all.

## What it does

Our app offers a comprehensive learning experience for sign language enthusiasts. It includes interactive learning modules, engaging practice exercises, and fun quizzes to strengthen your sign language skills. Utilizing computer vision technology, you can practice signs by making them in front of your camera, and the app provides real-time feedback to help you refine your signing accuracy. Whether you're a beginner or looking to enhance your sign language proficiency, our app is designed to make learning enjoyable and effective.

## How we built it

We started by filming ourselves doing sign language and taking screenshots at quick intervals to build up a database of 100 images for each letter in the alphabet. We then cropped each image, so it only included a hand. After cleaning up our database, we then passed all 2600 images to a forest regression model in an 80% training and 20% testing split. Once the model was fully trained, we began building our website to host this model. We developed pages for a home, about us, learning, and quiz section.

## Challenges we ran into

We were having some difficulties connecting our model to the frontend of our website and getting our model to properly train at the beginning.

## Accomplishments that we're proud of

We've very proud of how similar our final product resembled what we first envisioned at the beginning of this hackathon. We're also super ecstatic of how well the application actually functions, and all the new skills we learnt while developing it.

## What we learned

We learned how to extract a ML model and to host it in a separate application. We also learned how to develop our own fully functional user-friendly website. We also learned some of the basic principles of designing, training, and testing a deep learning model.

## What's next for ASLingo

Developing better learning modules/quizzes.
More customizable learning journey.
