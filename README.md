# CSS Media Query Cheat Sheet
Use the CSS code below to make your website responsive in other device

## Installation

```
git clone https://github.com/NyomanAdiwinanda/CSS-Media-Query-Cheat-Sheet.git
```

```
Open the CSS file on your text-editor / code-editor
(VScode, Atom, Sublime, other)
```
## Or just copy paste the code below to your own project file

``` css
/* 
  ##Device = Desktops
  ##Screen = 1281px to higher resolution desktops
*/

@media only screen and (min-width: 1281px) {
  
    /* Insert CSS */
    
  }
  
  /* 
    ##Device = Laptops, Desktops
    ##Screen = B/w 1025px to 1280px
  */
  
  @media (min-width: 1025px) and (max-width: 1280px) {
    
    /* Insert CSS */
    
  }
  
  /* 
    ##Device = Tablets, Ipads (portrait)
    ##Screen = B/w 768px to 1024px
  */
  
  @media (min-width: 768px) and (max-width: 1024px) {
    
    /* Insert CSS */
    
  }
  
  /* 
    ##Device = Tablets, Ipads (landscape)
    ##Screen = B/w 768px to 1024px
  */
  
  @media (min-width: 768px) and (max-width: 1024px) and (orientation: landscape) {
    
    /* Insert CSS */
    
  }
  
  /* 
    ##Device = Low Resolution Tablets, Mobiles (Landscape)
    ##Screen = B/w 481px to 767px
  */
  
  @media (min-width: 481px) and (max-width: 767px) {
    
    /* Insert CSS */
    
  }
  
  /* 
    ##Device = Most of the Smartphones Mobiles (Portrait)
    ##Screen = B/w 320px to 479px
  */
  
  @media (min-width: 320px) and (max-width: 480px) {
    
    /* Insert CSS */
    
  }
  ```