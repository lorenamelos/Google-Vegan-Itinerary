# Vegan Itinerary Planner with LangChain and Google Maps 📍🗺️🌱

This repository contains a web application that helps users find vegan restaurants and create travel itineraries using LangChain and Google Maps API. The application is built with Gradio for the user interface.

## Features
- Find vegan restaurants in a specified city.
- Generate a travel itinerary including vegan restaurants and landmarks.
- Display results on an interactive map using Folium.

## Inspiration
I've been vegan for 7 years and wanted to use my skills in data science and LLMs to build something useful for the vegan community. While researching, I found an inspiring example on Towards Data Science, which gave me the initial idea for this project. This is just the first step of a larger application I plan to build, aiming to provide detailed and personalized travel plans that cater to vegan lifestyles.

## Setup
### Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/yourusername/vegan-itinerary-planner.git
    cd vegan-itinerary-planner
    ```

2. Install the required packages:

    ```bash
    pip install -r requirements.txt
    ```

### Obtain API Keys

You will need API keys for OpenAI and Google Maps.

**Getting the Google Maps API Key:**
  - Go to the [Google Cloud Console](https://console.cloud.google.com/)
    
**Getting the OpenAI API Key:**
  - Go to the [OpenAI Developer Quickstart](https://platform.openai.com/docs/quickstart)

    
## How It Works

1. **Setting Up Functions to Fetch Data**:
  The application fetches coordinates and vegan restaurants using the Google Maps API.

2. **Integrating LangChain**:
  Functions are defined to find restaurants and generate itineraries using LangChain. These functions invoke the LangChain agent and create the map with the   results.

3. **Creating the Map**:
  An interactive map is created using Folium to display the vegan restaurants and itineraries.

4. **Building the Gradio Interface**:
  A Gradio interface is created with two tabs: one for finding restaurants and one for generating itineraries.

## Future Plans
This is just the first step of a larger application I plan to build. My goal is to create a comprehensive app that focuses on itineraries for the vegan community, providing detailed and personalized travel plans that cater to vegan lifestyles.
