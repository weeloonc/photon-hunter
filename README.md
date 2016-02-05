# CS4222 Assignment 1: Light Analyzer


## Group 20 Members
CHEU WEE LOON   A0097836L   
GOH JIAQUAN     A0097722X   
QUEK JUN JIE    A0098816M


## Task 1:
Data logs can be found in /rawdata folder.
Frequency distribution graph can be found at /FrequencyDistributionGraph.xlsx


## Task 2:
In analysing our frequency distribution graph, we can see a significant drop in the count of lumen after the range of 1500 lux. We think 1500 lux is a practical upper limit of the amount of light that can be detected in indoor environment. Hence we set 1500 lux as the threshold for indoor.


## Task 3:
Using the light sensor has limitations in accurately determining whether the user is indoor or outdoor. The ambient light sensor on mobile phones are directional. When the phone is angled sideways or downwards, the values recorded will be significantly lower due to lesser amount of light hitting the sensor. When gathering lumen data, we try to orientate the phone facing upwards to eliminate differences in values recorded due to device orientation.  Therefore in many places where the amount of light is close to the threshold, it is very likely to have incorrect answers.

Situation where the user could be outdoor but application indicates indoor:
    - In a cloudy day or when there are dark clouds, the amount of light could be reduced drastically, and even if the user is to walk outdoors, with the low amount of light, the application could display as indoor status.
    - The user is walking outdoor during the night and there is no strong light.

Situation where the user could be indoor but application indicates outdoor:
    - The user is inside a brightly lit room, for example in a room with fully opened windows during day.
