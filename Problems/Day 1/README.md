## Day 1



### The `Lab Performance` dilemma

Yagami and Ruyk are in the same "Introductory C Programming Class". Surprised? Don't be! There's more.

They want to get good marks with their lab performances. (Who wants to miss an easy A+ in C programming lab, right?) Now, Yagami is happy *IF* he gets more marks 
than Ruyk and Ruyk is happy *IF* Yagami can't score more marks than him. But, the teachers aren't so easygoing. Sometimes, they give negative marking.  :disappointed: 
No one is happy if he gets some mark *m* less than **0**.
 
 Given the marks of Yagami and Ruyk, can you predict their moods?
 :smiley_cat:    :crying_cat_face:
 
 In a single line there will be two integers, the score of Yagami *m_1*  and score of Ruyk *m_2*. Print two strings *"happy"* or *"non_happy"* based on the statement.
 
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
 
 > In first exapmle, Yagami got 12 and Riyk got 34. As, Ruyk got more mark than Yagami he is happy, Yagami is not.
 
 
 ### The `Signs` of `Three`

Three is indeed a magical number. Have you heard of the great **"Power of three"** ? (No, I'm not talking about `cgpa`!)

However, lets talk about something different. There are so many binary operations out there which will take two numbers and will give you one number as 
output.
When you multiply two integers, the result is always an integer. (What about division?) We are not going towards group theory though! Instead,
we will solve a simple enough problem. Lets say, you are given an integer which is the result of two binary multiplication or in simple 
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
 
 
 
 ### `Rectangle Intersection`

![Rectangle](http://www.geeksforgeeks.org/wp-content/uploads/rectanglesOverlap.png)

Itachi is working on a complicated computer vision algorithm, as a subtask he has to detect intersection of two rectangles. But, he has no time
to implement this as he has to write 4 lab reports today. So, he asks for your help. Can you implement it for him?

 You are given the upper left and lower right coordinates for each rectangle. You have to print "yes" if the rectangles intersect and "no" otherwise.
 
 In a single line there will be 8 integers, *x1* *y1* *x2* *y2* *x3* *y3* *x4* *y4* where, (x1,y1) is the upper left coordinate of first rectangle,
 (x2,y2) is the lower right coordinate of first rectangle, (x3,y4) is the upper left coordinate of second rectangle and (x4,y4) is the lower right
 coordinate of second rectangle.
 
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