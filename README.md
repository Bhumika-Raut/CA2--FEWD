��#   C A 2 - - F E W D 
 
# CA2--FEWD

# Dino-Play



# Brief information about the project

# Introduction
 This is a game named dino-play which is included in the list of one among the most played and interactive games.Here all you need to do is press any key to start (to make the dinosaur run) and press space key to jump (above the obstacle/cactus). 

 # About the game how to play

 As mentioned above, one needs to press any key to start and space key to jump. However, distace between the obstacles keeps on changing also, speed of the dinosaur keeps on increasing to build up a difficulty level.
 Once the collision occurs between the cactus and the dino, game gets over and player needs to start the game again. The score increases by 1 point per second.


 # brief/basic logic of the code
 Basic logic of the code was that Animation frame keeps on updating whenever the update function is called. 

 # brief/basic logic how dinosaur which appears to be running
 Changing of animation frame and images accordingly
 # brief/basic logic of land
 Here actually the ground is moving towards left, for this continuous loop two lands are been stitched according to the scale and thereby those appears one after the another. 
 # brief/basic logic of the cactus
 Cactus appears as per the declarations and if the dino jumps i.e now we don't want the cactus getting gathered at the end of the frame(towards left), we delete it using remove.
 # brief/basic logic how game started 
 Using event listener we specified that pressing the key is needed to start the game
 # brief/basic logic about the jumps
 Whenever space key is pressed , the dino jumps due to declaration of addEventlisteners , values are been specified about the height of the jump and how it should fall (taking velocity into consideration i.e it gets bit slower at the top and then falls with a particular speed)
 # brief/basic logic about the jumps
 Rects are been assigned to the cactus and dino along with the conditions for the collision. If any condition is satisfied, the game stops over there the text ("Press any key to start the game") which was hidden appers back again and one can restart the game.

 # Referrences :
 Following are the sites/videos I referred:
 Mostly referred websites:
 1. W3Schools
 2. MDN
 3. AWS
 4. upsplash
 5. CodeHim
 6. Chrome (also used to take sprites)

 Referred Videos:
 1. https://youtu.be/hlwlM4a5rxg?si=Rmz8C53NUSTWFnnW (for form)
 2. https://youtu.be/ooru4pyEv1I?si=DP42BZfHcUPNnysN (got some part of logic)
 3. https://youtu.be/ooru4pyEv1I?si=2kCBUJ6pz0ce6ZyS (for few more basic info)

    Drive link for screen shots:
    https://drive.google.com/drive/folders/1X3CHtC4lGZCzh3cEARCf182TOQ4uaez0?usp=sharing

 Hope you enjoy, thankyou.

 





 
