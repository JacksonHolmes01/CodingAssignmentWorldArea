# CodingAssignmentWorldArea
This is a repository for a coding assignment in I310D

Project Goal

The goal of this project was to construct, analyze, and publish a data set on data.world through reproducible and responsible means. The overall assignment was to take raw data from the internet, in my case, a Wikipedia page, clean that data, and produce a visualization with the cleaned and interpreted data. Another aim of this assignment was to teach me how to follow the best practices for reproducible research and how to document and make my data reproducible and open to the public.

API

I did not use an API for this assignment.

License

The license for the data I collected from Wikipedia is ​the Creative Commons Attribution-Share Alike License 4.0. The license for my data published on data.world is the MIT License.

Data Types

The data types for the original source data are as follows:

Unnamed: 0               string

Country / dependency     string

Total in km2 (mi2)       string

Land in km2 (mi2)        string

Water in km2 (mi2)       string

% water                 float64

Unnamed: 6               string

dtype: object

The data types for the most cleaned version of the data in my project are as follows:

Country/Territory/Dependency    string

Total area in km2               string

Land in km2                     string

Water in km2                    string

dtype: object

Column Description

Unnamed: 0 - Country/Dependency ranking of size based on sourcing and the way the data was collected

Country / Dependency - Name of the location

Total in km2 (mi2) - Total area of location in km2 (mi2)

Land in km2 (mi2) - Total land area of location in km2 (mi2)

Water in km2 (mi2) - Total water area of location in km2 (mi2)

% water - Total percentage of location that is water

Unnamed: 6 - Source and citation link for data provided, the notes column

Country/Territory/Dependency - Name of the location

Total in km2 - Total area of location in km2 

Land in km2 - Total land area of location in km2 

Water in km2 - Total water area of location in km2 

Known Issues/Bias

Issues with the data stem from the fact that not all countries and governments agree on the area of their and others claimed territory, which is why the Unnamed: 6 column exists. The Unnamed: 6 column, the notes column, has links to reasoning behind the numbers presented in the row and general notes about what data was included or not included. For example, in the row for Venezuela the link notes that the total area counted in the table does not include Guayana Esequiba, a disputed territory. For further information follow the link to the source data wikipedia page and view the hyperlinks for information regarding the reason for the areas listed. https://en.wikipedia.org/wiki/List_of_countries_and_dependencies_by_area 
Other than the data presented potentially differing from data on the same topic on other sources the data has no issues or quirks.

Potential bias in the data would also stem from the fact that not all countries and governments agree on the area of their and others claimed territory. For example, the total area for Ukraine includes the russian occupied territories of the state, despite Russia claiming and occupying those areas. This note is provided in the wikipedia page prior to the data table: 

“Entries in this list include, but are not limited to, those in the ISO 3166-1 standard, which includes sovereign states and dependent territories. All 193 member states of the United Nations plus the two observer states are given a rank number. Largely unrecognised states not in ISO 3166-1 are included in the list in ranked order. The areas of such largely unrecognised states are in most cases also included in the areas of the more widely recognised states that claim the same territory; see the notes in the "notes" column for each country for clarification”.
