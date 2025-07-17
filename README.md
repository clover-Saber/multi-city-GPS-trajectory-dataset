# Multi-City Taxi GPS Trajectory Dataset (Demo)

This repository provides a demo release of our **multi-city taxi GPS trajectory dataset**, collected from four major Chinese cities: **Beijing, Shanghai, Shenzhen, and Chengdu**. The dataset is designed to support research on urban mobility, ridesharing efficiency, and transportation systems.

## 🚕 Data Format

Each record in the dataset corresponds to a single GPS point from a taxi. The standardized format is shown below:

| Tag         | Description                        | Example      |
|-------------|------------------------------------|--------------|
| `VehicleNum` | Taxi ID                             | 18834        |
| `Time`       | Timestamp (HH:MM:SS)                | 14:25:21     |
| `Lng`        | Longitude                           | 121.441895   |
| `Lat`        | Latitude                            | 31.206928    |
| `OpenStatus` | Taxi status (0 = vacant, 1 = occupied) | 1         |
| `Speed`      | Speed (in km/h or relevant unit)    | -            |

> 📝 **Note**: `OpenStatus` is essential for identifying passenger-carrying segments in ridesharing analysis.

## 📦 Current Release

The current dataset is a **demo subset** that includes limited samples for preview and testing purposes. It is intended to help users understand the data structure and format.

## 🔄 Full Dataset Coming Soon

We will gradually release the **complete dataset**, covering longer time spans and more vehicles, with improved documentation and preprocessing scripts. Please stay tuned for future updates.

## 🔗 Access the Demo

You can access the demo dataset here:  
👉 [https://anonymous.4open.science/r/multi-city-GPS-trajectory-dataset-3F3D](https://anonymous.4open.science/r/multi-city-GPS-trajectory-dataset-3F3D)

---

For questions or collaboration opportunities, feel free to reach out to us.
