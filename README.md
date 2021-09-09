# robot_recommend_restaurant
This is the programming code robot recommend restaurant from user preference

I was conscious of "Clean Monolith Architecture"  
Reference is link below  
https://threedots.tech/post/microservices-or-monolith-its-detail/

# system of this code
## entity
* user
* robot
## usecase
* robot conversation with user
  * robot say hello
  * robot ask recommended restaurant to user
  * robot recommend restaurant
  * robot make ranking from user preference
  * robot say goodbye
## controllers
* get path of database
## infrastucture
* text file
* csv file
