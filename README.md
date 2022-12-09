# DataFellowship8-DataVizualization
![image](https://user-images.githubusercontent.com/85284506/206662638-d5a08a92-ba28-4a45-b35c-59f356982241.png)
Metabase is an open source business intelligence tool that lets you create charts and dashboards using data from a variety of databases and data sources.

## Install Metabase with Docker
Assuming you have Docker installed and running, get the latest Docker image:
```bash
docker pull metabase/metabase:latest
```

Then start the Metabase container:
```bash
docker run -d -p 3000:3000 --name metabase metabase/metabase
```
## Launching Metabase
To launch Metabase, simply go to http://localhost:3000/setup/ which is the default port that the Metabase server will be listening to.

After Metabase is launched, select your preferred language and add your contact information.
+ Setting up an admin account
+ Gathering your database info
+ Connect to your database

for more information about setting up Metabase, click [here](https://www.metabase.com/docs/latest/configuring-metabase/setting-up-metabase)

## All you need to know about Metabase
+ `Questions` a query, its results, and its visualization. This is where you want to create chart/graph
+ `Dashboard` Group of Questions we created before and present them on a single page
+ `Markdown` Metabase allows to add flexible text boxes to your dashboards using Markdown syntax. Learn more about markdown syntax [here](https://www.metabase.com/learn/dashboards/markdown)

## Create an Interactive Dashboard
Here is my dashboard from [Yellow Taxi Trip Data](https://github.com/bulletsrip/DataFellowship8-dbt)

![Yellow Trip Dashboard · Metabase_pages-to-jpg-0001](https://user-images.githubusercontent.com/85284506/206668374-f99841fe-645e-4141-8f12-34a1f09f17b3.jpg)

