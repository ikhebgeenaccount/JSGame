#Planned features

  - Regions
    - Minimum, maximum border
      - Influences growth and income
  - Cities
    - Specialize
      - Economy
      - Production
      - War
    - Development level
      - Increases with
        - Occupation time
        - Levels of three fields
    - Income
      - Money
      - Food
    - Produce armies
  - Armies
    - Supplying
      - Manual
      - Automatic
    - Border interaction
  - War
  
##Cities
Cities are a vital part of the game. They represent your country. The more cities you have, the bigger your country is. A city creates a 'soft border'. This is a region. Regions can change sizes, this happens through movement of armies. (See [Regions](#regions).)
####Specializing
A city can specialize in three different fields:  
1. Economy - increasing gold income  
2. Production - increasing food production  
3. War - increasing strength of produced armies  

When a city reaches development level 10, you can choose to specialize. You can change these specialization of a city, but you will have to start from development level 10 again.  
Even after you have chosen a specialization for your city, you can still increase the other three fields. The specialised field increases faster than the other two fields, and is therefore creating a specialized city.
####Development level
Cities have development levels. These increase with time and levels of the three fields (See [Cities/Specializing](#specializing).)

##Regions
Regions are areas on the map that change size depending on the armies in its proximity. Allied armies extend the region to a certain maximum, enemy armies reduce the size to a certain minimum. These minima and maxima are calculated from the development level of the city. 
Making your region as big as possible gives you several advantages in this region:  
- The food production increases
- The economy grows faster
- WIP

##Armies
Groups of soldiers that can move around the map freely: armies. These armies can wander the world as they please, their only barrier being enemy armies and natural obstacles. They are not bound by borders. They do however influence these borders. As armies move through an allied region, the border moves with them, until it reaches it minimum or maximum. After that, it stays in place until another allied army comes across. Enemy armies can also influence these borders, by moving closer to them and thus pushing their own border further, making the allied border retreat. 
####Supplying
While armies are travelling they need food and rations to survive. These can be supplied by cities, by creating a food supply to this army. These food supplies are not bounded by borders, as armies they can move freely across the map. They can however be destroyed or taken by enemy armies. Armies can hold a certain amount of supplies with them, dependent on their size and strength. If they do not have enough supplies, the soldiers start dying. This makes surrounding an enemy army a very strong tactic as they will have to fight at some point. 
Supplying can happen in two different ways:
  1. Manual supplying, the player can send convoys across the map to an army. These can be intercepted by enemies.
  2. Automatic supplying, a connection between the city and the army is established. This connection supplies the army. An enemy army can intercept such a connection by standing on it. If this is the case, the enemy army will receive the food send over the line and the allied army will not receive anything

Armies are represented by cricles on the map. The more soldiers in one army, the bigger the circle is. The type of the army can be seen by the logo inside the circle.

##War
War is the way to expand your country. 
