# Friender (frontend)
Social platform for finding new friends within a customized radius.

**Takes ~10 secs upon login to load authorized features**  
Deployed on: https://friender-ams.surge.sh/  
**Username: guest  
Password: password**  


To access backend codebase: https://github.com/amaesanchez/Friender-backend

## Features
- Use of AWS S3 Bucket for image storage
- Swiping feature in React, using an algorithm leveraging user zipcode and location preference to find the next potential match. 

## Local Setup
    
1. Install dependencies and start app.

    ```
    npm install
    npm start
    ```
    
Go to [http://localhost:3000](http://localhost:3000) to view on browser.

Fork backend codebase and follow instructions for setting up. 

## React design
![image](/public/react-design.png)

## TODO

- [ ] Implement instant messaging with matches
- [ ] Add OAuth login feature
- [ ] Add tests
