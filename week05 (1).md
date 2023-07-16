# Week 05
# Internet Applications

# Task 1. Create Web Pages in OpenWRT

Answer: Opening the index.html file in the openWRT and renamed it to my student id which is 12214838.html

![image](https://github.com/cquict/coit20246y23t1-journal-Pabitrathapa12214838/assets/127846893/34e6b1ed-4e97-4c77-8e5e-4e9ddb0943f1)


          Fig.5.1.I) Web page of OPenWRT


![image](https://github.com/cquict/coit20246y23t1-journal-Pabitrathapa12214838/assets/127846893/07457dd0-f05e-452b-97f8-ea0e5c69cb1f)

             Fig.5.1.II) changing index.html to 12214838.html file



![image](https://github.com/cquict/coit20246y23t1-journal-Pabitrathapa12214838/assets/127846893/93efc737-e237-431d-ba80-8b97575a41da)

              Fig.5.1.III) 12214838.html file
              
![image](https://github.com/cquict/coit20246y23t1-journal-Pabitrathapa12214838/assets/127846893/f98d1b1a-8914-42ef-8ef2-89a30c6530f1)

            Fig.5.1.III) 12214838.html  Web page 

              
In the above screen shot you can see that index.html file have been edited to the student id file in the OenWRT with the nano editor.

# Task 2. Capture HTTP Packets

![image](https://github.com/cquict/coit20246y23t1-journal-Pabitrathapa12214838/assets/127846893/abad294f-f228-4c2c-b3e4-d073f86fe9cc)

![image](https://github.com/cquict/coit20246y23t1-journal-Pabitrathapa12214838/assets/127846893/eedb16f0-6265-42be-948d-99f3caec307f)


             Fig.5.2.I) Captured  HTTP packets
             
  Note: Refer to the attched file for pcp packets
  
  a)  &  b) & c) & d)
  
  
  ![image](https://github.com/cquict/coit20246y23t1-journal-Pabitrathapa12214838/assets/127846893/a4104eb4-35ea-4448-878c-883b6cd68719)
  
  
  ![image](https://github.com/cquict/coit20246y23t1-journal-Pabitrathapa12214838/assets/127846893/a41367bc-fcc9-4ee5-a3e3-65ec8a230ae7)
  
  ![image](https://github.com/cquict/coit20246y23t1-journal-Pabitrathapa12214838/assets/127846893/eee43f1a-c524-4016-8eb7-8fc6a25bd5ef)
  
  
  
  


# Task 3. Analyse HTTP Packet Capture

a) 
 when we access to the  link the browser send the HTTP request for 12214839.html page. The server is able to response so the page is visible.
 
 b)For the first HTTP request/response the five address is given below:
 
 Source IP address: 192.168.56.1
 Destination IP address: 192.168.56.2
 Source Port Number: 59297
 Destination Port Number: 80
 Protocol: Transmission Control Protocol
 
 
 ![image](https://github.com/cquict/coit20246y23t1-journal-Pabitrathapa12214838/assets/127846893/35729795-7182-4a8b-a634-7526ef8d2b27)
 
                               Fig.5.3)  HTTP packets with http filter
 
  
 c) Yes while clicking the button it send request to the server in our case because this feature is created with event listner.If this functionality is implemented using scripting language, the user's browser will process the request locally. without requiring interaction with the web server
 
 
 d) The Packet diagram for 12214838.html is given below:
 
 ![image](https://github.com/cquict/coit20246y23t1-journal-Pabitrathapa12214838/assets/127846893/7087bf18-4b38-483d-853a-a29b3ce255ef)
 
    Fig.5.3.d) Packet Diagram
 
 e)  The value of the referrer in the HTTP request was "http://192.168.56.2/". It identify the URL of the page that the user was on before they clicked on the link to the current page. 
The referrer header is used by web servers for a variety of purposes, including:

1)monitoring how users arrive onto their pages
2) optimising for search engines (SEO)
3) monitoring how visitors use their website
4) monitoring the success of marketing initiatives

 
 f) The server did not learn any information about the web browser from the HTTP request http://192.168.56.2/. This is because the User-Agent header was not present in the request. The User-Agent header is a standard header field in HTTP requests that identifies the web browser and operating system that is being used to make the request. If the User-Agent header is not present, the server will not be able to learn anything about the web browser.
 
 
 
 g) The version of HTTP used is HTTP/2.0. The transport protocol used is TCP.
 
 
 H) All together we captured 32 packets for this web page 192.168.56.2. It take 25s between the start of connection setup and
the data transfer.
 
 
 I)In order to confirm that a packet was received properly, an acknowledgement is often issued in an HTTP request after receiving a packet. The sender of the acknowledgement packet anticipates receiving an acknowledgement packet for its acknowledgement packet since the acknowledgement packet specifies the sequence number of the packet that was received.
 


# Task 4. View Your Cookies

I used the developer tools in my web browser to view the cookies when I visited a particular website that I regularly visit. The website is Linkedin.

A cookie is a small text file that a website saves on your computer or mobile device when you visit the site. It enables the website to remember your actions and preferences (such as login, language, font size and other display preferences) over a period of time, so you don’t have to keep re-entering them whenever you come back to the site or browse from one page to another.

The cookies store the following information about:
My IP address, My browser's user agent, The date and time of my last visit to the website, the pages that I have visited on the website and my preferences for the website, such as my preferred language and font size


![image](https://github.com/cquict/coit20246y23t1-journal-Pabitrathapa12214838/assets/127846893/6a6501bc-2293-457e-a51c-1e985ca7749d)

                               Fig.5.4)  Cookies







   



  
  












