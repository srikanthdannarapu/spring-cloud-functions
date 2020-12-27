
C:\Users\sreekanth>curl -H "Content-Type:text/plain" localhost:8080/getEmployees
{"employees":[{"empId":"1","empname":"Srikanth","email":"srikanth@gmail.com"},{"empId":"2","empname":"Nikhil","email":"nikhil@gmail.com"},{"empId":"3","empname":"Shivam","email":"shivam@gmail.com"},{"empId":"4","empname":"satyam","email":"satyam@gmail.com"}]}
C:\Users\sreekanth>curl -H "Content-Type:text/plain" localhost:8080/toLowerCase -d "SrikantH"
srikanth
C:\Users\sreekanth>curl -H "Content-Type:text/plain" localhost:8080/getMessage
Hello Srikanth!!!
C:\Users\sreekanth>curl -H "Content-Type:text/plain" localhost:8080/writeMessage -d "hello world"

C:\Users\sreekanth>curl -H "Content-Type:text/plain" localhost:8080/toUpperCase -d "srikanTh"
SRIKANTH
C:\Users\sreekanth>        



![CURL commands](images/"curl commands.png")                                                                                                                                             
