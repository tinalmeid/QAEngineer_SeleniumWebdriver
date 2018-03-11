## Challenge QA Engineer ##

This small project implies in Test Automation of 'Flow Create an activity as a teacher' for AppAprova Teacher platform, using Junit and Selenium Webdriver and as IDE IntelliJ


#### Software required  ####

    Java JDK: Java SE Development Kit 8u161, 
    IDE: IntelliJ  » 2017.3.4, 
    Drive: ChromeDriver_win32  » 2.36,
    Browser: Chrome


#### Installation  
Download or clone the application

Download the libraries required to run and edit the tests 



#### Executando Testes ####
RunTest -> Ctrl+Shift+F10


#### Editando testes ####
 Use the IDE Intellij

 Import the project in File > Importe..> APPprova\QAEngineer


#### Estrutura do projeto ####


	test
   	 java
		suporte
	   		Generator //Class that defines the date and time of the file generated for in the Screenshot
	  		Screenshot //Class that captures system screens during test run
          	Web acessa //Class opens a Chrome session and AppAprova Teacher platform
 		Test
	 		CriarAtividadeComoProfessor // Contemplate this cases:
											          Access the login
											          Create a new Activity
											          Select the discipline
											          Select content
											          Add questiions questões
											          Salve activity draft
											          Select the saved activity draft
											          Edit activity draft
											          Post activity



#### Features ####
Supports multiple platforms (Windows, Linux, Mac OS, etc) and various architectures (32-bit, 64-bit),

Offers possibility to expose images as png,

In the project, you need to change the save location of the Screenshot ...APPprova\TestReport


#### Marven 
>https://mvnrepository.com/

<!-- https://mvnrepository.com/artifact/junit/junit -->
	 <dependency>
	  	    <groupId>junit</groupId>
	 	    <artifactId>junit</artifactId>
	  	    <version>4.12</version>
	 	    <scope>test</scope>
	</dependency>

 <!-- https://mvnrepository.com/artifact/org.seleniumhq.selenium/selenium-java -->
        <dependency>
               <groupId>org.seleniumhq.selenium</groupId>
               <artifactId>selenium-java</artifactId>
               <version>3.6.0</version>
        </dependency>

 <!-- https://mvnrepository.com/artifact/commons-io/commons-io -->
        <dependency>
              <groupId>commons-io</groupId>
              <artifactId>commons-io</artifactId>
              <version>2.6</version>
        </dependency>

  <!-- https://mvnrepository.com/artifact/org.easetech/easytest-core -->
        <dependency>
            <groupId>org.easetech</groupId>
            <artifactId>easytest-core</artifactId>
            <version>1.4.0</version>
        </dependency>

#### Download ####
The stable project version is available along with this file in Github.

>https://github.com/tinalmeid

