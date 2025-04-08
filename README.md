# Urban Mobility Analysis with Apache Spark

## Overview
This project applies fundamental Spark concepts (RDDs, DataFrames, transformations, and actions) to perform distributed analysis of urban mobility data. We'll work with real or semi-synthetic data based on Mexico City's public transportation, transit, and mobility open data.

## Project Goals

The analysis aims to answer key urban mobility questions including:
- Which routes experience the highest congestion?
- What time periods have the most trips?
- Which zones have the highest vehicle entry or exit rates?

## Analysis Requirements

The project must include:
- Data reading from CSV or JSON formats
- Implementation of RDDs and DataFrames with transformations and actions
- At least one distributed aggregation operation (e.g., reduceByKey, groupBy)
- Application of filters, maps, and joins (where applicable)
- Generation of a summary CSV file or simple visualization (optional using matplotlib or similar)

## Implementation Details

### Tech Stack
- PySpark or Scala Spark may be used
- Local environment or Databricks for execution

### Data Source
- Real or semi-synthetic data based on Mexico City's open data portal
- Dataset will simulate or be based on public transportation trip records, vehicle GPS data, or shared bike services

### Technical Approach
- Data will be processed using Spark's distributed computing capabilities
- Multiple transformations will be applied for cleaning and analysis
- Results will be aggregated to identify patterns and answer research questions

### AI Assistance Guidelines
- AI tools may be used for syntax questions
- All AI consultations must be documented in the report including:
  - Which queries were made to AI systems
  - Which parts of the code used AI assistance
  - How the AI assistance helped with implementation

## Deliverables

The final submission must include:

1. **Source Code**
   - Well-organized and executable in a local environment or Databricks
   - Complete with comprehensive comments

2. **Technical Report**
   - Dataset description (source or generation method if synthetic)
   - Explanation of operations performed and their purpose
   - Analysis of results
   - Key code snippets with detailed comments
   - Reflection on distributed processing efficiency

3. **Output Files**
   - Summary CSV files
   - Visualizations (if implemented)

## Evaluation Criteria

The project will be evaluated based on:
- Correct implementation of Spark concepts
- Quality of data analysis and insights
- Code organization and documentation
- Proper utilization of distributed computing techniques
- Thoroughness of the technical report