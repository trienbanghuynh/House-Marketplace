# House Marketplace
A React + Firebase v9 project
Purpose: Search and list houses for sale or for rent.


## Usage

### Geolocation

The listings use Google geocoding to get the coords from the address field. You need create .env file and add your Google Geocode API key OR in the **src/pages/CreateListing.jsx** file you can set **geolocationEnabled** to "false" and it will add a lat/lng field to the form.

### Install Dependencies

```
npm install
```

### Run

```
npm start
```
