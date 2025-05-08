---
description: >-
  A detailed, step-by-step guide to conducting an RFID-based asset audit by
  location, including tag scanning, unknown tag handling, and asset assignment.
---

# 🏷️ Asset Audit Workflow

The **Asset Audit Workflow** enables users to verify physical assets against digital records by scanning RFID tags in specific locations. This process helps in identifying missing, misplaced, or untagged assets, and ensures real-time validation and correction of inventory data.

Each audit is location-specific and provides a structured approach to:

* Select the location for audit
* Track progress of scanned vs expected assets
* Detect unknown RFID tags
* Assign or add assets to unknown tags
* Confirm and update asset status post-scan

This flow ensures accountability, operational visibility, and streamlined asset management on the go.

<div><figure><img src="../.gitbook/assets/07_01 Audit Search Location.png" alt="" width="360"><figcaption></figcaption></figure> <figure><img src="../.gitbook/assets/07_02 Audit Screen.png" alt="" width="360"><figcaption></figcaption></figure></div>

**🗂️ Step 1: Select Location to Begin Audit**

The audit process begins by selecting the desired location for the audit operation. This ensures that all scanned assets are matched against the expected inventory of that specific physical space.

* **Screen**: Location Selector Modal
* **Search Bar**: Allows quick lookup by location name.
* **Location List**: Displays all available locations synced from the backend, each accompanied by the count of assets assigned to it.

**User Flow:**

1. Open the Audit Scan module from the Dashboard.
2. The "Select Location" screen appears.
3. Either scroll or search to find the desired location.
4. Tap on the location (e.g., "16A - EVENT AREA") to initiate the audit for that area.

This foundational step ensures that the audit results are tied to the correct location and allows the system to validate scanned tags accordingly.



**📡 Step 2: Start RFID Scanning**

Once the location is selected, the system loads the audit screen for that specific area. This screen shows:

* **Location name** and total expected asset count.
* **Units Remaining**: Real-time tracking of how many assets are yet to be verified.
* **Other Locations**: Tags found in the wrong location.
* **Unknown Tags**: Tags not previously assigned to any known asset.

**User Action:**

* Begin scanning RFID tags using the connected RFID scanner device.

As each tag is scanned, the system updates the audit progress automatically and classifies the tags based on their status.
