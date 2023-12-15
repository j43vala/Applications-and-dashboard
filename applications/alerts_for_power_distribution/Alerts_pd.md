# System Monitoring Alerts

- reference - https://learn.microsoft.com/en-us/power-bi/create-reports/service-set-data-alerts#manage-alerts


| Alert ID | Location | Date Created | Description | Delete | On/Off |
|----------|----------|---------------|------------|-------|--------|
| 1        | energy meter 1  | 2023-01-15 | Low Frequency Alert | ❌ | <input type="checkbox" checked> |
| 2        | sub meter 2 | 2023-02-03 | Excessive Energy Consumption |  ❌ | <input type="checkbox" checked> |


## Frequency Alerts - **threshold**

### Low Frequency

- **Description:** Alert triggered when the frequency falls below a specified threshold.
- **Implication:** Indicates a potential issue with the power supply or generation.
- **Action:** Investigate the root cause and address the power supply or generation problem.

### High Frequency

- **Description:** Alert triggered when the frequency exceeds a specified upper limit.
- **Implication:** Indicates potential over-generation or a problem with the power supply.
- **Action:** Investigate the root cause and take corrective measures to balance the power generation.

## Power Factor Alerts - **certain level**

### Low Power Factor

- **Description:** Alert triggered when the power factor drops below a certain level.
- **Implication:** Indicates inefficient use of electrical power.
- **Action:** Investigate the power factor drop and optimize equipment for better power factor.

### Fluctuating Power Factor

- **Description:** Alert triggered when the power factor varies significantly over a short period.
- **Implication:** Suggests issues with power quality or equipment performance.
- **Action:** Conduct a thorough analysis to identify and address power quality or equipment issues.

## kWh Energy Alerts - **predetermined threshold**

### Excessive Energy Consumption

- **Description:** Alert triggered when energy consumption (kWh) exceeds a predetermined threshold.
- **Implication:** Indicates abnormal or inefficient operation.
- **Action:** Investigate the cause of excessive energy consumption and implement corrective measures.

### Unexpected Drops in Energy Consumption

- **Description:** Alert triggered when there is a sudden and unexpected decrease in energy consumption.
- **Implication:** Signifies a potential malfunction or shutdown.
- **Action:** Investigate the cause and address any malfunction or shutdown event.

## kVA Power Alerts -**predetermined limit**

### Excessive Apparent Power

- **Description:** Alert triggered when apparent power (kVA) exceeds the system capacity or a predetermined limit.
- **Implication:** Indicates a risk of overloading the system.
- **Action:** Investigate and take corrective measures to prevent overloading.

### Low Power Factor with High kVA

- **Description:** Alert triggered for scenarios with low power factor and high kVA.
- **Implication:** Indicates inefficient use of power.
- **Action:** Investigate and optimize equipment for better power factor and efficient power use.
