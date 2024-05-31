# Machine Learning Path
## Description
Travt is a mobile-based application designed to offer personalized recommendations for nearby tourist attractions and culinary experiences. Our goal is to provide users with suggestions tailored to their location and preferences, thereby enhancing the visibility and accessibility of local businesses. In this application, we aim to highlight five cities in the ex-Karesidenan Kedu area: Magelang, Temanggung, Kebumen, Purworejo, and Wonosobo.

## Recommendation System
The recommendation system for Travt leverages advanced machine learning algorithms to deliver these personalized suggestions. By analyzing user preferences, behaviors, and location data, the system identifies and highlights local gems and underrated destinations. This approach not only enhances the user experience by providing tailored recommendations but also supports the growth and visibility of local businesses, particularly UMKM, in the tourism and culinary sectors. By using collaborative filtering and content-based filtering techniques, the recommendation system ensures users receive the most relevant and appealing suggestions, fostering a deeper connection with the local culture and community.

## Dataset
The dataset used to build the recommendation system for Travt consists of detailed information on tourist attractions and culinary experiences in Indonesia, with a specific focus on the ex-Karesidenan Kedu area, including Magelang, Temanggung, Kebumen, Purworejo, and Wonosobo. The dataset includes the following components:

1. **Location Data**: Contains detailed information about places, including:
    - `place_id`: Unique identifier for the place
    - `name`: Name of the place
    - `site`: Website of the place
    - `subtypes`: Specific subtypes of the place
    - `category`: Category of the place (e.g., restaurant, park)
    - `phone`: Contact phone number
    - `full_address`: Complete address of the place
    - `city`: City where the place is located
    - `latitude`: Latitude coordinate
    - `longitude`: Longitude coordinate
    - `rating`: Average rating of the place
    - `reviews`: Total number of reviews
    - `reviews_link`: Link to the reviews
    - `reviews_per_score_1` to `reviews_per_score_5`: Number of reviews per rating score
    - `photos_count`: Number of photos available
    - `photo`: URL of a photo of the place
    - `working_hours`: Regular working hours
    - `other_hours`: Additional working hours information
    - `business_status`: Current operational status of the business
    - `about`: Brief about the place
    - `description`: Detailed description of the place
    - `verified`: Verification status of the place
    - `location_link`: Link to the location on Google Maps
    - `google_id`: Google Maps ID
    - `cid`: Customer identification number
    - `reviews_id`: Identifier for the reviews

2. **User Data**: Includes anonymized user profiles with:
    - `user_id`: Unique identifier for the user
    - `location`: User's location
    - `age`: User's age

3. **Rating Data**: Contains user interaction with places, including:
    - `user_id`: Unique identifier for the user
    - `place_id`: Unique identifier for the place
    - `rating`: Rating given by the user
    - `review`: Review text provided by the user

This comprehensive dataset enables the recommendation system to analyze and understand user preferences, behaviors, and contextual factors, facilitating the delivery of highly personalized and relevant suggestions.
