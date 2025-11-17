# PlayWrightTask
Simple project to meet the requirements in the task

- Create a BaseTest class to be inherited by all positive and negative tests. BaseTest class has @BeforeMethod and @AfterMethod
 @BeforeMethod is a setUp for instances - extent (for generating reports and tests), playwright, browser, page
 @AfterMethod is a tearDown to report failures/passes and to record screenshots for failed tests.

- Create a package to hold the tested pages with the methods in the corresponding page
- Create a package to hold the positive and negative tests
- Create a test output folder to hold the reports and the failed screenshots

