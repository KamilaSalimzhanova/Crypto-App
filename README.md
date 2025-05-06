# Crypto-App

A modern iOS application for tracking cryptocurrency data and managing a personal portfolio, built entirely with SwiftUI and utilizing the MVVM architecture.

## Features

Explore and manage your cryptocurrency investments with Crypto-App. This app provides:

* **Live Cryptocurrency Data:** Get up-to-the-minute price and market data for a wide range of cryptocurrencies.
* **Personalized Portfolio:** Easily track your current holdings and visualize your portfolio's value based on live market data.
* **Efficient Data Handling:** Search, filter, sort, and refresh the cryptocurrency list to find the information you need quickly.
* **Customizable Interface:** Enjoy a visually appealing experience with a custom color theme and smooth loading animations.

## Technical Details

Built with modern iOS development practices, this app showcases:

* **Architecture:** Implements the Model-View-ViewModel (MVVM) design pattern for a clear separation of concerns, improved testability, and maintainability.
* **Data Persistence:** Utilizes Core Data for reliable local storage and management of the user's portfolio data.
* **Local Asset Management:** Leverages `FileManager` for efficient caching and management of downloaded assets, such as coin icons.
* **Reactive Programming:** Employs the Combine framework for declarative handling of asynchronous events, including API responses and data flow throughout the app.
* **Networking:** Handles multiple asynchronous API calls concurrently to fetch comprehensive and up-to-date cryptocurrency data.
* **Data Decoding:** Uses Swift's `Codable` protocol for safe and efficient decoding of JSON data received from APIs into native Swift models.
* **User Interface:** Developed entirely with SwiftUI, providing a modern, declarative, and consistent user experience.
* **Performance:** Utilizes multi-threading to perform heavy operations (like network requests and data processing) on background threads, ensuring the UI remains responsive and fluid.
* **Robustness:** Incorporates best practices for error handling and uses constructs like `if let` and `guard` statements for safe unwrapping of optionals, enhancing application stability and preventing runtime crashes.

## Getting Started

To run the app locally:

1.  Clone the repository:
    ```bash
    git clone Link to this repository
    ```
4.  Select a simulator or a physical device in Xcode.
5.  Build and run the project (`Cmd + R`).
