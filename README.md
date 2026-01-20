# Bird-Migration-Pattern-Predictor

My first main Python project, created for my A-Level Computer Science NEA. The program can output past bird and weather data from 2000 to 2025, and predict numbers for the following year. It also includes a full GUI and web scraping functionality. Further information on how to use the project can be found on the 'Help' page of the GUI.

# Disclaimer

Please bear in mind that this was my first major project, and I had to teach myself how to web scrape, interact with databases and create GUIs during the implementation phase of the project. The project's data also only covers up to 2025, due to bird data needing to be added manually to the corresponding .csv file. Some alterations have been made to the web scraper and GUI since it was submitted for my A-Level project to fix errors preventing execution, but otherwise the program has been left untouched. I aspire to improve further on what is undeniably an inefficient but ambitious project.

# Usage

The project should function simply once all files have been downloaded and the main Python file is executed. To update the project for the present day, use the BirdTrack tool on the RSPB website (linked on the 'Credits' page of the GUI) to add the relevant data to the 'bird_data.csv' file in the established format. Then, change the 'CURRENT_YEAR' constant variable to the year AFTER the present year - this will become the year predictions are made for. DO NOT make this change before updating the .csv file. Finally, run the project, where the web scraper will collect the necessary weather data. The reason no web scraper exists for bird data is that BirdTrack's content is dynamic, but it was the only option I could find when developing the project that was feasible to use.
