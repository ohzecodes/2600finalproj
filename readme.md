enter your connectionString in .env
## how to use
* #### for the first form:  
 *  hotel name should be unique 
 *  name, city, and streetaddress should be 5 or more charecters 
 *  Image:   
    * only 1 image is allowed per hotel   
    * DONE: ImageName: must be alphanumeric charecters only -- I try to sanitize it  
    * Image size must not be bigger than 5MB.  
    * Images must have a unique name.  
    * each hotel has an image-> the user cannot submit the form without image 
    * hotels cannot stay without a picture. 
    * Images may be added on the storage if the hotel is not there meaning eventhough if there is an error on validation still the image will be posted. The user is expected to fix the problem if validation error . 
    * images are handled by multer which is an multiware for multipart form data handling ---> link for this is in the reference section.


* #### form 2 
user has to user the select button-> there is no other option
some of the sanitization happens on the clientside, other happens on the serverside

* ###### sample data 
some sample data has been loaded for you. :)

## References 
#### middleware
*  multer--> filehandling 
*  express-readme --> for the man page https://thegreathotelapp.herokuapp.com/man 


* sample data images  
    * https://unsplash.com/photos/lRowikzz4cw   
    * https://unsplash.com/photos/2gOxKj594nM   
    * https://unsplash.com/photos/M7GddPqJowg   
    * https://unsplash.com/photos/xuK2crQLELk   


* tutorials  
    * https://youtu.be/XeiOnkEI7XI  
    * https://youtu.be/9Qzmri1WaaE  
    * https://www.dyn-web.com/tutorials/forms/radio/get-selected.php



* These elements are used from bootstap:  
    * https://getbootstrap.com/docs/4.0/components/card/  --> for displaying the hotel element  
    * https://getbootstrap.com/docs/4.0/components/modal/ --> for displaying comments  
    * https://getbootstrap.com/docs/4.0/layout/grid/ --> grid system

* using bootstrap with fontawesome for search bar
   * bootstrap : https://getbootstrap.com/  
    * font Awesome: https://fontawesome.com/   
    * logo -- made with https://looka.com !!!   

NOTE: some of the styleset are only implemented in some browswers but rest in funchionality everything works. the styles are there for just styling!!    
https://developer.mozilla.org/en-US/docs/Web/CSS/::-webkit-file-upload-button
    

## Hosting
serving the proj at https://thegreathotelapp.herokuapp.com/ 
This Manual/readme page is also accesible via:  https://thegreathotelapp.herokuapp.com/man  OR 
localhost:8080/man 
