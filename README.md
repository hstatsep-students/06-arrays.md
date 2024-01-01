# Process Writeup

## Name: Wilson Huang
## Course: APCSA
## Period: 7
## Concept: Unit 6

### Introduction
In APCSA (Advanced Placement Computer Science A), we are learning about Java. Learning Java is somewhat similar to Javascript; so I am familiar with some of the code. In unit 6 we have been learning how about Arrays. It is like a container holding a certain amount of data, like strings and numbers. Learning this was quite easy because it is a similar concept to JavaScript. In this writeup I will be taking you through some of the challegnes I had when learning Arrays in Java and the questions I had trouble with in the exam. 

### Challenge 1
One challenge I had when learning about Arrays in java is trasversing through arrays. I had trouble with this becuase I didn;t understand how and when to use it. However after watching this [youtube video](https://www.youtube.com/watch?v=A31qPGH43Gw), I understood how it worked and when to use it. You trasverse through an array to go through each data in the array; this can include numbers and strings. It works by using a for loop and using the `.length` to go through each data in the array.
```Java
int[] num = {10, 20, 30, 40};
for(int i = 0; i < num.length; i++){
  if(num[i] > 25){
    System.out.println(num[i]);
  }
}
```
In this line of code there is a array that holds 4 different numbers. If you want to see if each number in the array is greater than 25 you will have to create a for loop that will go through each number and put and if statement. The code will print out 30 and 40 because they are greater than 25. 

### Challenge 2
Another challegne I ahd when learning about Arrays is modifying strings or numbers in an array. For example deletion, shifting elements, and reversing elements. This is confusing because I don't understand how it works but I know what code to use when I need to do it. So I went to [Phython tutor](https://pythontutor.com/visualize.html#mode=edit) since is shows the steps in the code. 



### Challenge 3
When finished with the unit 6 materials, we had to take a unit test to test our knowldege in Arrays. In this test time was a challenge for me because I would sometimes find myself focusing on one questions for a long time and not having time to look at the other questions. In this challegnge I will take you through some of the questions I had had wrong and explain the correct answer. 

#### Challenge 3.1
Consider the following instance variable and method.
```Java
private String[] words;

public void mystery(int n)
{
  for (int k = n; k < words.length - 1; k++)
  {
    words[k] = words[k + 1].substring(0, n);
  }
}
```
Assume that words has been initialized with the following values.

`{"dragon", "ogre", "troll", "goblin", “knight”} `
Which of the following represents the contents of the array words as a result of the call `mystery(1)`?
<br>For this question I got this wrong because I chose `{“d”, “o”, “t”, “g”, “knight”}` this is incorrect because the for loop does not start in the beginning.</br>

#### Challenge 3.2

#### Challenge 3.3



### Takeaways 
* Watch youtube videos when you don't get a certain concept because there is a lot of resources online
* Always review the questions you got wrong in the exam because that is how you learn
* 






