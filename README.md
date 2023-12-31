# Web_Testing---Selenium IDE

<h4><h2>Background to the Problem</h2>
In today's digital age, Facebook is a popular social media platform with billions of users 
worldwide. As Facebook undergoes frequent updates and changes, it is crucial to ensure that its 
features and functionalities are working correctly to provide a seamless user experience. Manual 
testing of Facebook's entire functionality can be time-consuming and prone to human errors, 
necessitating a more efficient and automated approach.</h4>

<h4><h2>Solution to the Problem</h2>
Implementing an automated testing framework using Selenium IDE for Facebook can greatly 
streamline the testing process and improve efficiency. Selenium IDE is a browser extension that 
allows the recording and playback of user actions, making it suitable for creating test cases for 
web applications like Facebook.<br>
By utilizing Selenium IDE, the following benefits can be achieved:
<h3><b>o  Test Case Creation: </b></h3>Selenium IDE enables the creation of test cases by recording user actions 
such as logging in, posting content, searching for friends, and interacting with various features 
on Facebook.<br>
<h3><b>o Efficient Test Execution: </b></h3>With Selenium IDE, test cases can be executed automatically, reducing 
the need for manual intervention and saving time. This allows for faster and more frequent 
testing, ensuring that changes or updates to Facebook do not introduce new bugs or issues.<br>
<h3><b>o Validation of Functionality:</b></h3>  Test cases can be designed to validate key functionalities of 
Facebook, including user authentication, posting and sharing content, commenting, liking, and 
messaging. By systematically checking these functionalities, any potential issues or regressions 
can be identified early on.<br>
<h3><b>o Error Detection and Reporting: </b></h3> Selenium IDE provides built-in mechanisms for capturing and 
reporting errors encountered during test execution. This helps in identifying specific areas of 
Facebook where issues are occurring and enables developers to address them promptly.
<h3><b>o Continuous Integration: </b></h3> Selenium IDE can be integrated with continuous integration tools like 
Jenkins, allowing for the automation of test execution as part of the development workflow. This 
ensures that Facebook's functionality is continuously tested, providing timely feedback on the 
impact of code changes.<br>
By implementing an automated testing framework using Selenium IDE for Facebook, the project 
aims to enhance the testing process, improve efficiency, and ensure the smooth functioning of 
the platform, ultimately leading to a better user experience for Facebook users. environment
where job seekers can discover reputable companies and organizations that align with their 
career aspirations.</h4>

<h3>Sample Work</h3>

![image](https://github.com/Opee10/Web_Testing---Selenium/assets/106880043/dc85897e-969e-4e45-acc7-802b6a2295f2)
![image](https://github.com/Opee10/Web_Testing---Selenium/assets/106880043/4c15fb13-4258-49d6-b472-94f93dc83fba)

<h4>In the above picture, I wanted to test by sending friend requests to another Facebook profile using Selenium IDE. And we can see all test cases that were written have been executed and run correctly.</h4>

<h3>Exported Code</h3>
<h4>// Generated by Selenium IDE
import org.junit.Test;<br>
import org.junit.Before;<br>
import org.junit.After;<br>
import static org.junit.Assert.*;<br>
import static org.hamcrest.CoreMatchers.is;<br>
import static org.hamcrest.core.IsNot.not;<br>
import org.openqa.selenium.By;<br>
import org.openqa.selenium.WebDriver;<br>
import org.openqa.selenium.firefox.FirefoxDriver;<br>
import org.openqa.selenium.chrome.ChromeDriver;<br>
import org.openqa.selenium.remote.RemoteWebDriver;<br>
import org.openqa.selenium.remote.DesiredCapabilities;<br>
import org.openqa.selenium.Dimension;<br>
import org.openqa.selenium.WebElement;<br>
import org.openqa.selenium.interactions.Actions;<br>
import org.openqa.selenium.support.ui.ExpectedConditions;<br>
import org.openqa.selenium.support.ui.WebDriverWait;<br>
import org.openqa.selenium.JavascriptExecutor;<br>
import org.openqa.selenium.Alert;<br>
import org.openqa.selenium.Keys;<br>
import java.util.*;<br>
import java.net.MalformedURLException;<br>
import java.net.URL;<br>
public class SendRequestTest {<br>
  private WebDriver driver;<br>
  private Map<String, Object> vars;<br>
  JavascriptExecutor js;<br>
  @Before<br>
  public void setUp() {<br>
    driver = new ChromeDriver();<br>
    js = (JavascriptExecutor) driver;<br>
    vars = new HashMap<String, Object>();<br>
  }<br>
  @After<br>
  public void tearDown() {<br>
    driver.quit();<br>
  }<br>
  @Test<br>
  public void sendRequest() {<br>
    driver.get("https://web.facebook.com/");<br>
    driver.manage().window().setSize(new Dimension(691, 727));<br>
    driver.findElement(By.cssSelector(".x1s07b3s")).click();<br>
    driver.findElement(By.cssSelector("#randy\\ blythe .xu06os2:nth-child(2) > .x193iq5w > .x1lliihq")).click();<br>
    driver.findElement(By.cssSelector(".xsgj6o6:nth-child(1) .x9f619 > .x193iq5w > .x1lliihq")).click();<br>
  }<br>
}<br>
</h4><br>


