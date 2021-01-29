Visualizing health trends among different demographics


Starting with a basic HTML webpage, run on the liveserver, we explore the relationships between health outcomes
and demographic indicators. Specifically, we look at Age, Obesity, and Income, with their relationships displayed in 
a bubble chart with hover-over tags for demographic information by state. This project uses D3, Bootstrap, tooltip, Cloudflare, and jquery.

I wrote in a pathway to access the data.csv file through the app.py. After filling in the rest of the information (and connecting to the css and d3 style sheets), the serv.py server launches the website itself. With critical information from the csv grabbed, the next step was to dissect out which bits were useful to the visualization. Tooltip provided the dynamic aspects like hoverover and changes upon event. The data is somewhat limited by being averages of the statewide population. For instance, most of the ages (average ages, that is) represented are "30's to 40's." This makes the visualization show a lot of cluster around a central horizon and not give us any dramatic variation or outliers, which may have flagged more public-health trends. 
