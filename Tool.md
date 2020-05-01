# [Watir-Web Application Testing in Ruby]Watir is a Ruby open source software tool. Watir operates exactly the same manner as a browser: clicking on links, completing forms and validating text. [Watir](https://en.wikipedia.org/wiki/Watir) runs Internet Explorer, Firefox, Chrome, Opera and Safari and is available as a gem from RubyGems.

**Testing Approach:** Ruby testing
**Testing Level:** Web browsers testing
**Target application domain:** Web application system

## Features
* **Location web elements**: You can find web elements that are made in the browser in various ways. The most frequent ones are username, gender, name of tag, customized attributes, mark etc.
* **Taking Screenshots**: Watir makes the testing performed as and when necessary to take a screenshot. It helps to track the interim check.
* **Page Performance**: The Performance Entity, which has properties like Performance.timing, Performance.navigation, Performance.memory and Performance.timeOreigin can be easily calculated by using page data. This knowledge is accessed by connecting to the navigator.
* **Page Objects**: Watir's page object lets us reuse the code as classes. With this feature, we can automate our app and make it manageable without duplicating code.
* **Downloads**: With Watir, downloading file for UI or website is easy to check.
* **Alerts**: Watir offers easy-to-use APIs in your UI or website to check popup warnings.
* **Headless Testing**: The specifics are collected in the command line using headless checking, without having to open the window. It assists in conducting UI test cases on the command line.

## Pros
* Being an open-source platform with comprehensive community support, the group responds to all scripting-related requests and addresses bugs in no time (if any).
* It’s a Ruby library
* Multi browser (& OS) support
* Has a rich API 
* gives more stable and straightforward feeling
* can detect when it's finished loading
* It performs faster in comparison to its counterparts available in the industry
* WATIR has 100s of light-weight ruby gems that makes scripting easier, faster, and maintainable
## Cons
* Every browser requires a different
library
* Doesn’t automate mobile-native applications.
* WATIR only supports Ruby code

## Required information / models: Watir connects with the provided client and follows the instructions to open the URL, clicks the button and enters data in a textbox like any real person does. Watir is most commonly used in testing system such as RSpec, Concumber, etc. for his browser support.
## Target platform and dependencies: The watir tool is written in Ruby. Ruby is a widely structured, general language of programming. Ruby is typed dynamically and removes waste. It follows many paradigms of programming, object and functional programming , including procedural.The watir tool is confirmed to work on x86 Linux, MacOS, windows and Solaris.
**Dependencies:** 
* Linux machine, Windows, Mac
* Command line experience
## Updates
From 2019 to 2018 there was strong contribution activity but, the last commit is almost fifteen months ago. Because of the various uses of the same tool I believe the tool has been reached in a very secure version. The lastest version is 6.16.5.
**Latest update:** December 25, 2018
**First release date:** November 16, 2009
## License:** MIT license
## Tutorials and documentation
* Tutorial: There is a watir tutorial site available [here](https://www.tutorialspoint.com/watir/index.htm). The specific site contains extra material like installation, pictures, examples with command line.
* Documentation: The official documentation is available [here](https://www.rubydoc.info/gems/watir/)
## Usage examples
For example im adding a code where we can see if we  go Google.co.in web page and then click on gmail
* code-
* require 'watir'
* test_site = "https://www.google.co.in/"
* browser = Watir::Browser.new:firefox
* browser.goto test_site
* browser.link(:href, "https://mail.google.com/mail/?tab=wm").click
* puts “Test Executes”
* browser.close

* In this example we can open browser in the presence of watir library ,test site and when we are done we can close the browser through browser.close command.

There are multiple examples of tools that used the watir. Some instances are:
* [Unit Test Frameworks](https://www.facebook.com/notes/facebook-engineering/watir-to-webdriver-unit-test-frameworks/10150314152278920):Watir to WebDriver: Unit Test Frameworks.
* [Opera Browser ](https://www.opera.com/computer/beta): A new member in the Watir-family
## Alternative tools
* [UI.Vision RPA](https://github.com/A9T9/Kantu)
* [Selenium](https://github.com/SeleniumHQ/selenium)
* [Testim](https://github.com/testimio)
