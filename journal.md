# This is my journal for Info Science
CLASS 1
1. What did we do?

We watched a video introducing us to the basics of Info Science, we also learned about the different ways to solve problems using computational thinking.  After this introduction we were presented with a sandwich making activity.  In this activity we had to create a extremely detailed "recipe" and present it to Dr. Ruebn, who made the sandwich for us. 

2. What is I learn?

I learned about the 4 components of computational thinking, decomposition, pattern recognition, abstraction, and algorithms.  I also learned that when coding, all of the actions need to be extremely detailed, in order for the final product to be successful.  

3. What questions do I have?

How do I understand coding better?

Are there different languges of coding?

CLASS 2

We went through our homework, which was to research and make a circle in Processing.  We also followed the teacher and create a few things using coding in Processing.  At the end we tired to make a dice on our own, which required a bit of research.

I learning how to code, and many ways things can be manipulated to change the final produce/outcome.

How do I make a dice?

CLASS 3

We finished making our rolling dice, and the link is below. We also played a game where we had to guess which number was biased.

I learned a bit more about coding and also how numbers ,

```.py 
def setup():
    size(700,700)
    dice=0

def draw():
    x=0
    
    
def mouseClicked():
    fill(255,255,255)
    
    rect(100,100,500,500,55)
    
    fill(255,0,0)
    
    dice=random(0,6)
    print(dice)
    if dice<1:
        circle(350,350,55)
    elif dice<2:
        circle(500,200,55)
        circle(200,500,55)
    elif dice<3:
        circle(350,350,55)
        circle(200,200,55)
        circle(500,500,55)
    elif dice<4:
        circle(200,200,55)
        circle(500,500,55)
        circle(500,200,55)
        circle(200,500,55)
    elif dice<5:
        circle(200,200,55)
        circle(500,500,55)
        circle(500,200,55)
        circle(200,500,55)
        circle(350,350,55)
    else:
        circle(200,200,55)
        circle(500,500,55)
        circle(500,200,55)
        circle(200,500,55)
        circle(350,350,55)
        
 ```
