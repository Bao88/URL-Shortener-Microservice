   <h1>URL Shortener Microservice</h1>
         <h3>Objective: Build a full stack JavaScript app that is functionally similar to this: 
           <a href="https://little-url.herokuapp.com/">https://little-url.herokuapp.com/</a> and deploy it to Glitch.
         </h3>
         <h3>User Stories:</h3>
         <ul>
           <li>1) I can pass a URL as a parameter and I will receive a shortened URL in the JSON response.</li>  
           <li>2) If I pass an invalid URL that doesn't follow the valid http://www.example.com format, 
             the JSON response will contain an error instead.
            </li>  
           <li>3) When I visit that shortened URL, it will redirect me to my original link.</li>  
         </ul>
         <h3>Usage - Creation of shortened URLs</h3>
         <ul>
           <li>https://bao88-url-shortener-microservice.glitch.me/new/https://www.google.com</li>  
           <li>https://bao88-url-shortener-microservice.glitch.me/new/http://kotaku.com</li>  
         </ul>
         <h3>Output of shortened URLs</h3>
         <ul>
           <li>{ "original_url":"http://kotaku.com", "short_url":"https://bao88-url-shortener-microservice.glitch.me/{numbers}" }</li>  
         </ul>
         <h3>Usage - use of shortened URLs</h3>
         <ul>
           <li>input - https://bao88-url-shortener-microservice.glitch.me/0</li>  
           <li>output - https://www.google.com</li>  
         </ul>
      </div>
      <h1>The app can be found <a href="https://bao88-url-shortener-microservice.glitch.me/" target="_blank">here</a> </h1>
   </body>
