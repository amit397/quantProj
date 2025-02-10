quant project 



Plan:

1) Create a webpage that can show option pricing models based on user input
    1a) creates heatmap of the prices like on optionsprofitcalculator.com
    1b) creates 4d chart like the one in this video https://www.youtube.com/watch?v=PZSqt7w1XBk&ab_channel=CodingJesus (implied volt surface)
2) create some simple backend that persists previously calculated values on mongodb or some shit, and work primarily on building out some gRPC middleware that communicates with that backend service
3) Connect the website to some market api that can call live stock information and start setting up some mock trade functionality
4) create some sort of custom network protocol, where would it apply here i have no fucking clue but i need it on my resume



First Step More in Depth:
- Front end gatsby (react framework), sends info to backend flask service
- takes the info and creates the chart in matplotlib
- front end should be pretty barebones for the most part as of now just a few boxes for user inputs
- primarily focus on creating the charts    
