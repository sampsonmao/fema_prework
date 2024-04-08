As part of the interview process for a GS-1560-11/12/13 data scientist, I analyzed the OpenFEMA Dataset: Disaster Declarations Summaries - v2, which can be found here: https://www.fema.gov/openfema-data-page/disaster-declarations-summaries-v2. Initially, I used plotly to create maps that allowed the user to hover over the states to obtain information. Since this resulted in a large notebook size, I created another notebook with static maps instead.

After my analysis, I had 10 minutes to present my results to the panel:

During the course of your interview, we’ll want to get a strong sense of your analytical experience and expertise, and we’ll also want to understand your communication and teamwork skills. In advance of your interview, we have some pre-work we’d like you to complete. Expect to have approximately 10 minutes to present the results of your pre-work during your interview.

We would like you to explore an OpenFEMA data set on FEMA disaster declarations: Disaster Declarations Summaries - v2 | FEMA.gov  (links to the data in CSV and JSON formats and a data dictionary are provided on that site)
(Note, please export a code notebook into PDF or HTML format -- do not assume all the interview panelists have access to tools like Jupyter or RStudio to open notebooks directly) 

- Data Exploration – Load and explore the OpenFEMA Disaster Declarations Summaries data set, identifying key variables, data types, and potential data quality issues.
- Data Cleaning – Clean the data for Major Disaster Declarations as needed, addressing any missing values, duplicates, or other data anomalies.
- Data Visualization – Create visualizations to depict trends or patterns in the data, specifically:
    - Number of disaster declarations per year
    - Top ten states with the most disaster declarations
    - Most frequent types of disasters, nationwide and for all 50 states
    - Most frequent declaration month for disasters, nationwide and for all 50 states
    - Disasters “open” the longest (i.e., for disasters with a disaster closeout date in the data set, which ones took the longest to close from the incident start date. Disaster closeout date is the date at which financial transactions for all FEMA assistance programs are completed)
    - Any other interesting visuals that you think tell the story of this data set
- Statistical Analysis – Calculate summary statistics and/or identify correlations that help further tell the story of insights you are seeing from your data exploration.
- Predictive Modeling – Which types of predictive modeling techniques are suitable to apply to this data set? Which are not? What additional data sets may be helpful in building a model that aligns to the goals in FEMA’s Strategic Plan? Be prepared to discuss and explain your thinking during the interview. Bonus points for implementing a predictive model as part of the pre-work assignment.

    - Other data sets you might consider include OpenFEMA, Census, Global Change Research Program, data.gov, Bureau of Labor Statistics, Climate and Economic Justice Screening Tool, CDC/ATSDR Social Vulnerability Index (SVI). FEMA National Risk Index. 

 No prior knowledge of FEMA or the disaster declaration process is needed to complete this exercise.  The most important thing you need to know is that a major disaster declaration (DR) is assigned a unique disaster number (4393) associated with a specific incident (e.g., Hurricane Florence), specific jurisdiction (e.g., a state like North Carolina or NC), and specific designated areas within that state (or statewide). Therefore, a FEMA declaration string such as DR-4393-NC is typically repeated in the Disaster Declarations Summaries dataset multiple times, for each “designated area” (e.g., county).