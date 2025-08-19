# 🏢 Onboard Project

>[!Note]
> **EDUCATIONAL PROJECT DISCLAIMER**
>
>This project is developed purely for **educational and demonstrative purposes**. While it aims to provide useful public transport information for Milan, it relies on data sources, including scraping information from `giromilano.atm.it`.
>
>**The terms of service for ATM (Azienda Trasporti Milanesi) regarding data usage are not explicitly clear, and this project may potentially violate them.**
>
>Therefore:
>- **Use at Your Own Risk:** We do not guarantee the accuracy or continued availability of the data, nor do we assume responsibility for any consequences arising from its use.
>- **Unscheduled Discontinuation:** This project, or parts of it, may be taken down or become non-functional unexpectedly if ATM's policies change or if the data sources become inaccessible.
>
>We advise caution and understanding of these limitations.

Welcome to the **Onboard Project**, your ultimate companion for navigating public transport in Milan, Italy! 🇮🇹 This open-source initiative aims to provide a comprehensive, real-time, and user-friendly experience for commuters and visitors alike.

## 🌟 What is Onboard?

Onboard is a multi-platform application designed to make your journey through Milan seamless. It features:

*   **Real-time Information:** Get live updates on public transport vehicle arrivals and waiting times.
*   **Interactive Map:** Explore all public transport stops and lines on a custom-designed, detailed map of Milan.
*   **Comprehensive Data:** Access information for both surface transport (buses, trams) and metro lines.
*   **Cross-platform Availability:** Use Onboard on Windows, Android, and Web.

## ⚙️ How It Works

The Onboard ecosystem is built on a robust architecture, combining various technologies to deliver accurate and timely information:

1.  **Data Sourcing:** Information is meticulously scraped from `giromilano.atm.it` and augmented with open data sources.
2.  **Vercel Python Backend:** A powerful Python server processes and serves this data, ensuring efficiency and scalability.
3.  **Custom Raster Maps:** Unique, performant raster tiles, hosted on GitHub, provide a beautiful and informative map experience.
4.  **Flutter Client:** The front-end application, built with Flutter, consumes the data and renders the user interface across multiple platforms.

## 🚀 Our Vision

Our goal is to create the most reliable and user-friendly public transport app for Milan, leveraging open-source principles and community contributions. We believe that better transport information leads to better urban experiences.

## 📚 Repository Overview

The Onboard Project is modularly organized into several repositories, each serving a specific purpose:

*   [`onboard-project/client`](https://github.com/onboard-project/client): The Flutter application, available for Windows, Android, and Web. ***Coming Soon***
*   [`onboard-project/server`](https://github.com/onboard-project/server): The Vercel Python backend for real-time data processing and API serving.
*   [`onboard-project/sdk`](https://github.com/onboard-project/sdk): Dart package to consume and model data from the Onboard server.
*   [`onboard-project/maps`](https://github.com/onboard-project/maps): Contains the custom raster map tiles and the generation tools.

*   [`onboard-project/stopsgen`](https://github.com/onboard-project/stopsgen): Python script for generating consolidated public transport stop data.
*   [`onboard-project/.github`](https://github.com/onboard-project/.github): Central configuration and this organization's main README.



This project is licensed under the GNU GPL v3.0 License.
