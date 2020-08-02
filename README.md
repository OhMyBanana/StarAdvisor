# StarAdvisor
Find and share the best stargazing spots near you!

## Inspiration
It was a beautiful summer night outside, here in north New Jersey. Not too hot, not too cloudy and above all else - perfect for stargazing! Or so you might think. You see, even on cloudless summer nights like those, there's no guarantee that one can see stars in the sky due to a myriad of factors ranging from light pollution to tree coverage. But every experienced stargazer has 'that one spot.' The spot the veteran stargazer might have randomly stumbled upon with an immaculate view of the surrounding universe. The spot so good that they want to share it with the world. So our team thought, what if there were some way to share the best places to look at the night sky near you via some sort of app? That's where StarAdvisor comes into play!

## What it does
StarAdvisor is an android app that takes in the user's location and converts it to coordinates using Radar.io, searches a database for user-submitted locations within a twenty mile radius and displays those locations on a map embedded into the android app. This embedded map then allows users to get directions to that location externally in Google Maps. StarAdvisor also allows for users to submit locations where they gaze at the stars themselves to our database for all users to see. We take in weather data that

## How we built it
StarAdvisor was coded from the ground up in Android Studio using Java and XML. The program is compatible with newer Android devices and was tested on a simulated Nexus 6 API 28. We used the Radar.io API's geocoding capabilities to convert the address into a location and compute the distance between the user's location and locations in the database. StarAdvisor also uses two services provided by the Google Cloud Platform: Google Firebase as a database and the Google Maps API to display a map of the locations in the database.

## Challenges we ran into
The hardest parts of this project were overcoming our own unfamiliarity with the APIs and services we used. Only two of us had used Android Studio before (and none of us had substantial experience in XML), only one of us had used Firebase and the Google Maps API was new to all of us. Considering there were only three of us, from the very get-go, you could say we were shooting for the stars. We also had initially intended for users to be able to see live weather data as well as information on light pollution in the area as well as the user-generated locations however due to time constraints we were unable to add these features.

## Accomplishments that we're proud of
To say the least, this Hackathon project marked a lot of firsts for all of us. First time using XML and Android Studio for some, and first time using Firebase and the Google Maps API for others. This project was certainly a heavy undertaking but it showed us that when you work hard and think outside the box, the sky is, in fact, NOT the limit! Even though there is still much that can be done with this project, we are thrilled to present a functional proof of concept to the judges of "To the Moon and Hack," and we look forward to collaborating again on more projects in the future.

## What's next for StarAdvisor
There were several additional features that we wanted to implement but couldn't due to time constraints. Above all else we want to implement a user rating system to weed out which stargazing spots are worth the trip and which aren't. We also want to have more information available to our users regarding the locations such as cloud coverage, tree density, public access or not, light pollution levels and even which stars are in the sky on that night. Eventually, we'd also like to implement some sort of interactivity between our users to create a StarAdvisor community! So stay tuned because there is no telling what the future has in store for StarAdvisor!
