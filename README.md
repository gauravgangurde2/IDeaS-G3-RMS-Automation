# IDeaS G3 RMS Automation Tools
This repository contains Python automation scripts for **IDeaS G3 RMS**, specifically focusing on data handling for both **GRO** and **QDN Pro** versions.

## 📈 Supported Versions
- **IDeaS G3 GRO:** Automation for [mention what your code does, e.g., daily uploads].
- **IDeaS G3 QDN Pro:** Tools for [mention specific feature, e.g., demand forecasting extracts].

## 🛠️ Features
- Automated data extraction from IDeaS portals.
- Cleaning and formatting of RMS reports for Excel/PowerBI.
- Reduced manual processing time by XX%.

## 🚀 How to Use
Navigate to the specific folder (`GRO` or `Pro`) and follow the instructions in the script comments.

### 📥 Data Prerequisites (How to get the input files)
Due to data privacy, sample reports are not included in this repository. To run this script, you must generate the reports directly from your own system.

**For IDeaS G3 Users:**
1. Log into your IDeaS G3 portal.
2. Navigate to **Dashboard >>> Business Analysis >>> Data Details >>> Select the Month (see that the BAR for the month include all days) >>> Hit the Filter Icon and select everything except Yearly Variance and Discountinued Rooms >>> Hit Apply >>> Hit Revert Column order and then Hit Reset to Default >>> Now hit the Excel Icon to download the excel sheet**
3. Repeat this for all the months from Jan to Dec or Months you desire.
4. Save the files in a folder or in downloads
5. Rub the code in Google Colab >>> An incon will pop up below to Browse Files >>> Click Browse then Select the Files you have downloaded >>> Upload/Open >>> This will initiate creating an extract and a consolidated extract will land in the Downloads sections or the pre desired download folder.
