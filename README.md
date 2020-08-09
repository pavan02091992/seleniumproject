1. SELENIUM is a free (open-source) automated testing framework used to validate web applications across different browsers and platforms. You can use multiple programming languages like Java, C#, Python etc to create Selenium Test Scripts. Testing done using the Selenium tool is usually referred to as Selenium Testing.

2. click element:
Clicking is perhaps the most common way of interacting with web elements.

It does not take any parameter/argument.
The method automatically waits for a new page to load if applicable.
The element to be clicked-on, must be visible (height and width must not be equal to zero).

3. Get command:
Get commands fetch various important information about the page/element. 

get(): It automatically opens a new browser window and fetches the page that you specify inside its parentheses.
       The parameter must be a String object.

getTitle(): Needs no parameters
            Fetches the title of the current page
            Leading and trailing white spaces are trimmed
            Returns a null string if the page has no title

getPageSource(): Needs no parameters
                 Returns the source code of the page as a String value

getCurrentURL(): Needs no parameters
                 Fetches the string representing the current URL that the browser is looking at

getText(): Fetches the inner text of the element that you specify
