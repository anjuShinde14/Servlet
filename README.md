
 	¬Servlet-
- servlet is a server side technology.
- It is used to make a java enterprise application.
- It is part of java web application .
- It is use to handle client side request process the request and generate the dynamic response.
        - In servlet life cycle their are three methods are present.
- A servlet is a java object that response to http request .
It runes inside the web container.
* InIt()=
        -The Web container calls the init method before interface the servlet can service any client request.
       -it get only once invoked.    
      -We Initialize a servlet by calling a Init method.
       *Service()= 
       -it its invoked many  more times.
        - the servlet call the service method to process the client   request.
       - it get calls when new request your that servlet comes in.
       - It determain which HTTP request should be called.
      * Destroy()
       -it get invoked  only once. – we terminate the servlet by calling the Destroy method


 	SERVLET COLLABRATION-
-	Call from one servlet to another servlet is called servlet collaboration.
-	We can add another HTML file.
-	To perform a servlet collaboration we need a object og request dispatcher.
-	Request dispatcher object we can obtained from HTTP Servlet Request.

 	Request Dispacher=
-	It is a interface .
-	It has a two method-1]Forword(Request , Response)
                                     2] include(Request, Response)

 	Limitations of Request dispatcher-
-	When we forword the request it does not get destroyed, while submitting a some sensitive information. It createat a problem of data redundancy. So we must avoid the use of request dispatcher.
-	To overcome this problem send redirect method is comes in picture.
-	This method is directoly called using an object of HttpServlet.










