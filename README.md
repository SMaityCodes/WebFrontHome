## 📦 The Organization of this repository:-

```
project-root/
├── docs/                  # Contains the fronend hosting files
│   ├── index.html
│   ├── script.js
│   └── style.css

├── render-backend/        # Contains the backend hosting files
│   ├── package.json
│   ├── package-lock.json
│   └── server.js
├── readme.md              # This file

```
## Programmer's Guidelines:-
This repository has been created to learn how to fist 1) Develop and test a full-stack website on local machine and then host it on web.

## How to test it on local machine:-
- download the repo.
- open the index.html in a browser
- go to the "render-backend" folder and run the following commands:-
  
   `npm init -y`
  
    `npm install express cors body-parser`
  
    `node server.js`
  
- now it is deployed at your local machine - test it on the browser you opened in the above step.
- if you want to access your webiste from another machine on the same network (intranet):-
- host the fronend on your machine using some web-hosting application (you may use "LiveServer" using which you can deploy easily from Visual Studio)
- open the 'script.js' and change the API-URL with your machine's IP adress (or loopback address) in this line:-
- `fetch("http://172.26.23.122:10000/calculate", {` \\ use your IP here

## Deployment Guidelines:-

Same as main branch
