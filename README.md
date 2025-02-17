# Google Maps Geocoding Custom Connector  

## Overview  
The **Google Maps Geocoding Custom Connector** for **Power Automate and Power Apps** enables seamless integration with the **Google Maps Geocoding API**, allowing users to:  

- Convert addresses into geographic coordinates (**Geocoding**).  
- Retrieve addresses from latitude/longitude data (**Reverse Geocoding**).  
- Include **Address Descriptors** to provide richer location details such as nearby landmarks and areas.  

## Features  
- 📍 **Geocoding** – Convert addresses into latitude/longitude coordinates.  
- 🔄 **Reverse Geocoding** – Retrieve detailed address information from geographic coordinates.  
- 🏢 **Address Descriptors** – Extract metadata such as place types and location descriptors.  

## Prerequisites  
Before using this connector, ensure you have the following:  

- 🔹 A **Google Cloud Platform (GCP) account** with the **Geocoding API enabled**.  
- 🔹 A valid **API Key** from Google Maps Platform.  
- 🔹 Access to a **Power Platform environment** (Power Automate, Power Apps, or Logic Apps).

## Installation  

### 1️⃣ Download Unmanaged Solution
```sh
GoogleMapsConnectorSolution_1_0_0_1.zip
```
### 🔄 Import the Solution into Power Platform
- Open Power Apps or Power Automate Home Page.
- Navigate to Solutions > Import Solution.
- Click Browse, select GoogleMapsConnectorSolution_1_0_0_1.zip, and upload.
- Click Next and follow the installation step


## API Endpoint Used  
```plaintext
https://maps.googleapis.com/maps/api/geocode/json?address={ADDRESS}&key={API_KEY}&latlng={LATITUDE},{LONGITUDE}&extra_computations=ADDRESS_DESCRIPTORS

