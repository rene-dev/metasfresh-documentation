---
title: How do I configure the outbound documents?
layout: default
tags:
  - Emails and Outbound Documents
  - Setup
lang: en
sequence: 10
ref: outbound_documents_config
---

## Overview
You can set up the outbound documents for a variety of tables so the documents that are created, such as invoices, shipment notes, dunning letters, etc., get listed under "Outbound Documents" in the menu where you can then continue to process them either one by one or collectively.

## Steps
1. Open "Outbound Documents Config" from the [menu](Menu).
1. [Create a new configuration entry](New_Record_Window).
1. Start typing the name of the **Table** for which you want to configure the outbound documents and select the corresponding one from the suggestions, e.g., "Dunning type".
1. Select a [**Print Format**](Add_print_format), e.g., *Mahnbrief (swat)*.
1. Make sure the box **In Direct Enqueue** is checked if you also want to send the completed documents to the print queue.
1. [metasfresh saves the progress automatically](Saveindicator).
<br><br>

| **Important note:** |
| :--- |
| For the configurations to take effect on the application server, it first has to be restarted by the admin. |

## Next Steps (optional)
- [Set up outbound documents for](Outbound_Documents_Config_Dunning) [dunning](Dunning_Run).
- [Set up outbound documents for the](Outbound_documents_config_serial_letters) [serial letter feature](Create_serial_letters).

## Example
![](assets/Outbound_documents_config+dunning.gif)
