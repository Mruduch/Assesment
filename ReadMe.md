# Feature: 
Automate the Search strings on the given website. Here we will search for few strings on given website

# Background
Given search strings and the website to search for.

# Prerequisites
Selenium Java version: 3.9.1
Java version: SE-1.8
Eclipse version: Oxygen.2 Release (4.7.2)
Google Chrome version: 64

# Test scenarios 
# Scenario 1:  search for the word RiskManagement
GIVEN  search  string Risk Management
WHEN I write a testcase and run it opens browser to URL: www.sword-Activeversion
AND search for string Risk Management
THEN the website searches the matching words and links for it

# Actual results
 I got all the results and links which matches the  string  RiskManagement.



# Scenario2: Succesfully searched for the string Leverage
GIVEN  search  string Leverage
WHEN I write a testcase and run it opens browser to URL: www.sword-Activeversion
AND search for string LEVERAGE 
THEN the website searches the matching words and links for it

# Actual results
 I am able to see all the results and links  that matches the string Leverage.


# Scenario3: 
GIVEN  search string Compatibility
WHEN I write a testcase and run it opens browser to URL: www.sword-Activeversion
AND search for string Compatibility 
THEN the website searches the matching words and links for it

# Actual results
Sorry no results found please try again.
