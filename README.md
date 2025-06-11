# newspaper_tags_project

This project was created during spring 2024.

Its goal was to collect and analyze tags from Greek news websites, specifically focusing on how tags relate to a given topic over time — for example, analyzing how the tag "δημοσκόπηση" (poll) is connected to other tags.

🎯 Objectives:
Extract tags from articles related to a specific tag (e.g. δημοσκόπηση) from various news websites.

Analyze how tags co-occur with the main topic.

Track temporal patterns — which tags appear more often together, and when.

Compare tag behavior across newspapers to explore:

Similarities in coverage.

Differences in focus or editorial approach.

📁 Output:
Each script generates two .csv files per run:

Tag Frequency File:
Contains all related tags and their frequency for a specific search topic.

Format: newspaperName_tag.csv

Example: Documento_δημοσκόπηση.csv

Tag-Date File:
Contains pairs of each tag with its corresponding publication date.

Format: newspaperName_tag_Wdate.csv

Example: Documento_δημοσκόπηση_Wdate.csv

These files are intended to be analyzed in tools like Excel, Python/Pandas, or Tableau for pattern discovery. (I used Tableau)
