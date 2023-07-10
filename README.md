# assist-tracking-app-v2

## Motivation

In the public realm, our access to spatial data is limited to shot coordinates. But what about spatial data looking at pass coordinates on assists? Passing is such an integral part of the game and [it’s what makes the game so beautiful to watch](https://www.youtube.com/watch?v=NsBGF1fjXvY&ab_channel=EvinGualberto). So how can we visualize passing location data? Can we create any interesting player insights using this data the way shot charts do with shot coordinate data?

## Development

- Code: Python
- Framework: Dash (A Python Framework)
- Libraries: Flask, SQLAlchemy, Plotly, Pandas, SQLite3, NumPy, Dash, Numpy, Dash Bootstrap, Dash Authentication
- Database: PostgreSQL via Heroku
- Deployment: Heroku

#### Useful Links
- [Dash DAQ](https://dash.plotly.com/dash-daq)
- [Dash Framework](https://plotly.com/dash/)
- [Dash Bootstrap Components](https://dash-bootstrap-components.opensource.faculty.ai/)

## Deployment
In a terminal at this directory, run the following command to install all necessary libraries / packages:

```pip install -r requirements.txt```

To test the app locally, run the following command:

```python main.py```

Deploy the App to Heroku, use the [tutorial that outlines the instructions here](https://drive.google.com/file/d/1kowjMGKN6rbxh9n-5q1cP3BkcZ2yOAvo/view).

#### Live Dashboard for Player Reports | A Before and After

The Interactive Dashboard builds a player report showing their directional tendencies, hotspots on the floor, flow diagrams of outcomes, and preferred timing for passes during assist plays based on 5000+ manually tracked data points that are stored in a PostgreSQL database. Users can apply multiple filters such as opponent team, date, shot type created, shot clock, minute left in the period, etc. and the dashboard will dynamically update accordingly.

##### Before

![image](https://github.com/lukarh/assist-tracking-app-v2/assets/65103724/d53aeb8b-a1e9-45d2-b838-1452c700db67)

![image](https://github.com/lukarh/assist-tracking-app-v2/assets/65103724/1dc8c168-feaf-4be8-a18d-52937237d76d)


##### After

![dashboard-ui](https://user-images.githubusercontent.com/65103724/163692815-85a7d1e1-f601-417f-801c-277c355b471f.png)

**NOTE: This Repository does not have access to SQL database key**
