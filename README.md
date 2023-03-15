# Getting Started with Friender)

Deployed on: https://friender-ams.surge.sh/  
Username: guest  
Password: password  

To access Friender backend codebase: https://github.com/amaesanchez/Friender-backend

## Features
- Use of AWS S3 Bucket for image storage
- Swiping feature in React, using an algorithm leveraging user zipcode and location preference to find the next potential match. 

## Environment Setup Frontend

```
git clone [repo url]
npm install
npm start
```
Go to [http://localhost:3000](http://localhost:3000) to view on browser.

Fork backend codebase and follow instructions for setting up. 

Note: You will need to create an AWS account to populate the following fields in the .env

## Env Variables
AWS_BUCKET_NAME=""
AWS_BUCKET_REGION=""
AWS_ACCESS_KEY=""
AWS_SECRET_KEY=""

### React design
![image](/public/react-design.png)
