

#Responsive design & SASS

I hope you enjoyed the lecture today on Responsive Design, SASS and Flexbox. Today, we provided some context, exploring the origin of responsive design, practices and tools.

##Responsive Design

###1. Principles of Responsive Web Design
* Number of Internet capable devices and screen has increased over the last few years
* Challenge : designing web content that fits a plethora of screen widths and heights (viewports)
* Different way of thinking : Modern web sites/applications adjust layout of content as the screen of the browser changes in width
* Ethan Marcotte, 2010
* Responsive web design components : Fluid Grids, Media queries, Flexible images

####Demos
* No responsive design : http://www.theweddinglens.com/
* Responsive design : https://globeandmail.com
* Responsive design : https://www.aircanada.com
* Responsive design explained : https://alistapart.com/article/responsive-web-design


###2. Fluid Grids for Responsive Design 
* Grid based design commonly used by web designers : flexible & respond to width of screen
* Use of percentages in CSS maintains consistency in column width

####Demos
* Fluid grids explained : https://alistapart.com/article/fluidgrids
* Grids 3 columns : https://alistapart.github.io/code-samples/fluidgrids/examples/grid/final.html
* Grids multiple columns : https://www.w3schools.com/Css/tryresponsive_grid.htm

###3. Media Queries for Responsive Design
* Size-based conditional styling (CSS3) 
* Rules use @media rule syntax to specify default design (desktop) & another when viewport (mobile device) is smaller

####Demos
* Laying out content with media queries : https://www.susanjeanrobertson.com/


###4. Recommendations for Responsive Web Design
1. Align all elements to scalable grid. Also use Flexbox tool.
2. Consider proportions (text and buttons are dynamically adjusted, images should keep aspect ratio)
3. Use Media Queries for applying different styles to application, depending on resolution.
4. Pay attention to navigation (use of icons rather long text). Navigation variants based on possible devices, font types selection
5. Design for smallest screen first.
6. Make Buttons Easily Understandable, Discernable and “Pressable”.

##SASS (Syntactically Awesome Style Sheets)

###What does SASS do for us?
1. Programmatic generation of CSS through a Preprocessor
2. More intuitive & concise structure
3. Less coding, deals with repetitive statements
4. Reusability
5. Consistency
6. Syntax variations
* SASS (.sass) Syntactically Awesome Style Sheets
* SCSS (.scss) Sassy Cascading Style Sheets

###SASS Features
1. Nested Rules
2. Variables
3. Functions
4. Operators & Trigonometry
5. Code Flow and Control Statements (if statements)
6. Mixins

Note : For child combinators, the symbols are used before the class or element name :

````
foo {
  > bar {
    > baz {
      color: red;
    }
  }
}
````

##Flexbox
* Flexbox Layout module
* Ability to alter items' width/height (and order) to best fill (more efficient layout, alignment, distribution ) the available space in a container
* More efficient for small-scale layouts, while the Grid layout is intended for larger scale layouts

###Flexbox Properties

Flex Container
* display : flex
* flex-direction : row | column
* flex-wrap : wrap | nowrap
* justify-content : flex-start | center
* align-items : flex-start | center
* align-content : flex-start | center

Flex Item
* order : <integer>
* flex-grow : <integer>
* flex-shrink : <integer>
* flex : (grow & shrink together)
* align-self : flex-start | center 







