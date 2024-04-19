# Weather-App
Android Studio Project

The Weather-App project is an Android application that retrieves the device's location coordinates (longitude and latitude) and sends this data to an API using an API key. The API returns a JSON response from which we extract the required data, such as the temperature and city of the location.

To make the Weather-App work, we need to request three permissions from the system:
- Coarse Location: `<uses-permission android:name="android.permission.ACCESS_COARSE_LOCATION"/>`
- Fine Location: `<uses-permission android:name="android.permission.ACCESS_FINE_LOCATION"/>`
- Internet: `<uses-permission android:name="android.permission.INTERNET"/>`

To retrieve the JSON data, we use the Volley Library, which is an HTTP library that simplifies networking in Android apps. Add `implementation com.android.volley:volley:1.1.1` to the Gradle app file.

Here is an overview of the Weather-App project:
- We have already generated an API key and obtained the location coordinates.
- We make a request to the API using the URL provided to retrieve the weather data.

## Layout

![Weather-App Screenshot](https://user-images.githubusercontent.com/93143666/189376444-9ae93757-7618-410c-a17e-e6dc8ef9c256.png)

Feel free to connect with us on these platforms for any inquiries, feedback, or collaboration opportunities.
# Support 
If you liked the project, please give it a star ⭐

# Feedback 
If you have any feedback, please reach out to me!!

# Contributing 
Contributions are always welcome!
