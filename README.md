# Google Maps Geocoding Custom Connector  

## Overview  
The **Google Maps Geocoding Custom Connector** for **Power Automate and Power Apps** enables seamless integration with the **Google Maps Geocoding API**, allowing users to convert addresses into geographic coordinates (geocoding) and retrieve addresses from latitude/longitude data (reverse geocoding). You can also add Address descriptors which provide richer location details by including nearby landmarks and areas in geocoding results. 

## Features  
- 📍 **Geocoding** – Convert addresses into latitude/longitude coordinates.  
- 🔄 **Reverse Geocoding** – Retrieve detailed address information from geographic coordinates.  
- 🏢 **Address Descriptors** – Extract metadata such as place types and location descriptors.  

## Prerequisites  
- 🔹 **Google Cloud Platform (GCP) account** with the **Geocoding API enabled**.  
- 🔹 **API Key** from Google Maps Platform.  
- 🔹 **Power Platform environment** (Power Automate, Power Apps, or Logic Apps).  

## API Endpoint Used  
```plaintext
https://maps.googleapis.com/maps/api/geocode/json?address={ADDRESS}&key={API_KEY}&latlng={LATITUDE},{LONGITUDE}&extra_computations=ADDRESS_DESCRIPTORS

## Installation  

### 1️⃣ Clone this repository  
```sh
GoogleMapsConnectorSolution_1_0_0_1.zip
