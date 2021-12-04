# final_project
Final Project for ECE 287

For our project we decided to create the classic game “brick breaker” on the FPGA board. We wanted the user to use the KEY[1] and KEY[2] keys on the board in order to move the paddle up and down on the screen and hit the ball as it came toward the paddle and send it back towards the bricks. The goal of the game is to get all of the red bricks hit and removed from the screen. If the ball goes behind the paddle, the user is met with a red screen meaning that the game is over and that they have lost. You can easily restart the game by pressing KEY[0]

To design this, we had to use a VGA (Video Graphics Array) controller that we were able to find online after testing many different methods that were not successful for our project. The creator of the VGA will be credited in the citations portion of this README. After we were able to get the VGA working it was time to actually get things to paint on the screen. We usea finate state machine or FSM to flow through our states of the project. 
