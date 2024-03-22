# <p align="center">Module 12 Challenge: NoSQL
## Data Analytics assignment to set up, update, and explore a database of UK food hygiene ratings with PyMongo
### Overview
1. Database set up
2. Database updating
3. Database exploratory analysis
### Features
1. Use the terminal to import data in the form of a .json file, creating a database and a collection to house the data, and create an instance of the Mongo client in Jupyter Notebook
2. Update the database using queries via PyMongo in Jupyter Notebook
3. Perform exploratory analysis on the database via PyMongo in Jupyter Notebook
### Prerequisites
- Familiarity with and use of the Python programming language, and software to interact with .ipynb files, such as [Jupyter Notebook](https://jupyter.org/)
    - Also familiarity with and use of the [PyMongo](https://www.mongodb.com/docs/drivers/pymongo/) package within Python
- Familiarity with and use of a terminal emulator, such as Terminal for macOS
- Familiarity with and use of MongoDB (the [Community Edition](https://www.mongodb.com/try/download/community) was used here)
### Usage
- Download the .ipynb files and the Resources.zip file to the same directory
- Unzip the Resources.zip file in the directory (at this point the .zip file can be deleted/removed from the directory)
    - The Resources directory contains the .json file that will be imported
#### NoSQL_setup.ipynb
- Launch Jupyter Notebook, navigate to the appropriate directory, and open NoSQL_setup.ipynb
    - Also open the terminal emulator, navigate to the Resources directory, and run the following line of code:
        - `mongoimport --type json -d uk_food -c establishments --drop --jsonArray establishments.json`
    - The code will simultaneously:
        1. Import the .json file
        2. Create a database called `uk_food`
        3. Create a collection called `establishments`
- Inspect the dependencies and ensure they're installed
- Clear outputs (if desired), and inspect/run the code cell by cell, paying attention to assignment prompts and comments throughout
- Have fun exploring/playing around with the data/code! Challenge yourself to come up with ways to make the code more clear or efficient!
#### NoSQL_analysis.ipynb
- If closed, re-launch Jupyter Notebook, navigate to the appropriate directory, and open NoSQL_analysis.ipynb
- Inspect the dependencies and ensure they're installed
- Clear outputs (if desired), and inspect/run the code cell by cell, paying attention to assignment prompts/questions/answers and comments throughout
- Have fun exploring/playing around with the data/code! Challenge yourself to come up with ways to make the code more clear or efficient!
### License
[MIT License](https://opensource.org/licenses/MIT)
### Contact
[Email](mailto:cengelhart@gmail.com)\
[GitHub](https://github.com/cengelhart0120)
