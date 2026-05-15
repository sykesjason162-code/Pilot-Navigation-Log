# Pilot Navigation Log & Flight Planner

A comprehensive flight planning and performance suite designed for student pilots, flight simulation enthusiasts (MSFS/VATSIM), and general aviation pilots. This tool digitizes the traditional paper navigation log, providing automated calculations for cross-country planning, weight and balance, and regulatory compliance.

## 🚀 Key Modules
<img width="1375" height="733" alt="image" src="https://github.com/user-attachments/assets/682de84c-41fe-4f4c-9df6-712d03c953cb" />

* **Weight & Balance:** Automated CG envelope verification. Input your specific aircraft's empty weight and arms from your weight and balance records to ensure every flight is within gross weight and CG limits.

<img width="1463" height="727" alt="image" src="https://github.com/user-attachments/assets/cbb1b176-3996-447a-afe0-f7c2cdb3e55b" />

* **Navigation Log:** A complete VFR/IFR planning sheet. Calculates Magnetic Heading (MH), Compass Heading (CH), and Ground Speed (GS) based on wind correction angles and magnetic variation.

<img width="1347" height="735" alt="image" src="https://github.com/user-attachments/assets/b6cc1b78-3d75-45e1-bdb0-a4957993fe46" />

* **Fuel Management:** Built-in calculators for Trip, Taxi, and Alternate fuel. Includes automatic validation against **FAA Reserve Requirements (14 CFR 91.151 / 91.167)** for Day/Night VFR and IFR operations.

<img width="1417" height="726" alt="image" src="https://github.com/user-attachments/assets/3ce705b7-89bb-46bc-828e-c6c1c929af2c" />

* **Performance & Atmosphere:** Pressure and Density Altitude calculators to determine actual aircraft performance based on current METAR/ATIS data (OAT and Altimeter settings).

<img width="1513" height="746" alt="image" src="https://github.com/user-attachments/assets/7549223e-624b-4a7a-a033-0d9f9f0699cb" />

* **Preflight Checklist:** Integrated **IMSAFE** (Personal Minimums) and **ARROW** (Required Documents) checklists to ensure both the pilot and aircraft are airworthy and legal for the flight.

<img width="1464" height="687" alt="image" src="https://github.com/user-attachments/assets/eba9f23c-f8a3-48bf-9aa3-c465ad2e3223" />

* **Pilot Logbook:** A digital log to track flight hours (SEL/MEL, XC, Night, Instrument). Includes a **JavaScript/OnlyOffice Macro** to automatically archive "Current Flight" data into a permanent history log.

## 💻 Macro & Automation Setup

The `LogFlight` macro automates the process of moving your "Current Flight" data (Row 4) into your permanent "Flight History" (Row 6+). 

<img width="1901" height="877" alt="Screenshot 2026-05-15 020041" src="https://github.com/user-attachments/assets/855e4e91-ad4f-4a0b-8ef1-0501b2d2cb3d" />

*A dedicated button is already created on the Pilot Log sheet for easy assignment.*

### 🔵 OnlyOffice (Optimized)
1. Open the **Macro Code** sheet in the workbook and copy the JavaScript code.
2. Go to **View > Macros > New Macro**.
3. Paste the code and click **Run**.
4. **To Assign:** Right-click the "Log Flight" button shown above and select the macro you just created.

### 🟢 Google Sheets
1. Import the `.xlsx` file into Google Drive.
2. Go to **Extensions > Apps Script**.
3. Paste the Google Sheets compatible code found in the **Macro Code** sheet.
4. **To Assign:** Right-click the button image, click the three dots (top right of the image), select **Assign script**, and type the name of the function (e.g., `logFlight`).

### 🔴 Microsoft Excel
* **Note:** You will need a version of Excel that supports premium automation features (Office Scripts for Web or VBA for Desktop).
* Right-click the button to assign your specific VBA macro or Office Script.

## 📋 Flight Planning Workflow

1.  **Prep:** Complete the **IMSAFE** and **ARROW** checks in the `Preflight Checklist` tab.
2.  **Weather:** Input current conditions into the `Weather & Flight Plan` sheet to calculate your **Density Altitude**.
3.  **Loading:** Verify your payload in the `Weight & Balance` tab.
4.  **Planning:** Map your waypoints in the `Navigation Log`. Use the `Fuel Required` tab to ensure you have sufficient "Fuel on Board" for your ETE plus required reserves.
5.  **Log:** After shutdown, use the `Pilot Log` to record your time and maneuvers.

## ⚖️ Disclaimer
This tool is for educational and supplemental planning purposes. It is the responsibility of the Pilot in Command (PIC) to ensure the accuracy of all data and to refer to the approved Airplane Flight Manual (AFM) or Pilot Operating Handbook (POH) for all flight operations.
