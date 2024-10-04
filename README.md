# Air-Quality Dashboard

This project is a Streamlit-based air-quality dashboard that visualizes pollutant data PM2.5 and provides AQI forecasts for a selected date range.

## Setup Environment

### Prerequisites

1. **Python**: Ensure Python is installed on your machine. You can download it [here](https://www.python.org/downloads/).
2. **VSCode**: Install Visual Studio Code for coding and development. Download it [here](https://code.visualstudio.com/).
3. **Streamlit**: Install Streamlit via pip:

    ```bash
    pip install streamlit
    ```

4. **Other Dependencies**: Install additional libraries required for the project:

    ```bash
    pip install -r requirements.txt
    ```

### Running the Dashboard

To run the air-quality dashboard, follow these steps:

1. **Activate Virtual Environment** (optional but recommended):

    - On **Windows**:
    
      ```bash
      venv\Scripts\activate
      ```

    - On **macOS/Linux**:
    
      ```bash
      source venv/bin/activate
      ```

2. **Navigate to the Dashboard Directory**:

    ```bash
    cd dashboard
    ```

3. **Run the Streamlit App**:

    ```bash
    streamlit run AQIDashboard.py
    ```

4. **Access the Dashboard**:

    Open your browser and go to:

    ```
    http://localhost:8501
    ```

### Features

- **Date Range Selection**: Choose a date range and station to view average pollutant data.
- **Pollutant Visualization**: Displays pollutant concentration charts with the title 'Pollutant and Concentration.'
- **AQI Forecast**: Provides AQI category forecasts along with temperature and pressure data.
