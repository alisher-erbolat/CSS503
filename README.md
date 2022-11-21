# CSS503

Methods:

  For scraping websites we use selenium. Selenium is an open source umbrella project for a range of tools and libraries aimed at supporting browser automation. It provides a playback tool for authoring functional tests across most modern web browsers, without the need to learn a test scripting language. 
	For finding elements in a web page we choose xpath locator. XPath in Selenium is an XML path used for navigation through the HTML structure of the page. It is a syntax or language for finding any element on a web page using XML path expression.
  
Syntax for XPath selenium:
Xpath=//tagname[@attribute='value']

  Advantages of xpath locator. Search by the text of the selected item. First of all, when
we get a web application to test, we see text. This text can be on the buttons, drop-down list boxes, and even in the links. If parameters of such elements can be modified, the text will probably stay the same. A set of built-in functions. Such parameters as a sibling, normalize-space(), and others in combination with a logical operator (for example, or and not) make it possible to develop flexible and efficient locators.
	But in some cases we use beautifulsoup to parse the site. This is convenient when we need to use many identical elements, that is, for blocks (a vacancy block).
And used the selenium methods WebDriverWait and expected_conditions to search for elements. These methods wait for the elements until they appear on the screen.
	For data manipulation, we used the pandas library. Pandas is a software library written for the Python programming language for data manipulation and analysis.[2] In particular, it offers data structures and operations for manipulating numerical tables and time series.
