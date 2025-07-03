# FFDS_62545
Description
This dataset comprises 310 time-stamped records collected from an environmental monitoring setup
Summary
Edit
This dataset comprises 310 time-stamped records collected from an environmental monitoring setup, likely intended for evaluating freshness or spoilage levels—possibly in a perishable item such as food or biological samples. Each record contains a set of sensor-based readings and a manually assigned freshness status.
Attributes Explained
Time (min:sec):
Indicates the elapsed time in minutes and seconds for each reading.
Object Temperature (°C):
Represents the temperature of the monitored object. It ranges from 3.5°C to 34.4°C.
Ambient Temperature (°C):
Captures the environmental temperature surrounding the object, ranging from 22.0°C to 52.9°C.
TMA (Trimethylamine):
Measures the concentration of TMA gas, which is a known indicator of spoilage in protein-based items. Values range from 120 to 1665 ppm.
H₂S (Hydrogen Sulfide):
Another spoilage-related gas, measured in ppm, with values between 90 and 1635.
NH₃ (Ammonia):
Ammonia levels also correlate with spoilage. The values fall between 80 and 1625 ppm.
Status:
A categorical label describing the current condition of the sample. It includes three possible states—FRESH, SPOILING, and SPOILED—with SPOILING being the most frequently occurring class.
Score:
A numerical freshness indicator on a scale of 0 to 2, where higher values likely denote better freshness.
Dataset Summary
The dataset is balanced in terms of sensor data coverage but skewed toward the "SPOILING" status.
Temperature and gas concentrations show wide variability, making them potentially strong indicators for classification tasks.
All data is complete with no missing values.
The presence of both categorical and continuous attributes makes this dataset suitable for supervised machine learning, especially for freshness/spoilage prediction.
