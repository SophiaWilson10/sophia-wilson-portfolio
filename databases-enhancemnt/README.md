# Database Enhancement: Grazioso Salvare MongoDB Dashboard

## Overview
This artifact is an enhanced version of the Grazioso Salvare MongoDB Dashboard project originally developed in **CS340: Advanced Programming Concepts**. The application connects to a MongoDB database containing animal records and provides an interactive dashboard that allows users to filter, query, and visualize data related to rescue animals.

The original project introduced core database concepts such as CRUD operations, query filtering, and data visualization. This enhancement expands the project into a more intelligent, performant, and professionally structured database driven application.

## Why This Artifact
I selected this artifact for my ePortfolio because it represents realistic database work that aligns closely with professional software engineering tasks. It demonstrates my ability to:

- Design and implement a database driven application
- Write clean and maintainable backend logic
- Prepare and transform data for use in a front end interface
- Improve performance and scalability through indexing and preprocessing

This project also shows my growth from basic database interaction to designing solutions that apply algorithmic logic to real world data.

## Enhancement Summary
The primary enhancement added to this project is the **Mission Suitability Advisor**, a feature that analyzes each animal record and recommends a suitable rescue role based on multiple attributes.

Enhancements include:

- A rule based scoring algorithm to classify animals into rescue categories
- Preprocessing logic to normalize age data by converting values into weeks
- Breed group mappings aligned to specific rescue missions
- Keyword based analysis of behavior and condition fields
- A compound MongoDB index to optimize queries filtering by breed, age, and sex

These changes transform the dashboard from a simple CRUD application into a system that performs classification, preprocessing, and performance optimization.

## Skills Demonstrated
This enhancement demonstrates the following skills and concepts:

- MongoDB query design and optimization
- Compound indexing for improved performance
- Algorithmic classification using rule based logic
- Data preprocessing and normalization
- Backend refactoring for maintainability and scalability
- Integration of database logic with a front end dashboard

## Reflection
Enhancing this artifact taught me the importance of designing software that supports growth and change. Adding the Mission Suitability Advisor required careful refactoring so that new functionality could be introduced without breaking existing features.

I gained a deeper understanding of how indexing impacts query performance and why preprocessing is critical when working with inconsistent real world data. One challenge I faced was enhancing the project without access to the original Apporto environment or the AAC MongoDB database. Without the ability to run the full application end to end, I relied on careful code review, consistency checking, and incremental testing of individual functions.

This experience strengthened my ability to reason about data flow, function interactions, and system design. Even with environmental limitations, I was able to produce a clean and complete enhancement that demonstrates my growth in database design, problem solving, and software engineering practices.

## Course Alignment
- Course: **CS340 Advanced Programming Concepts**
- Enhancement Category: **Databases**
- Related Topics: MongoDB, indexing, data preprocessing, algorithmic classification

