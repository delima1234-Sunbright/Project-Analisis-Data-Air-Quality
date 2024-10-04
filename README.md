# Air-Quality Dashboard

This project is a Streamlit-based air-quality dashboard that visualizes pollutant data (PM2.5, PM10, O3, NO3, SO2) and provides AQI forecasts for a given date range.

## Setup Environment

### Prerequisites

1. **Python**: Ensure Python is installed on your machine. You can download it from [here](https://www.python.org/downloads/).
2. **VSCode**: Install Visual Studio Code for coding and development. Download it [here](https://code.visualstudio.com/).
3. **Streamlit**: Install Streamlit via pip:

    ```bash
    pip install streamlit
    ```

4. **Other Dependencies**: You may need to install additional libraries used in the project. Install them using:

    ```bash
    pip install -r requirements.txt
    ```

### Running the Dashboard

To run the air-quality dashboard, follow these steps:

1. Clone this repository:

    ```bash
    git clone <your-repository-url>
    cd <repository-folder>
    ```

2. In VSCode, open the terminal and activate your Python virtual environment (optional but recommended):

    ```bash
    # On Windows
    venv\Scripts\activate

    # On macOS/Linux
    source venv/bin/activate
    ```

3. Run the Streamlit app:

    ```bash
    python -m run streamlit AQIDashboard.py
    ```

4. Open your browser and navigate to:

    ```
    http://localhost:8501
    ```

This will launch the dashboard locally.

### Features

- Select a date range and station to view average pollutant data
- Visualize pollutant concentration charts with a title 'Pollutant and Concentration.'
- Get AQI category forecasts, temperature, and pressure data.

### License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
