# TripPair-presentation
ripPair is a mobile application designed to connect travelers and make group travel more accessible, personal, and fun. The app was born out of a desire to solve common problems like social isolation, the difficulty of finding travel companions, and the limitations of expensive, pre-packaged group tours.

Instead of joining a rigid, pre-planned trip, TripPair empowers users to create their own custom journeys and find like-minded people to share the adventure with. It’s an alternative to traditional tour operators that puts the user’s freedom first.
### News
TripPair is still under development, with new features being added to make the app complete and engaging.
The goal is to release it once all functionalities are ready and fully tested.
This approach ensures that users will enjoy the best possible experience while staying safe.

---
### Key Features

* **Find Travel Companions:** Users can request to join any existing trip and, for trips they've created, they can view and select their own companions.
* **Seamless Communication:** After a request is received, users can contact each other directly to get to know one another and organize trip details.
* **Customizable Trips:** Every user can create trips with complete freedom, personalizing the itinerary, type, and other trip information as they prefer.
* **Accessible to Everyone:** The costs of the trip are managed directly by the users, who organize themselves autonomously to split expenses.

---

### Technologies Used

The app is built using a modern technology stack to ensure a responsive and efficient user experience.

* **UI/UX (User Interface/User Experience):**
    * **Material Design 3:** For a modern, intuitive, and consistent interface with Android.
    * **Jetpack Compose:** To implement a dynamic, reactive, and performant UI using a declarative approach.

* **Backend and Data Management:**
    * **Firebase Realtime Database:** A third-party service for managing real-time user and trip data, enabling immediate interactions.
    * **Firebase Storage:** A third-party service for storing the images used in the application.
    * **DB Room:** Used to save user data locally on the device.

* **External Service Integrations:**
    * **WhatsApp API:** Simplifies communication by directly connecting participants.
    * **Gmail API:** Used for sending emails as a second communication method between users.

* **Software Architecture:**
    * **Model-View (MV):** Provides a separation in the code between the visual part and the logical part.
