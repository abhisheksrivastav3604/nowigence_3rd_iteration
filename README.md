# Merge-multiple-CSV-files-Apache-NiFi

## Aim

To create an ETL for consolidate data so that we can create the Materialized views on this

## Schema: 
{
  "name": "Parent",
  "type": "record",
  "fields": [
    {
      "name": "location_id",
      "type": [
        "null",
        "string"
      ]
    },
    {
      "name": "invoice_no",
      "type": [
        "null",
        "string"
      ]
    },
    {
      "name": "sales_transaction_id",
      "type": [
        "null",
        "string"
      ]
    },
    {
      "name": "transaction_date",
      "type": [
        "null",
        "string"
      ]
    },
    {
      "name": "item_name",
      "type": [
        "null",
        "string"
      ]
    },
    {
      "name": "item_price",
      "type": [
        "null",
        "string"
      ]
    },
    {
      "name": "total_amount",
      "type": [
        "null",
        "string"
      ]
    },
    {
      "name": "location_name",
      "type": [
        "null",
        "string"
      ]
    },
    {
      "name": "sales_transaction_detail_id",
      "type": [
        "null",
        "string"
      ]
    },
    {
      "name": "item_id",
      "type": [
        "null",
        "string"
      ]
    },
    {
      "name": "site_id",
      "type": [
        "null",
        "string"
      ]
    },
    {
      "name": "kategori_id",
      "type": [
        "null",
        "string"
      ]
    },
    {
      "name": "prefered_vendor_id",
      "type": [
        "null",
        "string"
      ]
    },
    {
      "name": "vendor_id",
      "type": [
        "null",
        "string"
      ]
    },
    {
      "name": "vendor_name",
      "type": [
        "null",
        "string"
      ]
    },
    {
      "name": "description",
      "type": [
        "null",
        "string"
      ]
    },
    {
      "name": "m",
      "type": [
        "null",
        "string"
      ]
    }
  ]
}


## Files need to use: 
sale_transaction
sale_transaction_details
item
kategori
vendor
location
site


   
## Prerequisites

To run this project, you need the following prerequisites:

Apache NiFi: You need Apache NiFi installed on your system. If you don't have it, you can follow the instructions on `https://nifi.apache.org/docs/nifi-docs/html/getting-started.html#downloading-and-installing-nifi` to install it.

User and Password: You need a user and password to login to Apache NiFi.

We need the Access Key ID, Secret Access Key, and Bucket Name of AWS.

MongoDB: You need MongoDB installed on your system. If you don't have it, you can follow the instructions on `https://www.geeksforgeeks.org/how-to-install-mongodb-on-windows/` to install it.


## How to Run

To run the project:
Draw The process Flow or import template into Apache NiFi and, 
Click the "Run" button in Apache NiFi to execute the flow.
