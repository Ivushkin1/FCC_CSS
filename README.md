# FCC_CSS
.thick-green-border {
    border-color: green !important;   //Override All Other Styles
    border-width: 10px;
    border-style: solid;
    border-radius:50%;              //round
}

[type='radio'] {                    //attribute selector
  margin: 20px 0px 20px 0px;
}

<h1 style="color: green;">           //inline styles

#FF0000                             //hex
    
rgb(255, 255,255)                   //rgb
    
--penguin-skin: gray;               //create a CSS variable
    
background: var(--penguin-skin, black);   //black if your variable wasn't set
    
 :root {
--penguin-belly: pink               // var(--penguin-belly) will be available globally    
  }
    



  



    
