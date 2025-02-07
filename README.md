This app is to test TabView from react-native-tab-view

Currently when it is packaged and running locally I observe error

entry-1e75fd92c0d6d90477e5d34abc4a7735.js:145 Uncaught Error: Minified React error #418; visit https://reactjs.org/docs/error-decoder.html?invariant=418 for the full message or use the non-minified dev environment for full errors and additional helpful warnings.
    at Sa (entry-1e75fd92c0d6d90477e5d34abc4a7735.js:145:48937)
    at Ai (entry-1e75fd92c0d6d90477e5d34abc4a7735.js:145:121170)
    at Is (entry-1e75fd92c0d6d90477e5d34abc4a7735.js:145:111162)
    at Ds (entry-1e75fd92c0d6d90477e5d34abc4a7735.js:145:111090)
    at Rs (entry-1e75fd92c0d6d90477e5d34abc4a7735.js:145:110953)
    at ws (entry-1e75fd92c0d6d90477e5d34abc4a7735.js:145:106111)
    at k (entry-1e75fd92c0d6d90477e5d34abc4a7735.js:157:1376)
    at MessagePort.M (entry-1e75fd92c0d6d90477e5d34abc4a7735.js:157:1911)
Sa @ entry-1e75fd92c0d6d90477e5d34abc4a7735.js:145
Ai @ entry-1e75fd92c0d6d90477e5d34abc4a7735.js:145
Is @ entry-1e75fd92c0d6d90477e5d34abc4a7735.js:145
Ds @ entry-1e75fd92c0d6d90477e5d34abc4a7735.js:145
Rs @ entry-1e75fd92c0d6d90477e5d34abc4a7735.js:145
ws @ entry-1e75fd92c0d6d90477e5d34abc4a7735.js:145
k @ entry-1e75fd92c0d6d90477e5d34abc4a7735.js:157
M @ entry-1e75fd92c0d6d90477e5d34abc4a7735.js:157Understand this errorAI
entry-1e75fd92c0d6d90477e5d34abc4a7735.js:145 Uncaught Error: Minified React error #422; visit https://reactjs.org/docs/error-decoder.html?invariant=422 for the full message or use the non-minified dev environment for full errors and additional helpful warnings.
    at ei (entry-1e75fd92c0d6d90477e5d34abc4a7735.js:145:80255)
    at Go (entry-1e75fd92c0d6d90477e5d34abc4a7735.js:145:79194)
    at Ai (entry-1e75fd92c0d6d90477e5d34abc4a7735.js:145:121373)
    at Is (entry-1e75fd92c0d6d90477e5d34abc4a7735.js:145:111162)
    at Ds (entry-1e75fd92c0d6d90477e5d34abc4a7735.js:145:111090)
    at Rs (entry-1e75fd92c0d6d90477e5d34abc4a7735.js:145:110953)
    at ws (entry-1e75fd92c0d6d90477e5d34abc4a7735.js:145:106111)
    at k (entry-1e75fd92c0d6d90477e5d34abc4a7735.js:157:1376)
    at MessagePort.M (entry-1e75fd92c0d6d90477e5d34abc4a7735.js:157:1911)




 ##   Steps to Reproduce

 1.  
   ```bash 
   npm install 
   ```

 2.  
   ```bash 
   npx expo export --platform web
   ```

 3.  
   ```bash 
   npx serve dist
   ```


The error could be seen in the JS console in Chrome/Safari

