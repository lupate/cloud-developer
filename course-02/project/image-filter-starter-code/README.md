# Udagram Image Filtering Microservice

Udagram is a simple cloud application developed alongside the Udacity Cloud Engineering Nanodegree. It allows users to register and log into a web client, post photos to the feed, and process photos using an image filtering microservice.

The project is split into three parts:
1. [The Simple Frontend](https://github.com/udacity/cloud-developer/tree/master/course-02/exercises/udacity-c2-frontend)
A basic Ionic client web application which consumes the RestAPI Backend. [Covered in the course]
2. [The RestAPI Backend](https://github.com/udacity/cloud-developer/tree/master/course-02/exercises/udacity-c2-restapi), a Node-Express server which can be deployed to a cloud service. [Covered in the course]
3. [The Image Filtering Microservice](https://github.com/udacity/cloud-developer/tree/master/course-02/project/image-filter-starter-code), the final project for the course. It is a Node-Express application which runs a simple script to process images. [Your assignment]

How to run this project ?

### Setup Node Environment

You'll need to create a new node server. Open a new terminal within the project directory and run:

1. Initialize a new project: `npm i`
2. run the development server with `npm run dev`

Locally, The API to apply a filter to the image URL: http://localhost:8082/filteredimage?image_url={url}

for example: 

`http://localhost:8082/filteredimage?image_url=https://www.wonderslist.com/wp-content/uploads/2021/05/Anastasia-Knyazeva-worlds-most-beautiful-girl.jpg`

#BEFORE
![alt text](https://www.wonderslist.com/wp-content/uploads/2021/05/Anastasia-Knyazeva-worlds-most-beautiful-girl.jpg)

#AFTER

![alt text](https://raw.githubusercontent.com/lupate/cloud-developer/master/course-02/project/image-filter-starter-code/deployment_screenshots/worlds-most-beautiful-girl-after-filter.jpg)

AWS Elastic Beanstalk env: `http://udagram-edmer-dev-dev.us-east-1.elasticbeanstalk.com/ `

Elastic Beanstalk URL:
`http://udagram-edmer-dev-dev.us-east-1.elasticbeanstalk.com/filteredimage?image_url=https://www.wonderslist.com/wp-content/uploads/2021/05/Anastasia-Knyazeva-worlds-most-beautiful-girl.jpg`

main repo url
>> https://github.com/lupate/cloud-developer/
