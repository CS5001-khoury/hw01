# Homework 1: Welcome to CS5001

First before you start this homework assignment, make sure you compete the syllabus quiz! You won't be able to turn in this homework until you score a 4 of 4 on the quiz. Now let's start. Part of this homework will be autograded and parts will be graded via TAs. You will have four points possible for this assignment, each corresponding to a Tier Mastery category (see the syllabus!)



## Task 0: warm-up - Star Rating App

For this assignment, you will want to use the provided template file called [star_rating.py](star_rating.py). The file does have errors in it, but you should be able to load it fine into IDLE. If you run the file without changes, it should output the following:

```text
1 star rating: 
2 star rating:
3 star rating:
3 star rating:
3 star rating:


My star rating is
Help on function five_star in module __main__:

five_star()
    sets five * to the variable stars.
```

The final solution output should look like

```text
1 star rating: *
2 star rating: **
3 star rating: ***
4 star rating: ****
5 star rating: *****


My star rating is *****


Help on function five_star in module __main__:

five_star()
    sets five * to the variable stars.
```

### Let's get started

First you will see a lot of `functions` in the code. While we will cover these later in the course, we separated the warmup into these function, so you can think of your code in 'blocks' doing one thing at a time. 
> Always make sure to read through all provided code, and express what it does in your own words.  
>     Pros use comments in the code to do that, and not sure yet is  a valid answer!)

**Your Tasks**  
1. You should change each function to set the correct number of stars to the variable `stars` 
   * You don't need to modify anything else, just that one line!
   * You should use the string multiplication operator (review the lecture on concatenation)
2. Find the errors in the print out in the main function, fix them
   * Don't forget the two missing lines




## ASCII Art

[ASCII art](https://en.wikipedia.org/wiki/ASCII_art) is an age old tradition actually dating back to [printing presses](https://en.wikipedia.org/wiki/ASCII_art#/media/File:Brooklyn-Daily-Eagle-1875-01-06.png). It is the idea of using typography to build pictures out of the characters.  Even  today, emotes start off as simple ASCII art! 

>  ¯\\_(ツ)_/¯

Which is now part of the Emojicon, often translating to 🤷

For the rest of the assignment, you will be working on two pieces of ASCII artwork. 

### Task 1: Hobby Card

Use the file  [hobby_card.py](hobby_card.py) to start out. You will be building a `string` made up of additional strings. Once again,
review the lecture on concatenation. As a reminder to help you out, you can do something like the following:
a
```python
card = "This is my line\n"
card = card + "this is my second line\n"

print(card) # you should not be using print in your hobby_card.py unless it is to debug
```

would print to the screen
```text
This is my line
this is my second line
```

Even better, you can also modify the above to use shortcut assignments to produce the exact same result, but easier to read!

```python
card = "This is my line\n"
card += "this is my second line\n"

print(card) # you should not be using print in your hobby_card.py unless it is to debug
```

Your **task** - Build a card that lists your name and your hobbies. However, you have to meet the following conditions with the card.

1. the total width / length of the card is 32 characters
2. First and last row: 30 dashes (`-`) and a plus (`+`) signs on each corner
2. Each other row uses a bar `|` to start and end
3. The second row will have centered "A Hobby Card" (case matters!)
4. The third row will have your name (as in your actual name, or a nickname if you have a particularly long name)
5. You will have an empty row
6. Followed up by up to three hobbies listed
   1. Indent 4 spaces before your first hobby

Here is a templated example:
```text
+------------------------------+
|         A Hobby Card         |
| Your Name                    |
|                              |
|    hobby1, hobby2, hobby3    |
|                              |
+------------------------------+
```

Along with a finished example:

```text
+------------------------------+
|         A Hobby Card         |
| Albert Lionelle              |
|                              |
|    Fencing, D&D, Writing     |
|                              |
+------------------------------+
```

> **PRO TIP**  
> Run the program frequently as you are building the card. It will be *much* easier to get it correct.  
> Even when writing the solution we ran every time we created a new line. 

### Task 2:  Get Creative!

Your last **task**, use the following template file [my_art.py](my_art.py). Using print statements, create some ASCII art! You may want to look at [some examples](https://www.asciiart.eu/). Please note, for part of your in, you will be sharing this art with other students!

**IMPORTANT**  
After finishing your hobby card, and ASCII art, go ahead and post the *output* (not the code) to MS Teams.  You should only do this after you have earned 3/4 points using the assignment auto-grader (grade scope)!  To help with formatting, you can (and should) use the </> icon in teams to post the output. 

![Teams post example](teams_post.png)

Even though it says code snippet, when you click on it, you will have the 'text' option which is what you should use. You may have to have the application installed for it to show up as compared to the web version (you should have it installed anyway for this course!). As teams changes, and it is slightly different, do the best you can.




## Grading Rubric

1. Learning (AG)
   * each star rating function returns the correct number of stars
2. Approaching  (AG)
   * `main()` function fixed in star_rating.py with proper spacing
3. Meets  (AG)
   * Hobby Card completed with proper formatting
4. Exceeds  (MG)
   * Uses * concatenation or string  f-formatting for creating stars
   * Properly assigns the variables without additional prints or unneeded assignments
   * Properly updates docstrings in all files
   * Adds additional understanding / self explanation comments (better to do more than less for now)
   * Posted both ASCII art and hobby card to MS Teams 


AG - Auto-graded
MG - Manually graded