Hotel Bookings Data Cleaning

This repository contains a Jupyter Notebook dedicated to cleaning and transforming a hotel bookings dataset into a structured format suitable for analysis and modeling.

🔹 Dataset Overview

Original dataset: 119,390 rows × 32 columns

After cleaning & processing:

Train shape: (69,916 × 86)

Test shape: (17,480 × 86)

🔹 Cleaning & Processing Steps

Removed duplicates and irrelevant features

Handled missing values and inconsistent data

Standardized column formats and data types

Reduced and restructured dataset into train/test splits

🔹 Feature Engineering

New features were created to enrich the dataset, including:

total_guests – combined count of adults, children, and babies

total_nights – total nights stayed per booking

stay_duration – length of stay in days

is_family – flag for family-related bookings

is_repeated_guest – indicator for guest loyalty

date/time – structured booking and stay dates

Guest_related – features describing group dynamics

price – standardized cost-related feature

🔹 Tech Stack

Python

Pandas, NumPy

Jupyter Notebook

🔹 Purpose

The final dataset is optimized for:

Exploratory Data Analysis (EDA)

Booking trend visualization

Predictive modeling (e.g., cancellations, demand forecasting)
