# Project---Testing-the-functionality-of-AS-GLASS-pages
The functionality of AS GLASS pages


package Pagefunctionality;

import org.openqa.selenium.By;
import org.openqa.selenium.WebDriver;
import org.openqa.selenium.chrome.ChromeDriver;

public class GlazingService {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
	    System.setProperty("webdriver.chrome.driver", "C:\\Users\\user\\Downloads\\chromedriver_win32\\chromedriver.exe");
	    
	    WebDriver driver = new ChromeDriver();
	    
	    driver.get("https://ueni.com/fr-fr/societe/pont-de-cheruy-38230/reparations-de-vehicules/as-glass");
	    
	        // AS GLASS show the original seven pages but cannot navigate to select options from the pages.
	    
	    driver.findElement(By.cssSelector("#group-0 > div.cl1x0t-1-layout__Wrapper-fCnKct.jyYUZz > div:nth-child(1)")).click();  
	    
	    //driver.findElement(By.cssSelector("#group-0 > div.cl1x0t-1-layout__Wrapper-fCnKct.jyYUZz > div:nth-child(2)")).click();
	    
	    //driver.findElement(By.cssSelector("#group-0 > div.cl1x0t-1-layout__Wrapper-fCnKct.jyYUZz > div:nth-child(3)")).click();
	    
	    //driver.findElement(By.cssSelector("#group-0 > div.cl1x0t-1-layout__Wrapper-fCnKct.jyYUZz > div:nth-child(4)")).click();
	    
	    //driver.findElement(By.cssSelector("#group-0 > div.cl1x0t-1-layout__Wrapper-fCnKct.jyYUZz > div:nth-child(5)")).click();
	    
	    //driver.findElement(By.cssSelector("#group-0 > div.cl1x0t-1-layout__Wrapper-fCnKct.jyYUZz > div:nth-child(6)")).click();
	    
	    //driver.findElement(By.cssSelector("#group-0 > div.cl1x0t-1-layout__Wrapper-fCnKct.jyYUZz > div:nth-child(7)")).click();
	}

}
