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
    
    text-align: justify;            // each line has equal width.
    
    <u> </u>                        // text-decoration: underline
    
    <em>                            //italic text
        
    <s>                             //text-decoration: line-through;
        
   box-shadow: 0 10px 20px rgba(0,0,0,0.19), 0 6px 6px rgba(0,0,0,0.23);                    //box shadow
        
  opacity:  0.7;                    //opacity 0...1
        
   a:hover {                        //hover
  color: blue;
}
        
  p {
  position: relative;                   //should move it relative to its current position in the normal flow of the page
  bottom/left/right/top: 10px;
}
        
 position:absolute;                     //locks the element in place relative to its parent container.
        
 position : fixed;                      //won't move when the user scrolls.
        
float :left/right;                      //left or right of their containing parent element
        
z-index:2;                              //When elements are positioned to overlap (i.e. using position: absolute | relative | fixed | sticky), the element coming later in the HTML markup will, by default, appear on the top of the other elements. However, the z-index property can specify the order of how elements are stacked on top of one another
        
margin:auto;                            //center a block element horizontally
        
background: linear-gradient(95deg,#CCFFFF, #FFCCCC);        //gradient
        
background: repeating-linear-gradient(90deg, yellow 0px, blue 30px, green 50px, red 80px )              //linear-gradient
        
background:url(https://cdn-media-1.freecodecamp.org/imgr/MJAkxbh.png) ;                     //background png
        
div:hover {  transform: scale(2) }                                        //Change the Size of an Element
        
background-color: transparent;                          //прозрачный
        
.heart::before {
  content: "";                                          //pseudo-elements
  background-color: yellow;}
        
 #rect {                                                        
animation-name : rainbow;
animation-duration: 10s;
  }
@keyframes rainbow{
  0%{
    background-color: blue;                                 //ANIMATION
  }50%{
    background-color: green;
  }
  100%{
    background-color: yellow;
  }
}
    






        
  

    



  



    
