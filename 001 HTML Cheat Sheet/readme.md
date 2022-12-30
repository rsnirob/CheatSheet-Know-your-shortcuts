### The <!DOCTYPE> Declaration
            <!DOCTYPE html>
            
### HTML Headings
            <h1>Page title</h1>
            <h2>Subheading</h2>
            <h3>Tertiary heading</h3>
            <h4>Quaternary heading</h4>
            <h5>Heading 5</h5>
            <h6>Heading 6</h6>
###### Bigger Headings
            <h1 style="font-size:60px;">Heading 1</h1>
### HTML Paragraphs
            <p style="text-align: center;">text</p>
### HTML Horizontal Rules
            <hr>
### HTML Line Breaks
            <br>
### The HTML `<pre>` Element
            <pre>Content goes here...</pre>
### The HTML Style Attribute
            <tagname style="property:value;">
###### Background Color
            <body style="background-color:powderblue;">
###### Text Color 
            <h1 style="color:blue;">This is a heading</h1>
###### Fonts
            <h1 style="font-family:verdana;">This is a heading</h1>
###### Text Size
            <h1 style="font-size:300%;">This is a heading</h1>
###### Text Alignment
            <h1 style="text-align:center;">Centered Heading</h1>
### HTML Formatting Elements
            <b> - Bold text
            <strong> - Important text
            <i> - Italic text
            <em> - Emphasized text
            <mark> - Marked text
            <small> - Smaller text
            <del> - Deleted text
            <ins> - Inserted text
            <sub> - Subscript text
            <sup> - Superscript text
### HTML `<blockquote>` for Quotations
            <p>Here is a quote from WWF's website:</p>
            <blockquote cite="http://www.worldwildlife.org/who/index.html">
                    For 60 years, WWF has worked to help people and nature thrive. As the world's leading conservation organization, WWF works in nearly 100
                    countries. At every level, we collaborate with people around the world to develop and deliver innovative solutions that protect communities,
                    wildlife, and the places in which they live.
            </blockquote>
### HTML `<q>` for Short Quotations
            <p>Browsers usually insert quotation marks around the q element.</p>
            
            <p>WWF's goal is to: <q>Build a future where people live in harmony with nature.</q></p>
### HTML `<abbr>` for Abbreviations
            <p>The <abbr title="World Health Organization">WHO</abbr> was founded in 1948.</p>
### HTML `<address>` for Contact Information
            <address>
                    Written by John Doe.<br>
                    Visit us at:<br>
                    Example.com<br>
                    Box 564, Disneyland<br>
                    USA
            </address>
### HTML `<cite>` for Work Title
            p><cite>The Scream</cite> by Edvard Munch. Painted in 1893.</p>
### HTML `<bdo>` for Bi-Directional Override
            <bdo dir="rtl">This text will be written from right to left</bdo>
### HTML Comments
            <!-- Write your comments here -->
            
            <!--
            <p>Look at this cool image:</p>
            <img border="0" src="pic_trulli.jpg" alt="Trulli">
            -->
### Inline CSS
            <h1 style="color:blue;">A Blue Heading</h1>
###### CSS Border
            border: 2px solid black;
###### CSS Padding
            padding: 30px;            
###### CSS Margin
            margin: 50px;            
###### Link to External CSS
            <link rel="stylesheet" href="https://www.w3schools.com/html/styles.css">
            <link rel="stylesheet" href="/html/styles.css">
            <link rel="stylesheet" href="styles.css">
### HTML Links
            <a href="https://www.w3schools.com/" target="_blank">Visit W3Schools!</a> 
            <p><a href="https://htmlg.com/" target="_blank" rel="nofollow">Click here</a></p>
            <p><a href="mailto:me@ruwix.com?Subject=Hi%20mate" target="_top">Send Mail</a></p>
                 
###### HTML Links - The target Attribute
            _self - Default. Opens the document in the same window/tab as it was clicked
            _blank - Opens the document in a new window or tab
            _parent - Opens the document in the parent frame
            _top - Opens the document in the full body of the window
###### HTML Links - Use an Image as a Link
            <a href="default.asp">
                    <img src="smiley.gif" alt="HTML tutorial" style="width:42px;height:42px;">
            </a>
###### Link to an Email Address 
            <a href="mailto:someone@example.com">Send email</a>
###### Button as a Link
            <button onclick="document.location='default.asp'">HTML Tutorial</button>
###### Link Titles  
            <a href="https://www.w3schools.com/html/" title="Go to W3Schools HTML section">Visit our HTML Tutorial</a>
### HTML Link Colors
            By default, links will appear as follows in all browsers:
                    An unvisited link is underlined and blue
                    A visited link is underlined and purple
                    An active link is underlined and red

Example
Here, an unvisited link will be green with no underline. A visited link will be pink with no underline. An active link will be yellow and underlined. In addition, when mousing over a link (a:hover) it will become red and underlined:
        
            <style>
                    a:link {
                        color: green;
                        background-color: transparent;
                        text-decoration: none;
                    }

                    a:visited {
                         color: pink;
                         background-color: transparent;
                         text-decoration: none;
                    }

                    a:hover {
                        color: red;
                        background-color: transparent;
                        text-decoration: underline;
                    }

                    a:active {
                        color: yellow;
                        background-color: transparent;
                        text-decoration: underline;
                    }
            </style>

### HTML Links - Create Bookmarks
            <a href="#C4">Jump to Chapter 4</a>
            <h2 id="C4">Chapter 4</h2>
### HTML Images
            <img src="img_girl.jpg" alt="Girl in a jacket" style="width:500px;height:600px;">
            <img src="img_girl.jpg" alt="Girl in a jacket" width="500" height="600"> 
###### Image Size - Width and Height
            <img src="img_girl.jpg" alt="Girl in a jacket" style="width:500px;height:600px;">
            <img src="img_girl.jpg" alt="Girl in a jacket" width="500" height="600">
###### Images on Another Server/Website
            <img src="https://www.w3schools.com/images/w3schools_green.jpg" alt="W3Schools.com">
###### Animated Images 
            <img src="programming.gif" alt="Computer Man" style="width:48px;height:48px;">
###### Image as a Link
            <a href="default.asp">
                    <img src="smiley.gif" alt="HTML tutorial" style="width:42px;height:42px;">
            </a>
###### Image Floating
            <p><img src="smiley.gif" alt="Smiley face" style="float:right;width:42px;height:42px;">The image will float to the right of the text.</p>
            <p><img src="smiley.gif" alt="Smiley face" style="float:left;width:42px;height:42px;">The image will float to the left of the text.</p> 
        
###### HTML Image Maps
            <img src="workplace.jpg" alt="Workplace" usemap="#workmap" width="400" height="379">
            
            <map name="workmap">
                    <area shape="rect" coords="34,44,270,350" alt="Computer" href="computer.htm">
            </map>

            rect - defines a rectangular region
            circle - defines a circular region
            poly - defines a polygonal region
            default - defines the entire regio
###### Background Image on a HTML element
            <p style="background-image: url('img_girl.jpg');">        
###### Background Image on a Page
            body {
                    background-image: url('img_girl.jpg');
                    background-repeat: no-repeat;
            } 
###### Background Cover
            body {
                    background-image: url('img_girl.jpg');
                    background-repeat: no-repeat;
                    background-attachment: fixed;
                    background-size: cover;
            }
###### Background Stretch
            background-size: 100% 100%;
### HTML Tables
###### Collapsed Table Borders
            table, th, td {
                    border: 1px solid black;
                    border-collapse: collapse;
            }
###### Style Table Borders
            table, th, td {
                      border: 1px solid white;
                      border-collapse: collapse;
            }
            th, td {
                      background-color: #96D4D4;
            }

###### Round Table Borders
            table, th, td {
                      border: 1px solid black;
                      border-radius: 10px;
            }
            The following values are allowed:
                      dotted
                      dashed
                      solid
                      double     
                      groove
                      ridge
                      inset
                      outset
                      none
                      hidden  
###### Dotted Table Borders
            th, td {
                        border-style: dotted;
            }
###### Border Color
            th, td {
                        border-color: #96D4D4;
            }
