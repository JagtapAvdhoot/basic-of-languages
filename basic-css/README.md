# **EVERYTHING ABOUT CSS/LESS/SCSS/SASS**

Cascading Style Sheets or css can style html element<br>

> You should have good understanding of html elements

To style html document head tag write

    <style>
      div { 
        background:red; 
      } 
    </style>

## *OR*

Link a Cascading Style Sheets to html document head tag write

    <link ref='stylesheet' href='to your css file.css' />
    

# **CSS**
In this you have one selector then it's property and value

- ## **SELECTOR**
  A selector selects the HTML element you wish to style.

  - ### **Selecting element with Class**
    To select this element

        <div class='header'></div>

    use

        .header{}
    
    to style element with header class
  - ### **Selecting element with Id**
    To select this element

        <div id='header'></div>

    use

        #header{}
    
    to style element with header id
  - ### **Selecting element with Pseudo classes**
    These are the special classes to elements in hover state while active or valid or invalid etc..
  - ### **Selecting element with Element**
    To select this element

        <div></div>

    use

        div{}
    
    to style element
  - ### **Selecting element with Attributes**
    To select this element

        <div data-header ></div>

    use

        div[data-header]{}
    
    to style element with header class
    
- ## **COLORS**
  you can change color of backgrounds and text color like

      .text-red {
        color:red;
      }
      .background-red {
        background-color:red;
      }

  Css have in build css colors like gray,blue,red,green and many more

- ## **COLORS**


# **LESS**
  I don't use it

# **SASS**
  - ## **SYNTAX**
        body
          font-size:16px
          color:#1a2a1d

    no semi colons and brackets

# **SCSS**
  - ## **SYNTAX**
        body {
          font-size:16px;
          color:#1a2a1d;
        }

    no semi colons and brackets