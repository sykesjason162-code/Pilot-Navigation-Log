# Pilot Navigation Log & Flight Planner

A professional-grade flight planning suite designed to streamline pre-flight calculations and in-flight navigation. Built for student pilots, flight simmers (MSFS/VATSIM), and general aviation enthusiasts who prefer a structured, "process-oriented" approach to flight planning.

## 🚀 Features

This workbook is divided into specialized modules to cover every aspect of a flight from planning to shutdown:

* **Navigation Log:** A detailed leg-by-leg planner including VOR frequencies, courses, altitudes, and time/fuel estimates.
* **Weight & Balance:** Automated CG envelope calculator. Input your aircraft's specific arms and weights to ensure you are within limits.
* **Performance & Atmospheric Calc:** Integrated Pressure/Density Altitude calculator and wind component (headwind/crosswind) tool.
* **Fuel Requirements:** Detailed fuel planning including Trip, Taxi, Reserve (FAA Minimums), and Alternate fuel calculations.
* **Preflight Checklist:** Digital implementation of IMSAFE and ARROW requirements to ensure pilot and aircraft readiness.
* **Digital Pilot Log:** A dedicated sheet to track flight history, including a built-in macro for committing "Current Flight" data to long-term history.

## 🛠️ Getting Started

### Prerequisites
* **Microsoft Excel** or **OnlyOffice** (Recommended for Macro compatibility).
* Your aircraft's **Pilot Operating Handbook (POH)** for V-speeds and performance data.

### Installation
1.  Clone this repository or download the `.xlsx` file.
2.  Open the file and navigate to the **Performance** tab to enter your aircraft's specific V-speeds (Vx, Vy, Va, etc.).
3.  (Optional) For the Pilot Log automation, refer to the `Macro Code` tab to install the `LogFlight` script.

## 📋 How to Use

1.  **Weather & Flight Plan:** Start by pulling your METARs and winds aloft. Fill out the Weather & Flight Plan tab.
2.  **Performance:** Enter the Field Elevation and Altimeter setting to calculate your Density Altitude. This will help you determine your ground roll and climb rates.
3.  **Weight & Balance:** Update the blue cells with your actual payload (passengers, baggage, and fuel) to verify your CG is within the envelope.
4.  **Navigation Log:** Plot your waypoints. The sheet will help you calculate your Magnetic Heading (MH) and Compass Heading (CH) based on wind correction.
5.  **Log Your Flight:** Once the flight is complete, use the **Pilot Log** tab to record your time.

## 📜 Macros
The repository includes a `LogFlight` macro (located in the `Macro Code` tab) designed for OnlyOffice. This script automates the process of moving your completed flight data into your permanent flight history.

## ⚖️ Disclaimer
*This tool is intended for flight simulation and educational purposes only. Always cross-check calculations with an official Pilot Operating Handbook (POH) and approved flight planning software before conducting real-world flight operations.*
