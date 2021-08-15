# WWChallenge
# UI Automation - Take Home Challenge

Details: Eclipse Maven Project 

Eclipse Community Latest Version = Eclipse IDE 2021‑06

Java = JRE System Library [JavaSE-1.8(Java SE 14.0.2)]

Maven dependencies added for Selenium-java (3.141.59) & Selenium-api (3.141.59), Common-io (2.6), JUnit (4.11)

Selenium Chromedriver = present in Challenge folder at location = src/test/resources/drivers/chromedriver (Compatible with mac only)


Test Steps:

1) Navigate to WW Studio Finder page  https://www.weightwatchers.com/us/find-a-workshop/

2) Assert loaded page title contains “Find WW Studios & Meetings Near You | WW USA”

3) Under Find your Workshop, click on Studios

4) In the search field, search for meetings for zip code: 10011

5) Print the title of the first result and the distance (located on the right of location title/name)

6) Click on the first search result and then verify displayed location name/title matches with the name of the first searched result that was clicked.

7) Click on Business Hours

8) Create a method to print all the business hours for that studio


Steps to run attached project

1. Download Challenge.zip on local machine 
2. Unzip compressed Challenge.zip to Challenge
3. Open Eclipse
4. Click on Open Project from file system
5. Provide the path of the Challenge folder
6. Build Project & make sure all the maven dependencies are installed properly 
7. Run takeHomeUIAutomationTest.java as JunitTest 

