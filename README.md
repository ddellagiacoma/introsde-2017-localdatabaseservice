# Local Database Service (RESTful)

This service is part of the project described [here](https://github.com/ddellagiacoma/introsde-2017-userinterface).

LocalDatabaseService is a RESTful service that provides CRUD operation on its data. This Service contains the application database and its models are:

```java
public class Person{
  int idPerson, 
  String firstname, 
  String lastname, 
  String birthdate, 
  String email, 
  String genre, 
  String password, 
  int nGoalAchieved, 
  int nTotalGoal, 
  int idLifeStyle, 
  int idLevel,
  LifeStyle lifeStyle,
  Level level
}
public class LifeStyle{
  int idLifeStyle, 
  String style, 
  String description
}
public class Level{
  int idLevel, 
  String name, 
  String description, 
  int nGoalNecessary
}
```
