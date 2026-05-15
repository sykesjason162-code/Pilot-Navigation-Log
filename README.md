# Pilot Navigation Log & Flight Planner

A comprehensive flight planning and performance suite designed for student pilots, flight simulation enthusiasts (MSFS/VATSIM), and general aviation pilots. This tool digitizes the traditional paper navigation log, providing automated calculations for cross-country planning, weight and balance, and regulatory compliance.

## 🚀 Key Modules

* **Weight & Balance:** Automated CG envelope verification. Input your specific aircraft's empty weight and arms from your weight and balance records to ensure every flight is within gross weight and CG limits.
* **Navigation Log:** A complete VFR/IFR planning sheet. Calculates Magnetic Heading (MH), Compass Heading (CH), and Ground Speed (GS) based on wind correction angles and magnetic variation.
* **Fuel Management:** Built-in calculators for Trip, Taxi, and Alternate fuel. Includes automatic validation against **FAA Reserve Requirements (14 CFR 91.151 / 91.167)** for Day/Night VFR and IFR operations.
* **Performance & Atmosphere:** Pressure and Density Altitude calculators to determine actual aircraft performance based on current METAR/ATIS data (OAT and Altimeter settings).
* **Preflight Checklist:** Integrated **IMSAFE** (Personal Minimums) and **ARROW** (Required Documents) checklists to ensure both the pilot and aircraft are airworthy and legal for the flight.
* **Pilot Logbook:** A digital log to track flight hours (SEL/MEL, XC, Night, Instrument). Includes a **JavaScript/OnlyOffice Macro** to automatically archive "Current Flight" data into a permanent history log.

## 🛠️ Setup & Configuration

1.  **Aircraft Data:** Open the `Weight & Balance` and `Performance` tabs. Enter your aircraft's specific data from the **Pilot Operating Handbook (POH)**, including V-speeds, fuel burn rates (GPH), and loading stations.
2.  **Macros:** To use the automated logbook feature in OnlyOffice, copy the code from the `Macro Code` tab into the Macro Editor (View > Macros).
3.  **Inputs:** Cells highlighted in **Blue** are for user input; **Green** cells contain automated calculations or linked data.

## 📋 Flight Planning Workflow

1.  **Prep:** Complete the **IMSAFE** and **ARROW** checks in the `Preflight Checklist` tab.
2.  **Weather:** Input current conditions into the `Weather & Flight Plan` sheet to calculate your **Density Altitude**.
3.  **Loading:** Verify your payload in the `Weight & Balance` tab.
4.  **Planning:** Map your waypoints in the `Navigation Log`. Use the `Fuel Required` tab to ensure you have sufficient "Fuel on Board" for your ETE plus required reserves.
5.  **Log:** After shutdown, use the `Pilot Log` to record your time and maneuvers.

## ⚖️ Disclaimer
This tool is for educational and supplemental planning purposes. It is the responsibility of the Pilot in Command (PIC) to ensure the accuracy of all data and to refer to the approved Airplane Flight Manual (AFM) or Pilot Operating Handbook (POH) for all flight operations.
