# Women's Travel Guide: Global Perspectives on the Wellbeing of Women

**Please note this project was orginally completed as part of DSAN5200 at Georgetown University. The repo has been copied to my personal GitHub for viewing purposes.**

## Team 19
* Lizzie Healy
* Amina Nsanza 
* Samyu Vakkalanka
* Marie Vaughan

## About the Project
We designed a website to provide a comprehensive overview of women's wellbeing through the lens of travel. The site features a range of data visualizations—from bubble plots to choropleth maps—to offer a global perspective on four key pillars: Economic Empowerment, Political Empowerment, Health and Safety. The final product is an interactive tool that allows users to select the indicator most important to them and explore how it varies across the world. Through this project, we aim to support women who are traveling or considering relocation by helping them make informed decisions. This is especially important to us because the safety and security of women around the globe are at risk every day, and with this tool, we hope to make navigating the world a little safer and easier.

Audience: This website is designed for a general audience, with a focus on women who travel and are interested in relocating. It is also intended for anyone concerned about global gender disparities and women;s safety. 

## Repository Structure
The repository is organized into the following directories:
* `code/`: It has all the code used to generate the data visualizations and the website. It contains the code source for data processing & generating the individual plots
* `data/`: This contains the data files used in the project. It is organized into subdirectories for analysis data, clean data, and common files. These subdirectories represent raw and processed data. 
* `img/`: This directory contains images used in the website, including logos and icons. 
* readme.md: This file contains the project description as well as the repository structure.
* `website/`: This directory contains the website files, it is self-contained and can be deployed independently.  (We need to add an index.html file to this directory)

## Usage Instructions
To view the rendered and finalize product of the website, please feel free to navigate to **https://ehealy.georgetown.domains/womens_travel_guide**

However, if you wish to reproduce the website, follow these instructions:
  1. Clone the github repository to your local machine: _git clone https://github.com/gu-dsan5200/dsan5200-spring2025-project-group-19.git_
  2. Utilize the following command to create the virual environment with the necessary dependencies: _conda env create -f environment.yml_.
  3. Navigate to the code folder: _cd code_
  4. If wishing to preview the website:\
    a. Render the website: _quarto preview 'womens_travel_guide.qmd'_.\
    b. View the .html file in a web-browser.
  5. If wishing to render:\
    a. Render the website: _quarto render 'womens_travel_guide.qmd'_.\
    b. You may need to launch a local web server for the OJS portions: utilize _python3 -m http.server_ in the terminal still within the code folder.\
    c. Select the womens_travel_guide.qmd file from the options and view in the web-browser.

