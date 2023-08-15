<h1>Java 11 | Selenium | TestNG | Maven | POM | Allure report | Integration with TMS Qase | Parallel Test</h1>
<p>This is a sample Java 11 Adopt Open JDK | Selenium WebDriver | Maven | TestNG | project created in IntelliJ IDE, using Page Object Model and Generic Type.</p>
<p>Website <a href="https://dev.swisscows.com">https://dev.swisscows.com/</a>&nbsp;was used to create functional, API, and UI tests.</p>

<p><strong>pom.xml dependencies used:</strong></p>
<blockquote>
<dependencies>
    
        <dependency>
            <groupId>org.testng</groupId>
            <artifactId>testng</artifactId>
            <version>7.7.1</version>
        </dependency>
        
        <dependency>
            <groupId>org.seleniumhq.selenium</groupId>
            <artifactId>selenium-java</artifactId>
            <version>4.10.0</version>
        </dependency>
        
        <dependency>
            <groupId>io.github.bonigarcia</groupId>
            <artifactId>webdrivermanager</artifactId>
            <version>5.3.3</version>
        </dependency>
        
        <dependency>
            <groupId>com.google.code.gson</groupId>
            <artifactId>gson</artifactId>
            <version>2.10</version>
        </dependency>
        
        <dependency>
            <groupId>com.fasterxml.jackson.core</groupId>
            <artifactId>jackson-databind</artifactId>
            <version>2.14.1</version>
        </dependency>
        
        <dependency>
            <groupId>io.rest-assured</groupId>
            <artifactId>rest-assured</artifactId>
            <version>5.3.0</version>
            <scope>test</scope>
        </dependency>
        
        <dependency>
            <groupId>org.json</groupId>
            <artifactId>json</artifactId>
            <version>20220924</version>
            <scope>test</scope>
        </dependency>
        
        <dependency>
            <groupId>org.apache.pdfbox</groupId>
            <artifactId>pdfbox</artifactId>
            <version>2.0.26</version>
        </dependency>
        
        <dependency>
            <groupId>io.qameta.allure</groupId>
            <artifactId>allure-testng</artifactId>
            <version>2.20.1</version>
            <scope>test</scope>
        </dependency>
        
        <dependency>
            <groupId>io.qase</groupId>
            <artifactId>qase-testng</artifactId>
            <version>3.0.5</version>
            <scope>test</scope>
        </dependency>
        
    </dependencies>
</blockquote>
<h1>Setup the project and execute tests locally</h1>
<p>1. Install IntelliJ IDE:<br /><a href="https://www.jetbrains.com/help/idea/installation-guide.html">https://www.jetbrains.com/help/idea/installation-guide.html</a></p>
<p>2. Copy the HTTPS project link from the GitHub repository:&nbsp;<br /><a href="https://github.com/ant0d0v/SwisscowsDev.git">https://github.com/ant0d0v/SwisscowsDev.git</a></p>
<p>3. Clone a repository from the main menu:&nbsp;<br /><a title="https://www.jetbrains.com/help/idea/cloning-repository.html#clone_project_from_main_screen" href="https://www.jetbrains.com/help/idea/cloning-repository.html#clone_project_from_main_screen">https://www.jetbrains.com/help/idea/cloning-repository.html#clone_project_from_main_screen</a></p>
<p>4. Go to the resources package, and copy local.properties.TEMPLATE file. Paste it to the resources package, and re-name the new file as&nbsp;local.properties</p>
<p>5. Execute test class or single test by opening the Test class, right-clicking on the green triangle, and choosing Run</p>
