![img](https://github.com/user-attachments/assets/2d5ad1c4-4f49-417d-8c8b-e11fac0b6a31)# GDIM32 In Class Activities

# Week 1



## Activity 1:



Try looking though the pre-learning slides this time, cuz we are testing on it this time.



## Activity 2:



1. x = 10
2. x = 2
3. print "hello world" on the log section in every tick
4. MonoBehaviour
5. print "x = 10" in the debug log
6. (10) is an Argument, ("x = " + x) is an Expression
7. it should be \_playerTransfrom.Translate(\_direction) not Transform.Translate(\_direction). 'Transform' is a instance method, but we should use a static method for this thing.
8. it should be \_playerTransfrom.Translate(\_direction)


## Activity 3:



[This is our breakdown document](https://docs.google.com/document/d/1y5LOXHts-EvqE00ku0UjBCC5AgohWl3lteMNVPOctuo/edit?usp=sharing)

# Week 2


## Activity 1:

<img width="768" height="480" alt="Relations" src="https://github.com/user-attachments/assets/60897f7a-dac4-49d2-a95b-080b8e07dfa9" />

[This is the commited link](https://github.com/UCI-GDIM32-W25/mg2-WolffielotSecond/commit/3f81f6942abf436586efa11b693f59efa06eba97)

I've done the whole project. Like the scene, the code for the bird, coin and player controller and the algorithm of the random generation of coins.

# Week 3

## Activity 0-2

Buddy's name: Haoyi Zhang

## Activity 3

<img width="1521" height="951" alt="image" src="https://github.com/user-attachments/assets/19f9e8ce-ac20-4c39-af2f-b229cc1de42a" />


# Week 4

## Activity 1

Haoyi Zhang

## Activity 2


<img width="3024" height="4032" alt="image" src="https://github.com/user-attachments/assets/5db0c8ca-738e-4475-8f27-26b9dcbb98db" />

## Activity 3

[This is the commited link](https://github.com/WolffielotSecond/HW4/commit/22a00c86d012c35212b9244edbd082ea8bf6a116)

# Week 5

## Activity 1

It's okay for me. And I'll learn and keep that because although I know little about unity but in Unreal I can use more interface and abstract classes instead of casting to blueprints.

## Activity 2

EmemyStats and ItemW5Demo2 are model, EnemyW5Demo2 and PlayerW5Demo2 are controller, DialogueBubble and InventoryUI are view.

## Activity 3

1. A rhyme game should have a scriptable object to store the data for points awarded and things that will happen when responded to a kind of key. The game controller should be a singleton(to handle the total scores and general data)
2. The model will be the stats of the player or enemy, the bullet, the health, thescore of the player. The view is the HUD, or the scoreboard. The controller will be the control of the character of the player or the game.
3. The Inheritance will be helpful for the plant systems. The Finite state machine will be used for the state of the plant will be, like sead, growing, or ripe. State Machine will be helpful for the whole state of the plantes.

## Activity 4

Pengcheng Qi, Haoyi Kun, Allen Gu

Proposal: [Link to the google doc](https://docs.google.com/document/d/1x9D6Q_2PD2IP5_ACEah36JJO2HM0rF6mYcNEO8_yNTk/edit?usp=sharing)

# Week 6

## Activity 1

For gizmos, it's a good tool to visualize like player moving direction and collision, and it's useful to know if they are wrong when the game objects are going to the wrong way.

For profiler, it's a good way to analyze the fps and what's causing the game to lag, like specific game object's specific component.

For break points, it's a good tool to debug and know which lines are causing certain bugs.

## Activity 2

Attendence: Pengcheng Qi, Haoyi Zhang, Allen Gu

# Week 7

## Activity 1

1. private Vector3 _raycastStart calculates the srarting point of the raycasting. It switches the object position to the world postion. This is a read-only property that is like a getter. It prevents the data stored in it from being modified.
2. private Vector3 _raycastDir creates a vector pointing to the player character. It is also a property for the same reason. 
3. private void UpdateState () updates the finite state machine by using if() statement and the HasLineOfSightToPlayer() method, which initializes the bool return value to false, projects raycast using Physics.Raycast(), and then checks if the player is in sight by checking the tag.
4. Physics.SphereCast() is used to create a spherecast in HasCloseObstacles () method. This method is used to check if there are close obstacles in the area and return the bool value. If there is, _spherecastHitLocation is modified.
5. OnDrawGizmos() draws the raycast and changes the color according to _hasLineOfSightToPlayer on gizmos; it also draws the area of the spherecast on Gizmos. This is important because it helps the developers see these elements in the scene.

## Activity 2

Pengcheng Qi, Haoyi Zhang, Allen Gu

## Activity 3

<img width="822" height="717" alt="5f5f337556e90bfbdca6da1725232f75" src="https://github.com/user-attachments/assets/c2b85e13-4438-4549-b600-1bde1cc1a56f" />

## Activity 4

https://trello.com/b/TcDWOqGX

## Activity 5

https://github.com/leiyu0803/GDIM32-Final/commit/d315dd5126402acd08f19c4d7dfb0f70845ec35b

I editied the map and fixed the bugs 

## Final Draft Link

[Link to google doc](https://docs.google.com/document/d/1x9D6Q_2PD2IP5_ACEah36JJO2HM0rF6mYcNEO8_yNTk/edit?usp=sharing)

## Week 8

### Activity 1

A rendering pipeline is how everything is rendered on screen. It can be modified in settings and can be seen if it's working. Post Process Profile is a file that used to manage all the post process effects. You can use it to add all kinds of screen effects like dizzyness.

### Activity 2

Haoyi Zhang, Pengcheng Qi, Allen Gu

### Activity 3

[Test itch page](https://stormmoon.itch.io/gdim32-final-test1)

Goal: Test all the interactable item. 

After 30s of explore, tester known how to interact with all the items in the sense. All system working as intended in the current test version. 

### Activity 4

Polished the background to make it more lively

Made a raw NPC that can move to specific locations and can play animation(but bugged).

### Activity 5

[Link to the commit](https://github.com/leiyu0803/GDIM32-Final/commit/fe3abe131af76f3f7a79ad029fffd0032272ceee)
