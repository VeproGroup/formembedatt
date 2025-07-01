# 📍 Google Form Attendance with Geolocation Auto-Fill

This project embeds a Google Form for attendance and automatically appends geolocation data (timestamp, coordinates, and address) to the linked Google Sheet using **Google Apps Script** and the **OpenCage Geocoding API**.

## 🚀 Features

- 📋 Embedded Google Form for seamless attendance entry
- 🌍 Automatically appends:
  - Current timestamp (`GeoStamp`)
  - Latitude & Longitude (`GeoCode`)
  - Human-readable address (`GeoAddress`)
- 🧠 Uses [OpenCage Geocoding API](https://opencagedata.com/) for reverse geocoding
- 🔁 Redirects to Apps Script endpoint after submission for further logic

