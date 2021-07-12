# Code 201 Reading Notes
Notes I have taken from reading.

## Introduction
**Book Structure**
1. HTML-Creating web pages
2. CCS-Presentation and Layout
3. Practical-HTML5 and Search engine optimization (SEO)

**How We Access The Web**
- Browsers-Software used to access web (FireFox, Safari, Chrome ect.)
- Web Servers-Website stored sent to those requesting by a Web hosting company
- Devices-Computers, phones, tablets, laptops
- Screan Readers-Programs that read out the contents of a screen to a user.

**Website Creation**
- What you see- Web browser interprets HTML & CSS to create the page you see.
- How it is Created- HTML, CSS Languages
- HTML5 & CSS3- Latest Versions of HTML and CSS (Still being developed)

**How the Web Works**
1. You connect to the web through Internet Service Provider (ISP)
   - Type a domain name or web address into you browser
2. Your computer contacts a network of servers called Domain Name Systems (DNS)
   - This tells you computer the IP address associcated with the requested Domain name
3. The DNS returns a unique IP address that allows your computer to contact the web server. 
   - The web server is a computer that is constanly conntected to the web to send web pages to users.
4. The web server sends the page you requested to your web browser.
   - Ta-Da... You see the website!!

## HTML Chapter 1: "Structure"
_HTML= HyperText Markup Language_ 
 
**How pages use structure**
  - Heps readers understand the stories 

**Structuring Word Documents** 
  - Headings and Sub Headings reflect heirarchy of information.

**HTML Describes the Structure of Pages** 
  - HTML uses code to add structure to the words that appear on the page
    - Tags
      - <> = Opening tag
      - </> = Closing tag
      - The information between the tags tells the browser something about the information
    - Attributes
      - Sit inside tags to give additional information about the 
      - Have a (name="value") inside a opening Tag (<>)
    - Body, Head, Title
      - < body> = Anything within the body tag will be displayed on the web browser
      - < head> = This will be before the body containing information about the body
      - < title> = Contents will appear at the top of the browser window

**How did they do that?**
  -The best ways to find new tricks and tips is to check out a websites source code (f12) or (right click: View page source)
  
## HTML Chapter 8: "Extra Markup"

**HTML Evolution**
  - Each new version was designed to improve the last.
    - HTML4:Released in 1997 -The Elements in this book are all availible for HTML4
    - XHTML 1.0: Released in 2000 - Strict rules (All used in this book) Works seamlessly with other programs
    - HTML5: Not released - Authors do not need to close all tags, and new atributes and elements are to be added.

**Extra Markup** 
  - Doctypes: All pages should start with a doctype to tell the browser what version of html it is using.
  - Comments in HTML: (< !-- -->) Allows you to add a comment without showing on your webpage, can be viewed on source code
    - Always a good idea to comment on your code
  - Id Attribute: (< p id="example">)Used to uniquely identify one element. Known as the "Global attribute" because it can be used on any element.
  - Class Attribute: Used to uniquely identify several element
  - Block Elements: Appear to start a new line in a browser ex: List < li> Heading < h1> or a paragraph < p>
  - Inline Elements: These will continue on the same line ex: **bold** < b>, _ _Italic_ _ < em>, or and image < img>
  - Grouping in a Block: < div> Holds elements together or makes it easier to follow code.
  - Grouping inline: < span> allows you to control these seperate elements in CSS and have specific value
  - iFrame(inline frame): Enter a window into another page. Ex- a map. You can control the page it came from < src>, height and width.
  - Info about your Page: &lt; meta &gt; Lives inside < head>. It is not visible to users but tells engines about your page.
  - Escape Characters: use elements as examples of the code you are writing. 














