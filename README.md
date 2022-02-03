# Documentation
We live in the era of big data. For each topic, we have a huge amount of data that we can analyze. Powerful tools have been created over the years to manage big data. In this document, we will try to use these tools to make an in-depth analysis of one of the largest pandemics the world has ever suffered. We are talking about Covid-19. In the past two years of the pandemic, a vast amount of epidemiological data has been collected. We have created a platform for visualizing this data, using the latest available Visual Analytics techniques. We have come up with a solution that can help users better understand information about COVID-19 deaths, cases, and vaccines with a focus on the European countries.

For the complete documents:

* [Full report](./report)

* [Presentation slides](./slides)


# Reference dataset
Dataset is provided by Our World in Data. The Dataset is very huge, it contains the collected data for all the world. This dataset was built by collecting data from different sources:

1) COVID-19 Data Repository by the Center for Systems Science and Engineering (CSSE) at Johns Hopkins Uni- versity (JHU)
2) European Centre for Disease Prevention and Control
3) Government sources

***Dataset***: **[Our World in Data](https://github.com/owid/covid-19-data)**

# Technologies
Our platform is made by a Backend and a Frontend like a proper web app. The followin are the link for the relative repos:

* **[Backend](https://github.com/EU-CoVis-19/covid19-visualization-backend)**
* **[Frontend](https://github.com/EU-CoVis-19/covid19-visualization-frontend)**

# How to run

1) Download backend:
    ```
    git clone https://github.com/EU-CoVis-19/covid19-visualization-backend.git
    ```
2) Download frontend
    ```
    git clone https://github.com/EU-CoVis-19/covid19-visualization-frontend.git
    ```
3) Launch backend:
    ```
    node node bin/www.js
    ```
4) Launch frontend:
    ```
    npm start
    ```

# Authors

**[Valerio Coretti](https://www.linkedin.com/in/valerio-coretti-2913721a3/)**

**[Fabio Caputo](https://www.linkedin.com/in/fabio-caputo-41163b171/)**

**[Weihao Peng](https://www.linkedin.com/in/weihao-peng-a872b320a/)**
