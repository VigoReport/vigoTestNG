# vigoTestNG
TestNG middleware for https://vigoreport.io


### Integration with vigoreport.io
----------------------------------------------

####Step 1
Download the `Vigo-TestNG-xxx.jar` from this repo.

####Step 2.
Generating Config file
`Java -jar Vigo-TestNG-xxx.jar -init`

####Step 3.
Add Report directoryPath and Project key into config file
```
{ 
  "projectKey": "502d97c9a94567GH59711966a3ec8d758", 
  "reportDirectory": "F:/TestProjWorkspace/Test1/test-output"
}
```
####Step 4.
 Start the VigoBot-TestNG & Enjoy reporting on web.
 
`Java -jar Vigo-TestNG-xxx.jar`
