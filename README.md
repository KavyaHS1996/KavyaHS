package Selenium1;

import org.openqa.selenium.WebDriver;
import org.openqa.selenium.chrome.ChromeDriver;
import org.testng.Reporter;
import org.testng.annotations.Test;

public class Demo1
{
	@Test(priority=1)
	public void testDemo()
	{
		Reporter.log("test result", true);
	}
	@Test(priority=2)
	public void test1()
	{
		Reporter.log("testresult", true);
	}
		
}


