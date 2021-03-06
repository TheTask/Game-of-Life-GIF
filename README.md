# Game of Life - GIF

### Prelude

Hello everyone,

we decided to make your coding of Assignment 4 a little bit more fun as well as give you an option to earn some extra marks ( up to 10% back on your assignments ). Your task is going to be simple - make two GIFs out of the iterations from your Game of Life program.

### Context

[John Horton Conway](https://en.wikipedia.org/wiki/John_Horton_Conway), the creator of the Game of Life is one of the most respected mathematicians currently alive. He is also known for his Conway Notation, Surreal Numbers, Free Will Theorem and many other attributions. You can play The Game of Life interactively at [https://playgameoflife.com](https://playgameoflife.com).

### Your Task
Since the Game of Life is a zero-player game ( meaning the evolution is determined by its initial state ), people have discovered interesting patterns that produce fascinating output. Here is an example of what is known as *Gosper Glider Gun*. 

![alt text](https://upload.wikimedia.org/wikipedia/commons/e/e5/Gospers_glider_gun.gif)

Your task is to create 2 GIFs by taking screenshots of each evolution and then by using any tool you want ( such as [gifmaker.me](https://gifmaker.me) ) create the GIF files. 

This is my take on pentadec with 15 iterations ( the 15th iteration is the same as the first one ):

![alt text](https://media.giphy.com/media/4NcZqzQLKQRPv7gxKA/giphy.gif)


### Starting Conditions
Copy the starting arrays to your main method and call simulateNGenerations().

GIF 1:
- 16 iterations ( including the original seed ), 150 ms between frames, infinite loop*
```
int[][] exploder = {       {0,0,0,0,0,0,0,0,0,0,0,0,0,0,0}, 
                           {0,0,0,0,0,0,0,0,0,0,0,0,0,0,0}, 
                           {0,0,0,0,0,0,0,0,0,0,0,0,0,0,0},
                           {0,0,0,0,0,0,0,0,0,0,0,0,0,0,0}, 
                           {0,0,0,0,0,0,0,0,0,0,0,0,0,0,0}, 
                           {0,0,0,0,0,0,0,1,0,0,0,0,0,0,0}, 
                           {0,0,0,0,0,0,1,1,1,0,0,0,0,0,0}, 
                           {0,0,0,0,0,0,1,0,1,0,0,0,0,0,0}, 
                           {0,0,0,0,0,0,0,1,0,0,0,0,0,0,0}, 
                           {0,0,0,0,0,0,0,0,0,0,0,0,0,0,0},
                           {0,0,0,0,0,0,0,0,0,0,0,0,0,0,0}, 
                           {0,0,0,0,0,0,0,0,0,0,0,0,0,0,0},
                           {0,0,0,0,0,0,0,0,0,0,0,0,0,0,0} };
```
GIF 2:
- 20 iterations ( including the original seed ), 150 ms between frames, infinite loop*
```
int[][] glider =   {       {0,0,0,0,0,0,0,0,0,0}, 
                           {0,0,1,0,0,0,0,0,0,0}, 
                           {0,0,0,1,0,0,0,0,0,0}, 
                           {0,1,1,1,0,0,0,0,0,0}, 
                           {0,0,0,0,0,0,0,0,0,0}, 
                           {0,0,0,0,0,0,0,0,0,0}, 
                           {0,0,0,0,0,0,0,0,0,0}, 
                           {0,0,0,0,0,0,0,0,0,0},
                           {0,0,0,0,0,0,0,0,0,0} };
```
*\*Infinite loop means that the GIF should repeat forever*

Note: 16 iterations ( including the original seed ) means that the GIF should consist of 17 frames ( 21 for the 2nd GIF ).

### Deadline
The deadline is **March 31st, 23:59pm**.

### How to submit
Email both GIF files to me at **marek.borik@mail.mcgill.ca** with the subject line **GIFs**.

### Rules and Points
- The GIFs have to be screenshots from your IDE. If you send me other GIFs from the internet, it will not count.
- You will be able to get back up to **5%** per GIF on your assignments A1-A5 for the total improvement up to **10%**.
- To get full points, your GIFs have to produce correct output and follow all the other conditions posted.
- We are going to assign the points after we are done grading A5 and I will email every person who submitted and letting him/her know, how many points they earned.
- It is possible to get partial marks on the GIFs, however if you scored 100 on all 5 assignments, you won't get any extra marks.
- You cannot resubmit the GIFs for more marks if you didn't get 10 points. One submission per person.
- The key is to align the individual images as much as possible, a jittery GIF like this wouldn't get full points:

![alt text](https://media.giphy.com/media/kKKHCM0FNngYwqzP9W/giphy.gif)

Any additional questions should be directed to the MyCourses forum or Reddit. Have fun and happy coding!
