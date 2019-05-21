To run this project you must carefully follow the following steps-:
  1.First run the eurekaserverdemo project to start the Eureka Discovery server.
  2.Next run the adminmicroservice project,followed by lecturermicroservice project
   and finally run the studentmicroservice project and hit port localhost:8761 to check if they are up
   on the Eureka Server.
  3.Now run the ZuulGateway project and refresh the Eureka server to see if its registered.
  4.To access the adminmicroservice use zuul port localhost:8762/admin/home.
  5.To access the studentmicroservice use zuul port localhost:8762/student/home.
  6.To access the lecturermicroservice use zuul port localhost:8762/lecturer/home.
  7.Give the zuul url three tries to give it time to locate routes 
  8.You should be good to go.
