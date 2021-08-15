# WWChallenge
# UI Automation - Take Home Challenge

Details:Eclipse Maven Project 
Eclipse Community Latest Version = Eclipse IDE 2021‑06
Java = JRE System Library [JavaSE-1.8(Java SE 14.0.2)]
Maven dependencies added for Selenium-java (3.141.59) & Selenium-api (3.141.59), Common-io (2.6), JUnit (4.11)

Run takeHomeUIAutomationTest.java as JunitTest 

Following steps are executed as part of test:

Steps:

1) Navigate to WW Studio Finder page  https://www.weightwatchers.com/us/find-a-workshop/

2) Assert loaded page title contains “Find WW Studios & Meetings Near You | WW USA”

3) Under Find your Workshop, click on Studios

4) In the search field, search for meetings for zip code: 10011

5) Print the title of the first result and the distance (located on the right of location title/name)

6) Click on the first search result and then verify displayed location name/title matches with the name of the first searched result that was clicked.

7) Click on Business Hours

8) Create a method to print all the business hours for that studio


