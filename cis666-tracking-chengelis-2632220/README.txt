Alex Chengelis - 2632220

I followed the basic outline that was provided. I was able to make heavy use of the enumerate function in python to get the index in lists
to update them. Otherwise the implementation followed the general outline provided. 

For the first observation I implemented a counter then initialized to all the JailPositions and set the values to 1.0. From that I updated by
taking the value of emissionMOdel at that Distance for each location and PacmanPosition, and the beliefs based on each location in legalPositions.
For the Elapsed time I take the distribution of the GhostPosition based on the game state and oldPosition. Then i set all the probabilities for
each based on our current belief and the old belief. 

The particle filter works fairly similarly just with having to keep track of more things. 

for the BustersAgents. I just find the Max probability coordinate. Then I find the action that is the shortest to that coordinate and
return that action. 


Hours spent:
17. 7 of those hours were spent hunting down a simple space error. For that I can't say I am happy with Python. 


This was a pretty resource intesnive program to run. It utilized 15% of my i7-6700k resources. 


I was pleasently surprised with this. First time ever actually getting the autograder with all the points.


                     ALL HAIL GRANDPAC.
              LONG LIVE THE GHOSTBUSTING KING.

                  ---      ----      ---
                  |  \    /  + \    /  |
                  | + \--/      \--/ + |
                  |   +     +          |
                  | +     +        +   |
                @@@@@@@@@@@@@@@@@@@@@@@@@@
              @@@@@@@@@@@@@@@@@@@@@@@@@@@@@@
            @@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@
            @@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@
            \   @@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@
             \ /  @@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@
              V   \   @@@@@@@@@@@@@@@@@@@@@@@@@@@@
                   \ /  @@@@@@@@@@@@@@@@@@@@@@@@@@
                    V     @@@@@@@@@@@@@@@@@@@@@@@@
                            @@@@@@@@@@@@@@@@@@@@@@
                    /\      @@@@@@@@@@@@@@@@@@@@@@
                   /  \  @@@@@@@@@@@@@@@@@@@@@@@@@
              /\  /    @@@@@@@@@@@@@@@@@@@@@@@@@@@
             /  \ @@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@
            /    @@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@
            @@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@
            @@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@
              @@@@@@@@@@@@@@@@@@@@@@@@@@@@@@
                @@@@@@@@@@@@@@@@@@@@@@@@@@
                    @@@@@@@@@@@@@@@@@@



Your grades are NOT yet registered.  To register your grades, make sure
to follow your instructor's guidelines to receive credit on your project.