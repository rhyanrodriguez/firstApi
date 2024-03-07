# Ambient Temperature Data Collection API

## Overview
The Ambient Temperature Data Collection API is a simple tool designed to gather temperature data from various environments using local sensors. This data is then securely transmitted to a cloud-hosted PostgreSQL database. The API is capable of computing the average temperature for each room individually and logs relevant time and date information. Aimed primarily at healthcare and hospital settings, this API ensures accurate temperature monitoring to maintain optimal conditions.

## Features

- **Data Collection**: Collects ambient temperature data from local sensors strategically placed in different rooms or areas.
- **Cloud Database Integration**: Seamlessly sends collected data to a PostgreSQL database in the cloud for secure storage and easy access.
- **Temperature Averages**: Calculates and provides the average temperature of individual rooms, allowing for detailed environmental control.
- **Time and Date Logging**: Records the time and date for each data entry, facilitating historical data analysis and trend observation.
- **Healthcare and Hospital Use**: Specifically designed with healthcare and hospital environments in mind, ensuring compliance with regulatory standards for patient care environments.
- **Automatic Temperature Adjustment**: A forthcoming feature that will enable the API to communicate with a control system to automatically adjust the internal temperature based on external conditions, promoting energy efficiency and consistent environmental conditions.
- **Future GoLang Rebuild**: Plans for a future rebuild in GoLang to enhance API performance, with a focus on more efficient data processing and integration capabilities.

