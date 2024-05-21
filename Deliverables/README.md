# CMPE 258 Final Project - Infinite Interact: Multi-Agent Operational Suite

Team Name: Bay Area Rockers

Team Members:

1. Shawn Chumbar
2. Aagam Shah
3. Dhruval Shah
4. Sajal Agarwal

## Project Overview

This is a repository that was made for our CMPE 258 Final Project. The challenge was to create different types of agents that will carry out several tasks. Using the power of LLMs with LangChain and OpenAI, we were able to create AI Agents that performed different functions. Please see below for the 5 different agents that we were able to build:

1. **AssemblyAI Agent**: Retrieves a youtube video, downloads it, generates the transcription of the video, and allows the user to ask questions regarding the video.
2. **PandasAI Agent**: Allows the user to upload CSV files and to query the CSV. This agent is mostly used to generate plots of the data.
3. **Presentation Agent**: Allows the user to upload a file and generate powerpoint presentations of the data that is presented in their files. Currently supports only .ipynb files.
4. **README Agent**: Allows the user to give a file path on their local machine and generates an associated README file. This will be used by the members of this team to create README files in the future for future assignments.
5. **Web Scraping Agent**: This agent is given a URL as an input and scrapes the web. You are then able to ask questions regarding the data that was generated, and it can retrieve content from the web page.

## Assignment Deliverables

Please see below for the list of deliverables that have been submitted for this assignment. Please note that all deliverables are under the `Deliverables` folder.

1. `README.md`: README.md file detailing the project details. This file contains the deliverables and details everything about the project.
2. `CMPE258_Final_Project_Presentation_BayAreaRockers`: Powerpoint presentation detailing the project.
3. `Screenshots`: Folder containing screenshots of the application in use.
4. [Link to Video Presentation](youtube.com)

## Division of Labor

Please see below for the list of contributions made by each team member.

1. Aagam Shah: Wrote the code for the web scraper and youtube video portion.
2. Shawn Chumbar: Wrote the code for the Pandas AI Agent and the README generator agent.
3. Dhruval Shah: Wrote the code for the Powerpoint presentation agent.
4. Sajal Agarwal: Wrote the code for the main.py file and helped create deliverables. Helped setting up python environments on all dev machines and researched deployment steps.

## Setup Steps

Please see below for the steps required to get the project running locally.

1. Git clone the project.
2. Create a python virtual environment using conda: `conda create --name myenv`
3. Activate the virtual environment: `conda activate myenv`
4. install all requirements in the requirements.txt file: `pip install -r requirements.txt`
5. Run the main.py using streamlit: `streamlit run main.py`

From here you can navigate to the URL that streamlit provides and use the application.
