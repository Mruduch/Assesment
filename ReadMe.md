# Test requirement: 
Automate the Search strings on the given website
# Prerequisites
Selenium Java version: 3.9.1
Java version: SE-1.8
Eclipse version: Oxygen.2 Release (4.7.2)
Google Chrome version: 64

# Test scenarios
# Scenario1: Successfully searched for the word Risk Management.
GIVEN Automate program to open a link and search for Risk Management
When I create a project and a class write a automate program starting with setproperty Method and copy Chromedriver path in it
AND write Webdriver method and import chromedriver and webdriver methods in it.
THEN write driver.get method to open link and serach for wenElement Id in search button
THEN Webpage www.sword-activeversion should be opened and searched succesfully for the string RiskManagement. 

# Scenario2: Succesfully searched for the string Leverage
GIVEN Automate to open link and search for string Leverage
open link www.sword-activeversion and search for the string Leverage

# Scenario3: 
open link www.sword-activeversion and search for the string Compatibility

# Expected results
For the 3 scenarios the search should appear with relevant names.
