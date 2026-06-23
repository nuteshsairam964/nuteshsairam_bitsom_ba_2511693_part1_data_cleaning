# Data Cleaning Log





## 1\. Issues Found

* Missing values in Region column
* Missing values in Discount column
* Duplicate records present
* Mixed date formats in Order Date and Ship Date
* Negative discount values
* Invalid date parsing records





## 2\. Cleaning Actions Performed

* Replaced blank Region values with "Unknown"
* Replaced blank Discount values with 0
* Removed duplicate records
* Standardized date formats where possible
* Created calculated columns:

  * shipping\_delay\_days
  * order\_month
  * order\_year
  * data\_quality\_flag





## 3\. Business Rules Applied

* Missing Region values replaced with "Unknown"
* Missing Discount values replaced with 0
* Date conversion issues flagged as Warning
* Shipping delay calculated as Ship Date - Order Date
* Profit considered as Sales - Cost





## 4\. Assumptions Made

* Missing discount implies no discount applied
* Unknown region used when region information was unavailable
* Date conversion errors retained and flagged for review





## 5\. Records Removed

* Duplicate records removed: 20





## 6\. Records Flagged

* Date parsing errors: 129
* Invalid date records marked as Warning





## 7\. Limitations

* Some date formats could not be automatically standardized
* Flagged records may require manual review

