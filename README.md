# Jenkins-Closing-Task

## features  
1. Reads the “Breaking News” from YNet new service: http://www.ynet.co.il/Integration/StoryRss2.xml  
2. parses and Presents the Breaking
News XML in an HTML Table Format (Don’t forget to make right to left as in
Hebrew)


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


https://user-images.githubusercontent.com/57872327/176015158-6410871c-bb72-46c1-92d1-1e1ff9699af2.mp4

## Jenkins pipeline Job

<img width="668" alt="image" src="https://user-images.githubusercontent.com/57872327/176038731-d1951a5b-e526-4c8a-81a5-bf13c91885a6.png">

### the pipeline sends a slack notification
<img width="537" alt="image" src="https://user-images.githubusercontent.com/57872327/176038638-d3075267-7f8d-42f8-a291-79dccd4de4dd.png">
