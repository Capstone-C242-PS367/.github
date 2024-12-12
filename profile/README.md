## Bangkit Capstone-C242-PS367
The documentation of <b>Finky</b> application in Bangkit Capstone Project 2024

## About
Finku is an app for recapping income and outcome by mutation account or bank e-statement. To get started, users need to upload the mutation account or bank e-statement with image format, the system will recognize the transaction details, such as type (debt or credit), date, and amount. Before submitting the data, the user can validate the result and edit if necessary. After that user submits the form, the data will be stored to their account where users can view their monthly trends through interactive charts and summaries, with the option to send it to their email account.

The problem we aim to solve is the time-consuming and also the inconsistent of the manual financial tracking. By automating data extraction from bank mutation or e-statement using OCR, allowing users to efficiently monitor their financial activity without the need for any complex finance knowledge and constant manual input. We hope by building this app, we can help people to recap their financial activities and make better financial decisions while saving more times.

## The Team

|            Member           | Student ID |        Path        |                    Role                    |                                                       Contacts                                                      |
| :-------------------------: | :--------: | :----------------: | :----------------------------------------: | :-----------------------------------------------------------------------------------------------------------------: |
|        Muhammad Fathan Assadad        | M002B4KY2835 |  Machine Learning  |         Machine Learning Engineer          |         [Github]()           |
|     Ashanti Fairuza    | M002B4KX0691 |  Machine Learning  |          Machine Learning Engineer         |  [Github]()  |
|     Annisa Risty     | M002B4KX0583 |  Machine Learning   |          Machine Learning Engineer                     |   [Github]()             |
|    Muhhamad Syauqi Jannatan     | C002B4KY3142 |  Cloud Computing   |         DevOps Engineer, Backend Engineer          |   [Github]()    |
|   Afnan Edsa Ramadhan   | C002B4KY0160 |  Cloud Computing|     DevOps Engineer, Backend Engineer               |   [Github]()            |
|      Falih Naufal      | A782B4KY1385 |  Mobile Development|    Android Mobile Developer, Designer                | [Github]() |
|      Al Hajjri Prima Saputra      | A497B4KY0309 |  Mobile Development|    Android Mobile Developer                | [Github]() |

## Repositories

|   Learning Paths   |                                Link                                |
| :----------------: | :----------------------------------------------------------------: |
| Mobile Development | [Github]() |
|  Cloud Computing  | [Github]()  |
|   Machine Learning  | [Github]()  |


## Mobile Development Documentation
The source code of Android app of Travens using Kotlin in order to complete Bangkit Capstone Project.



 - ### Feature
      * **Splash Screen**, There is logo screen before into the login page

      * **Login**, Allows a user to gain access to an application by entering their username and password

      * **SignUp**, Enables users to independently register and gain access to the system

      * **Home**, The start page that is displayed when you have logged in on your device
      
      *  **Profile**, page to view user profiles and display user posts
 
      * **PetLens**, You can take image from camera in preparation for uploading an image to detect Race of animals.

      * **Send image to server to detect race of animals**, After you prepare the image, you can click the process button to send the image and detect the image and get the detail about the race.


* #### Dependencies :
  - [Jetpack Compose](https://developer.android.com/jetpack/compose)
  - [Lifecycle & Livedata](https://developer.android.com/jetpack/androidx/releases/lifecycle)
  - [Navigation Component](https://developer.android.com/jetpack/androidx/releases/navigation)
  - [kotlinx-coroutines](https://developer.android.com/kotlin/coroutines)    
  - [Retrofit 2](https://square.github.io/retrofit/)   
  - [StickyScrollView Library](https://github.com/amarjain07/StickyScrollView)    
  - [Ok Http 3](https://square.github.io/okhttp/) 
  - [Place API](https://developers.google.com/maps/documentation/places/android-sdk) 

### Getting Started Application

  - ### Prerequisites
      - ##### Tools Sofware
        - [Android Studio](https://developer.android.com/studio)
        - JRE (Java Runtime Environment) or JDK (Java Development Kit).

      - #### Installation
        - Get an API Key at [Google Maps Platform](https://developers.google.com/maps/documentation/android-sdk/get-api-key)
        - Clone this repository and import into Android Studio    
            ```
               https://github.com/ferddev21/pet2home.git
            ``` 
        - Enter your API in buildConfigField `build.graddle`
           ``` defaultConfig {
               buildConfigField("String", "MAPS_API_KEY", '"Your Api Key"')}
  ## Acknowledgements
  * [Clean Architecture Guide](https://developer.android.com/jetpack/guide)
  * [Android Application Fundamental](https://developer.android.com/guide/components/fundamentals)
  * [Android Jetpack Pro](https://developer.android.com/jetpack)
  * [Dependency injection](https://developer.android.com/training/dependency-injection)


## License
Distributed under the MIT License. See `LICENSE` for more information.

<p align="right"> Keep the Bangkit Spirit and Stay Safe! <br> Capstone-C242-PS367 Teams </p>
