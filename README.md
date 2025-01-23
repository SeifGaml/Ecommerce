# MVVM E-commerce Application (Android)

This is a sample MVVM-based e-commerce application built for Android using the Kotlin programming language. The application showcases 100 different products across various categories.

## Features:
- Display a range of products from multiple categories.
- Uses the MVVM architectural pattern to structure the app.
- Integrates various Android libraries to simplify development.

## API:
The application uses an API to interact with the backend, allowing it to fetch product details and display them in the app.

## Dependencies:

| **Name**           | **Description**                                                                                                                                                 |
|--------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **LiveData**        | LiveData is an observable data holder class that allows us to monitor changes in data. LiveData is lifecycle-aware and helps ensure that data updates are only made when the UI is in a valid state. |
| **Retrofit**        | Retrofit is a type-safe HTTP client for Android and Java that simplifies making API calls and parsing responses.                                                  |
| **RxJava**          | RxJava is a library that enables composing asynchronous and event-based programs using observable sequences, making asynchronous programming easier to manage.      |
| **Coroutines**      | Coroutines simplify asynchronous programming by allowing operations to run in the background without blocking the main thread. It’s used to handle tasks like network calls and database operations. |
| **Room**            | Room provides an abstraction layer over SQLite, allowing you to interact with a local database seamlessly. It simplifies database operations while ensuring full access to SQLite. |
| **View Binding**    | View Binding allows you to interact with views in a more efficient and type-safe manner. It eliminates the need for `findViewById()` calls and helps avoid null pointer exceptions. |
| **MVVM**            | MVVM (Model-View-ViewModel) is the architectural pattern used in this app: <br> - **Model**: Contains the data of the application. <br> - **View**: Represents the UI elements of the application. <br> - **ViewModel**: Mediates between the Model and the View. |
| **Data Binding**    | Data Binding allows you to bind UI components in layouts to data sources declaratively, rather than writing code to update views manually.                         |
| **Jetpack**         | Jetpack is a suite of libraries, tools, and architectural guidance that simplifies app development. It includes libraries like Room, Hilt, Paging, and Data Binding. |
| **Glide**           | Glide is an image loading and caching framework for Android that allows you to load images from the web or local storage with minimal setup.                      |

## Contributions:
Feel free to fork the repository and contribute by submitting pull requests. If you find any bugs or have feature suggestions, don't hesitate to open an issue.

Don't forget to star the project if you like it! ❤️ == ⭐
