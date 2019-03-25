# Game of Life - GIF

### Prelude

Hello everyone,

we decided to make your coding of Assignment 4 a little bit more fun as well as give you an option to earn some extra marks ( up to 10% back on your assignments ). Your task is going to be simple - make two GIFs out of the iterations from your Game of Life program.

### Context

[John Horton Conway](https://en.wikipedia.org/wiki/John_Horton_Conway), the creator of the Game of Life is one of the most respected mathematicians currently alive. He is also known for his Conway Notation, Surreal Numbers, Free Will Theorem and many other attributions. You can play The Game of Life interactively at [https://playgameoflife.com](https://playgameoflife.com).

### Your Task
Since the Game of Life is a zero-player game ( meaning the evolution is determined by its initial state ), people have discovered interesting patterns that produce fascinating output. Here is an example of what is known as *Gosper glider Gun*. 

![alt text](https://upload.wikimedia.org/wikipedia/commons/e/e5/Gospers_glider_gun.gif)

Your task is to create 2 GIFs by taking screenshots of each evolution and then by using any tool you want ( such as [gifmaker.me](https://gifmaker.me) ) create the GIF files. 

This is my take on pentadec with 15 iterations ( the 15th iteration is the same as the first one ):

![alt text](https://media.giphy.com/media/4NcZqzQLKQRPv7gxKA/giphy.gif)


### Starting Conditions
Copy the starting arrays to your main method and call simulateNGenerations().

GIF 1:
- 16 iterations, 150 ms between frames, infinite loop
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
- 20 iterations, 150 ms between frames, infinite loop
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
### Deadline
The deadline is **March 31st, 23:59pm**.

### How to submit
Email both GIF files to me at **marek.borik@mail.mcgill.ca** with the subject line **Gifs**.

### Rules and Points
- The GIFs have to be screenshots from your IDE. If you send me other GIFs from the internet, it will not count.
- You will be able to get back up to **5%** per GIF on your assignments A1-A5 for the total improvement up to **10%**.
- We are going to assign the points after we are done grading A5 and I will email every person who submitted and letting him/her know, how many points they earned.
- It is possible to get partial marks on the GIFs, however if you scored 100 on all 5 assignments, you won't get any extra marks.
- The key is that the individual images are alligned as much as possible, a jittery GIF like this wouldn't get full points:

![alt text](https://media.giphy.com/media/kKKHCM0FNngYwqzP9W/giphy.gif)

Any additional questions should be directed to the MyCourses forum or Reddit. Have fun and happy coding!
