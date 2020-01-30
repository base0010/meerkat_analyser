# Meerkat Analyser Frontend
 **What is it?**

 -  On page load displays rotating 3d Meerkat totals to the number of accounts created across all blocks/chunks
- "render studio" generates the amount of NEAR Studio IDE accounts created across all blocks/chunks that are saved on the backend
- NOTE: to get detailed information about whats going on you need to open the JS Console (I couldn't get Three.js to display text ¯\_(ツ)_/¯ .... refresh page to get the correct new number of accounts

**BUGS/TODOS**
- Refactor Websockets
- Sometimes the camera gets confused and meerkats disapper (zooming out fixes this) 
-
- Websockets emit events for all clients ex. 'accountsInBlock' event emits the result to all clients instead of just the requesting client MOVE this Logic to ServerManager
