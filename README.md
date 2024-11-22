# Make My Trip: Enhanced Trip Planning with Agentic AI

<img width="938" alt="image" src="https://github.com/user-attachments/assets/1a21e5c2-015d-4be3-9a53-3c74e90d946d">

![image](https://github.com/user-attachments/assets/6aea8a97-a927-4357-9c2e-d08ed9613b17)

![image](https://github.com/user-attachments/assets/287157c9-8856-4389-98d3-aa9405c6fb0f)

# Overview
Make My Trip is an innovative project that leverages the CrewAI framework to automate and enhance the trip planning experience. This project integrates a user-friendly Streamlit interface, demonstrating how autonomous AI agents can collaborate and execute complex tasks efficiently. Unlike other approaches that use closed-source Large Language Models (LLMs), Make My Trip utilizes the open-source LLama3.2 model, ensuring transparency and accessibility.

# Features
Agentic AI: Autonomous AI agents that collaborate to plan and execute trips.
Streamlit Interface: A user-friendly interface for interacting with the AI agents.
Open-Source LLM: Utilizes the LLama3.2 model for transparency and accessibility.
Complex Task Execution: Efficiently handles complex trip planning tasks.
Interactivity: Enhanced interactivity through the Streamlit interface.
Getting Started
Prerequisites
Python 3.8 or higher
Git
Streamlit
CrewAI framework
LLama3.2 model
Installation

# Clone the Repository:


git clone https://github.com/aadilganigaie/make-my-trip.git
cd make-my-trip

# Set Up a Virtual Environment:


python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`
Install Dependencies:


pip install -r requirements.txt
Download the LLama3.2 Model:
Follow the instructions in the models directory to download and set up the LLama3.2 model.

# Running the Application
Start the Streamlit App:


streamlit run app.py
Access the Interface:

Open your web browser and navigate to http://localhost:8501 to interact with the Make My Trip interface.

# Project Structure

make-my-trip/
│
├── app.py                   # Main Streamlit application
├── agents/                 # Directory containing AI agent implementations
│   ├── trip_planner.py     # Trip planning agent
│   ├── booking_agent.py    # Booking agent
│   └── ...                 # Other agents
├── models/                 # Directory for LLM models
│   ├── llama3.2/           # LLama3.2 model files
│   └── ...                 # Other model files
├── data/                   # Directory for data files
│   ├── sample_data.json    # Sample data for testing
│   └── ...                 # Other data files
├── requirements.txt        # List of Python dependencies
├── README.md               # This file
└── ...                     # Other project files

# Usage
# Plan a Trip:

Use the Streamlit interface to input your trip details (destination, dates, preferences, etc.).
The AI agents will collaborate to plan the trip, including booking flights, hotels, and activities.
Interact with Agents:

The Streamlit interface allows you to interact with the AI agents, providing feedback and adjusting preferences as needed.

# View Results:

The interface will display the planned trip, including itinerary, bookings, and any additional recommendations.
