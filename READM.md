# SPS-5542-Intelligent-Water-Distribution-Monitoring-System- This project is done under IBM-GURUCOOL FDP Program 
### Skills Required: IBM IoT Platform,IBM Nodered,IBM Cloudant DB
#### Project Description:
#### Project Idea:The project Intelligent water distribution system, as the name says it is all about management of water supply throughout the scale, 
                   right from small societies, townships to entire urban infrastructure and also for irrigation water supply management. Main task of 
                   the water distribution system is to maintain the water in the tank and also generate the water bills to the individual households 
                   which involves human efforts. This system can be automated using the Internet of things.
#### Solution Requirements:The proposed system should continuously monitor the main tank water level and should automatically switch on/off the motors
                           according to the tank water level and alert the admins.it should monitor the water flow of the individual houses and store 
                           the flow rate of each in the Cloudant DB to generate the water bills. Tank water level and the bills should be visualized 
                           in the dashboard so that the Admin can monitor them.
###Project Flow:

# 1.Main tank water level and Water flow to individual houses is continuously updated to IBM IoT platform (Use Online simulator sensor for water flow and water level) 

# 2.Create a Node-RED flow to get the data from IBM IoT platform and store it in cloudant DB. 

# 3.Display the tank water level in the UI 

# 4.Retrieve the flowrate of individual houses and generate bills and display them in UI.

