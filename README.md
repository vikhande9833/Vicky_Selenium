# Vicky_Selenium

What is Selenium?
•	Selenium is open-source tool.
•	Selenium is used to automate the web application.

2. Different Types/Components of Selenium

a. Selenium IDE
b. Selenium RC
c. Selenium Web Driver
d. Selenium Grid

3. Advantages of Selenium Web Driver
	
•	Selenium Web Driver support for multiple languages like- java, C#, ruby, python etc.

•	Selenium Web Driver support for multiple OS like mac, Windows, Linux etc.

•	Selenium Web Driver support for different browsers like chrome, edge, Firefox etc.

•	Selenium Web Driver are support for to design the framework using TestNG and Maven.

•	Selenium Web Driver is used to execute multiple test cases.

4. Disadvantages of Selenium Web Driver

•	Selenium Web Driver are not support for desktop application.
•	It can’t support for mobile based OTP.
•	It can’t support for captcha images. 
•	It can’t support for image-based application.
New Features in selenium-4

•	New relative locators like above, below, toLeftOf, toRightOf

•	Can create new window tab by using Window.Tab button
Example: driver.switchTo().newWindow(WindowType.WINDOW);

•	Changes in Actions class.

Example:
Selenium-3 : moveToElement(on Element).click(). 
Selenium-4: click(WebElement)
Selenium-3 : moveToElement(element).doubleClick()
Selenium-4: doubleClick(WebElement)

•	We can take screenshot of any web element.

Example:
WebElement element = driver.findElement(By.id("actual value"));
File source = element.getScreenshotAs(OutputType.FILE);            
File destination = new File("path of file");
FileUtils.copyFile(source, destination);


8. What is DOM?
•	DOM is Document Object Model and it have the HTML web page that contains the Web Elements of Web Page.




12. Which are the Interfaces in Selenium?

•	WebDriver
•	WebElement
•	Alert
•	TakeScreenShot
•	JavascriptExecutor
•	OutputType
•	SearchContext

9. What is Web Driver?
•	Web Driver is an Interface.  
•	Web driver is used for to initialize the different Web Browser. 
•	Web Driver connects the test script with Web Browser.

10. What is WebDriver driver = new ChromeDriver ();

•	WebDriver is an Interface and controls the Browser Driver.
•	Driver is a reference variable which is access the Selenium library.
•	ChromeDriver is a class in Selenium and Browser driver which is control the      Chrome Browser.

11. Can we initialize ChromeDriver driver = new ChromeDriver ()?
•	Yes, we can initialize the browser using ChromeDriver instead of WebDriver.


12. Which are the Navigation methods in Selenium?

•	driver.navigate().to(Url);
•	driver.navigate().forward();
•	driver.navigate().back();
•	driver.navigate().refresh();



13. What are different methods used in “Search Context” Interface?
•	driver.findElement();
•	driver.findElements();





13. Which are the different ways to launch the browser?
•	driver.get(“Url”);
•	driver.navigate().To(“Url”);

•	JavascriptExecutor js = (JavascriptExecutor) driver;
•	js.executeScript ("window.location='https://www.google.com'");

14. What is difference between driver.get(); and driver.navigate();?


driver.get();	
driver.navigate().To();
This method will wait until the page has finished loading.	This method will not be wait only redirecting to url and returning back.
We can’t get history of any page by this method.	We can get history of any page by this method.


12. Different common methods in Web Driver 
•	driver.get ();
•	driver. getWindowHandle();
•	driver.getWindowHandles();
•	driver.findElement();
•	driver.findElements();
•	driver.manage();



