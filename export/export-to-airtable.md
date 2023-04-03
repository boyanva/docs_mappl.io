---
description: Importing your CSV files in Airtable
---

# Airtable

**Use Airtable as a data repository for your Miro data.** Work with separate tables for CSV file import or build a master table by appending many CSV files with a shared format. You can, for example, build a master table for all tasks in your project for an extended period of time, where you will always be able to find a particular task and go back to the original Miro board item by following the backlink.

1. Create a new table in your Airtable base.
2. Click the "+ Add or Import" button at the top of the table.
3. In the pop-up, choose "CSV file".
4. Select a previously saved CSV file from mappl.io Spatial Tables results table view and click Upload.
5. Review the imported data in the preview screen that appears. Make sure that the column on the left is the Title column. The Title column must be of type Long text, the Backlinks column must be of type URL, and the rest of the columns should be of type Single Select. You can click on the downward arrow and adjust the type at this time.&#x20;
6. Click Import and the data must be successfully imported in Airtable.

<figure><img src="../.gitbook/assets/Export_Airtable_01.png" alt=""><figcaption></figcaption></figure>

Modifying Airtable Column Field Types

Ensure that the Items and Backlinks columns have the correct field types:

1. Check column field types.
2. Make sure "Items" is set as the "Single line text" field type.
3. Ensure "backlinks" has the "URL" field type.

To change a column field type from "Single line text" to "Single select":

1. Click the column header.
2. Select "Customize field type" from the drop-down menu that opens and choose "Single select".

Appending CSV Data to an Existing Airtable Table

1. Open the Airtable table where you want to append data.
2. Click the "Import" button at the top of the table.
3. In the pop-up, choose "CSV" and check the "Append data to an existing table" option.
4. Select the CSV file you want to append.
5. New data rows are added to the master table.
