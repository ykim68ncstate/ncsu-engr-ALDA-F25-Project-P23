## Semantic Mapping of FWH Building Data
Building automation systems (BAS) often contain heterogeneous and inconsistent variable names, making automatic data labeling challenging across different buildings and vendors.
To address this issue, this project develops a value-based labeling model that classifies sensor and actuator types using only their time-series patterns, without relying on variable names.
Using one year of hourly BAS data, the model extracts temporal statistical features and trains an XGBoost classifier to distinguish key operational variables such as temperature, flow, and status.
This work highlights a direction toward scalable, vendor-agnostic BAS data processing for automated building model generation.
