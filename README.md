<!DOCTYPE html>
<!--
To change this license header, choose License Headers in Project Properties.
To change this template file, choose Tools | Templates
and open the template in the editor.
-->
<html>
    <head>
        <meta name="robots" content="noindex,nofollow">
        <meta http-equiv="X-UA-Compatible" content="IE=edge">
        <meta name="viewport" content="width=device-width, initial-scale=1.0, user-scalable=no">
        <meta name="robots" content="noindex,nofollow">
        <link rel="stylesheet" media="all" href="styles.css">
        <meta charset="Windows-1252"> 
    </head>
    <body> 
        <div class="wrap-centered-content">    
        <div class="m-container-text">
        <h1>Accessing My Programming Demos</h1>
        <hr style="border:2px solid #ff0000;"> 
        I list Demo I and Demo II on my resume. The sections that follow provide access to the demos. <br>
       The <b>content of the demo Web pages is not optimized for hi-res devices</b>, such as a device with Retina display.
        <br>
        <h2>Demo I: Bitcoin Price in Real Time&mdash;an Implementation
            of the HTML 5 WebSocket Interface</h2>
            To receive real-time prices using a <i>WebSocket</i>, I programmed Demo I to implement
            the WebSocket API of a bitcoin exchange.
        <br>
        <ul>
           <li><a href="https://cryptoestudiante.github.io/xbt-websocket-with-server/">
            View the Demo</span></a>!
           <ul>
              <li>This demo has a server application (app) that provides a set of exemplary last transaction prices to the JavaScript
                  client at startup. The server app makes a HTTP request to the <a href="https://www.CEX.io/">CEX.IO</a> exchange 
                  for a last transaction price, and then forms a set of exemplary last transaction prices to return to 
                  the client. This design simulates a 24-hour price monitor from the perspective of the client.
                  At startup, the client displays the prices in its Web page chart.<br><br>
                  I programmed the server app in Node.js with express, and axios, a Node package for
                  asynchronous communication. I developed the app on the Ubuntu 16.04 operating system, 
                  a Linux operating system. To see the server app only, go to the
                  <a class="my-link" href="https://radiant-fortress-26008.herokuapp.com/">server app Web site</a>. 
                  On the Web page of the server app, you will see a set of prices. These are the prices the server app would 
                  return to the client. 
                  <br>
              </li>
           </ul>
         </li>
       </ul>
     <h2>Demo II: Bitcoin Price in Real Time&mdash;an Implementation of Web REST APIs</h2>
       I programmed Demo II to implement the Web REST APIs of a bitcoin exchange and a blockchain reader. 
       Demo II gets real-time bitcoin prices using HTTP.  
      <ul>
      <li><a href="http://www.advancedtechnicalwriter.com/http-demo/index.html">
        View the Demo</a>!
         <ul>
           <li>The first eight prices displayed on the Web page chart are <b>hard-coded prices</b> 
             and not real-time prices. 
           </li>
         </ul>  
      </li>
      </ul> 
    <footer>  
        <br>
         <hr style="border:2px solid #ff0000;">  
    </footer>
       <br>
      </div>
     </div>
   </body>
</html>
