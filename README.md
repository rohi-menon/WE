# WE
Sample framework for WealthEngine
The framework is a basic framework to test 2 flows on the goindigo flight booking site.
Below are the classes in the project
Wrappers - This class initializes the webdriver and has methods that perform actions on the web page such as click, get text, perform keyboard actions etc
Page classes - Locaed elements using page factory @FindBy methods and methods to perform actions on these web elements
Test class - 2 Sample test cases that have a ticket booking navigation and a contact us navigation
I have used Data Providers to parameterize the tests . If given more time I would like to add an input from an xml file or excel
Reports - For now I have used the in built testNG report . Results can be seen in the console once a test is run. I would add Extent report to the framework for better reporting. Due to lack of time I have stopped this implementation.
