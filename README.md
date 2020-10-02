# CSS Media Query Cheat Sheet
Use the media query code below inside your CSS file for responsiveness of your website in other devices

## Download CSS file

```
git clone https://github.com/NyomanAdiwinanda/CSS-Media-Query-Cheat-Sheet.git
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
  
  @media only screen and (min-width: 1025px) and (max-width: 1280px) {
    
    /* Insert CSS */
    
  }
  
  /* 
    ##Device = Tablets, Ipads (portrait)
    ##Screen = B/w 768px to 1024px
  */
  
  @media only screen and (min-width: 768px) and (max-width: 1024px) {
    
    /* Insert CSS */
    
  }
  
  /* 
    ##Device = Tablets, Ipads (landscape)
    ##Screen = B/w 768px to 1024px
  */
  
  @media only screen and (min-width: 768px) and (max-width: 1024px) and (orientation: landscape) {
    
    /* Insert CSS */
    
  }
  
  /* 
    ##Device = Low Resolution Tablets, Mobiles (Landscape)
    ##Screen = B/w 481px to 767px
  */
  
  @media only screen and (min-width: 481px) and (max-width: 767px) {
    
    /* Insert CSS */
    
  }
  
  /* 
    ##Device = Most of the Smartphones Mobiles (Portrait)
    ##Screen = B/w 320px to 479px
  */
  
  @media only screen and (min-width: 320px) and (max-width: 480px) {
    
    /* Insert CSS */
    
  }
  ```