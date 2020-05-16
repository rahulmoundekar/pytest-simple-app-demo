# Pytest With Python :

![python](https://img.shields.io/badge/Made%20with-Python-1f425f.svg)
pytest is a framework that makes building simple and scalable tests easy. Tests are expressive and readable—no boilerplate code required. Get started in minutes with a small unit test or complex functional test for your application or library.

Pytest is a testing framework which allows us to write test codes using python. You can write code to test anything like database , API, even UI if you want. But pytest is mainly being used in industry to write tests for APIs.
# Why use PyTest?
* Very easy to start with because of its simple and easy syntax.
* Can run tests in parallel.
* Can run a specific test or a subset of tests
* Automatically detect tests
* Skip tests
* Open source

#### Pre Requisites

  - Making the project as :
    ```
    mkdir pytest-simple-app-demo
	cd pytest-simple-app-demo
    ```
  - Web Scraping installation:
     ```
     open command prompt type 
        pip install virtualenv
     create virtualenv
    	>>virtualenv venv
     we need to activate virtualenv for use
    	>>venv\scripts\activate
     
     need libraries for Web Scraping :
     
    pip install -U pytest
    pytest --version
    ```
    While the installation of Selenium makes the functionality available to you, you need additional drivers for it to be able to interface with a chosen web browser. The download links for the drivers are available here: Chrome, Edge, Firefox and Safari. For the remainder of this tutorial, we will use the Chrome driver. Follow the link for the browser of your choice and download the driver for the compatible version.
    
#### Test files and Test methods
   * By default pytest only identifies the file names starting with test_ or ending with _test as the test files. 
   * Pytest requires the test method names to start with "test."
   
   All other method names will be ignored even if we explicitly ask to run those methods.
 - In order to execute code
    * To run tests only from a specific file
            
            pytest test_TestDemo.py