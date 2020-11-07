# web-scraping-challenge
Mars web scraping, data storage, and Flask app

All of the content created for this project is stored in the [Missions_to_Mars](Missions_to_Mars) folder.

The [Jupyter Notebook](Mission_to_Mars/mission_to_mars.ipynb) contains the code used to test scraping 4 different websites for the data and images about Mars to display on a single webpage.

[app.py](Missions_to_Mars/app.py) is a Flask app that references [scrape_mars.py](Missions_to_Mars/scrape_mars.py), which includes the function to scrape the websites, using the code developed in the Jupyter Notebook file mentioned above. The output webpage uses a jingu template found in [Missions_to_Mars/templates/index.html](Missions_to_Mars/templates/index.html)

## Screen Shots

The following screenshots sample the webpage output.

![Website top](Missions_to_Mars/Resources/screenshots/Mars_SS_top.png)

![Featured image and Mars Facts](Missions_to_Mars/Resources/screenshots/Mars_SS_image_facts.png)

![Hemispheres top row](Missions_to_Mars/Resources/screenshots/Mars_SS_Hemispheres_1.png)
![Hemispheres bottom row](Missions_to_Mars/Resources/screenshots/Mars_SS_Hemispheres_2.png)