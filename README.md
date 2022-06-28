# Jenkins-Closing-Task

## features  
1. Reads the “Breaking News” from YNet new service: http://www.ynet.co.il/Integration/StoryRss2.xml  
2. parses and Presents the Breaking
News XML in an HTML with Java Spring Boot Framework, And BOOTSTRAP front-end framework


## Run Locally

Clone the project

```bash
  git clone https://github.com/mohamadassi173/Jenkins-Closing-Task   
```

Go to the project directory

```bash
  cd Jenkins-Closing-Task 
```

Build the project

```bash
  mvn package  
```

Start the server

```bash
  java -jar ./target/xmltohtml-0.0.1-SNAPSHOT.jar
```

access : http://localhost:8080/ 



https://user-images.githubusercontent.com/57872327/176147392-cd1d8706-5c08-43b9-a30e-c10f2d89b4da.mp4



## Jenkins pipeline Job

<img width="668" alt="image" src="https://user-images.githubusercontent.com/57872327/176038731-d1951a5b-e526-4c8a-81a5-bf13c91885a6.png">

### the pipeline sends a slack notification
<img width="537" alt="image" src="https://user-images.githubusercontent.com/57872327/176038638-d3075267-7f8d-42f8-a291-79dccd4de4dd.png">
