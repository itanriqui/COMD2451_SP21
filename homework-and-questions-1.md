1. What does HTML stand for?
    Hyper Text Markup Language
    
2. What does HTML do?
    HTML gives a page structure and meaning by defining content.
    
3. What is an HTML element? What can it represent? And what does it define?
    An HTML element is an individual componet within an HTML document. It can represent semantics or meaning and it defines the structure and content of an object within a webpage.
    
4. How is an HTML element identified?
    Elements are identified by angle brackets < > surrounding an element name.
    
5. What is an HTML tag?
    The use of angle brackets surrounding an element creates a tag. Tags usually denote the start and end of an element. They can be self-closing as well.
    
6. What is the difference between an HTML element and an HTML tag?
    As is it is generally used an HTML element refers to a start tag, its attributes, an end tag, and the content within. An HTML tag can be an opening tag, closing tag, or a self-closing tag. HTML tag and HTML element are often used interchangeably.

7. What is an HTML attribute and what is the format for defining an HTML attribute? And where is the attribute and its value placed?
    An HTML attribute is a property used to provide additional information about an element. The format consists of the attribute name followed by a = and then the attribute value in between "". An attribute and its value are defined within the opening tag.

8. What is the HTML id attribute? And what is it mostly used for?
    An id attribute specifies a unique id for an HTML element, it's mostly used to point to a style in a stylesheet and by Javascript to manipulate the element with that specific id.

9. What kind of an attribute is the id attribute and what does that mean?
    The id attribute is global which means it can be used by any HTML element.

10. What is the HTML class attribute? And what is it mostly used for?
     The class attribute specifies one or more class names for an element. It is mostly used to point to a class in a stylesheet.

11. What kind of an attribute is the class attribute and what does that mean?
    The class attribute is global which means it can be used by any HTML element.
        
12. How is an HTML element defined? In other words, what does its markup basically consist of? Use your h1 element in your index.html file as an example.
    An HTML element is defined by a start tag, some content, and an end tag. For example my h1 element uses a start tag, content (This is my first html file!), and an end tag.
    <h1>This is my first html file!</h1>
    
13. What does <!DOCTYPE html> mean? What is its purpose and what kind of declaration is it?
    	<!DOCTYPE html> is a document type declaration and it informs web browsers which version of HTML is being used.

14. What is the purpose and meaning of the html element? And which attribute does it usually contain?
	The HTML element represents the root/top-level element of an HTML document. All other elements on the page must be descendants of the HTML element. It usually contains the lang attribute.
    
15. What is the purpose and meaning of the head element?
	The main purpose of the HTML head element is to contain machine-readable information about the document(metadata). The head element primarily holds information for machine processing, not human readability. 

16. What is the general purpose and meaning of the meta element? And when it contains a charset attribute (what is the value of this charset attribute) ?
    The meta element is used to provide structured metadata. Metadata is not displayed on the web page but is machine parsable. The charset attribute is one of the attributes that the meta accepts and it specifies the character encoding for the HTML document.

17. What does UTF-8 stand for?
    UTF-8 stands for “Unicode Transformation Format - 8 bits”
    
18. What is encoding?
	Encoding is the process of converting characters in human languages into binary sequences that computers can process.

19. Why is character encoding important in HTML documents?
	Character encoding lets us use complex english text on a web page that users might not be able to see otherwise. Not using some kind of character encoding could affect how reliably the data on the page is processed by machines and its SEO.
    
20. What is Unicode?
	Unicode is an encoding system that solved the space issue of its predecessor ASCII. Unicode assigns a unique code, called a code point, to each character and is able to produce over a million code points.

21. Why can't Unicode be a standalone when it comes to encoding characters?
	Unicode can not store characters in binary, which computers need in order to the characters in text files.

22. What is UTF-8 and what does it do?
	UTF-8 is the encoding system for Unicode. It translates any Unicode character into a matching unique binary string and vice versa. 
    
23. Why is the UTF-8 encoding system unique?
	UTF-8 represents characters in one-byte units.

24. What are the advantages of UTF-8?
    - UTF-8 is spatially efficient, it converts code point into a set of 1-4 bytes, using less space for common characters and more space for less common ones.
    - UTF-8 is backwards compatible with ASCII and is able to convert a text file formatted by ASCII to human-readable text.

25. What is the purpose and meaning ot the HTML title element?
	The title element defines the title of the document. It should summarize the content/purpose of the document and is important for SEO. The title shows up in the browser’s title bar or a page’s tab. 

26. What is the purpose and meaning of the body element?
	The body element represents the main content of the document; It follows the head element on the web page and typically contains all the content that will be displayed on the screen.
    
27. What does the h1 element represent and what should its contents describe?
	The h1 element is a heading and represents the most important heading on a page; its content should describe the overall purpose of the page content. This improves accessibility, as well as SEO with information in higher heading levels given more weight.

28. What does the p element (usually) represent? What element(s) does it often follow? And how are multiple p elements usually represented?
	The p element represents a paragraph of text and often follow heading elements. Paragraphs are usually represented as blocks of text separated from adjacent blocks by blank lines and/or first-line indentation. 

29. What is the default character set for HTML5?
    UTF-8
    
30. What is the viewport? Why was it created? What element defines it? What attributes are used, and what do its attributes and corresponding values represent? Please also provide an example of the meta viewport tag.
	The viewport is the user's visible area of the web page. It was created when tablets and mobile phones were introduced in order to work dynamically with different screens. It is defined by the meta element. The attribute name=”viewport” is used in the meta element to give browsers instructions on how to control the page’s dimensions and scaling. The attribute content=”width=device-width, initial-scale=1.0” contains two values; width=device-width sets the width of the page to follow the screen width of a device and initial-scale=1.0 sets the initial zoom level when the page is first loaded by the browser. 
    Ex:<meta name="viewport" content="width=device-width, initial-scale=1.0">