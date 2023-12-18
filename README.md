

# Carbon Footprint Calculator


## Overview
The Carbon Footprint Calculator is a Streamlit web application designed to estimate an individual's carbon footprint based on various factors such as daily commute distance, electricity consumption, waste generation, and daily meals. The app utilizes emission factors specific to the selected country to provide a breakdown of carbon emissions in different categories.

## VIEW APP 

https://employeecf-xbjqftrgjfdpvbkmvzmmeh.streamlit.app/

![App Screenshot](https://github.com/sneha-4-22/carbonFootprint-Cal/assets/112711068/0f30a80e-cc3a-416a-bb35-dea5d01487a9)
## Usage
- Select your country from the dropdown menu.
- Input relevant information such as daily commute distance, monthly electricity consumption, waste generated per week, and the number of meals per day.
- Click the "Calculate CO2 Emissions" button to see the results.
  
## Emission Factors
Emission factors used for calculations are defined in the code. Modify these factors with accurate data for your country.
  ```bash
   EMISSION_FACTORS = {
    "India": {
        "Transportation": 0.14,  # kgCO2/km
        "Electricity": 0.82,  # kgCO2/kWh
        "Diet": 1.25,  # kgCO2/meal, 2.5kgco2/kg
        "Waste": 0.1  # kgCO2/kg
    }
}
   ```

## Results
The app provides a breakdown of carbon emissions in different categories, including transportation, electricity, diet, and waste. Additionally, the total carbon footprint is displayed.

## Additional Information
+ The app layout is designed to be wide for better user experience.
+ The page title is set to "Personal Carbon Calculator."

## Contributing
  Contributions are welcome! Feel free to open issues or submit pull requests.
## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/sneha-4-22/carbonFootprint-Cal.git
   ```
   ```bash
   cd carbonFootprint-Cal
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the Streamlit app:
   ```bash
   streamlit run app.py
   ```
