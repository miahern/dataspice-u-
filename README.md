# dataspice
 
{
  "@context": "http://schema.org",
  "type": "Dataset",
  "name": "Grocery Inventory and Sales Dataset",
  "creator": [
    {
      "type": "Person",
      "id": "none",
      "email": "none",
      "affiliation": "Kaggle",
      "name": "Salahuddin Ahmed"
    }
  ],
  "description": "This dataset provides detailed information on various grocery items, including product details, supplier information, stock levels, reorder data, pricing, and sales performance. The data covers 990 products across various categories such as Grains & Pulses, Beverages, Fruits & Vegetables, and more. The dataset is useful for inventory management, sales analysis, and supply chain optimization.",
  "datePublished": "01/01/2024",
  "keywords": "Business",
  "funder": "Kaggle",
  "temporalCoverage": "2024-01-01/2025-03-09",
  "license": "Attribution 4.0 International (CC BY 4.0)",
  "spatialCoverage": {
    "type": "Place",
    "name": "none",
    "geo": {
      "type": "GeoShape",
      "box": "none none none none"
    }
  },
  "variableMeasured": [
    {
      "type": "PropertyValue",
      "unitText": "numerical",
      "name": "Product_ID",
      "description": "Unique identifier for each product"
    },
    {
      "type": "PropertyValue",
      "unitText": "letters",
      "name": "Product_Name",
      "description": "Name of the product"
    },
    {
      "type": "PropertyValue",
      "unitText": "letters",
      "name": "Category",
      "description": "The product category (e.g., Grains & Pulses, Beverages, Fruits & Vegetables)"
    },
    {
      "type": "PropertyValue",
      "unitText": "letters",
      "name": "Supplier_ID",
      "description": "Unique identifier for the product supplier"
    },
    {
      "type": "PropertyValue",
      "unitText": "letters",
      "name": "Supplier_Name",
      "description": "Name of the supplier"
    },
    {
      "type": "PropertyValue",
      "unitText": "numerical",
      "name": "Stock_Quantity",
      "description": "The current stock level of the product in the warehouse"
    },
    {
      "type": "PropertyValue",
      "unitText": "numerical",
      "name": "Reorder_Level",
      "description": "The stock level at which new stock should be ordered"
    },
    {
      "type": "PropertyValue",
      "unitText": "numerical",
      "name": "Reorder_Quantity",
      "description": "The quantity of product to order when the stock reaches the reorder level"
    },
    {
      "type": "PropertyValue",
      "unitText": "numerical",
      "name": "Unit_Price",
      "description": "Price per unit of the product"
    },
    {
      "type": "PropertyValue",
      "unitText": "numercal",
      "name": "Date_Received",
      "description": "The date the product was received into the warehouse"
    },
    {
      "type": "PropertyValue",
      "unitText": "numerical",
      "name": "Last_Order_Date",
      "description": "The last date the product was ordered"
    },
    {
      "type": "PropertyValue",
      "unitText": "numerical",
      "name": "Expiration_Date",
      "description": "The expiration date of the product, if applicable"
    },
    {
      "type": "PropertyValue",
      "unitText": "numerical",
      "name": "Warehouse_Location",
      "description": "The warehouse address where the product is stored"
    },
    {
      "type": "PropertyValue",
      "unitText": "numerical",
      "name": "Sales_Volume",
      "description": "The total number of units sold"
    },
    {
      "type": "PropertyValue",
      "unitText": "numerical",
      "name": "Inventory_Turnover_Rate",
      "description": "The rate at which the product sells and is replenished"
    },
    {
      "type": "PropertyValue",
      "unitText": "letter",
      "name": "Status",
      "description": "Current status of the product (e.g., Active, Discontinued, Backordered"
    }
  ],
  "distribution": [
    {
      "type": "DataDownload",
      "name": "Grocery_Inventory_and_Sales_Dataset",
      "contentUrl": "https://www.kaggle.com/datasets/salahuddinahmedshuvo/grocery-inventory-and-sales-dataset/data",
      "encodingFormat": "csv"
    }
  ]
}
