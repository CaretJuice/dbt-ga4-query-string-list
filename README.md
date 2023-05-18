# dbt-ga4-query-string-list

This Google Colab notebook creates a list of query string parameters with sample values from a Google Sheet with a list of URLs for the purpose of discussing which values should be filtered in analytics reports.

It is assumed that users will be using the [dbt-GA4 package](https://github.com/Velir/dbt-ga4/) which allows you to filter query parameters from URLs for analysis purposes, although others may find this notebook useful in other contexts.

## Installation
This notebook uses some Google-specific Google Colab functions so it only runs in Colab.

To install this on Google Colab, 

1. Create an empty notebook
2. In the main menu, select **File** > **Upload Notebook** to open the upload dialog
3. In the upload dialog, switch to the **GitHub** tab
4. In the search box, paste the URL for this repository (https://github.com/CaretJuice/dbt-ga4-query-string-list) and click on the search icon to populate matching notebook files
5. Click on the matching notebook and the code should load into your Colab notebook
