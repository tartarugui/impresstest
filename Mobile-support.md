Impress.js' mobile support is disabled by default. However on most recents mobile platforms it works perfectly well.  
  
You can enable mobile support (at your own risks) by deleting the following lines in the impress.js source code
file :  
 
    &&  
    // but some mobile devices need to be blacklisted,  
    // because their CSS 3D support or hardware is not  
    // good enough to run impress.js properly, sorry...  
    ( ua.search(/(iphone)|(ipod)|(android)/) === -1 );