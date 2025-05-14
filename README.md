<html>
  <head>
    <style>
      div {
        right: 30px;
        border: 3px solid ##ff0000;
      }
      div.absolute {
        position: absolute;
        left: 50px;
        border: 3px solid red;
      }
      div.relative {
        position: relative;
        left: 100px;
        border: 3px solid #ff0000;
      }
      div.fixed {
        position: fixed;
        top: 0;
        right: 20px;
        border: 3px solid #ff0000;
      }
      div.sticky {
        position: sticky;
        top: 1px;
        left: 20px;
        width: 100px
        border: 3px solid #ff0000;
      }
    </style>
    <style>
      div {
        background-color: #98FB98;
        padding: 10px;
      }
      div.first {
        opacity: 0.1;
      }
      div.second {
        opacity: 0.3;
      }
      div.third {
        opacity: 0.6;
      }
    </style>
  </head>
  <body>
    <h1> The Opacity Property </h1>
    <p> This Is How The Property Looks </p>
    <div class="first"><p opacity 0.1></p></div>
    <div class="second"><p opacity 0.3></p></div>
    <div class="third"><p opacity 0.6></p></div>
    <div><p>opacity 1 (default) </p></div>
  </body>
</html>
<html>
  <head>
    <style>
      div {
        right: 30px;
        border: 3px solid ##ff0000;
      }
      div.absolute {
        position: absolute;
        left: 50px;
        border: 3px solid ##ff0000;
      }
      div.relative {
        position: relative;
        left: 100px;
        border: 3px solid ##ff0000;
      }
      div.fixed {
        position: fixed;
        top: 9;
        right: 20px;
        border: 3px solid ##ff0000;
      }
      div.sticky {
        position: sticky;
        top: 100px;
        left: 20px;
        width: 100px
        border: 3px solid ##ff0000;
      }
    </style>
  </head>
  <body>
    <h2> Postioning</h2>
    <div>
      Div No Postion Property
    </div>
    <div class="sticky">
      Div With Sticky Class
    </div>
    <div class="relative">
      Div With Relative Class
    </div>
    <div class="absolute">
      Div With Absolute Class
    </div>
    </div>
    <div class="fixed">
      Div With Fixed Class
    </div>
  </body>
</html>
