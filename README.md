# Taxi-Fare-Analysis-PowerBI
Power BI dashboard analyzing ride bookings, revenue, vehicle performance, cancellations, ratings, and ride distance.


# Taxi Fare Analysis Dashboard – Power BI

## Project Overview

This project analyzes ride-booking data using Microsoft Power BI to understand booking trends, revenue performance, vehicle performance, cancellation patterns, ride distance, and customer/driver ratings.

The dataset contains 150,000 ride-booking records with information related to bookings, vehicles, payments, cancellations, distances, and ratings.

## Business Objective

The objective of this project is to analyze ride-booking data and identify useful patterns related to:

* Booking performance
* Revenue generation
* Vehicle-type performance
* Ride distance
* Customer and driver cancellations
* Cancellation reasons
* Customer and driver ratings
* Payment methods
* Time-based booking trends

## Dataset

**File:** `rideBookings.csv`

**Records:** 150,000

**Columns:** 21

### Key Columns

* Date
* Time
* Booking ID
* Booking Status
* Customer ID
* Vehicle Type
* Pickup Location
* Drop Location
* Avg VTAT
* Avg CTAT
* Booking Value
* Ride Distance
* Driver Ratings
* Customer Rating
* Payment Method
* Customer Cancellation Reason
* Driver Cancellation Reason
* Incomplete Ride information

## Tools Used

* Microsoft Power BI
* Power Query
* DAX

## Data Analysis Process

### 1. Data Collection

Imported the ride-booking CSV dataset into Power BI.

### 2. Data Cleaning

Used Power Query to inspect, clean, and prepare the dataset for analysis.

### 3. Data Transformation

Prepared the data fields required for booking, revenue, cancellation, distance, vehicle, payment, and rating analysis.

### 4. KPI and Measure Creation

Created Power BI measures to support KPI reporting and business analysis.

Key metrics included:

* Total Bookings
* Completed Bookings
* Cancelled Rides
* Cancellation Percentage
* Booking Value
* Revenue per KM
* Ride Distance
* Customer and Driver Ratings

### 5. Dashboard Development

Developed multiple Power BI report pages:

* Overall Report
* Vehicle Report
* Revenue Report
* Cancellation Report
* Rating Report
* Summary Report

## Analysis Performed

### Booking Analysis

Analyzed monthly booking trends and booking status including completed, cancelled, incomplete, and no-driver-found bookings.

### Vehicle Analysis

Compared ride performance across:

* Auto
* Bike
* eBike
* Go Mini
* Go Sedan
* Premier Sedan
* Uber XL

### Revenue Analysis

Analyzed booking value based on:

* Payment Method
* Vehicle Type
* Day Part
* Revenue Tier
* Distance Category

### Cancellation Analysis

Analyzed customer and driver cancellations and examined the reasons associated with cancelled rides.

### Rating Analysis

Compared customer and driver ratings across different vehicle types.

### Time-Based Analysis

Analyzed booking and revenue patterns across months, weeks, days, and different parts of the day.

## Dashboard Pages

### Overall Report

Provides an overview of booking volume, booking status, and overall ride performance.

### Vehicle Report

Compares booking and distance performance across vehicle types.

### Revenue Report

Analyzes booking value, payment methods, and revenue per KM.

### Cancellation Report

Analyzes customer and driver cancellations and cancellation reasons.

### Rating Report

Compares customer and driver ratings across vehicle types.

### Summary Report

Provides additional business metrics including revenue, customer retention, peak-hour performance, day-part analysis, revenue tiers, distance categories, monthly revenue, and weekly bookings.

## Key Metrics from the Dashboard

* Total Bookings: 148.767K
* Completed Bookings: 92.551K
* Total Cancelled Rides: 38K
* Cancellation Percentage: 25%
* Total Revenue per KM: 967.93K
* Customer Retention Rate: 9.64%
* Premium Peak Hour Index: 61.72%

## Project Outcome

The dashboard provides an interactive view of ride-booking operations and allows users to compare booking, revenue, vehicle, cancellation, distance, and rating performance using Power BI visualizations and filters.

## Files

Dataset/
    rideBookings.csv

PowerBI/
    Taxi_Fare_Analysis.pbix

Dashboard/
    Taxi_Fare_Analysis.pdf

## Skills Demonstrated

* Data Cleaning
* Data Transformation
* Data Analysis
* Power Query
* DAX
* KPI Development
* Power BI Dashboard Development
* Business Reporting
* Trend Analysis
* Cancellation Analysis
* Revenue Analysis
