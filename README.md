
![logo_ironhack_blue 7](https://user-images.githubusercontent.com/23629340/40541063-a07a0a8a-601a-11e8-91b5-2f13e4e6b441.png)

# Lab | Movie Rating

<br>

## Introduction

Labs are mandatory and must be completed before the start of the next class. 
You may work collaboratively with your classmates, but you may not copy and paste another student's code.

## Requirements

- Fork this repository.
<!-- - Add your instructor and the class graders to your repository and ensure that your repository is private. Public repositories will receive a zero on the assignment.
  - If you are unsure who your class graders are, ask your instructor or refer to the day 1 slide deck. -->
- Upload the code for all of the following prompts to your repository.

## Submission

- Upon completion, run the following commands:

  ```shell
  git add .
  git commit -m "done"
  git push origin main
  ```

- Create a Pull Request

When you make pull request in pair-programming: `student1,student2-nameOfTheExercise` <br>
When you make pull request in individual-programming: `student-nameOfTheExercise`

<br>

## Starter code

No starter code needed/provided.

<br>

## Iterations

### Iteration 1

Create a new Swift playground using Xcode.

### Iteration 2

Create a new enum, named "Rating". It should contain the following cases: "awesome", "great", "average", "bad", "awful".

### Iteration 3

Create a new dictionary of movies. The key should be the movie's name: a string, and the value a Rating. Just pick the first movies that come to your mind.

Print your dictionary.

### Iteration 4

Using the method we've seen in class, add the most awful movie and it's (obvious rating) you can think of your dictionary.

Print your dictionary.

### Iteration 5

On second thought, this movie is just too bad for us to even have it in our code. using another method we've seen, remove it from your dictionary.

### Iteration 6

Add a string associated value to your ratings enum. It should be the number of stars (:star:) associated with each rating (0 for awful, etc).

### Iteration 7

Make your enum comform to `CaseIterable` and print each case's associated value using a loop.

### Iteration 8 (Bonus)

Find out how to iterate over all of your dictionary's keys. Using this and a switch statement, print an interpolated string similar to this for each movie, but displaying the actual movie's name & rating: "Matrix is an awesome movie; I give it ⭐️⭐️⭐️⭐️⭐️ !!!")

<br>

Happy coding! :heart:
