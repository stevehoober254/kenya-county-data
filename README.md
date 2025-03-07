# Kenya County Data (Constituencies, Wards, Polling Stations)

This repository provides structured data on Kenya's **counties, constituencies, wards, and polling stations** in JSON format. The data is sourced from the **Independent Electoral and Boundaries Commission (IEBC)** and publicly available government resources.

## 📌 Dataset Overview

The `county_data.json` file contains a structured array with the following format:

```json
[
  {
    "name": "Mombasa",
    "constituencies": [
      {
        "name": "Changamwe",
        "wards": [
          {
            "name": "Jomvu",
            "pollingStations": []
          }
        ]
      }
    ]
  }
]
```
🏛 Data Structure:

Counties → List of Kenya’s 47 counties.
Constituencies → Constituencies within each county.
Wards → Wards inside each constituency.
Polling Stations → Polling stations inside each ward.
📌 Source of Data
The data was extracted using automated scripts from official Kenyan government sources:

Independent Electoral and Boundaries Commission (IEBC)
Official public repositories from the Kenyan government.

📌 How to Use
```bash
    Clone the repository:
    git clone https://github.com/YOUR_GITHUB_USERNAME/kenya-county-data.git
    cd kenya-county-data
    Open county_data.json and use it in your applications.
```

📌 Contribution
If you find missing or incorrect data, feel free to submit a pull request or open an issue. Your contributions are welcome!

📌 License
This dataset is open-source and available for public use.
When using this data, please credit IEBC and official Kenyan government sources.

📢 Stay updated! If the Kenyan government updates constituency, ward, or polling station data, we will strive to update this dataset accordingly.
