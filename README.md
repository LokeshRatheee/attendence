This brach will contains only the html5,  scss and javascript functionality of the pages.


Folder structure :-
<pre>
1.) Page
      -> Page Name (exapmple:- Dashboard)
          -> index.html 
          -> stylesheet 
              -> index.scss 
              -> mobile.scss 
              -> desktop.scss 
              -> tablet.scss 
          -> javascript 
              ->  index.js 
              
2.) Common 
      -> Javscript 
</pre>

Page name will contains the name of the page like dashboard, login etc which represent the name of the page.\
Stylesheet \
  index.scss -> the index page will include the mobile, desktop and talet scss which we will include in the page. \
  mobile.scss -> will contains the scss which belongs to mobile (screen smaller than 768 px) \
  tablet.scss -> will contains the scss which belongs to mobile (screen b/w 768 to 1024 px) \
  desktop.scss -> will contains the scss which belongs to desktop (screen above 1024 px) \
Javascript \
  contains the index file which will include common js  and the other js file in the same folder
            
