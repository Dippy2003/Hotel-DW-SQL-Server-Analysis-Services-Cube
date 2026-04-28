# Hotel Bookings OLAP Cube (SSAS)

This repository contains a Microsoft SQL Server Analysis Services (SSAS) Multidimensional project for hotel booking analytics.  
It was developed as part of a Data Warehousing and Business Intelligence (DWBI) assignment.

## Project Overview

The solution models hotel booking data as a dimensional analytics cube so business users can analyze performance across multiple perspectives such as time, room type, meal plans, booking status, and market segments.

## Main Components

- `HotelCubeProject.sln` - Visual Studio solution file.
- `HotelCubeProject/HotelCubeProject.dwproj` - SSAS project definition.
- `HotelCubeProject/Hotel DW.ds` - Data source configuration (SQL Server).
- `HotelCubeProject/Hotel DW.dsv` - Data source view metadata.
- `HotelCubeProject/Hotel DW.cube` - Cube structure and measure definitions.
- `HotelCubeProject/Hotel DW.partitions` - Partition metadata for cube processing.

## Dimensions Included

- `Dim Date`
- `Dim Room`
- `Dim Meal Plan`
- `Dim Booking Status`
- `Dim Market Segment`

## Technologies Used

- Microsoft SQL Server Analysis Services (SSAS) - Multidimensional
- Microsoft Visual Studio (SSDT / Analysis Services Projects)
- SQL Server (warehouse source database)

## How to Open the Project

1. Open `HotelCubeProject.sln` in Visual Studio with Analysis Services extensions installed.
2. Verify the data source connection in `Hotel DW.ds` points to your local SQL Server/database.
3. Build and deploy the project to an SSAS instance.
4. Process the cube and browse it for analysis.

## Notes

- `bin/`, `obj/`, `.vs/`, and `*.user` files are excluded from source control using `.gitignore`.
- Upgrade logs are included for project history (`UpgradeLog.htm`, `UpgradeLog2.htm`).
