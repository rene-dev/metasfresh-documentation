---
title: Data Import to metasfresh
layout: default
tags:
  - Data Management
  - Data Import
lang: en
sequence: 10
ref: data_import_metasfresh
---

## Overview
You can quickly import externally stored data (such as Excel spreadsheets with data on business partners or products) into metasfresh through the use of the import feature and thus also bring existing entries up to date. To do so, you first have to format the data appropriately, upload them as a CSV or TXT file and then simply import them via the [actions menu](StartAction).

## Requirements
1. [Add an import format using the appropriate database table](Add_import_format) (see above) where you define the data, or rather the columns, as well as their data types that are to be transferred from the import file into metasfresh.

   | Import Data | Corresponding DB Table |
   | :--- | :---: |
   | Bank Statement Data | Import Bank Statement |
   | Business Partner Data | Import Business Partner |
   | Chart of Accounts Data | Import Account |
   | Custom Data Entries | Import Data Entry Record |
   | Discount Schema Data | Discount Schema Import |
   | Postal Data | Import Postal Code Data |
   | Product Data | Import Product |
   | Replenishment Data | Import Replenishment |

1. Have an [import file](Import_file_useful_tips) ready containing data formatted according to the import format.<br> ***Format examples:***
   - [Bank statement data import](Import_format_example_bank_statement)
   - [Business partner data import](Import_format_example_bpartner)
   - [Chart of accounts data import](Import_format_example_charts_of_accounts)
   - [Custom data entry import](Import_format_example_data_entry)
   - [Discount schema data import](Import_format_example_discount_schema)
   - [Postal data import](Import_format_example_postal_data)
   - [Product data import](Import_format_example_product)
   - [Replenishment data import](Import_format_example_replenishments)<br><br>

1. Import your data using the appropriate import format.
   - [Follow these instructions](Import_bank_statement_data) to import external data on **bank statements** into metasfresh.
   - [Follow these instructions](Import_bpartner_data) to import external data on **business partners** into metasfresh.
   - [Follow these instructions](Import_charts_of_accounts) to import external data on **charts of accounts** into metasfresh.
   - [Follow these instructions](Import_custom_data_entries) to import external data on **custom data entries** into metasfresh.
   - [Follow these instructions](Import_discount_schema) to import external data on **discount schemas** into metasfresh.
   - [Follow these instructions](Import_product_data) to import external **postal data** into metasfresh.
   - [Follow these instructions](Import_product_data) to import external data on **products** into metasfresh.
   - [Follow these instructions](Import_replenishment_data) to import external data on **replenishments** into metasfresh.<br><br>

    | **Important Note:** |
    | :--- |
    | **1)** Make sure that the ***separator*** from the import file coincides with the one defined in the import format (comma, semicolon, tab, etc.).<br> **2)** Please also make sure that both the ***decimal*** and the ***thousands separators*** from the import file conform with your respective language-specific system preferences (e.g., Eng.: *$ 1,999.95* vs. Ger.: *€ 1.999,95*). |
