 # Find Map Route with Intermediate Points


This project allows users to find a route on a map from a source (src) to a destination (dest) via two intermediate points. It leverages Google APIs for geocoding, distance calculation, directions, and places, while also incorporating reCAPTCHA for user verification during registration.

After setting up djanago enviroment go to the setiings of route , scroll down to bottom
  - Find google api key and recaptcha 
  - generate your own keys and add there brfore using .


## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)

## Introduction

This project aims to provide users with a convenient way to find a route on a map, including two intermediate points, from a specified source to a destination. It leverages various Google APIs to perform tasks like geocoding (converting addresses to coordinates), calculating distances between points, generating directions, and searching for places of interest along the route. Additionally, reCAPTCHA is integrated into the registration process to ensure user authenticity.

## Features

- **Find Map Route**: Users can input a source (src) and destination (dest), along with two intermediate points, to find a route on a map.

- **Geocoding**: The project utilizes the Geocoding API to convert addresses into coordinates for accurate routing.

- **Distance Calculation**: The Distance Matrix API is used to calculate the distances between points.

- **Directions**: The Directions API generates step-by-step directions for the chosen route.

- **Places Search**: The Places API allows users to search for points of interest along the route.

- **reCAPTCHA**: Registration includes reCAPTCHA verification to prevent automated bot sign-ups.

## Technologies Used
- Django
- jQuery, HTML, CSS
- reCAPTCHA
- Google Maps APIs

## Getting Started

To get started with this project, follow these steps:

### Prerequisites

Before you can use this tool, make sure you have the following prerequisites:

- Django: [Installation Guide](https://docs.djangoproject.com/en/3.2/intro/install/)
- Google API Key: Generate your own Google Maps API key and reCAPTCHA key. Add these keys to the project settings before using the tool.
- Install required files by command(pip install -r requirements.txt)

### Installation

1. Clone this repository to your local machine:

   ```bash
   git clone https://github.com/suraj-ps25/Map-Route.git
