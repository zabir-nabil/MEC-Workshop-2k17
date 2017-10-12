## Day 1



### The `Lab Performance` dilemma

Yagami and Ruyk are in the same "Introductory C Programming Class". Surprised? Don't be! There's more.

They both want to get good marks with their lab performances. (Who wants to miss an easy A+ in C programming lab, right?) Now, Yagami is happy *IF* he gets more marks 
than Ruyk and Ruyk is happy *IF* Yagami can't score more marks than him. But, the teachers aren't so easygoing. Sometimes, they give negative marking.  :disappointed: 
No one is happy if he gets some score *m* less than **0**.
 
 Given the marks of Yagami and Ruyk, can you predict their moods?
 :smiley_cat:    :crying_cat_face:
 
 In a single line there will be two integers, the score of Yagami *m_1*  and score of Ruyk *m_2*. Print two strings *"happy"* or *"not_happy"* based on the statement.
 
 #### Sample Input Output
 ------------------------------------------------------------------------------------
 ```
 12 34
 not_happy happy
 2 3
 not_happy happy
 5 2
 happy not_happy
 -1 0
 not_happy happy
 0 0
 not_happy not_happy
 -5 -10
 not_happy not_happy
 15 15
 not_happy not_happy
 
 ```
 
 #### Explanation
 ------------------------------------------------------------------------------------
 
 > In first exapmle, Yagami got 12 and Riyk got 34. As, Ruyk got more marks than Yagami he is happy, Yagami is not.
 
 
 
 
 
 
 
 
 
 
 ### The `Signs` of `Three`

Three is indeed a magical number. Have you heard of the great **"Power of three"** ? (No, I'm not talking about `cgpa`!)

However, lets talk about something different. There are so many binary operations out there which will take two numbers and will give you one number as 
an output.


When you multiply two integers, the result is always an integer. (What about division?) We are not going towards group theory though! Instead,
we will solve a simple enough problem. Lets say, you are given an integer which is the result of two multiplications or in simple 
words, I will take three integers, multiply them and give you the result.

 
 Now, can you predict the signs of those three integers?
 
 In a single line there will be one integer, the multiplied result. Print the possible signs of the individual integers.
 
 #### Sample Input Output
 ------------------------------------------------------------------------------------
 ```
 12
 + + +
 + - -
 5
 + + +
 + - -
 
 ```
 
 #### Explanation
 ------------------------------------------------------------------------------------
 
 > What about numbers <= 0?
 
 
 
 
 
 
 
 ### `8 o'clock class`

![Graph](https://preview.ibb.co/mH24Dw/done.png)

 Kirito has "Solid state physics" class @ 8 o'clock :clock8:, Now he has many options. He can either go to pocketgate
 or maingate for having breakfast, then can go to class. (Or he can sleep and miss the class! :sleeping: )

 There's a road between his home and pocketgate which takes *t1* time to traverse, his home and maingate
 which takes *t2* time, pocketgate and maingate which takes *t3* time, maingate and class which takes 
 *t4* time, pocketgate and class which takes *t5* time.
 
 Obviously, Kirito will choose the path which will take him to class (after having breakfast) in minimum
 time but he doesn't want to reach too early (Who wants?). So, the time taken should be greater than *T*. 
 
 You will be given 6 integers, *t1*, *t2*, *t3*, *t4*, *t5*, *T*. You have to print the minimum time
 satisfying the conditions, if there is no valid path print **"ajke_ghumabo"**.
 
 #### Sample Input Output
 ------------------------------------------------------------------------------------
 ```
 2 3 4 2 1 3
 5
 3 5 1 2 10 5
 6
 2 5 1 1 2 8
 ajke_ghumabo
 
 ```
 
 #### Explanation
 ------------------------------------------------------------------------------------
 
 > Think about all possible paths.
 
 
 
 
 
 
 
 
 
 
 ### `Rectangle Intersection`

![Rectangle](http://www.geeksforgeeks.org/wp-content/uploads/rectanglesOverlap.png)

 Itachi is working on a complicated computer vision algorithm, as a subtask he has to detect intersection of two rectangles. But, he has no time
 to implement this, as he has to write 4 lab reports today. So, he asks for your help. Can you implement it for him?

 You are given the upper left and lower right coordinates for each rectangle. You have to print "yes" if the rectangles intersect and "no" otherwise.
 
 In a single line there will be 8 integers, *x1* *y1* *x2* *y2* *x3* *y3* *x4* *y4* where, (x1,y1) is the upper left coordinate of first rectangle,
 (x2,y2) is the lower right coordinate of first rectangle, (x3,y4) is the upper left coordinate of the second rectangle and (x4,y4) is the lower right
 coordinate of the second rectangle.
 
 #### Sample Input Output
 ------------------------------------------------------------------------------------
 ```
 0 4 5 0 2 2 9 -2
 yes
 5 5 9 2 13 5 20 20
 no
 
 ```
 
 #### Explanation
 ------------------------------------------------------------------------------------
 
 > Draw some rectangles on paper first.