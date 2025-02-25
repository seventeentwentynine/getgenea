## GetGenea Anomaly Detection System Toy Examples
### Data Description and Variables

### Overview
### This project utilizes the **Individual Household Electric Power Consumption** dataset from the UCI Machine Learning Repository. The dataset contains measurements of electric power consumption in a single household, recorded at a one-minute sampling rate over a period of almost 4 years (December 2006 to November 2010). It provides rich time-series data useful for regression, clustering, and other analyses in energy consumption studies.

### The dataset comprises the following variables:

1. **Date**  
   - **Description**: Date in the format `dd/mm/yyyy`.  
   - **Role**: Temporal feature identifying the day of the measurement.

2. **Time**  
   - **Description**: Time in the format `hh:mm:ss`.  
   - **Role**: Temporal feature identifying the minute of the measurement.

3. **Global_active_power**  
   - **Description**: Household global minute-averaged active power, measured in kilowatts (kW).  
   - **Role**: Continuous feature representing overall active power consumption.

4. **Global_reactive_power**  
   - **Description**: Household global minute-averaged reactive power, measured in kilowatts (kW).  
   - **Role**: Continuous feature representing reactive power consumption.

5. **Voltage**  
   - **Description**: Minute-averaged voltage measured in volts (V).  
   - **Role**: Continuous feature capturing the electrical potential.

6. **Global_intensity**  
   - **Description**: Household global minute-averaged current intensity, measured in amperes (A).  
   - **Role**: Continuous feature representing current intensity.

7. **Sub_metering_1**  
   - **Description**: Energy sub-metering for the kitchen (e.g., dishwasher, oven, microwave), measured in watt-hour of active energy.  
   - **Role**: Continuous feature.

8. **Sub_metering_2**  
   - **Description**: Energy sub-metering for the laundry room (e.g., washing machine, tumble-drier, refrigerator, light), measured in watt-hour of active energy.  
   - **Role**: Continuous feature.

9. **Sub_metering_3**  
   - **Description**: Energy sub-metering for an electric water-heater and an air-conditioner, measured in watt-hour of active energy.  
   - **Role**: Continuous feature.
### Additional Information
- **Derived Calculation**: The expression `(global_active_power * 1000 / 60 - sub_metering_1 - sub_metering_2 - sub_metering_3)` estimates the active energy consumed per minute (in watt-hour) by appliances that are not included in the sub-metering.
