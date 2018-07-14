# AngularJS TODO list 

## Deployment Instructions:


```
1. Clone the Project 
```
2. Create FBCreds file with firebase credentials setting the search index to 
3. CD into lib folder and type in the terminal: 
``` 
npm install
```
4. Set Up a Firebase account and set the rules to:
```
{
"rules": {
".read": "true",
".write": "true",
"posts" : {
".indexOn": ["uid"]
}
}
}
```
5. Run https server by typing in the terminal:
``` 
hs 
```
6. Open browser and type: 
``` 
http://localhost:8080 
```
7. Register, then start submitting images or comments.



