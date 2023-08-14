
# Meta
## AVOID WORDS:
- Back-end, front-end, full stack
- Syntax

## To Do:
- For brackets, colon, semicolon, dash, slash, etc - show on screen what key it is on the keyboard
- This course is unconventional and different from others
- Quotes: you hold SHIFT and you press quote
- Remake the functions example cause its too complicated
- I encourage you to take notes that YOU can read and understand. Don't blindly write down everything I say, write it down so you understand.
- Code should look like english
- Make sure you deliberaly avoid saying it copy/pastes code, but let users think it does at the beginning
- Clickbait titles for lessons
- Basic concept: All programs are just input->processing->output
- chatGPT
- Explore! Try to break things! I encourage you after every lesson, try to explore 2 ways you can write the code and see if it works. A lot of times, it just won't work.
- Escape string characters
- Decide what type of quotes you want to use
- Tell them that you really don't need to memorize. Programmers don't memorize!
- Exercise: convert :) to 😊
- FAQ for each section
- Make each lesson stand-alone (e.g. how to run JS without browser page)
- Put [Optional] in front of some lessons

`dasd`

## Where to Post
- Udemy
- Coursera
- Skillshare
- learn.fiverr

## Course Structure
## Name:
- Include Programming and Coding as keywords in the name
- No BS
- Zero-to-hero
- Unusual
- Practical Programming/JavaScript


# Intro
## Welcome (2:00 max) (focus on what you'll have at the end)
- Thank you and welcome
- Who is this course for?
- What is this course? What does it teach?
  - Will supply you with everything, minimum necessary you need to build anything
	- Made so even the most beginner people who have never seen code in their life will understand
	- I was disappointed with other courses online as they always assumed the viewer already knows some things, have ambiguous explenations, are inconsistent or overload the learner with information they don't need
	- This course will teach you strictly the minimum necessary you need to build big application, real life code and I will take you from zero to hero. I will give you both simple practice exercises and exercises that are real use cases for that lesson, problems that programmers encounter in the real world. 
	- I will also teach you how to host your apps and websites, deploy them to Google play, and even host your databases, all for free
- By the end of this course, you will be able to build applications like this... or like this...
- Why JavaScript?
	- Also you'll learn other languages easier
- Questions? How you can contact me
- I can't wait to get started!


## Resources (2:00 max)
- Transcript here, project files here, comment section etc
- Do leave feedback

## Topics covered in this course (3:00 max)
- We will start with JavaScript (which is the hardest part), then switch to HTML, CSS which are both really easy, then back to JS. All of these 3 are required to build any website or so on
- The super basics of programming: numbers, strings, if/else, variables, arrays, objects (if you are already familiar with these, feel free to skip)
- TODO: how the course is split into chapters# Skillshare
## Requirements
Video length: 2-8 minutes
Requires a project that can be showcased by students


# JavaScript (Basics)
## Setup
- What is JavaScript? What can it do?
	- change text on the page, colors, do calculations
	- an example
- JS works in browser
- No setup required for now, just used jsfiddle or a custom made website for JS coding. No account required. You can take notes in a notepad text file, or word, or whatever is comfortable for you.
- I highly recommend you take some notes, but if you choose not to, you will always have this course, structured so that you can always look up something you don't remember.

## What is code?
- Here is where we write code
	- The computer will read the code, top to bottom, left to right, and, line by line, it will execute that code
	- We will basically tell the computer what to do through code
- A programming language is a language the computer understands. We can't just use English to talk to the computer and tell it what to do, because English is too ambiguous.
	- Programming languages are very very clear and know how to work better with numbers, text, automating things, etc

## Super duper basics: numbers and text
- alert number (parenthesis are on shift 9 and 0)
- alert text (backticks only)
- explain string (text) and number, text without quotes does not make sense, explain spaces
- text + text (hi Daisy nice to meet you), number + numbers, text that looks like number (don't use word _concatenation or append or data type, functions)
- text + text + text, a + b + c
- string + number (you might be wondering what happens if...)
- Homework

## Some more operations!
- Previous lesson we did only addition (+)
- a - b
- a * b
- a / b
- Remember 8th grade operation order, like if you have:
	- a + b * c
	- b * c is calculated first
	- This is not a JS thing, this is just a basic math concept
	- Some more examples with operation order...
- If you want a part of the equation to be done first, use parentheses (on 9 and 0)
- If we want numbers with decimal points, use "." (NOT ",")

## Text and Numbers? Let's see if it works!
- string * number, string / number, number * string, etc
- Let's try them out and see what happens (don't worry, it's not gonna break your computer or what not)
- Explain how a string, even if it looks like a number, is NOT a number. It's still just TEXT

## Variables
- A variable is just a word that represents something else; whenever we write that word in code, the program will replace it with whatever it represents
- So let's make a variable!
- `let myage = 25`
- First, explain as aliases; wherever JS sees `myage`, it will replace it with 25 (essentially making `myage` an alias for `25`)
- So let's try that: `alert(myage)`
	- `alert(myage + 10)`
	- The program just replaces `myage` with `10`
- Same for strings (name = `Dave`)
	- Wherever JS sees name, it will replace it with "Dave"
- Variable names can't contain spaces but can contain underscores
	- You can NOT say `my name = "dave"` (and quickly delete it so you emphasize it)
	- Important thing! Variable names should start with a small letter. A lowercase letter. This, again, isn't mandatory, but you should start a variable name with a small lowercase letter [select the first letter]. You will see why in the future

You might be asking: can you set a variable equal to another variable?
Of course!
`let dave = "Dave"
let teacher = dave
let friend = teacher
alert(friend)`
So, JS reads the code line by line and (yeah, uhuh, yeah) and gets to alert. It sees `friend` and looks at the code before and sees that `friend` is the same as `teacher`, then it looks at `teacher` and sees `teacher` is actually `dave`, then finally, sees `dave` is the same as `"Dave"`, so it alerts Dave on the screen.

If you want to put it this way, `friend` is another word for `teacher`, and `teacher` is another word for `dave` and `dave` is another word for "Dave".

This example was a bit extreme perhaps, but if you ever want to understand what a variable represents, just follow the code back up, like we did in this example.

- Do everything we did earlier (exactly same examples) with variables
- Homework

## Variables - Cool Popup Trick
- So far we learned to use alert dsadasdto show stuff on the screen (show that)
- There's one more very similar command that instead of showing text, it gives you a popup with an input field, where you can WRITE something and put it into a variable
- `name = prompt()`	(make sure you put these parentheses, very important)
- Boom! We'll be using that a bit later!

## Variables - some more stuff
- Explain that variables can change throughout the code. That's why they are called 'variables'.
	- "From now on, down, x will be ___"


- You can even do this: x = x + 20
	- Can you guess, what alert(x) will print next?
	- Yes, so this will be x = <x> + 20
- And this works with strings as well:
	- `let cow = "moo"`
	- `cow = cow + "oooooo"`
	- `alert(cow)`

And you might be wondering: Dave, why do we use let the first time and not the second time? Can I just say...
`let x = 10
let x = 20`
Well, I hear you, I see what you mean, and this would make sense to work, you're right. But it just doesn't. You even see here you get a little red circle and an underscore.
What's important to remember is when you _create_ the variable, you use let. Then, when you want to **change** it, you don't use let.



- And of course, you can combine them however you like!
	- let myname = "Dave"
	- let yourname = "Max"
	- alert("Hi " + yourname + " my name is " + Dave)
		- Let's add a little comma here to make it look better
- Case sensitive! Dog is not the same as dog and it's not the same as DOG
	- dog = "Daisy"
	- DOG = "Goonter"
- Code is executed top to bottom, line by line, instruction by instruction. The computer goes through each line of code and executes it
- Examples:
	- dog = "Daisy", then alert(dog) -- this works
	- alert(dog), dog = "Daisy" -- this does not work
	- Obviously, you should first

Now, remember that when you _create_ the variable, you must use let. 


- Exercise: Alert my weight in pounds
- Homework, real life: we have a variable salary = 2000 and we know the tax = 30%, so 30% of this money goes away. We want to alert the calculate the salary after the tax. Can you do it? (remember that the salary and tax can change, so the program should work even if I come and change the tax to, say 50% or 10% and salary to 3000).
	- Hint: you will have to use both division (/) and multiplication (*)
	- Solution: `salary = salary * (100 - tax) / 100` or `salary = salary - (tax * salary) / 100`
		- Hope it wasn't too complicated, but if it was, no worries, we will explain it later!

## Variables - FAQ for angry math students
For people who are used to math, and I've heard this a lot, you might say: hey in Math this is just a contradiction, cause we said `let name = "Bob"` and now we say `name = "Mary"`? No name does not equal to Mary, what the hell?
No, no, no. Listen. In programming, what this does is it **changes** the value of name to be Mary. This is what it does when you use equal. When you say <something> = <something else>, this means you change  <something> to be <something else>.
It's not a true or false statement or an equation or whatever you learned in math class. It is assignment!

## Frequently Asked Questions (FAQ)
1. What do I do if my code doesn't work and I don't know why? Developer console.
	- Show open console, clear console
	- Make intentional error
2. How do I make my variables have multiple words in their name? For example, how would I name a variable called "dog name"? How do I write that?
	- you can have dog_name or maybe dogname
	- JS uses a notation which might feel a little strange at first, we do it as:
		- dogName
		- dogName = "Daisy"
	- Again, it's up to you how you name your variables, all examples work
	- But, generally, JavaScript programmers hate underscores. If you look at JavaScript code online, if you ever need to look something up, you will see that nobody uses '_'. Why? No idea. People just don't like it. I guess people just think it's ugly.
	- Again, if you like underscores, please by all means use underscores. You should just know that in the JavaScript world, people don't like underscores.
3. You might see variables declared with var instead of let, online or maybe in other courses. That is also correct, but it's the OLD way of declaring variables, you might encounter problembugs if you use that. In real life, nobody uses "var" anymore. Don't do it!
4. What happens if I don't use let at all?
`x = 10
x = 20`
Well, the program will just go like: Ok, I should **change** this x to 10. But what was x before that? Well, x doesn't exist, so there's nothing to change!
So, this does not work. Because when you say just `x = 10`, that means **change** x to 10, and you didn't create x before this, so there's nothing to change.
But... if you actually test this, you might see that it works - but it's deceptive! It only looks like it works but it actually doesn't!
Because of a stupid way JavaScript works, this works _sometimes_ so even if it appears to work, it actually doesn't so you should never ever do this.
I repeat: when you want to **create the variable**, the first time, you use let.
When you want to **change** it later, you don't use let.

Homework: There are some extra things I haven't answered, but I'd like **you** to answer them yourself. So here's the homework - try these things and write down in the comments what it happens if:
- You try to change a number or a string itself, like 20 = 30 or "Dave" = "Bob", does that work? What happens?
- 

## Some cool JS built-in variables!
- window.location.href (dot, this is a dot)
	- If you change this variable to, say, "http://google.com" can you guess what would happen?
	- Yes! You are correct! The page will change!
	- For now you can treat this whoole thing as one single variable (highlight)
	- However, jsfiddle.net won't allow you to do this because they are douchebags.
	- We can open the browser console to do it, though!
	- And yes, you will be able to do this from code in your own project
- window.innerWidth / window.innerHeight
- window.Browser.name (capital B)
	- you can also get the browser version with window.Browser.version
	- And the operating system: window.Browser.platform

# IF
## IF
- We want to do something **only** if a number is greater than another number.
	- Example with literal numbers
	- Explain brackets, the code inside the brackets is **only** executed if the condition is met. Otherwise, it is skipped.
- Explain tabs and spaces. They don't matter, it doesn't matter if your code is like this (     ...) or like this (...    ) it's the same thing, but we align code to make it easier to read and understandmore readable. It will be easier to understand which lines of code are in the if, because it may not always be immediately visible where the bracket is.
- Aight, ok
 		- An example where the condition is met and it's skipped
		- An example where the condition is not met and it's skipped
- Let's make an app that checks if you are over 18 years old, and only then it will say on the screen "yes, you are allowed to enter on this website"

## Tabs and Spaces

- Instead of writing 2 spaces, you can just press tab on your keyboard, it's the same thing. You might want to get used to pressing tab because programmers use it a lot ;)
	- Trust me, you need to start pressing tab if you're not doing it already

## Comments
A very quick thing I want you to know is you can add **comments** to your code.
If you say `//`, everything after this `//` will be ignored by the program. You can even see it turns gray.

This is just for you as a human programmer to leave notes.
`window.location.href = "https://google.com"`
We can add a comment on another line to explain what this does:
`// Changes the current browser page to Google`

We can even put it at the end of this line if we want.

Another way to do write comments is to use `/* <enter> */` and inbetween these, here, you can write your comment.
This is especially good if you want to write multiple lines. But essentially there's no difference between
`/*
Changes the current browser page to Google
*/`
and
`// Changes the current browser page to Google`
They don't do anything, they're gray, they are just notes.

## IF - equal and not equal
- We want to check if something equals something.
	- This might look strange but that's just the way it is
	- string === string
	- number === number
	- string === number? will this work? well, no
		- explain 20 === '20' is not true
- x !== y

## IF - not

## IF - and, or, if inside if
- if (x > 0 && x < 10)
- We can ask the user for a name with  `prompt()`
	- if (name === 'Jane' || name === 'Dave')...
- note: if you want to use prompt() it will only work with strings, so if you type in 20, it will take it as a string, so be very careful
- if (...) { if (....) ....
- Exercise: program that will display "welcome" only if the user accesses the website only from google chrome and windows

## else/else if
- if (...) {} else { }
- if (...) {} else if (...) {} else if (...) {} else {}
	- And you can have as many ifs as you like
	- if name is "Dave" ... else if name is "Boris" ... else if name is "Pablo" else ...
- Homework: make a "log in" system. There is a username variable and a password variable, and the user has to type in the username and, if the username is correct, then also type the password. If they are both correct, a message will say "Login successful" otherwise it will say "username incorrect" or "password incorrect"
	- (give them the starting code, username=... and password=....)

# WHILE
## WHILE: execute again and again!
- Congratulations for making it so far!
- Let's say we want to alert with a popup all numbers from 1 to 10
- We could do it like alert(1) alert(2) ...
- But what if we want to alert all numbers from 1 to 100?
- ThisWe have a dog and we want it to bark 9 times
- 
- We have a cow and we want the cow to say (alert) moo
	- We have a variable, howManyOs = 9
	- Our "moo" must have that many O's. How can we do that?
		- So isf why we need the WHILE loop. The WHILE loop allows us to repeat the same commands over and over again, as many times as we want!

`while (something) { ...  wil times letis, s te whou cti}`

- Te `howManyOs = 9` then it alerts `mooooooooo`
	- Obviously we can't just copy paste this code or make 2938 ifs.
	- Let me present to you the while loop is exactly. It's like the IF, but instead of doing what's inside the brackets once, it will do it again and again, until the conditi and then moving on, is no longer valid. Let's do the example mentioned

`let x = 1
while (x < 10) {
	alert(x)
	x = x + 1
}`

And this does exactly what it sounds like it does: while x is less than 10, it alerts X, then increases X by 1.
Let'st's going to do it again and again.
	- The way it works is like this: it checks if it works!

So, let's go through it again, line by line, to see how it works:
- checks if x < 10. if x < 10, it goes inside the brackets.on i alets x up here is met, then it executes all code below, lincreases x by 1, and then it goes back to the while.
- checks if x < 10 again. if x < 10, it goes inside the brackets. alert x, increases x by 1, and then it goes back to the while.
- checks if x < 10 again. if x < 10, it goes inside the brackets. alerts x, increases x by 1, and then it goes back to the while.
- And so on, until x is 10; it will check if x < 10, it is not, so it skips the brackets
	- (ass an `alert('finished')` after the while)



## WHILE: Exercise
- We have a ce after line, until it reaches the end of the the brackets. Then, the code goes back up at the condition and does it again and again!
	- while (x === 10) { alert ('Yes, x is still 10') }
	- So, how cand we want the cow to say (alert) moo 9 times
	- Our "moo" must have that many O's. How can we do that with the while??
- Ok, let's look at the problem. We needmake it stop? Here's how.
	- Let's say you want to do the sasome thing 910 times. How can we do that? Well, we already know the answer. With a loop, just like before!

```
let x = 1
while (x <= 9) {

	here we do something that will be done 9 times

	x = x + 1
}
```

- Okay, so how can we alert a mooooo with 9 O's?
- Let's make an extra variable that will hold the current moo
- `let moo = "m"`
- Why just m? Becaauusee... were's how you would do it:
	-  = 0
	- while (x < 10) { x = x + 1 } alert(x)
		- x is 0
		- is 0 smaller than 10? yes! so we do what is inside the whill add an "o" to the moo 9 times!
- `moo = moo + "o"` (so this makes the moo
- And at the end, we `alert(moo)`
- Of course, if we change this 9 to, say, 25, we'll get a much longer moo

So, you'll probably want to get yourself familiarized with how you do something a number of times. You'll keep encountering problems where you need, inow an we  to doomething times, 10 times, 100 times, I worked with a program where we had to do something about 40 millione.
			- x becomes 0 + 1 so x becomes 1
		- then we go back up and check again: is 1 less than 10? yes! so we do what is inside the while
			- x becomes 1 + 1 so x becomes 2
	- if you don't believe me that this really happened 10 times.
`, let x = 1
while (x <= 40000000) {
	do something
	x = x + 1
}`

So you'll want to remember how you do that. Get this code in your head.

So as a homework, and I really really want you to do th's put an alert at the beginning of each loop
- The way to think about it is, ias to alert "Gooooooogle" with 30 o's.
And do not copy/paste the code from this exercise. Delete everything and I want you to do it from scratch. Try to remember if with a blank page here in front of you. Of course, if you don't remember, look back again at the video and do it, but keep trying. It's very important.

## WHILE: Practice
- There's another way to exit a while loop, and that's with the special keyword "break"
	- How can we make an infinite loop?
	- while (1 === 1) { }
		- this will crash the browser, because it will try to do something again and again forever
	- `while (1 === 1) { x = x + 1; if (x === 10) break }`
	- You can also do this: while (true)

This way to do it is completely optional; almost every time, if you want to do something, you can do it either with an infinite loop or a normal while loop like we did earlier.

Exercise: guess my name- Exercise: we make an annoying web page, where you have to click ok on the alert popup 30 times and and tells us how many times more we need to click
- Homework: make a game in which you have to shoot  (you need to use while and prompt)


# Arrays
## Arrays (lists)
Let's say we are a veterinarian and we want to hold the name of all dogs we treated today. One way
to do that is:
dog0 = "Daisy"; dog1 = "Goonter", dog2 = "Winnie", dog3 = "Hogger"
And if we want to show the name of dog 2, we would do alert(dog2)
We can have a variable for each dog name, but that's quite ugly because every time we want to
add another dog, we need to create another variable. So if we have 100 dogs, we will have 100
variables! And that's a lot!
So what we can do, is we can create a list of all these dogs:
dogs = ["Daisy", "Goonter", "Winnie", "Hogger"] (note the little commas between the
elements)
Now, to show the name of dog 2, that's really easy:
alert( dogs[2] )
Makes sense, right? This should give us the 2nd dog in our dogs. Right?...
Wait, it says "Winnie"! Our dog #2 is Goonter. What?
Well, in programming, numerotation starts at 0.
So the first position of the array is actually position 0 element, Daisy.
0 - always always 0. Arrays always start at 0.
On position 1 we have Goonter, and position 2 we have Winnie
Just as with normal variables, we can change one of the elements of dogs. Let's say, instead of
Goonter, we want Bessy. Just as with normal variables, we can do:
dogs[1] = "Bessy"
and we can alert it so make sure it was changeds
Now let's say we want to add another dog to our list - dog number 4 names "Butch". Can you guess
how we do that?
Yep! dogs[4] = "Butch"
Woohooo!
Ok, so, in JavaScript, lists are called Arrays. Lists exist in all programming languages, but in JS they
are called Arrays. This is an array (dogs). Also, all arrays, in all programming languages, start at 0!
The first dog in our dogs array is dog number 0. The 4th dog is dog number 3.
This is very important for later.
As you would expect, you can also use variables in array, because the program just replaces that
variable with its value
let mydog = "Lego"
let dogs = ["Daisy", mydog, "Winnie", "Hogger"]
And, very importantly, we can use number variables to get an element from an array:
let pos = 3
dogs[pos] = "Lord"
alert( dogs[pos] )

And ofc if we change pos 3 to 2 it will show "Winnie"
And, if we change pos to 1, it will show "Lego", because dogs[pos], dogs[1] is mydog, and mydog is
Lego.
Homework: I want you to play with arrays a little bit, see what happens if you do the following:
What happens if you make an array that combines numbers and strings (texts)?
What happens if you skip a position in the array, like you add dogs[6] = "Lego" but there's no
dogs[5]. Alert that and see what you get!


## Arrays: looping through them
Let's say we have a list of Mike's dollars madesaved from each month of a year. In January, he
madesaved 10 dollars, in February, he madesaved 20 dollars and so on. We want to calculate the
total moneysavings of Mike.
let mikemoneymikeSavingchoolGrades = [10, 250, 5, 10, 10, 10, 35, 30, 25, 0, 10, 30]
One way to do it is to have a variable totalmoney = mikemoney[0] + mikemoney[0] +
mikemoneySavings = mikeSavings [0] + mikeSavings choolGrades[0] + mikeSchoolGrades[1] +
...
But that's really a lot to write and what do we do if his savings are on 24 months or 10 years!
We would have a lot to write
So how do we do it? Remember that while loop from a previous episode?
insert scene with while loop, a bit desaturated and cloudy
We will use the WHILE loop to go through all of them
while (something) {}
Ok, so let's look at how many numbers we have. There is a number of dollars for each month, so
that's 12 numbers.
So that means we need to do something 12 times. Do you remember how to do that?
let x = 1 while (x <= 12) { ... x = x + 1 }
In this case, we need to go through all the positions of the array from 0 to 11 (because remember that
arrays always start at 0; we have 12 elements, so the 12th element is on position 11) To make it more clear in this loop, let's change x to pos.
let pos = 0 while (pos <= 11) { ... pos = pos + 1 }
Let's see if this works by alerting every element of our mikemoney array
alert( mikemoney[pos] )do it just like that: - let monthNumber = 0 - let totalSavings = 0 -
while (monthNumber < 12) { totalSavings = totalSavings + mikeSchoolGrades[monthNumber]
monthNumber = monthNumber + 1 }`
So at first, pos is 0, so it alerts the first element of the array. Then it makes pos 1, goes up and
alerts mikemoney[1], then makes pos 2 and so on
So how would we calculate the total sum of this array?
Remember how we did the "moo" exercise? W, we start with monthNumber = 0. We enter the while
and we check: is 0 smaller than 12? Yes! so we dgo it just like that. We make a variable:
let totalmoney = 0
And every time in the loop, for every element of thenside. - totalSavings is 0, mikesSavings array, we
will do `totalmoney = totalmoney + mikemoney[pos]
So when we are at mikemoney[0], totalmoney will become 0 plus 10
Then when we are at mikemoney[1], totalmoney will become 10 plus 25, which is 35
Then when we are at mikemoney[2], totalmoney will become 35 plus 5, which is 40
If we want to make it a bit clearer, we cchoolGrades[0] is 10, so totalSavings = 0 + 10 = 10 -
monthNumber becomes 0 + 1 = 1 - then we go back to the top of the while and create another
variable inside the while
let moneythismonth = mikemoney[pos]
totalmoney = totalmoney + moneythismonth
Next video I'll show you a helpful nifty trick!
Arrays: Length (and Strings)
Check: is 1 less than 12?
yes! so we go inside again
You might be wondering, what do we do if we don't know how many elements there are in an array?
What if someone gives us this varrayiable but we can't see what is inside?
We can easily get how many elements are in an array with mikemoneySchoolGrades.length (12,
because there are 12 elements).
If you ever have an array and want to find its number of elements, just add .length at the end of its
name and that will give you the number of elements - This .length thing is what we call a property
of the variable and it's basically a variable inside another variable. I will explain this when we get to
the Objects lesson but until then, just take it as it is: if you put .length after the variable, you will get
how many elements are in the array. - If we add another one (mikemoneySchoolGrades[12] = 40), it
will be 13. - Remember that since it starts at 0, mikeSchoolGrades[12] is the 13th element of the list,
not the 12th, keep that in mind
That is the basic way to going through an array. In the next video, I will show you the modern way to
do it, but to understand that one, you needed to understand this basic method to go through an
array and, in real life, you will need both).
Homework: calculate mike's total money for all months except for June and July (cause he was on
vacation). Can you do that? As always, I want you to erase the code you have here (except for this
part with mikemoney) and try to do it from scratch. Hint: you will need to use an IF for this as well,
inside the while
Strings behave kind of like arrays
I want to show you something quite cool and useful. With arrays, you can just put dogs[1] and get the
dog on position 1, the second dog. Well, you can do the same with strings and it will get you the letter
on that position! Let's check it out! let name = "Dave" name[1]
Oh, and .length works on strings too!
name.length
"Daisy".length (maybe you have a whole page from harry potter inside this string and you
want s length)
Exercise: We have a variable `let website.
Homework: make a more complex login system. We have 2 arrays, one with usernames and one with
passwords. Make it so that if usernames[0] == prompt()` Check if the website starts with "http" We
take it letter by letter!
Homework: Check if the a website address ends with "ro". Hint: you will need to use .length; this might
be a hard one, but you have all you need to work with. Take it step by step, check the last letter, then
check the second-to-last letter.asswords[0], ok. - Tips: you will need to use the "break" keyword

## Arrays: looping through them, the modern way (for)
mikeSavingchoolGrades = [10, 20, 5, 10, 10, 10, 35, 30, 25, 0, 10, 30]
What we want to do is to go through each and every element of this array and add them to the
totalSavings, just as we did before. Here's how we do it in the modern way, and it's a lot easier: for
(let element of mikemoneySavings choolGrades) { totalmoneySavings = totalmoneySavings +
element }
This will go through every element of mikemoneySavingchoolGrades and, for each grade in
mikemoneySavings choolGrades, it will do the code between the brackets and element will be that
number
Let's go through it step by step:
element will be 10 first, so totalSavings = totalSavings + 10
then, element will be 250,
then, element will be 5
Exercise: alert ('yes') if "Daisy" went to the vet, otherwise alert('no')
break can also be used herein arrays
Homework:
We have an array of objects that represents the shopping card of online store: let shoes =
["Nike", "Puma", etc]
Find out how many Nike shoes are in the shopping cart
Any questions, feel free to leave me a comment or contact me directly


## Brushing Up: recap and what's next
- Firstly, congratulations for making it this far! You're doing amazing! That's all the basics of the language, the building blocks!
- In the next few lessons, we are going to brush up on JavaScript with some more exercises to get you more and more familiar with the language before we move on to the next lessons, which addresses three of the most important concepts in programming: booleans, functions and objects. And if you liked JavaScript so far, believe me, you will LOVE what's coming next, because JavaScript makes these two things much easier to understand and learn than other languages, especially Objects, you will love objects in JavaScript, they just make so much sense. And with what you will learn, you will make your life soo much easier, believe me. Everything will come together nicely.
- So, to recap what we've learned so far [have slides here]:
	- We learned how to alert a popup with a message on the screen
	- We learned how operations work and how JS calculates everything.
		- How you can add together strings (text)
	- We learned about variables: how to create a variable, how JS replaces wherever it sees that variable with the value of it and how variables can change
	- We learned about the almight IF with conditions and it's nice, squiggly braces
	- We learned about loops, and how the inside of braces keeps repeating over and over again until the condition up here is not met anymore
		- Or how you can simply stop the while loop with the "break" keyword
	- We learned about lists of elements, which are called Arrays in JavaScript, and how we can go through the array element by element
- In the next video, I will show you how to show messages to the console, so let's get into it and I hope we'll be having fun together in the next lessons as well!
- Thank you for being awesome!

## Console.log and the Developer Console
- So far we've been using alert to show messages on the screen. Once you work enough with JavaScript, you will see that it becomes a bit tedious and slow to just always keep alerting, especially if you want to see multiple messages, such as you want to see multiple variables:
	- alert(dogName)
	- alert(dogAge)
	- alert(dogOwner)
- So you would have to click on "ok" in the menu for each of them, which becomes annoying. 
- There is a better way to show messages, on the screen, and that is with "console.log"
- In a previous optional lesson, I talked about the developer console.
- Follow me and I'll explain it in a bit. On Chrome, you can click on the 3 dots here > More Tools > Developer Tools > Console. If you are on google Chrome, you can press Ctrl + Shift + J to open the console, if you're on Firefox you must press Ctrl + Shift + K.
	- If you use another browser, such as Safari or Opera, you can google "how to open console on Safari" and I'm sure you will get an answer.
- If you have any messages, here clear the console by pressing this button, it's all good, don't let those messages scare you, they are errors from other websites you've visited, because other websites have terrible programming.
- So now you should have what looks like an empty white panel. This is called the console and it's basically just like a panel that can display text!
- So now, instead of alert, let's use console.log. And when you use console.log, your messages will appear here, in the console, instead of on the screen.
- So let's replace all alerts with console.log and see what happens
- Aaah... it seems that we no longer get a popup and have to click, the messages just appear here in the order in which you showed them.
- This will be very useful if, for example, you want to see the names of all dogs on your list. Instead of alerting every single dog, you can just write a for and console.log the dog's name
	- And you can just type in console.log(dogs) to see all dogs
- That's the most common thing you will do with the console and for now, you really don't need to know more. But believe me, in time, you will learn more tricks to do with the console such as hacking website and modifying them, which is really easy to do actually.

## Boolean ('yes' or 'no')
- In this lesson you will learn about boolean variables.
- Booleans are very simple: just as you have variables that are strings (or text) and variables that are numbers, you can also have variables that are booleans. And unlike strings or numbers, there are only 2 boolean values possible: true and false.
- So, if you have a dog with name and age, you can have a variable which holds whether the dog is male.
	- ismMale = true
- And just as with normal ifs, you can check if this variable is true or false:
	- if (isMale === true) ...
- Now, you may be thinking "ok, but how is this different from writing isMale = 'true' and checking if isMale === 'true'.
- Let me explain:
	- First thing you should know: by default, every if and every while actually calculates what is inside the parenthesis as either true or false. So, every comparison you make is actually calculated to true or false.
		- `if (name === 'Daisy')`, the `name === 'Daisy'` part is calculated to true or false
		- And actually, what the if takes between the parentheses, is actually just either true (write it) or false (write it)
	- And to prove that to you, let me write it like this:
		- `if (true) alert('Yes')`
 		- `if (false) alert('Yes')` this will not say 'Yes'
- Ok, so, remember how we wanted to say 'Yes, it's a male' if the dog is a male. Instead of writing:
	- `if (isMale === true)` we can simply write `if (isMale)` (because isMale will be replaced by `true`).
	- And this might be a bit strange at first, but if you look at it, it's actually easier to read like English. If is male, alert ...
	- Mind blown? There's more!
- Ok, let me show you another really cool thing you can do with booleans. So as I said, `name === 'Daisy'` is actually a calculation which results in either true or false. What that means is we can use it in a variable!
	- `let isNameDaisy = name === 'Daisy'`
	- So, just like you add together numbers or strings, so you can compare values. Just as a number plus a number calculates into a number, so does "something" === "something else" calculate to a boolean, to true or false!
	- That means we can put these into variables!!!
	- `let isnamedaisy = name === "Daisy"`
	- `if (isnamedaisy) { alert("yes!") }`
	- This can be useful for making your code a little cleaner
- So, listen, nothing is stopping you from never using booleans in your programs. But the main idea is that IF's and WHILE's always have something

- Hold on! It's the end of the video, but I must tell you something super super important!
- In the following lessons, we'll do some more practice with booleans and then we'll move on to functions. Functions are absolutely the most important concept in programming, period. So, if you got this far, you absolutely need to continue on to functions!

## Booleans: practice
- Exercise: program that tells us if a person qualifies for free public transport (use booleans):
	- age > 15 and age < 26
	- isStudent true
	- isRomanian if name.length > 18 and < 20
	- Lives in one of these areas: Bucharest, Transylvania, Moldavia, Muntenia
- This might seem daunting because there are lots of things we have to check and now I will tell you about how we, programmers, think when we have to solve a problem.
	- When we have a problem, we always split it up into smaller problems that we can solve separately.
	- So we have this big problem. Let's separate the 3 requirements.
	- Do we know how to verify that the age is between 15 and 26? Sure...

## When you're doing things wrong...
By now, you probably have questions. Like what if I put a string inside an if?
`if ("hello")`
Or what if I put something else inside a for, like
`for (let x of 420)`
What will happen?

This is not a trick question. Indeed, these things don't work and you should not do them.
As a general rule of thumb, if something does not make sense but you can still do it, don't do it. Some things just don't make sense to work and they won't work.


## Brushing Up: practice
- Write a program that logs to the console all elements of an array that are also present in another array
	- You need a for inside another for!

## Functions that DO something: write less code, avoid copy paste!
- Welcome to the lesson on Functions! This is arguably the most important thing EVER you need to know in programming. I because it's very very very very important.!
- Let me begin with a simple explenation: a function is a way to group up lines of code and reuse that code without having to copy/paste
- Let's say we have a program where the user must type in their first name, their middle name and their last name, one after another, in order. And we must check that after the user types in a name, the name must be at least 13 letters long and at most 30 letters long. Each of firstAfter the user types in all the 3 names, middle name and last name, each must be more than 10 letters longbetween 3 and 30 letters long.
- So how would we do that? Let's do it the normal way. You can try to write it in advance. Feel free to pause the video and think how we'd do this.
- Let's start by making it read a name and make sure it's length is correct
- Let's start by making it read a name and make sure it's length is correctwe check that the full name is also between 3 letters long and 30 letters long.
- So how would we do that?
`let n = ''		// We're gonna use this n variable as a helper variable, so we start with it empty
n = prompt()
; if n.length > 10:
	= 3 && n.length <= 30: alert('Name is ok!')
 else alert('Name is not correct')
let firstName = n`
- Ok, now we have to do this again 2 more times. So what we're gonna do, because we are lazy, we're gonna copy and paste this code... (NOTE: use right click > copy / paste)
`n = prompt(); if n.length >= 3 && n.length <= 30: alert('Name is ok!') else alert('Name is not correct')
let middleName = n`
- And since we used this helper variable `n`, we don't need to change this code in the if, just here
`n = prompt(); if n.length >= 3 && n.length <= 30: alert('Name is ok!') else alert('Name is not correct')
let lastName = n`
- And now, to check the full name, we copy and paste it again in a similar fashion
`n = firstName + " " + middleName + " " + lastName`
And now we copy and paste this part again
`n = prompt(); if n.length >= 3 && n.length <= 30: alert('Name is ok!') else alert('Name is not correct')`
And finally, `fullName = n`

- Alright, let's test the code...
- Ok so the code works. But now if you have a keen eye you will notice this code is... ugly. It's ugly code. Why? Because there's a lot of copy paste.
- And what happans if your manager comes and says "Hmmm yeah I don't like that the messages (highlight them) are in English. I want the messages in Spanish. Ooook so now we are a bit screwed. So we could go around eeevery alert and change it from 'Name is ok' to 'Nombre esta bien" and ohhh it's a lot of work and we're gonna lose a lot of time.
- For that, I present you with a very simple and elegant solution: instead of copy pasting these lines of code, we will make a function:
- So, let's look at what code repeats.. (select code).
- And we're going to type the following up here:
`function readAndCheckName() {` very imporant here, these parentheses, I will explain later what they mean
`	n = prompt(); if n.length >= 3 && n.length <= 30: alert('Name is ok!') else alert('Name is not correct')
}`
- And now, I think you can guess what we're going to do next. We will replace aaaall of this duplicate code with our nice little function. So whenever JS sees readAndCheckName() -- again, very important, these parentheses here --, JS will replace this go up here and do the code here, and then it will return back here.
- Remember, very important, the code up here is NOT executed the moment you write it. The way JS reads this code is `ok we have an n variable` and then it reaches the function and remembers `ok, we have a function that does this when it is used`. So it will skip what is inside this function an will only do this code when  JS finds `readAndCheckName()` afterwards. So, again, when it finds this `function readAndCheckName` itand remembers `ok we have a function that does somthing, I won't concern myself for now with it` and reads on and then sees this and says `aha, ok, here the function gets executed, so: back to the function brackets and let's execute this code now!`
- Whooh... that was a mouthful. Functions are amazing! They allow you to reuse code! They are like copy paste but way way better! In a sense, they're like variables, but for many lines of code!
- So now, let's test if this works... aaand yep, it works just like before! Brilliant!

- And in programming, we use LOTS of functions. Like... looooots of functions. You will see that in a big project, coding on it becomes harder and harder the bigger the project is. And imagine if all our code didn't have functions. We would all be doomed to copy and paste! And copy/paste will produce lots of bugs. Trust me on that one. Functions are amazing!
- But that was only the beginning lesson on functions! Functions are sooo much more powerful! They can do a lot more and they can be a lot cooler!
- And in the next episode, you will learn even cooler things about functions. Stay tuned!

## Functions that RETURN something: transform something into something else
**NOTE: save the black boards**
- For this lesson, I want us first to take a trip back to 8th grade math and remember how functions were in math. If you don't remember, that's fine, I will explain it anyway.
- For now, we will use just math notation [NOTE: Use a black board for this], not JavaScript
- Do you remember what functions did in math class? They were a bit different. Every function was actually a transformation of something into something else. For example:
	- `f(x) = x * 10`
	- This is a function that takes an x and it transforms that x into x * 10
	- Let's put this function to use:
	- `myNumberage = 5 + f(3) - 8`
	- So when we use this function f here, we go back up here and we replace x with 3.
	- The calculation for f(3) will be: f(3) = 3 * 10 = 30 [NOTE: draw like an arrow from f(3)]
	- So now, we can replace f(3) with 30 and we get `myNumberage = 5 + 30 - 8` which is equal to `27`
- Let's take a more practical example. Let's make a function that takes a website name and adds http in front of it. We're still doing maths, this is not javascript 
	- `website(name) = "http://" + name`
	- And now, if we have `website("google.com")` it will be equal to... yes, `"http://google.com"`
- Alright. So, these functions can transform what we give them into something else.
- In programming, we generally have 2 types of functions:
	- Functions that DO something, like in the previous lesson
	- Functions that TRANSFORM something into something else
- In the previous lesson, we learned about functions that DO something, right? Functions that, when you use them, they just execute the code inside their curly braces.
- Now we are learning about functions that transform something. We give them a number or a string or something and they spit out something else. Good?
- Let's look at the example from before: `f(x) = x * 10` and we also have `myNumberage = 5 + f(3) - 8`
- Let's write this with JavaScript. So, we need to transform this from math to javascript. It's really easy!
	`function f(x) {
		return x * 10
	}`
- As you can see, it's very similar to functions that DO something from the previous lesson. This is exactly _this_. We used the special keyword `function` to create f(x) and the thing it spits out is after this `return` keyword.
- [NOTE: Blur the 'function' and 'return' keywords and also the brackets to illustrate that]
- Let's try it out. So let's first translate the other math thing into JS:
`let myNumberage = 5 + f(3) - 8` and we can `alert(myNumberage)` and let's see.
- It works! Amazing!

- Let's try it out with the website example. Can you guess what it's gonna look like?
	- And, if you remember this magical `window.location.href` built-in variable of JS, we can use it to change the page!
	- Let's change the page to the `about` page on skillshare.com.
	- We see the link is `skillshare.com/about`
	- `window.location.href = website("skillshare.com") + "/about"`

- So you remember how we used to use this `prompt()` thing before?
	- [NOTE: Show how we used it]
	- Well, if are thinking "hey, isn't prompt() actually a function that returns what we type in the box??"
	- And my answer is: YES! That's exactly what prompt is! But it doesn't even take a value, it doesn't need to.
- Anyway. In the next lesson, we will go back to functions that do something and we will complete it with some extra things!

## Functions that RETURN something: inside the curly braces
- Let's take a look at how JS flows and looks at the code and executes it.
- We have our `website` function and `window.location.href = website("skillshare.com") + "/about"`
- So JS reads this code and when JS reaches `website("skillshare.com")` here, it goes up here to the `function website(name)` part. Inside the function, it makes name equal to `"skillshare.com"`. TSo you can imagine that's literally what it does. It makes the variable `name = "skillshare.com"`. [NOTE: Use comments to show this] Then, it spits out `"http://" + "skillshare.com"` which is `"http://skillshare.com"`.
- So, when JS finds `website("skillshare.com")`, it replaces ithis whole thing with `"http://skillshare.com"`

- As you probably think, you can have extra code in a function before you write "return" something. [select the return part of our website function]. And the function is going to go through alll of its lines of code inside the braces, just as with normal code and with ifs and whiles, until it reaches the line with "return".
- However, for every function that RETURNS something, return must always be the last thing the function does! You can't put code after "return". You can't just press enter here and start typing code down below. It won't work. Don't do that.

	- I mean, you can, I'm not stopping you, but it's not gonna work.
- You can, though, write as much code as you want before the return! So let's try it! Let's add some code before the return!
	- So, let's say our function will be smart and, if the name we give it already has "http" in front of it, it will not add the "http://" part. Otherwise, it will.
	- So we're gonna have to add an if and an else here!
	- Let's declare another variable to hold what we will return `let finalresultreturnedName`
	- We put name inside it.
	- Now, we have to check if the name given aleready has "http" in front of it. How in the world could we do that!?
 	- `if (    ) {` what do we put inside the parentheses of this if?
	- Well, the easiest solution is to check letter by letter! So, the first 4 letters must be h t t and p
	- `if (name[0] === "h" && name[1] === "t" && name[2] === "t" && name[3] === "p")`
		- so here we use name just like we use a normal variable, because that's what name is. It's basically just a variable that is made equal what was inside the parentheses when we used the function, here [show where]
		- we make the returnedName = name; we don't do anything to it, we will just return the name
	- else
		- we make the `returnedName = "http://" + name`
	- Lastly, return returnedName
	- We can check if this works properly with alert. So we can do it on "skillshare.com"...
		- And on "http://skillshare.com"
	- Now, we didn't check for the `"://"` part as well [select it] and we kindda cheated because the program will not work if we have a website called, let's say "http.net". If we type in http.com into our browser, we will see it's a real website. But if we put this into our website function, it will be returned as "http.net". Which is wrong, because we want it to have "http://http.net". So http here is the actual name of the website!
And to make that work, I will leave it as homework!
- So, the homework for this lesson, add to t he function whatever is needed to check the :// part as well, and to make website("http.net") return "http://http.net"
- Think you can do it? Great! See you in the next lesson!

## Functions that DO something: parameters
- So far we learned that there are 2 types of functions: functions that do something and functions that spit out something, thatey transform something into something else.
- In the example where functions transform something, we had:
	- `function website(name) { return "http://" + name }`
	- Here, `name` is is called a parameter. And inside the curly braces of the function, `name` works exactly like a variable.
- In the previous lesson we discussed that you can have multiple lines of code in the function that returns something as well as in functions that do something. I showed you how you can take a parameter (name in our website function) and you return something else, aka you transform the name given to the function.
- Well, you can also have parameters on functions that do something! And I made the previous lesson so that it becomes more obvious, but if it's not, no worries

- So let's say we have an online shop website. And when you click on a product, it will add that product to the cart. Let's say it will execute a function called addProduct which will add the product to an array containing all products in our cart and will tell the user "You now have <that many>  products in your cart". If you have 2 items in the cart, it will alert that you have 2 items in the cart."
- So we have this `let cart = ["Nike Shoes Size 38", "Brown Coat"]` and these 2 products:
	- `// "Green T-Shirt"`
	- `// "0.5L Water Bottle"`
- And we must make this addProduct function and use it do add, one by one, each of those 2 products.

- Now, functions that DO something can also take a parameter. And we COULD do it like we did in first name, middle name and last name problem we did a few lessons ago, remember that one? Where we used a single variable n. We could do it like that, but I want us to use a **parameter** `productName` to add the product to the cart. [Note: flash on the screen, grayed and memory-ish the problem with the names].
- Let's first write howwhat we want the function to work.
	- when we use `addProduct("Green T-Shirt")`, it will be added to the cart and alert a message.
- Let's write the function!
- `function addProduct() {  }` and we will give it the parameter productName
- `function addProduct(productName)` so whenever we use `addProduct("Green T-Shirt"`), productName will be made equal to "Green T-Shirt". And, again, productName works exactly like a variable inside the function.
	- We have 2 steps: 1. add the element to the array and 2. alert how many elements there are
	- remember how we can add an element to an array?
	- Our array currently has 2 positions, so we would need to add an element on the third position. But since array positions start at 0, the third position is actually position number 2.
		- If we had 3 elements, the 4thwe would need to add on position will be number 3
		- If we had 4 elements, the 5thwe would need to add on position will be number 4 and so on and so forth
		- To get the number of elements in an array, you use .length, so cart.length tells us the number of elements currently in the array. It's a variable built into an array
	- So we write `cart[cart.length] = productName` and then we must `alert("You have " + cart.length + " products in your cart")`
- Does it work?... yep, it does!
- So a quick recap on how this code gets executed [Again, go through the code and explain]. When JS reaches here the... 

- Homework: we are a veterinarian who needs to track dogs who came to the cabinet and the date they came. You have 2 arrays, `dognames` and `dogdates`. Write a function that takes 2 parameters, a name and a date (which is just a string), and adds the name to the dognames and the date to the dogdates.

## Functions: Frequently Asked Questions (FAQ)
Congratulations! You pretty much know everything there is to know about functions! Well, as always, there are some other cool tricks you can do with functions, but more on that later. You know the basics and that's what matter!
You might have some questions though, and I'm here to answer them:
1. Can you change the value of a parameter?
	- Yes, you can, but you should not
	- `function website(name) { name = ... }` this does work, but for clarity's sake, don't do it. If you need to change it, just make another variable `let nameChanged = name` and change that one instead.
2. Do things inside the function stay the same if you call it multiple times?
	- No! Every time you use a function, everything inside it is reset! As it should be. Sure, you can use things from outside the function inside the function, and those things can change and stay like that. But a variable declared with let inside the function stays inside the function. It can never ever go outside.
3. What happens if we already have a variable outside of a function with the same name?
This is a very good question!
`let name = 'facebook.com'`
`function website(name) { name = ... }`
`alert(website('google.com'))`

As a general rule of thumb, in programming, if something looks unclear or it's unclear what it does, then it really is unclear and you should change it.
	- The code above works and the name here and the name here are 2 different variables with the same name. This `name` and this `name` are different variables! While inside the function, here, it sees: Hey, there are 2 names. One is created here outside the function, and one here inside the function. Which one does it use? Well, it always uses the one that is the "closest".

So when JS reaches the alert(website('google.com')) it will go up to the function and make this name equal to 'google.com', and, again, this name and this name are 2 different variables, and it can never ever use this `name` up here anymore. Be very careful!

It sounds confusing? Well, yeah, it kindda is confusing. That's why, in my opinion, you should avoid having variables with the same name. Use different names for all variables and parameters to avoid confusion!

4. Can you have functions that return something with no parameters?
	- Yes, we can make a function called 'returnMyAddress()' which returns 'Kingston City Street 74'. (alert it)
	- There's also some really nice built-in functions with no parameters like prompt() we used earlier.
	- Also, there's `Math.random()` which always returns a random number between 0 and 1. This is useful for making games or simulate dice rolls. (show that if we run it again, we get a different number)
54. Can we have a function with more than 1 parameter?
	- Yes, absolutely! Let's write a function that takes 3 parameters and returns their sum
	- `function sum(a, b, c) { return a + b + c }`
6. What happens if you call a function with fewer number of parameters than it has?
	- It will not work properly (show the sum above)
7. What about if I give it too many parameters?
	- You should not do this, but if you reIt will work normally want, itd will just ignore the extra parameters (show the sum above)
8. What happens if I call a function without parentheses
	- It will not work (e.g. prompt or Math.random). Nothing will happen

## Function: last cool little tip
One last thing I want to mention with functions. As a fair warning, you don't need to memorize this or even ever do this. It's just something I want to show you.

Let's say we have this function:
`function convertdollarstoeuro(number) {
	return number * 0.93
}`

If you ever feel like the name is too long, you can create a variable that holds this function!
`let dte = convertdollarstoeuro`
DTE standing for dollars to euro of course. Also, no parentheses, because you're not **using** the function, but just making a variable that's the same.
So now you can use it like `alert( dte(100) )`. This `dte` is exactly the same as `colvertdollarstoeuro`.

I know that's a bit strange, but you can make a variable equal to the function itself.
I wanted to show you this because you might see it online and in other places, so you just know it's possible.

## Functions... you did it! That's all!
Congratulations! You are now an expert on functions! This was hard, I know, but you did it! Take a break if you need to. What follows is a lot easier. 

# Objects
Welcome to the second most important thing in programming, after functions.
You're almost there! By the end of these lessons on objects, you will know everything programming has to offer. That's it, that's all programming is. Once you learn Objects as well, there's no stopping you. You've gone through the hard part. The rest of programming is just combining all of these conceps you learned in various ways, and lots and lots of functions made by incompetent people.

Do stick to the very end, don't skip the last 1 or 2 minutes of this lecture, trust me, it's very important information.

I've tried to slowly get you into the idea of objects. Like `dogs.length`, or `window.location.href`.
An object is just a variable that has multiple variables inside of it. Let's say we want to have a dog that has a name and an age.
What we could do is have:
`let dogname = "Daisy"
let dogage = 9`

But objects help us organize our code much more nicely! We would like do have a variable called `dog` that has a `name` variable and an `age` variable inside of it, so that we can use `dog.name` and `dog.age`.

`let dog = {
	name: "Daisy",
	age: 9
}`

Note this little comma right here...

And that's it, we now have a variable called `dog` that has a `name` variable and an `age` variable inside of it.
`alert(dog.name)`
`alert(dog.age)`

You might be wondering: ok but does `dog` actually have a value? If I use `dog`, what will it be replaced by?
The answer is `dog` doesn't do anything by itself. It's just a variable that holds other variables. If you use in an alert or in a math equation, it won't work. The only reason arrays and strings have a value AND have variables inside of them is because they're the base building blocks of JavaScript.

And you might be thinking: Dave, why is this useful? Can't we just have normal variables? And you're right. You can just have normal variables.
In fact, you can probably make any program without using objects at all! You could just use normal variables and arrays. But objects help you organize the code so so well, and everything uses Objects. If it's not clear how and why objects are useful, you'll understand, trust me.

Let's see an example. We'll look at a previous exercise from the functions lessons, with the dogs who visited the veterinarian.
`let dognames = ["Daisy", "Harold", "Winnie"]
let dogdates = ["20 Jan 2023", "23 Jan 2023", "17 Feb 2023"]`
But imagine we also want to have hold other information about our dogs, like their health status
`let doghealth = ["Healthy", "Recovering", "Healthy"]`

You can clearly see how this gets messier the more information we want to hold for our dogs. And in the real world, you will probably need a lot more of these. Imagine if you have an  online shopping website and, for each item, you need to have its name, price, date of fabrication, category, number of items in stock, current discount and the list goes on and on and on.

Now imagine you need to modify the health for Winnie. You'd have figure out which element in this whole array corresponds to Winnie, which is a complete pain in the but.
And yes, in real life, sometimes you will need to open up some data file and change things manually. If you want to manually change the health of Winnie, you'd have to count which is the position of Winnie in this array, and then count where the health of Winnie is. And if you accidentally make a mistake, the our data will be all screwed up!

Let's organize our dogs in a nicer format:

`let daisy = {
	name: "Daisy",
	date: "20 Jan 2023",
	health: "Healthy"
}
let harold = {
	name: "Harold",
	date: "23 Jan 2023",
	health: "Recovering"
}
let winnie = {
	name: "Winnie",
	date: "17 Feb 2023",
	health: "Healthy"
}`
And then we have our array which looks like:
`let dogs = [daisy, harold, winnie]`

Off the bat you can clearly see how our code looks much more organized.
If we want to change one thing about our dogs, we can just go to our dog and change one of its variables. Just to make it clear, `daisy` is an object variable which holds 3 variables inside of it: name, daet and health. And so are the other 2 dogs.

If you want to use a certain dog, you just get it like you learned it:
`let mydog = dogs[1]`
`alert(mydog.name + " visited the vet on " + mydog.date + " and they were " + mydog.health)`
If we change 1 to 2, we can clearly see this changes. When JS finds `dogs[1]`, it looks and ses that it's this `harold` variable so it replaces `dogs[1]` with `harold`, and then it looks to see what `harold` represents, and so it replaces `harold` with our object.

In fact, we don't even need to use another `mydog` variable - we can just use the dog from the array directly:
`alert( dogs[0].name )`
Again, JS sees `dogs[0]`, replaces it with `daisy`, and then it's like saying `daisy.name`.

If you have a keen eye, you'll think: hold on, is `daisy` actually also replaced with this whole thing [select the daisy object] and, my friend, yes, that's right.
Just to prove it to you, instead of `alert( daisy.name )` you can copy this [daisy object code] and paste it in here instead of `daisy` aaand... voila.
This looks bad, don't do it like this, but now you know it works

We can further organize our dogs in this way: so we have our dogs array...
`let dogs = [daisy, harold, winnie]`
And instead of these variables, we can just take these code pieces and put them in place...
`let dogs = [{
	name: "Daisy",
	date: "20 Jan 2023",
	health: "Healthy"
}, harold, winnie]`
And again...
`let dogs = [
	{
		name: "Daisy",
		date: "20 Jan 2023",
		health: "Healthy"
	},
	{
		name: "Harold",
		date: "23 Jan 2023",
		health: "Recovering"
	},
	{
		name: "Winnie",
		date: "17 Feb 2023",
		health: "Healthy"
	}
]`
Remember that spaces don't matter, so you can align this code however you like [say this while putting some tabs] 
Oh and don't forget these little commas between the objects, very important...


Aand voila!
Do you know what this is? Do you know what you just made?
This... is a database. This is what real life JavaScript databases look like. Just like this. the databases of Uber, Netflix, Forbes, Linkedin they all have their data stored like this. Sure, some have their data stored like Excel spreadsheets, but some do it like this.

And I know what you're thinking: Dave, this is sooo much code, I have to write so much more just to be more organized? Can't I make just 3 arrays, one with name, one with date and one with health? And I say yes, it is more code, but believe me, it's worth it. Especially when you're working with more data in a real project. Yeah they take more space, but they're also easy to work with directly in JavaScript. And that's why all these big companies have their databases stored as JS Objects. If you literally open up the databases of these companies like Netflix and Uber and all, you'll see something like this.

What you're seeing here is called JSON, which comes from JavaScript Object Notation. And it's so widely used that other languages have added ways to work with JSON objects directly inside the language, like Python and C++.
JavaScript is king, JavaScript is chad.

Of course, there are drawbacks to writing them manually like this, and in reality, you will not do it manually and we'll get to that a bit later. You might type in something wrong, for example, and it's simply a lot more to write. So in real life, you won't write them manually one by one.  We'll get to that later. Either way, you will still use objects. Objects are the building blocks of organizing code and organizing data.

I know you have more questions - I'll answer them in the next lessons.

## Objects Continued
Welcome back! Let's continue our lessons on Objects!

`let dog = {
	name: "Daisy",
	date: "20 Jan 2023"
}`

We have our dog object variable here. And just like you'd imagine, you can change the name and date of the dog:
`dog.name = "Goonter"`
This will work, because it's just like changing a variable.


I think you remember this `window.location.href` and you're probably wondering: is `href` a variable inside the `location` object, which is a variable inside the `window` object?
You're right, that's exactly what it is!

What we can do is make objects inside objects!
Again, let's say each dog has an owner, who has a car and an age.
What we could do is hold them like this:
`let dog = {
	name: "Daisy",
	date: "20 Jan 2023",
	ownerage: 25,
	ownercar: "Toyota"
}`
But let's make it prettier, more well organized!
`let dog = {
	name: "Daisy",
	date: "20 Jan 2023",
	owner: {
		car: "Toyota",
		age: 25
	}
}`
So, `car` is a variable inside `owner` which is a variable inside `dog`
Let's alert the car of our dog. Try to do this ahead, you can pause the video and alert the car.
`alert( dog.owner.car )`

## Objects - FAQ and Homework
1. Do spaces and tabs matter? No, they don't. If you have your dog:
`let dog = {
	name: "Daisy",
	date: "20 Jan 2023"
}`
You can just write it as:
`let dog = {name: "Daisy", date: "20 Jan 2023"}`
And remove the spaces or add any number of spaces...
What's important to remember is the format of it: the brackets, the colon and the comma between variables

2. Can I use other variables inside objects?
Sure!
`let dogname = "Daisy"
let dog = {
	name: dogname,
	date: "20 Jan 2023"
}`
Hey, if you really want, you could even call this `name` instead of `dogname` and it will still work.
JavaScript is smart enough to understand what you mean when doing this, but, again, if something is ambiguous, you should probably avoid it.

4. Not really a question, but a term: making an object inside another object is called "nesting". And an object inside another object is called a "nested" object.

5. Can I put an object inside another objects inside another object?
Yes! That's the whole idea! You can put objects inside other objects as many times as you want. You can have an object inside an object inside an object inside an object if you so choose to.

6. What happens if I try to use a variable that doesn't exist inside another variable?
It won't work, you'll get "undefined" which is an error essentially.

7. Can I create a variable inside another variable even if it didn't exist before?
You can do that if you want, but it's not recommended.
`let dog = {
	name: "Daisy",
	date: "20 Jan 2023"
}`
You can add a `health` to `dog` by saying `dog.health = "Healthy"`, and now you can alert this.
But, again, you should not do that because it's not clear. Though if you like it, feel free to use it.

**Homework**: As a homework, I want you to create an object for a laptop. Just create it in JavaScript, like our dog.
The object has a name and a price, and it has components like a CPU, which also has a name and a frequency, a GPU which has a memory and a frequency as well and a name, etc. I want you to think of all things a laptop has and make an object with inside objects as big as possible and write it in the comments section. Remember you can put objects inside other objects as many times as you want. You can have an object inside an object inside an object inside an object if you so choose to.

## Objects, functions and variables
Alright let me show you something.
Let's say we have a function that takes a number and returns it multiplied by 10.
`function timesten(x) {
	return x * 10
}`
As a reminder, whenever the program will see `timesten(something)`, it will replace this whole thing with `something * 10`

Here's a cool thing you can do: you can make a variable and make it equal to a function:
`let t = timesten`
And now you can do `alert( t(7) )` which is exactly the same as `alert( timesten(7) )`

I think you can see where this is going, as we're still at the objects lesson. You can have variables inside objects be functions!
`let math = {
	t: timesten
}`
And now you can do `alert( math.t(7) )` and it will work exactly like you expected!

In fact, let me show you something cool: JavaScript already has a Math object with a lot of cool functions.
For example, you can use `Math.floor(number)` which is going to take that number and cut away its decimals.
`alert( Math.floor(4.20) )` this should print out 4.
Capital M, very important.
And Math has a lot of other useful functions as well. Basically anything you can think of that has to do with numbers, Math has it. We can get more into that later or if you have any questions about it, feel free to address them in the comments and I'll answer!

Another thing I want to show you is that you don't necessarily need to create the function separately, outside of the object.
You can make the function directly inside the object, like this:
`let math = {
	timesten: function(something) {
		return something * 10
	}
}`
So they are basically the same, but the name is here instead of after function.
There's no difference between doing it like this and making the function outside of the object and then doing it like we did before.
Doing it like _this_ can be helpful because you define fewer variables and that might make your code cleaner.

## Objects: some clarifications
`let name = "Dave"
let dog = {
	name: "Lego",
	age: 2
}`
You might be wondering: Hey, what happens if I have a variable called "name" outside of an object and also inside the object?
This will work perfectly fine, since they're essentially different variables. There's never a situation in which JavaScript doesn't know which variable to use. This `name` is always used as just `name` and this `name` is always used as `dog.name`.
But, again, and I mentioned this previously, if 2 variables have the same name, they can cause confusion, so it's best avoided.

## Objects: the shocking truth
In this lesson, you're going to have a revelation about objects and variables in general. I've used certain words in this course before that weren't quiet accurate, just to get you used to programming. This is very very important so pay close attention.

Alright, let me show you.
Let's say we have a dog object from earlier:
`let lego = {
	name: "Lego",
	age: 2,
	weight: 9
}`
And then we want to make another dog.
`let winnie = {
	name: "Winnie",
	age: 2,
	weight: 9
}`

So then maybe you're thinking: Hey, these 2 objects are quite similar. Both of them have the same age and the same weight.
Couldn't we just say...
`let winnie = lego
winnie.name = "Winnie"`
Because when you set a variable to another variable, it makes a copy right? Right?
That's what some people might think intuitively, but no, it actually does not work.

If we run this and `alert( winnie.name )` it seems fine, but if we also `alert( lego.name )` we see it's also Winnie, which might sound strange but here is why that happens.

In our first lesson on Variables, the first thing I told you was that if we have a variable called:
`let myvar = 25`
`myvar` essentially becomes an alias for the number `25`. So yes, when JS sees `myvar` it replaces it with `25`.

So we have `lego` = this object right here.
What happens is `lego` becomes an alias for this object right here.
Let me say that again: `lego` is an alias for THIS exact object. Not an object that looks like it, not a copy/pasted object that looks like this, but this EXACT object here. Right here. This object.
When you use `lego`, `lego` is NOT actually replaced with the code here. JS does NOT just copy/paste this code instead of `lego`. Instead, it uses THIS object.

Let me show you.
If you say `lego.name = "Big Lego Boy"`, `lego` refers to THIS object right here.
So it's like saying THIS object right here `.name = "Big Lego Boy"`.
It does NOT copy paste this into `lego`, but it actually uses THIS object directly.
So, again, `lego` is an alias for THIS object right here.


So when you say `let winnie = lego`, `weenie` becomes an alias for `lego`, which is an alias for THIS object, so then `weenie` becomes an alias for THIS object as well. It does NOT become a copy of `lego`.

Let's take a very similar example to what we did in our first lesson on Variables - back to basics.
`let dave = {
	name: "Dave",
	age: 25
}
let teacher = dave
let friend = teacher`
So, in this example, `friend` is an alias for `teacher`, then `teacher` is an alias for `dave` and finally `dave` is this object right here [select it]. This exact object, right here. So `friend` becomes ALSO an alias for this object right here.
Yes, teacher is the same object here, and friend is also the same object here.
Yes you have 3 variables that are aliases for the SAME object. Not copies, but the ACTUAL same object.

Ok? So NOT copy. Ok? Never copy! Alias yes, copy no!
And this applies to all variables! When you set a variable equal to another variable, that **ALWAYS** means it's just another name for that variable's value.

JavaScript **NEVER** actually copies a variable's value into another variable. It NEVER does actual copy/paste. If you use `friend`, it uses this EXACT object [select it]. Not a copy of it, but the EXACT object here.


If you have an array:
`let dogs = ["Daisy", "Lego", "Winnie"]`
And make another variable `let cats = dogs`, `cats` is just an alias for `["Daisy", "Lego", "Winnie"]`. It's not a different variable that's a copy, it's **the same array**, but with another name.

`let God = {
	powerlevel: 9999999999
}
let Allah = God`
Kind of like how Christians and Muslims use different words for the same entity: Christians call it God, Muslims call it Allah, but it's the same. They're just 2 names for the same thing.

I can't stress this enough!! This is very important, please remember this. Alias. Alias. Another word. Different words, same meaning. Different names, same object. Never copy paster! Never! Extremely important.

## Objects: ...but seriously, this is important
Listen, I know exactly what you're going to ask next.
Looking at the previous example with the teacher:
`let dave = {
	name: "Dave",
	age: 25
}
let teacher = dave
let friend = teacher`

So Dave, I understand, `friend` is an alias for `teacher` and `teacher` is an alias for `dave` and `dave` is this object right here, so then `friend` is just an alias for this exact object.

So what happens if I change `dave` to something else?
`dave = {
	weight: 100
}`

Well, let's follow the logical steps of this. Let's go line by line through this code:
`friend` is an alias for `teacher` and `teacher` is an alias for `dave` and `dave` is this object right here, so then `friend` is just an alias for this exact object.
So, so far, `friend` is `{ name: Dave, ...}`.
Ok then `dave` becomes a new object right here. `dave` is now THIS exact object.
`friend` doesn't change. `friend` remains THIS object. Doesn't change. Why would it?



Let's take another look at functions.
We have our dog right here:
`let lego = {
	name: 'Lego',
	age: 1
}
let winnie = {
	name: 'Winnie',
	age: 7
}`

Question is: can we make a function that increases a dog's age by 1?
`function increaseage(dog) {
	dog.age = dog.age + 1
}`

Now we say:
`increaseage(lego)
alert(lego.age)`

And we see that this worked!
Now, my quesiton for you is: do you understand why this works?
Let's take a look!

So we created our dogs, simple objects.
Then we make a function that DOES something. This function doesn't have a `return` keyword, so it's a function that DOES something.
If you remember from our functions lesson, when we say `increaseage(lego)`, the code goes up to the function and continues from there, inside the curly braces.
We say `increaseage(lego)`, code goes up here, makes this `dog` variable here = to `lego`. So, `dog` up here will be an alias for `lego`.
Now, again, `lego` refers to THIS object right here.
Then `dog` refers to `lego` which is THIS object right here, so `dog` will now ALSO be this object right here. Not a copy of it, but THIS exact object. Both `dog` and `lego` are names for this object. Same object.
So now, inside the function, `dog` is actually this object, so it takes the `age` variable inside the object and will increase it by 1.
The function is finished, no more lines of code inside the braces, so the code returns to where it was.
It now does `alert(lego.age)` and voila, lego has changed!

So, again, note that when we call `increaseage(lego)` and JS goes inside this function, `dog` refers to THIS object. So it it modifies the variables inside THIS object.

Always, always follow the trail of variables to see which object is actually modified.

Conclusion: ALWAYS alias, NEVER copy.

TODO: Homework

## Objects: Less copy paste
In a previous lesson, we talked about how much code it takes to write a whole database by hand.
We had our cute dogs:
`let daisy = {
	name: "Daisy",
	date: "20 Jan 2023",
	health: "Healthy"
}
let harold = {
	name: "Harold",
	date: "23 Jan 2023",
	health: "Recovering"
}
let winnie = {
	name: "Winnie",
	date: "17 Feb 2023",
	health: "Healthy"
}`
Like we talked, it indeed is a lot of code, especially if you write it by hand.
So I will show you a way to do it with less code using a function!
I think you might already be guessing how we do that, but let me explain: we can make a function that returns a dog object.

Here's how we do that:
Let's make a function called `createdog`:
`function createdog()`
Our dogs have a name, a date and a health status. So, our function should take a name, date and health as parameters:
`function createdog(dogname, dogdate, doghealth) {
	...
}`
So what do we do? We return a dog object!
`function createdog(dogname, dogdate, doghealth) {
	let dog = {
		name: dogname,
		date: dogdate,
		health: doghealth
	}
	return dog
}`
We have a function that RETURNS something. It takes in a dogname, dogdate and doghealth and quote-unquote _transforms_ them into an object!
A function that creates and returns an object is called a "factory function". You don't need to remember this name, but it's good to know what they're called.

So now, we can write our dogs like this:
`let daisy = createdog("Daisy", "20 Jan 2023", "Healthy")
let harold = createdog("Harold", "23 Jan 2023", "Recovering")
let winnie = createdog("Winnie", "17 Feb 2023", "Healthy")`

Looks weird? Let's unpack this.
We can take this step by step: JS finds `createdog`. It goes up here, makes `dogname` equal to `"Daisy"`, makes `dogdate` equal to "20 Jan 2023" and makes `doghealth` equal to "Healthy".
Then, it creates our dog object with the name as dogname, date as dogdate and health as doghealth and returns it.
So, when JS sees `createdog("Daisy", "20 Jan 2023", "Healthy")`, it will replace all of this thing with the object we just created, our new `dog`.
So, it makes `daisy` equal to `dog`, which means it makes `daisy` equal to this object right here.

And I know what you're thinking: Dave, you said variables are always the same object. This looks strange to have an object inside a function and use it 3 times. Doesn't that just modify an object or return the same object or something like that?
And my answer is no. And if we go through this step by step, you will see exactly why.
So first, it finds `createdog`, goes up to the function and goes line by line through the function's code.
It creates a dog object, returns it, goes out of the function, replaces this whole `createdog` this with our new `dog` here, which is just another name for this object here [select it].
So, `daisy` will be this object here.

Here's where the tricky part is:
Whenever we use `createdog`, everything inside the function is new!
Yes it creates the `dog` object, and the second time you use `createdog`, this object HERE is a different object!
Because imagine this: the function's code is as if it continues the code from where it was used:
`let daisy = .... something something
...{
	let dog = {
		name: dogname,
		date: dogdate,
		health: doghealth
	}
	return dog
}`
Ok then we have harold, so it goes like:
`let harold = createdog...`
Sees create dog, and it's as if the function's code continues just here:
`let harold = .... something something
...{
	let dog = {
		name: dogname,
		date: dogdate,
		health: doghealth
	}
	return dog
}`
See that? Every time we use a function, it's as if we're talking about brand new code. When we say `let dog`, we create a new variable called dog that's equal to a new object!

[Ctrl-Z to the new nice dogs].

So, doing it like this is going to be how you take care of making new objects in a more controlled and faster way.

## Objects: Factory Functions Continued
In the previous lesson we learned how to write less code to create objects.
I mentioned that making a function that creates an object is called a factory function.

These are good for multiple reasons, such as if you need to calculate things when you create the object or add extra variables inside your objects.

`let daisy = createdog("Daisy", "20 Jan 2023", "Healthy")
let harold = createdog("Harold", "23 Jan 2023", "Recovering")
let winnie = createdog("Winnie", "17 Feb 2023", "Healthy")`

Let me show you what I mean:
Maybe we want that whenever we create a dog, it automatically adds another variable to the object called `timesvisited` which is always 1 at the beginning, and maybe we want to modify it in the future.
We can easily just add this to our object!

`function createdog(dogname, dogdate, doghealth) {
	let dog = {
		name: dogname,
		date: dogdate,
		health: doghealth,
		timesvisited: 1
	}
	return dog
}`
Let's console.log one of the dogs to see if it works:
`console.log(harold)`
As you can see, here it is!

Great! Now what if we don't want to manually put in the date every time we create a dog? What if we want to automatically get the current date?
We can do that!
So first, let's rmeove the dogdate parameter:
`function createdog(dogname, doghealth) {
	let dog = {
		name: dogname,
		date: dogdate,
		health: doghealth,
		timesvisited: 1
	}
	return dog
}`
And instead of `dogdate` we use something directly from JavaScript that gives us our date right now!
It looks a bit weird, you don't have to understand it, this is just the way it is:
`date: new Date().toString()`

So now we also remove the dates...
`let daisy = createdog("Daisy", "Healthy")
let harold = createdog("Harold", "Recovering")
let winnie = createdog("Winnie", "Healthy")`

Let's console.log one of the dogs to see if it works:
`console.log(harold)`
Great!

Now, we might make a mistake writing "Healthy" or "Recovering" every time, so instead, let's just make it a boolean variable, called `ishealthy` that only takes `true` or `false`
`function createdog(dogname, ishealthy) {
	let doghealth
	if (ishealthy === true) {
		doghealth = "Healthy"
	} else {
		doghealth = "Recovering"
	}
	let dog = {
		name: dogname,
		date: new Date().toString(),
		health: doghealth,
		timesvisited: 1
	}
	return dog
}`
So now our dogs look like this:
`let daisy = createdog("Daisy", true)
let harold = createdog("Harold", false)
let winnie = createdog("Winnie", true)`
So remember from our booleans lesson, a boolean only has true or false as values.

This, my friends, is the power of functions once again!

Homework: We are making an app for a university that keeps track of students that just finished this year.
Each student is an object.
I want you to write the code, just like we did with dogs, for several students. Each student has:
- a name
- a final score that goes from 1 to 10
- a "didgraduate" variable that is true only if the finals core is 5 or more
- a sum they have to pay, which is between $500 to $5000, depending on their final score. The lower the score, the more they have to pay
- and a favorite subject
I want you to use a factory function to create the students. You will also need to use ifs and overall you will have something similar to what we had with dogs.
Make this for the following students:
- Jesse Black, 4.5 final score, likes Math
- Rodney Red, 9.65 final score, likes English
- Tommy Tin, unknown final score, likes Computer Science

## Objects: Classes 
This lesson is optional. If you feel like you've had enough of objects, you can feel free to skip this one.
But in this lesson, I will show you something that all programming languages have and it's a "standard" way to make objects.
Maybe you've heard of the term Object-Oriented Programming or OOP and maybe you've heard of Classes. I'll show you these things in this lesson.
Feel free to chill, you don't need to memorize these things, but it's good for you to have a taste of classes.

`function createdog(dogname, dogdate, doghealth) {
	let dog = {
		name: dogname,
		date: dogdate,
		health: doghealth
	}
	return dog
}
let daisy = createdog("Daisy", "20 Jan 2023", "Healthy")
let harold = createdog("Harold", "23 Jan 2023", "Recovering")
let winnie = createdog("Winnie", "17 Feb 2023", "Healthy")`
So let's get back to our simple dogs we had before.
This way to do it works great! Especially in JavaScript.
There is one more way to do it though. Instead of making a function that returns an object, we can make a class.

For simplicity's sake, let's remove some of these parameters just to make all of this easier to understand:
`function createdog(dogname) {
	let dog = {
		name: dogname,
		health: "Healthy"
	}
	return dog
}
let daisy = createdog("Daisy")
let harold = createdog("Harold")
let winnie = createdog("Winnie")`

Let's recreate this function as a class:
`class Dog {
}`
For starters, let's just give it a health that's always "Healthy"
`class Dog {
	health = "Healthy"
}`
So what is a class? A class is just a template. A class is NOT a function, it's something else.
So how do we create a dog from this?
Like this:
`let daisy = new Dog()`
`console.log(daisy)`
And just to show you this is just a normal object, we can just cnsole.log daisy.health:
`console.log(daisy.health)`

So as you can see, we now have a dog that's just like writing it as `let daisy = { health: "Healthy" }`.
NOTE: Notice the uppercase D, the big D here. Class names always start with an uppercase letter.
There isn't really anything else to explain: this `new` keyword right here is just the way you create objects from classes. There's really nothing else to it, that's just how it works, and it is for the most part, the exact equivalent of using a factory function.

Now let's give it a name:
`class Dog {
	name
	health = "Healthy"
}`
Now, at the start, this name has no value. If we console.log our `daisy`, it says `undefined`.
To give it a value, we must make a `constructor`:
`class Dog {
	name
	health = "Healthy"
	//
	constructor(dogname) {
		this.name = dogname
	}
}`
And to give it the name, we must put the parameters near Dog right here as if it were a function:
`let daisy = new Dog("Daisy")`
`console.log(daisy)`

There isn't really much to it to explain. This is just the way it is.
In the constructor, you put some parameters and then you can set the variables inside that specific dog using `this`.
The keyword `this` refers to, well, this object that you're just creating through the constructor.

Let's now make it so that we also add the health of the dog through a parameter:
`class Dog {
	name
	health = "Healthy"
	//
	constructor(dogname, doghealth) {
		this.name = dogname
		this.health = doghealth
	}
}`
`let daisy = new Dog("Daisy", "Healthy")`
`console.log(daisy)`

And finally, let's add the date as well.
I want you to do this. We will have the code down here like
`let daisy = new Dog("Daisy", "20 Jan 2025", "Healthy")`
And I want you to pause the video and see if you can add a date to the dog template as well and set it through the constructor.

So, in the end, we have our objects like in our previous lesson:
`let daisy = new Dog("Daisy", "20 Jan 2023", "Healthy")
let harold = new Dog("Harold", "23 Jan 2023", "Recovering")
let winnie = new Dog("Winnie", "17 Feb 2023", "Healthy")`

There are some advantages to doing it like this, with classes instead of factory functions, but honestly, it's not worth explaining. This is generally useful for people coming from other languages like Java or C++ and trying to learn JavaScript, because this is how you do it in other languages by default.

And now I think you remember how to get the current date from the previous lesson:
`...date: new Date().toString()`
Yeah, here you are making a date object from the Date class and then calling a function from inside it!





## Objects: Method Functions
In programming, we use objects and functions to help us organize our code very very well.
Imagine we have an online banking application. Let's say you have a few objects that hold information about someone's bank account, like how many dollars they have and how much debt they have.
`let john = {
	fullName: "John Holt",
	dollars: 420,
	debt: 0
}`
`let peter = {
	fullName: "Peter Tosh",
	dollars: 35,
	debt: 0
}
let dennis = {
	fullName: "Dennis Brown",
	dollars: 12500,
	debt: 1700,
}`

Firstly, let's convert these plain objects to objects created with a factory function.
I want you to pause the video here and do it for these, just like we did in the previous lesson with the factory functions.
Just be careful, this is a capital N here.

Your function should look something like this:
`function createbankaccount(persondollars, personDebt, personfullname) {
}`
Now, we're starting to notice how hard it is to read things.
Let's make each word start with capital letter, except the first letter of each word.
`function createBankAccount(personFullName, personDollars, personDebt) {
}`
Look at that! Do you think that's easier to read? Let me know in the comments.
I know it might look a bit weird, but trust me, this is how JavaScript names should be.
Let's make the rest of the function:
`function createBankAccount(personFullName, personDollars, personDebt) {
	let person = {
		fullName: personFullName,
		dollars: personDollars,
		debt: personDebt
	}
	return person
}`
`let john = createBankAccount("John Holt", 420, 0)
let peter = createBankAccount("Peter Tosh", 35, 0)
let dennis = createBankAccount("Dennis Brown", 12500, 1700)`

Let's create a function that makes a person borrow some money from the bank.
When a person borrows a sum of money from the bank, it instantly goes to their dollars in the account, and their debt increases by 110% of the sum.
So, a function that takes the person as the first parameter, and the amount of money as the next parameter.

`function borrowMoney(person, amount) {
	person.dollars = person.dollars + amount
	person.debt = person.debt + 1.10 * amount
}`

Let's check if this works:
`borrowMoney(peter, 400)
console.log(peter)`

Good! So all works like it should and this looks pretty nice. But can we make it even nicer?
What if we put the borrowMoney function inside the person object? Kind of like the math object we talked about some lessons ago?
Maybe it would be really cool if, instead of saying `borrowMoney(peter, 400)` we could say `peter.borrowMoney(400)`

Let's try it out:
`function createBankAccount(personFullName, personDollars, personDebt) {
	let person = {
		fullName: personFullName,
		dollars: personDollars,
		debt: personDebt,
		//
		borrowMoney: function(amount) {
			//
		}
	}
	return person
}`
Remember this? We talked about functions inside objects a while ago, but now we can use them to their full strength.
Let's contiue implementing this function!
Try to pause the video and do it yourself, or do it at the same time with me.
Don't copy/paste from the other version of the function, write it manually.

Well, there isn't much else to change from our previous version! It's pretty much the same!
`function createBankAccount(personFullName, personDollars, personDebt) {
	let person = {
		fullName: personFullName,
		dollars: personDollars,
		debt: personDebt,
		//
		borrowMoney: function(amount) {
			person.dollars = person.dollars + amount
			person.debt = person.debt + 1.10 * amount
		}
	}
	return person
}`

Let's test it...
`peter.borrowMoney(400)
console.log(peter)`
Awesome!

Let's add another function.
We want to see how much money a person has in Japanese Yen.
We want to make a method function called "moneyInYen()" that returns us the amount of money in the person's bank account, but in Japanese Yen instead of dollars.
Pause the video here, try to do it yourself, and come back

`moneyInYen: function()` (takes no parameters)
`moneyInYen: function() {
	return person.dollars * 132.13
}`

So now we can do something like `console.log(dennis.moneyInYen())`
Great!
Just to be clear, when JS sees `dennis.moneyInYen()`, it replaces it with `person.dollars * 132.13`. But `person` here is actually `dennis`, so it returns `dennis.dollars * 132.13`; and `dennis.dollars` is actually 12500. So then it does the math and all is great!

#### HOMEWORK
I will leave a homework for you to continue the code that we're writing.
I want you to add another method function to a person's bank account object, that transfers money from one person to another.
You should be able to write `peter.sendTo(dennis, 200)` and this should work.
First step is, naturally, this takes away from the money of the sender, and gives that money to the other person.
Second step is, if the person doesn't have enough money to send, it sends all the money he has and then his debt [select debt] increases by the missing sum of money. Makes sense? Money you don't have goes into debt.
You'll have to use some ifs and elses and some 4th grade math.
Try your best and I'll see you in the next lesson!

## Objects: "this" (optional)
So we have our code for creating bank accounts:
`function createBankAccount(personFullName, personDollars, personDebt) {
	let person = {
		fullName: personFullName,
		dollars: personDollars,
		debt: personDebt,
		borrowMoney: function(amount) {
			person.dollars = person.dollars + amount
			person.debt = person.debt + 1.10 * amount
		}
	}
	return person
}`

See there's a way to simplify this even further. What we could do is not even put the object into this `person` variable, and just return the object directly!
Let's try that!
`function createBankAccount(personFullName, personDollars, personDebt) {
	return {
		fullName: personFullName,
		dollars: personDollars,
		debt: personDebt,
		borrowMoney: function(amount) {
			person.dollars = person.dollars + amount
			person.debt = person.debt + 1.10 * amount
		}
	}
}`

But now we see a problem. Do you spot the problem? Try to spot the problem with this code.
Dave, this `person` here doesn't exist anymore! This won't work!
Exactly! That's a problem!
Thankfully, in JavaScript there exists a special keyword we can use instead of `person`. The keyword is `this` [type it].

`function createBankAccount(personFullName, personDollars, personDebt) {
	return {
		fullName: personFullName,
		dollars: personDollars,
		debt: personDebt,
		borrowMoney: function(amount) {
			this.dollars = this.dollars + amount
			this.debt = this.debt + 1.10 * amount
		}
	}
}`
The keyword `this` refers to THIS object. `this` always refers to the object it is used inside.
You can't use `this` outside of an object. You can't just go here and say `this`. You also can't use it outside of a function. It's a very specialized word that always refers to the object it is used in.
And now this is how you get rid of some code. It might seem a bit weird at first, but once you get used to it, you'll start using it more, because you know `this` always refers to the object it is inside. In other cases, if you say `person` or `dog` you will have to look up here and check "hmm where does this `person` variable come from?".

The cleaner your code is, the better. And trust me, when you work on larger projects, you will write some code, completely forget what it does, and if you wrote it poorly, you'll be like "What the hell does this code even do?". This happens to everyone at first. You should clean your code as much as you can. It's very important for real life work.

That being said and done, congratulations!
That's all with objects!
Now, you know the fundamentals of JavaScript and YOU ARE INFINITELY POWERFUL!
This was the hardest part, by far. From now on, the rest is smooth sailing.




## Misc: Strings
In the next few lessons I will just show you a few useful functions that are built-into JavaScript, already made, that you can use to ease your work.

So, as we saw earlier, strings are just text. 
In many applications and programs, there are many calculations with strings.

And let's do an exercise just to show you all the cool things you can do with strings.
When you create a new account on a website, for example Netflix, it will not allow you to make a password fewer than 8 characters, and it must contain at least 1 uppercase letter, 1 lowercase letter, 1 number and 1 symbol. And you might be thinking "how on earth do you check all those things?".
We will learn that in this lesson and that's gonna be this lesson's project.


Let's setup a small program that asks the user for a password and the first name:

	let firstName = prompt()
	let password = prompt()

Ok, let's lay out our conditions for the project [write these as comments]:
- password must contain at least one `*` (star)
- first name will be transformed into ALL CAPS
- password can't start with exactly the first name (e.g. "DAVE" and "DAVE1234" - this is not valid)
- if first name contains spaces, the spaces will be replaced with underscores ('_')

If there is a problem with the password or the name, we will alert to the user that the password or name is not valid:
First things first, let's make a function that checks these things, just to practice functions:

	function checkNameAndPassword() {}

We will call this function after we read firstName and password:

	checkNameAndPassword()

Now we will go through the requirements one by one and add a check for each.

## Strings: "includes" method
The first check we need to make is to make sure the password contains at least one star [select that requirement]. If the password contains no stars, we will alert a message on the screen.

Let me show you a trick, and that's with a function from JS, called "includes".
Let's say we have our password as:	(separately)
`let password = "davedoublee123"`

And let's say we want to save in a variable that's true if the password contains one or more stars and false if it doesn't.

`let doesPasswordContainStar` (this will only be true or false)
With only the knowledge you have so far, I want you to think of how you would do this. The final value of `doesPasswordContainStar` should be either true or false. How would you do this? Pause the video and think about it. You don't need to write the code, just think about it.

There's an easy way to do this.
We can do this with the "includes" function.

`let doesPasswordContainStar= password.includes('*')`

Now, `includes` is a function inside our password variable. And all strings have the `includes` function inside of them. So when you use `password.includes(something)`, you use the `includes()` function from the `password` string with the argument `something`.
Yes, strings are also objects in a sense. They're special objects, cause, you know, they're text, but they do have other variables and functions inside of them, just like objects!
And when JS sees this, it calculates it and replaces it with either `true` or `false`

If it looks strange, look at it this way: this reads like English:
`password includes ' '`

Let's check this indeed works [check].
Now let's input a password without spaces: "davedoublee123" and yep, this will be false.


It is worth nothing that this function does NOT change the original string. It simply gives you another value which is either true or false.
Like in our example with bank account objects, our moneyInYen function does not change the bank account. It merely returns something about it without changing it.

Let's write the code for our password check!

`let firstName = prompt()
let password = prompt()`

`function checkNameAndPassword() {
	let doesPasswordContainStar = password.includes('*')
	if (doesPasswordContainStar === false) {
		alert("Password must contain a star!")
	}
}`



Q: Can you check entire words or sentences or long strings?
A: Sure you can!

	let sentence = "I like dogs a lot."
	if (sentence.includes('dog'))
		alert('Yes, it contains a dog')

Notice that it doesn't matter if it's the whole word or if there is anything before and after it. The function simply finds this part [select it in the sentence] and if it finds it, then it returns true.


## Strings: toUpperCase method
Next, we need to transform our first name into ALL CAPS!
This means that if I type "Dave" in our first prompt here [do that], it should be transformed into "DAVE", all capital letters.
We're in luck, because JS has exactly that already made!

After we read our name with promps, we can just change firstname to be:
`firstName = firstName.toUpperCase()`
When JS sees firstName.toUpperCase(), it replaces this thing with, well, its version but in all caps!
Careful with this big U and big C! Very important!

Let's console.log it so we see it!
Great!

[Open a new tab, clean code]
Ok, with that out of the way, now you might have some questions about `toUpperCase()` and I will try to answer them, but I want you to guess in your mind what you think it does and let me know in the comments sections how many answers to these questions you got right with your intuition!
	1. What happens if you use `toUpperCase()` on a string that is already upper case:
		- Let's try it out!
		- `let myString = 'HELLO'`
		- `alert(myString.toUpperCase())`
		- So... nothing happens! Next question
	2. What happens if you use `toUpperCase()` on a string that has some upper case letters and some lower case?
		- Let's try!
		- `let myString = 'jEtFuElCanTmElTStEeLBeAmS'`
		- `alert(myString.toUpperCase())`
		- So we see that it makes all
	3. What happens if you use `toUpperCase()` on a string that has some numbers or symbols in it?
		- Let's see!
		- `let myString = "71)&#!927309@&#)(*)"`
		- `alert(myString.toUpperCase())`
		- Soo... nothing. But if we have some letters there...
		- `let myString = "71)&#!9aaa27309erar@&#)(*)"`
		- We will see that all letters are made upper case.
	4. Can you call string methods directly from strings? Like
	-	`"crocodile".toUpperCase()"`
	-	Yes, absolutely! This works!
	-	In fact, remember when we said that `lowerCroc = "crocodile"`, wherever JS sees this lowerCroc variable used, it replaces it with `"crocodile"`.
	- If you have any more questions, please do leave them in the comments section and I will do my best to answer them!

Homework: what if we wanted to convert it to lower case? Do you have an idea how we would do that? Hint: we use a different function and yes you are allowed to google it. Post your answer in the comment section!

## Strings: startsWith
[Clean code]
Remember how in the past we checked if a string was a correct URL for a website?
We checked every letter one by one, letter 0, letter 1, letter 2, etc
Thankfully, there's a much easier way to do this!

`let password = "dog123465"`
`if (password.startsWith("dog")) {
	alert("Password starts with dog!")
}`

Quite simple! JS sees this [select it] and replaces it with either `true` or `false`.
Note that it does not work if we say here DOG. It checks exactly the letters, exactly uppercase or lowercase letters!
Also careful with this capital W [select it].

Going back to our code, let's make this happen with our password and first name!
`...
	if (password.startsWith(firstName)) {
		alert("Password can't start with your first name!")
	}
...`

Of course, there's also an `endsWith` function. But i'll let you do that in the homework.
So make another check just like this one where you check if the password _ends_ with the first name.
Try not to copy/paste code, and try to write it manually.


## Strings: replaceAll
Let's recap what our next check should do: if first name contains spaces, the spaces will be replaced with underscores ('_')

[clean code]
Let's suppose I am Korean and my first name name is "Ju Won". Therefore my first name contains a space.
`let firstName = "Ju Won"`
Let's change firstName to have underscores instead of spaces!
`firstName = firstName.replaceAll(" ", "_")`
`console.log(firstName)`

This worked!
Great!
Let's return to our password and check if this works!

I merely wanted to show you the most useful things you can do with strings.
If you want to see everything that strings can do, you can search on bing "javascript string methods" and click on one of the links, especially this one from w3schools.
It will show you all the method functions strings have! All with examples!

## JS is Done. What's next?
You're done! You're ready for the next chapter of this course and it's great!
You already learned the hardest part. The upcoming parts will be easy peasy.

In the next chapter, I will teach you HTML, zero to hero, all you need to know, which is really really easy and it's a very short chapter.
Following that, I will teach you CSS, which is also very easy, but sometimes annoying to work with. Don't worry about what these mean, you'll see.


# HTML

## What is HTML?
Let's jump straight in to HTML.
What is HTML? HTML is just another language, which you use to make websites.
All websites you see online, even this one you're watching the course on, are made with HTML.
With HTML, you make **boxes**, **images**, **text** and other similar things.
Later on we will learn CSS, which allows us to change colors, fonts, etc.

Let's take a look at exactly a website: https://brittanychiang.com/, this is a very nice website.

So, let's take a look at the various elements we have on the page.
This website is made with HTML and CSS.
This text here, this is HTML. So is this text, and these buttons up here, and so on.
What makes this text green, though, is CSS. It's also CSS that says "hey, this box should be about 70% of the whole width of the page".

Let's jump into it: how do we make a website?

First off, make a new folder on your PC. Yes, this time we will actually make it on our own PC.
In that folder, Right Click > New > Text Document.
Open it up and now, very importantly, go to File > Save As > change "Save as type" to All Files, and name it mywebpage.html.
VERY IMPORTANT - make sure it's not `.txt`, but `.html`

Now, we have our website file! We can open this in the browser, in Google Chrome or Edge or Firefox or whatever browser we're using! I recommend Google Chrome.
Double click on it... aand voila! We have a website!
Well, it's blank because there's nothing inside, but we'll add a few things.

You can now delete the `New Text Document.txt` and, if you want to open this again to edit, just right click it > Open With > Choose Another App and find Notepad.
Here is where we write the HTML code of our website.


Let's begin with something simple: text. How do we make some text appear on the screen?
We need to make a box that contains some text.
Like this:

	<div>Hello World!</div>

Note this slash here.

Go to File > Save (or hit Ctrl + S) and, in the browser, click Refresh.
Nice, we have the text on our screen!

What this code does is it makes a box, and inside that box, it puts this `Hello World!` text. This `<div>` part is the start of the box and this other `</div>` is the end of the box. And the box will contain whatever is inbetween these 2 things.


Let's make some more boxes, one under another:

	<div>Hello World!</div>
	<div>This is HTML</div>
	<div>It's quite alright!</div>

And if we refresh the page, here are our texts.

To prove to you these are boxes, I'll open the inspector [], click on this little button right here, then hover over them.
There you go - see? Boxes.

Well, can we make a box that contains multiple boxes?
Of course, that's the point!
Let's first delete everything, then let's make a box:

	<div>

	</div>

Like in JavaScript, spaces and empty lines don't matter. So we can put multile lines of code inside this div box.
It doesn't matter how much space we have between these `<div>` things. We can put 1000 lines of free space, but that will not make the div larger.


	<div>
		<div>Hello World!</div>
		<div>This is HTML</div>
		<div>It's quite alright!</div>
	</div>

Awesome, we have a big box [highlight the div start and end] containing 3 boxes [highlight the 3 other divs].
Hit File > Save (very important), then open up the browser and refresh the page, and here it is.
If we hover over them with the inspector tool, we can see that, indeed, it makes a large box containing 3 smaller boxes.
Great!

And you might be asking yourself: but Dave, how can I make all these boxes be the same size, or fit in the same line?
When you make boxes with `div`, they will always be under eachother.
Even if you put the divs on the same line that doesn't make the boxes on the same line.
There are ways to put them on the same line, but you need CSS to do that.

Alright, congratulations! That's pretty much all there is to HTML! You now have a master's degree in HTML!
That's all it is and that's all you need to remember: it's all boxes!

In the next lessons, we will learn how to add images and links.

## Images
Alright, how do we add images to html?
It's very easy.

But first, I want you to make another website, inside a new folder, just to practice making a new website. Pause the video here and make a new site called myphotowebsite.html, inside a new folder.


First, let's get an image from the internet.
I got this beautiful image of a roachdog (search "short black dog"). Save your image in the same folder as `myphotowebsite.html`.
So, in our folder, we have `myphotowebsite.html` and `dog.png`.

Now, to add it to our website, let's write some code.

Well, it's simple:
`<img>`
Note that for `img`, you don't need to close the box with an `</img>`. The `img` is a box that can't have any other boxes inside.

And how do we connect this `img` to our image in the folder? Simple:
`<img src="dog.png">`
And now, if we refresh the page, you can see our image box working!

Okay, some very important things: make sure you spell these right - it's IMG and SRC and make sure you put an arrow here and another arrow here.
Also make sure these are DOUBLE QUOTES, ok? And finally, make sure you don't forget `.png` here or, if your image is `jpeg` or another format, make sure it matches that format, ok?

Great!
I have a quesiton for you: can you change the image size from HTML?
What do you think?
No you can't. As I said previously, that's CSS only. You can't change the size of an image from HTML.

What does src stand for? It stands for source, but, again, we don't care about that. You just need to learn that it's src. That's just the way it is. It's specific to the img.

But I do have a homework for you: make a page with the menu of a restaurant and call it `menu.html`. It should have 3 to 4 items.
I want you to make a page that has 1. Apple Pie and then an image of the apple pie, then 2. Orange Juice and then an image of orange juice, and so on. Use divs and use images.
You NEED to do this homework because we will use it in the next lesson.
Post it in the comments section!

## Images Are Inline
Very quick tip:
Maybe doing the homework you realized that if you put 2 images one after another, they will not be under eachother, but on the same line.
That's kind of strange, but I will show you why it's like this: it's easy to work with emojis and put images inbetween words when you have text.

Let's say we have a box with some text:

	<div>Hello dear reader! Welcome!</div>

I found this image of a goose online. It's just a very small png image.
What I can do is add this `img` directly inside the text:

	<div>Hello dear reader! <img src="goose.png"> Welcome!</div>

And voila! So remember this: by default, images are inline.

If you want to have multiple images one after another, you can simply put each image inside a `div` box.
Let's say we have 3 images of a goose:

	<img src="goose.png">
	<img src="goose.png">
	<img src="goose.png">

These are displayed on the same line.
If you want to have them on separate lines, you can put each `img` inside its own div:

	<div>
		<img src="goose.png">
	</div>
	<div>
		<img src="goose.png">
	</div>
	<div>
		<img src="goose.png">
	</div>

## Folders
I hope you did your homework from the last lesson, because we're going to use that project.
We have our fancy restaurant menu. Very simple, but effective. [make sure it's visible that images are different sizes]
`<div>1. Apple Pie</div>
<img src="apple_pie.png">
<div>2. Orange Juice</div>
<img src="....png">
<div>3. Cookies</div>
<img src="....png">
<div>4. Indian Coffee</div>
<img src=".....png">`

And this is the folder of our web page.
Imagine if we have tens of different images for our menu. Wouldn't it be nice to organize them a little bit?
Doing that is very simple - let's make 2 folders: one called foods and one called drinks.

Now let's put the apple pie and cookies into the foods folder, and the orange juice and coffee into the drinks folder.

Now, you'll notice that if we refresh the page, the images don't work anymore, and that's obviously because the website looks exactly for the name "apple_pie.png", and it sees it's not here.

When we write the SRC part of an img [highlight it], we must tell it where the image is and what its name is.
To tell it "the applie_pie.png image from the foods folder", we just type `"foods/apple_pie.png"`
We save it (Control + ), and now, voila! The web page works again!
Note that this is a normal slash, NOT a backslash. It's a forward slash, ok? Always a forward slash.

Until the next lesson, I'd like you to do the same for thing for all of the images in your restaurant menu. Find some way to separate them. Maybe by vegan and non-vegan images, high fat or low fat, with or without gluten, etc.
See you in the next lesson!

## Further Folders
Hi! Welcome back.
If you did your homework, then all your menu items should now be neatly organized into folder.
I want to show you that you can make folders inside folders, just as you would expect.
If I make 2 folders inside my `foods` folder... one called `vegan` and one called `nonvegan` and I put the pie in vegan and the cookies into nonvegan, of course, our images don't work anymore...
[open notepad] ...because the location of the two images changed.
We can easily update it by doing another slash here... and... `foods/vegan/apple_pie.png`.
Alright. Save it, control + S.
Now it works!

In the next lesson, we will start using a real code text editor. Stay tuned!

## Visual Studio Code
Okay, so far we did all the coding in notepad. Which yes, it works, but it's a bit hard to work with and, frankly, it's ugly.
Now we will get what is known as a code editor, which is just a more advanced version of notepad. You will LOVE it, you will see.

The code editor that 90% of all programmers use is Visual Studio Code. Why? Because it's just good.
Let's get Visual Studio Code.

We go to Google. And we type in `Visual Studio Code` and click on the first link. Note: it's Visual Studio CODE. NOT just Visual Studio, but V. S. CODE. Very important, they're different.
Click on download for windows, and it should download this `.exe` file for you. Click on it.
And just like installing any other windows app, click on Accept, next, next and Install.

Now you can open Visual Studio Code. Don't be scared by all these options, you don't care about them.
To start working on your project, go to your website's folder, go back one folder and drag all this folder into Visual Studio Code. Click yes that you trust the authors.
And now you will see alll the files in this folder on the left side (you can hide search if it's there).
Your version of Visual Studio Code might look slightly different, but it works exactly the same.

You can click on any of the files here to see and edit the code.
And now, it's just like working with notepad, but you can see the nicely colored text.

You can also open multiple files and switch from one to another just like in a browser!

And that's it, really. You will see, Visual Studio Code will help you in many ways down the path to becoming a programmer.

From now on, we will work using Visual Studio Code and in the next lesson, we will learn about links.

## Links
[code open] We have our nice little restaurant menu website.
You surely know that on websites, you always see links to other websites.
Text that is blue and when you click on it, it opens a different website or a different page of the same site.

Links to other websites are quite simple to do.
Let's add some text that reads:
`Click here to view the cabbage recipe`.
Hit Ctrl + S to save.
Right now, this is just some text. We want it to open a youtube link with the recipe for the cabbage.
It's quite simple to do: we use an `a` tag.
`<a>Click here to view the cabbage recipe</a>`
This will create a box that will open a link when you click on it.

And to make it open another page, we write:
`<a href="youtube.com/..."...`
Save with control + S, and refresh the page.

Now, when we click on this, it should get us to the youtube tutorial for the cabbage.
Does it work? Yes it does!

So, `a` is just a box that, when clicked, changes the page to the page specified in the `href` property.

You can even put the `a` only around the `here` word:
`Click <a>here</a> to view the cabbage recipe`
As you can see, like the images, the `a` boxes are inline with text. That makes it easy to use!

## Pages

But you know, a website can have more pages. This `menu.html` thingy is just one page. We can make more pages, and we can tie them together!

So let's make another page for the special, limited edition offer menu for our restaurant!

Open Visual Studio Code. Right click here on the folder click New File.
That will create a new file in this folder.
Name it `specialmenu.html`.
Make sure you don't forget the `.html` part at the end.

And just like with the normal website, we will have a couple of strange foods in here.
I want you to pause the video here and make this menu. Just think of a couple of menu items, put them here with a name and an image, just like the previous page.
Pause here and do it.

Alright so while you were working on it, I found a couple of nice images for a cabbage and some peanuts and I added them to the new page.

Let's switch back to our base menu page.
We want, at the top of our page, to have a text that says `ATTENTION: We have a special limited edition menu! Click here to open the special menu!`
And if we click on that text, it should open the `specialmenu.html` page.
How do we do that?

...

I have a question for you: can we make this text a different color? What do you think?
No we can't, that's with CSS.


What does A stand for? It stand for anchor, but we don't care about that.
What does href stand for? It stands for hypertext reference but we don't care about that.
There's really no hidden logic to any of these - this is just the way it is. Same for the images. Images have `SRC` and a's have `HREF`. That's just the way it is.

Just before we get to the next lesson, I want you to know that these _things_, the a, the img, the div with these arrows, these are called tags.
We will keep using and you'll keep hearing the term "tag". When you hear "tag", just know that it refers to someting between these arrows that usually represents a box in the page.

Sounds good?
Good! We're almost done with HTML.
In the next video, I will show you some extra HTML tags you can use.

## Some Extra HTML Tags (Optional)
TODO: p tag
[open the main menu page code on the left, browser on the right]

So what other tags are there?
Well, there are a few tags to make text look a bit different, but honestly, they don't really matter because all of the tags I'll show you in this lesson can me made with CSS.
If you really want to, you're free to skip this chapter or not take any notes, but there are a couple of interesting things here, so just stay with me, ok?

First of, we can make text bold by putting it between B tags:
Let's add a line to the title that says WELCOME TO OUR RESTAURANT!
`<b>WELCOME TO OUR RESTAURANT</b>`
Save with Control + S, refresh and here it is. B for BOLD.

In fact, we can use tags inside other text to make it bold.
Let's take a look here, at our special menu link.
I want to make this "special limited edition" part bold.
I want you to pause the video here and make this part bold.
...........................
Alright, it should be fairly simple. We just put the "special limited edition" between B tags.
Press Control + S to Save, refresh the page and voila!
I'll let you guess how we can make some text be in italics instead of bold... hmm I wonder how.


Anyway, there's another tag called H1 that will make the text BIG!
Let's replace the B tag with an H1 tag:
`<h1>WELCOME TO OUR RESTAURANT</h1>`
H1 stands for Header 1. Are you thinking what I'm thinking? If so, you're right, there are also H2, H3, H4 and so forth.
H2 will make the text slightly smaller [we do that].
Then H3 will be even smaller [we do that] and so on.
H1 is the biggest.
Let's change the names of our foods to actually be H2's, because they make more sense like that.


You can make lists with html.
Let's add a list of allergens that can be found in our foods. These alergens are eggs, milk, peanuts, sesame and sulphites [write them down].
You know, things people can be allergic to.
First, we must define a box for our list:

	<ul>

	</ul>

UL stands for unordered list.
Inside, each list item will be inside a `<li>` tag.
So let's put our 5 allergens there:

	<ul>
		<li>eggs</li>
		<li>peanuts</li>
		<li>sesame </li>
		<li>sulphites </li>
		<li>milk</li>
	</ul>

Great! If you want numbers instead of these little dots, you can use `<ol>` instead of `ul`.
Pause the video and try to make a list with `ul` instead of `ol`.

There are some extra cool tags which you can only use with JavaScript, otherwise they don't do anything.
Like buttons!

`<button>Click Me!</button>`

This is a button. Does it do anything? Nope. You need JavaScript to make it do something. But, I'll show you a little trick: you can write an "onclick" property on it to make it run some JS code.

	<button onclick="">Click Me!</button>

And in these quotes, you can literally write JS code which will be run when you press the button:

	<button onclick="alert(420)">Click Me!</button>

We also have inputs: `<input>` you can type things in here.
Also, we have `<textarea>Type anything here.</textarea>`
And also dropdown menus!
`<select>
	<option>Pay by cash</option>
	<option>Pay by card</option>
	<option>Pay with coupons</option>
</select>`
And look at that! A nice dropdown menu!

There are other random tags, some of which you will use, others you will never use. There are plenty of tags that in my 8 year experience with HTML I have never used, but they are all very simple and straightforward and, if you want to learn them, you can simply:
- go to google
- search for "all html tags"
- and click on any link

The next lesson is the final lesson of HTML, and I will show you a couple things you should know about HTML, very simple as well.

## HTML Page Structure and Other Garbage
[Make sure you align the price properly]
In this lesson, I will show you some extra HTML tags that you might see online, but they are not needed. It's just so you know what's up when you see them.

First off, you might see this thing at the start of the HTML code: `<!DOCTYPE html>`. Back in the day 50 years ago, this used to tell browsers it's an HTML page and not something else. You do not need to put it anywhere, and if you see it, just know it's there to support internet explorer from Windows 98.

You will also see the `<html>`, around the whole page, like this.
Again, this is not needed anymore, you can skip it.
Another thing you will see is `<body>` covering, again, everything.
See, this is optional, again.

However, when you open a page, the browser will automatically create the `<html>` and `<body>` boxes, just because it has nothing better to do. They shouldn't affect your HTML code.

Now, I also want to show you one extra important tag which you should have - that's the HEAD tag.
You usually put the HEAD at the, well, head of the code, as such:

	<head>

	</head>

The head does not contain things that should show in the page, but rather it contains some settings for the page.
For example, here is where you define a title for your page, here, in the browser's tab:
`<title>My Restaurant Menu</title>`
Press Ctrl + S to Save, refresh the page, and here it is.

You can also define other things, like an icon. Like our title, this will appear in the browser tab, a little image.
I drew this nice logo of our restaurant, just called `logo.png` which I put directly in the folder or our HTML. Let's add it!
The code for this is ugly as hell, so bear with me:
`<link rel="icon" type="image/x-icon" href="logo.ico">`
You absolutely don't need to memorize this. Whenever you want to add an icon to your website, just look it up on Google. I still haven't memorized it. I always look it up online.

And there are other small settings like these you can add to your page's HEAD, but we'll leave them for later.
That being said, congratulations! You're an HTML professional now!
See, I told you it would be very simple.

But now the cool part comes.
In the next chapter, we will learn CSS and we will make our website look from this... to this...
https://marketplace.canva.com/EAFJgMSOsNY/1/0/1131w/canva-red-and-yellow-modern-fast-food-menu-8KbN0csxDcE.jpg
Crazy makeover! That's what CSS can do. CSS is life, CSS is love.
I'll see you in the next chapter.

# CSS
## Welcome... and Warning
Hello and welcome to the third chapter of this course, zero to hero, for entrepreneurs and freelancers.
In this chapter, we will learn CSS, which is the language you use to make your website look good.

In the previous chapter, we learned about HTML. We learned that HTML is only used to create the structure of the website. All HTML does is it makes boxes, text, images, etc. But HTML can not tell the website what color boxes should be, or what font, or what the borders of boxes should look, or even how boxes are aligned on the page. This is what CSS does.

Now, a word before we begin: CSS is very very easy, but CSS is also commonly referred to as the most horrible language you can work with. Why horrible? Well, because most of the time, CSS works great and you can do what you want! However, sometimes, something will not work and you will have no idea why.
One thing you should learn to expect when working with CSS is that no, you're not stupid for not making something work, it's just the way CSS is. CSS, sometimes, is very very stupid.

In this course, I will try to explain to you all of the pitfalls of CSS as well.

Also, CSS has a lot, a looot of things, like colors, borders, margins, etc. You DO NOT have to learn them all. Even I, when I want to do something with CSS, I will google a lot of it. Why? Because I know I CAN do it, I just don't remember how. And that's the best approach you can have with CSS. Don't memorize - you don't need to memorize and you shoudn't. Trust me, nobody memorizes all of this. It's good to know how it works, it's good to use everything once and it's good to know you can do it!

So, what is our goal?
This is what we will make: https://marketplace.canva.com/EAFJgMSOsNY/1/0/1131w/canva-red-and-yellow-modern-fast-food-menu-8KbN0csxDcE.jpg
It's a restaurant menu website. We made it in the previous chapter, with HTML. If you skipped it, don't worry, I'll explain everything.
Without further ado, let's begin!

## The Very Basics
Let's upen up our restaurant menu page and remove some of the parts so it's easier to work with.

So, how do we make it stylish?
First, we create a new HTML tag called `style`
`<style>

</style>`
Inside here, we write CSS code. 
This style thing won't appear on the page. It's simply a box where we write CSS code.

Here we will write all the rules of our page.
And rules sound like this: ALL links should be purple. ALL div boxes should have a yellow border. THIS one box should have small text. And so on.

For example, we could say: ALL `a` tags should be green. How do we do that? Let's see:

	a

Then we write brackets:

	h2 {

	}

And inbetween these brackets we write all the rules and styles and alignments and colors we want ALL the a tags on the page:

	color: green;

Important here - colon here and semicolon at the end.
If you remember from JavaScript, this is similar to a JavaScript object, but not quite.
Save with control + S, refresh, and boom! Now all our a's have green text!

What else can we do? Background colors!
Let's make the background color of all H2's purple:

	background-color: purple;

Notice the little line here - that's how words in CSS are separated.

What else? Border?

	border: solid;

And we can change the color of the border with... pause the video and try to guess.

	border-color: red;

Another thing we don't like is that our images are all different sizes.
So let's change them to all have the same width.
For that, we need to write some rules for ALL images.
Pause the video here and try to think of how we'll do that. You don't need to write it, just think abot how it would be like.

Well, just like with our link rules here, we make some rules for imgs:

	img {

	}

Alright. What could possibly be the rule for width. Hmmm...
If you guessed width, you're right!


	width: 500px;


Note the `px` here. This means pixels. My screen, for example, is 1920 pixels wide. We HAVE to specify pixels, because there are also other things we could specify. Like a percentage:

	width: 50%;


This will make the width of each image equal to 50% of its parent's width. Our images have no parent, so their parent is just the page, the body of the page.
I will let you guess how you can set the height of something. Try to make the height of images also 500px. Pause the video and do it.

What other important properties are there?
We haven't talked about space much, so here is how you can add space before or after an element.

`margin-top: 100px`

And now, all images have 100px of empty space above them!
If you guessed that there is margin for left, right and bottom as well, you're right!

`margin-left: 65px;`
`margin-bottom: 50px;`

So now, notice that our images have 65 pixels of empty space to the left, and then the images themselves occupy 50% of the screen size.
Notice we don't use margin-right. We only have top, left and bottom and that is because everything, by default, is left to right. I'm sorry if you speak Arabic or Hebrew, but it's all left to right.
There is also `margin-right`, but it won't do anything in our case.

Let's take a look ar our div boxes and give them a gray background so we can see where they start and where they end.
The text is a bit too close to the edges. How do we give it a padding? It's simple:

	padding-left: 25px;

Of course, we can also add padding-top and padding-bottom.
You can remember the difference between padding and margin by knowing padding is on the inside and margin is on the outside.
Padding is basically like when you take a box in real life and you pad it with soft stuff so what is inside doesn't break. Padding inside, margin outside.

There is one last thing I want to show you: borders!
Let's add a red border to all of our images:

	border-width: 5px;
	border-color: red;
	border-style: solid;

If we want to give it round corners, we just go:

	border-radius: 25px;

Aaand that's pretty much about it! That's all CSS is about.
I know the website looks horrible but bear with me. We'll make it look like this soon. Trust the process.
In the next lesson, I will teach you how to apply CSS rules to only one or some elements. Cause maybe you only want this image to be larger for some reason, or this h2 to be yellow instead of green. I'll show you in the next lesson!

## CSS Only On Some Elements
Sometimes you want to have CSS only on one element.
For example, maybe you want this specific div here to have a gray background, but not all divs, just this one right here.

Well, to do that, you need to give it a class property:
You simply give it a class property:

	<div class="my-gray-div">

From now on, this div will be named "my-gray-div".
In CSS, we are not allowed to use spaces for classes, so we use little lines. This is a minus sign.
If you want, you _CAN_ use underscores, but, like in JavaScript, web developers really, really don't like underscores. So, for CSS, if you have multiple words, you separate them with a minues.

So now, you can write some CSS rules only for my-gray-divs, like this:

	.my-gray-div {

	}

Remember how we do background color?
It's:

	background-color: gray;

Save (control + S), refresh... and there it is.

This rule that we wrote will apply to ALL things on our page that have this class.
If we add this class to another div, it will also be gray [show this].


So that's how you can apply CSS only to some elements.
That's honestly all.

As a homework, I want you to make the text for this specific div to be red. Just this one. Good luck and see you in the next video.

## Boxes On Same Line

[clean project]
In this lesson, we will learn how to have multiple boxes on the same line.
So here we have a simple big box, with some simple small boxes inside.

To make them on the same line, the big box must have DISPLAY: FLEX.
What does DISPLAY: FLEX mean?
It means we have to give it a DISPLAY: FLEX rule.

Let's give it a class: `class="big-box"` so we only make THIS boX have a DISPLAY FLEX.

So now we go to CSS and we write:

	.big-box {
		display: flex;
	}

And now everything inside this box will be on the same line.
Awesome!

## Flex: Gap, Center
Just to see the small boxes better, let's make the small boxes have an orange background.
I want you to do that using classes. Give the small boxes each a class called small box and make them orange with CSS. Pause the video and do that.

Alright, here we are.
Now we see the boxes much better.

There are a few interesting things you want to do.
For example, what if you want to have a gap between your elements?
You do that with a gap property for the big box:

	gap: 20px;

Awesome.
If you want all elements to be the same width, you need to set their width. Can you remember how to do that and figure it out?

	width: 200px;

And you can see where all of this is going - we're getting closer and closer to making our dream fast food menu page.

[blank page with transition]
Last thing in this lesson: how do you make a box centered on the screen?
The truth is, there are multiple ways to do it, but I will show you the best way to do it:

Let's say we have a black box, with a size, and we want it to be on the middle of the screen.

Step 1.
We need to put it inside another bigger box with the width equal to the entire screen.

	<div class="bigger-box">
		...
	</div>

	.bigger-box {
		width: ...
	}

To cover the entire screen width, what do you think we will put here?
Exactly: 100%
And to see it truly covers the entire screen, let's give it a background color...
You don't need to give it a height, because it automatically has a height equal to whatever is inside.

So now, to have whatever is inside be on the center, we first must give the big box a DISPLAY: FLEX and a justify-content: center:

	justify-content: center;


Hit control + S to save, and let's refresh the page.
There you have it - that's how you center things on the screen.

If you want, you can play with this. You can have boxes centered inside boxes that are not centered that are inside centered boxes and so on.



Now, I know what you're thinking: how do you center it also vertically?
My answer to that is - it's tricky. And I want you to know one very important thing about CSS:
CSS is NOT made for you to center things vertically. You're free to play with 100% width and center things horizontally, like here, but vertically (indicate with the mouse), that's tricky.
Yes sometimes you want to, but you should avoid centering things vertically like the plague. Try not to do that, because that's what CSS is really bad at.

But if you really want to, you can simply set the height of the bigger box to something in pixels:

	height: 350px;

And also give it an align-items: center:

	align-items: center;

Save, refresh. There it is.

Now, what if you want to make it perfectly centered on the screen?
Your first thought is probably to give it a 100% height.
Well, that doesn't work [try it].
Why doesn't it work? No one really know. It just doesn't work and you should know that.

## Pitfalls (IMPORTANT)
This is a very important lesson and I'll explain some things about CSS that you MUST know.

#### Put This Code Everywhere
First off, I will give you some CSS code to put on EVERY web page. This code will save you so much headache.

[css memes]
Sometimes, elements on the page will glitch and go one through another, or be misaligned, or not work at all.
That is because CSS is an old language that came with a lot of problems.
To avoid those problems, just put this code on your page.
You don't need to know what it does for now, but just trust me on this one, it will save you so much headache.
In my personal projects, I always add this code to all of my pages. It won't break anything, it will just fix things.
Save this code and put it everywhere and you will thank me later.

#### Also This
Here's another piece of code you should probably put on every page.
If your page is only supposed to scroll down, then put this on your page.
Sometimes your page will get bugged and display a scrollbar here, which will make your page scroll to the right and be completely misaligned.
IF you do NOT want your page to have a scrollbar down here, put this on your page and thank me later.

#### Working With Height
Next, like I already said, CSS doesn't really like working with vertical things. If you're working with 100% height, be extra careful because it can break.


# HTML + CSS Project
For this chapter, we will start actually building the website we have in the picture.
Our website is a restaurant menu as well.
We will start from scratch, from 0.

We will only have one page on our site.

To start this out, I want you to create a new folder for this project and create a new page called fastfoodmenu.html, just like I taught you.
Do this again to familiarise yourself with starting a new project.
Pause the video and do that now.

Okay, I'll quickly do that here as well.
New folder, drag and drop it to VSCode, right click on it > new File, fastfoodmenu.html.

Done, now we can begin writing code.
We open this in the browser and we currently have nothing on our page.

Well that is about to change.
We will look at all of these one by one - the title, the background, these images, etc and we will make them one by one.

Before we start doing it, I want you to find 6 similar images to these ones: one for a big burger, one for a pizza, for a kebab, and so on.
And I want you to put them in a folder called `images`.


## Starting Out
Before we begin, I want you to be sure we have the same file structure.
Here's our fastfoodmenu.html file.
And near it there's a folder called `images` with a small `i`.
Inside, we have some random pictures.

Here's the plan: we will build our website little by little with HTML and CSS.For every new thing we don't know, we will google how to do it together.
Googling is a very important part of being a programmer.
As a programmer, you will google A LOT. And I mean A LOT.
We programmers google things all the time, there's absolutely no escaping it.
You WILL need to use google and search for how to do new things. There's just no way around that. That's the truth.

Alright, first things first: we make a style tag and put that CSS code that I gave you to fix issues in it.

We have a blank page.

## Background Color
Let's begin by setting the background color of the page and make it brown.
Do you remember how the browser covers all of our code inside a `<body>` tag?
`<body>` is just a box that contains all of our page. You don't see it here, because it is added automatically by the browser.
So to set the background color of our page to brown, we need to set the background color of the body to brown.
Pause the video and write a CSS rule for that.

	body {
		background-color: brown;
	}

Awesome, it works.
But this color is not exactly what we need. The brown of our page is slightly different.
How do we set an exact color?
Here's how.

## Exact Colors
In computers, there are 3 primary colors: Red, Green and Blue.
All the colors you've ever seen on your monitor are combinations of Red, Green and Blue.
[Slide] Yellow is Red + Green.
[Slide] Purple is Red + Blue.

To choose an exact color, you need to specify the exact combination of how much Red you want, how much Green you want and how much Blue you want on a scale from 0% to 100%.

[Slide] 100% Red + 100% Green + 0% Blue = Yellow
[Slide] 50%... 0%... 80%...

Let me show you how to set a custom color.
Instead or `brown`, let's set the color to a unique yellow:

	rgb()

Yellow, as I said, is 100% red, 100% green and 0% blue:

	rgb(100%, 100%, 0%);

So, this first 100% represents how much red you want, in that color, this second 100% is how much green you want and the last one is how much blue you want.

We can lower the green here to make it more towards red. And make sure you put the % sign (that is Shift + 5). Otherwise, it's not going to work properly.

Just so you know, 0% in all 3 means black, and 100% in all 3 means white. No colors means black, all colors means white.
I want you to pause the video right now and try out a few combinations of red, green and blue. Try to get this exact color we have on our inspiraiton photo here.


I wanted to get you used to working with RGB, but there's a cute trick in our text editor here.
If you hover over this little square, it will open this color picker, and you can just click anywhere on this color picker to choose your color, and it will automatically write the combination for that color here.

## The Splash Image
Next up is the paint splash in the corner here.
There is no spcecial effect or trick for this. It's just an image.

So we're going to go to Google, find an image of a paint splash and download it and put it in our website folder with the name splash.png.
Make sure it has a transparent background.
An image can only have a transparent background if it's a PNG. JPEG, WEBP, GIF these can't have transparency.
When you're downloading the image, if it appears to have a white background and then you click on it and it has these squares, then it means the background is transparent.
Just be careful because a lot of images online are PNG but don't actually have a transparent background, even if they have these squares. If your image doesn't have transparent background, try downloading more images and see which one truly has transparent background.

How do we put it in the upper-right corner here? Try to guess.
We use something we've already learned.

Yes, we use `margin-left` and we can put it to 80%.
Let's give our image a class so we can easily make rules for it in CSS...

	.splash-image {
		margin-left: 80%;
	}

Now the image will have a space to the left equal to 80% of our screen.
I quite like that.

## The Title
Next up, we have the title up top.
Let's make a simple div box to hold our text:

	<div>Fast Food</div>

Now, there are 4 things we need to change to it:
The font size, its position (it should be centered), its color (cause it's white) and finally, the font..

Let's start out with the font size and color.
Pause the video, give it a class called title-fast-food and make it let's say 40 pixels and white.
Pause the video now.

	<div class="title-fast-food">Fast Food</div>

	.title-fast-food {
		font-size: 40px;
		color: white;
	}

Next up, let's make it centered on the screen. Do you remember how to do that?
Pause the video and do whatever it takes to center this text on the screen.
Feel free to go back to the previous lesson.
I'll give you a hint: you need to use display flex and justify-content center.
Pause the video now.

If you remember, to make something be in the middle of a box, you need to put it _inside_ another box.
So let's do that

	<div>
		<div class="title-fast-food">Fast Food</div>
	</div>

Let's give it a class to use it in CSS:

	<div class="title-box">
		<div class="title-fast-food">Fast Food</div>
	</div>

	.title-box {
		display: flex;
		justify-content: center;
	}

Great!

## Fonts
There are a few fonts you can choose from that all browsers and computers have.
Changing the font is easy: the most popular font is Arial.
So, for our title-fast-food, we'll give it a rule for:

	font-family: 'Arial';

Notice that it's font-family, NOT font. Font-family. Why it's like that? Nobody know, that's just the way it is.

Now, there are only a few fonts that work by default for everyone. And you can't memorize them.
So, open up Google and type in "css web safe fonts".
I want you to do this with me.

Open the w3schools link and here, you will see several options for fonts.
If you click on "Try it" for any of these fonts, it will take you to a page where you have the code for that font. Let's say, Courier New.
What you do is you simply copy this and paste it in your code, and voila! You changed the font!

Let's find one that looks similar to the one we need for our fast food. Arial was fine, but maybe... I think I like Trebuchet MS even more. So click on try it yourself...
Copy this... and paste it in our code.
Great! We're getting closer to our dream website!

Next up, we have this subtitle here, called "Menu".
Let's first make it in any font and then, later, we'll worry about the font.

I want you to pause the video here and make this subtitle menu yourself, just like we made the fast food title [select the code]. It should be yellow, in the middle, and 30 pixels size.
Try to write the code yourself, using the keyboard and don't copy-paste.
Pause the video now.

	<div class="title-box">
		<div class="title-fast-food">Fast Food</div>
	</div>

The code is very very similar to our title's code.
It should be fairly simple. Make sure your divs for the subtitle have a different class from your normal title, otherwise it's all gonna be messed up!

[close other browser tabs]
One last thing: notice how our subtitle menu here overlaps our fast food title? How do we do that?
Well, remember how elements have have a margin-top and margin-bottom?
What if I told you that the margins can be negative!? That's crazy, but it works!

Here, let me show you:
So, if I give this element a margin-top: 15px, it's going to be more down.
However, if we give it a margin-top: of _-15px_, it's going to go up! It's weird, but it works just like you'd expect!
That's pretty cool.

Only one last thing remains to be done: changing the font family.
Let's take a look online at the web safe fonts: we Google "css web safe fonts" and we go to w3schools. Take a look through these fonts... none of them looks like the one we need.
So what do we do?
Well, we'll have to download a font.
We'll do that in the next episode!

## Custom Fonts
First things first: we need to find a good font that looks similar to what we need.
Online, we can find tons of high quality free fonts that we can use on our website.

Simply Google "free fonts".
Personally, I like DaFont, but even if you're watching in 2045, you'll probably find a good website for free fonts.

This website has so many fonts! Let's look for a good category of font. I feel like our font looks like a calligraphy font.
Let's take a look... I feel like this one, Cream Cake, is pretty similar. So let's download it.

It will download a zip file. If you're not familiar with zip files, you have to first extract it. A ZIP file is like a folder with extra steps. So right click on it > extract all. Click ok.

Awesome, now we truly have our font.
A downloaded font is just file that has OTF at the end. Alternatively, yours might be TTF or WOFF. They are all fine. Just take note of what the file ends with.

Now, we right click on this and copy.
Go to our website folder and paste it in there. Now our font file sits in the same folder as our website, so we can use it! Let's go back to the code.

First things first: we need to CREATE the font family in CSS before we use it.
Up here, at the very start of our style, type in like this:

	@font-face {
		font-family: (this will be the name we want to use in code, so let's say cream-cake)
		src: url("") (and in quotes you type in exactly the name of this file, exactly as it is)
			"Cream (SPACE) Cake.otf"
	}

Very important, it's an .OTF. Yours might be TTF or WOFF.
Just to be clear, it should NOT be zip. If it's ZIP, you skipped a very important step, my man. Go back to the beginning of the video and watch it again.

Phew, ok. That was something. Now, we can simply use our new font.
For our menu subtitle here, we go:

	font-family: "cream-cake";

Lo and behold, we have a new font.

I have a homework for you.
You see, in our website image right here, [zoom in] I think the font is not Arial. I think it's something a bit thicker.
So, go to a font website, like DaFont, and find a different font for our Fast Food title. Download that font, extract it, copy the font file to the website folder, create a new font like here [select] and give this cute title here the new font instead of Arial [select it].

Feel free to try things out. Maybe you find a font that looks even better. Try it out, see how it goes. Do that, I'll be doing the same offscreen, and I'll see you in the next video!



## The Menu Items
[Prepare Paint to show boxes]
Next up is the 6 items on the menu, with pictures, text, stars and a price.

Whenever you're building a website from an image, I want you to think in terms of boxes.
Again, everything is a box. Your website is just boxes inside boxes inside boxes.
And pretty much all we need to do is apply the techniques we have learned so far.

Let's think about the structure of our HTML for this part.
We have 2 rows, which means 2 boxes.
Each row box has 3 boxes inside, see?
And inside each of the 3 boxes, there's an image, another box with text for the name, another box underneath it with stars and another box with the price.
That's a lot of boxes, but we'll take them one by one. The code for all the white boxes will be almost exactly the same, except for you know, the images, text, price, etc.

[Show Folder]
To start up, here's my website folder. I have a folder here called `images` inside which, I have 6 images, each for a different food.

[Show Code]
Now, I want you to create the first row, the first 3 items in our menu.
You will need to create a box to hold them and center them, and create 3 more boxes inside, each with an image.
I want you to pause the video here and try to create the structure for the 3 first items yourself. It's a more complex task, but you can do it using only things that we have learned so far.
Just try. If you don't manage to do it, come back to the video and follow what I do and then try to do the rest in advance. Whenever you feel like you can do it on your own, pause the video and do it.
Pause the video now.

First, we need a box to hold the 3 boxes.

	<div [we'll call it row-box] class="row-box">

	</div>

Inside it, there are 3 boxes: so, we make 3 boxes.

	<div class="row-box">
		<div [we'll call these white-box] class="white-box"></div>
		<div class="white-box"></div>
		<div class="white-box"></div>
	</div>

If we press control + S to save and refresh the page, we don't see any of the boxes, because they have nothing inside.
First off, we want the 3 boxes to be white and be about 200px wide and 300px tall.
Pause the video now and make them so.

	.white-box {
		background-color: white;
		width: 200px;
		height: 300px;
	}

But they're not all on the same row.
Do you remember how to make multiple boxes on the same row?
Pause the video now and see if you remember how to do it.

We need to make the big box, the row box, flex:
	
	.row-box {
		display: flex;
	}

We also want them to be aligned on the middle of the page.
Remember how we do that?
Pause the video and try to align them on the middle.
Pause the video now.

To have some boxes centered inside another box, we simply add to the big box display flex and justify content center. Our box already has display flex, so we just use justify content center.

	justify-content: center;

They are a bit too close together, so let's give them a gap, about 20px:

	gap: 20px;

They must also have rounded corners, so let's do that:

	border-radius: 25px;

It's starting to look a lot more like what we need.
Let's add the images:

	<img [we'll call them menu-item-image]...>

Now, the images are really a wrong size. So, let's set the size of each image.
Since each white box is 300px wide and 500px tall, let's make the image 280px wide and 300px tall.
We're simply approximating right now. There's no correct solution, really. If you want to be exact, I suppose you can measure exactly how many pixels there are here, but let's just approximate for now.

	width: 180px;
	height: 200px;
	[We should also make the borders of the images round] border-radius: 25px;

Nice! The images look a bit distorted, though. You can either fix this by editing the images in something like adobe photoshop or paint, but we can also fix it with code. However, we'll take care of that later.

[Have website image opened]
Next, our images are on the left, but you see that in this image, there's a small white space here.
Remember how to add space? We can use either margin for the image, or padding for the white box.

[Paint open with the image of our current WIP website]
Now let's do some quick maths:
Our white box is 200px wide. Our image is 180px wide.
200px - 180px = 20px
So, we need a total of 20px space. Which means 10px on the left and 10px on the right.
Since boxes are always on the left side, we only need to add a margin-left to the image:

	margin-left: 10px;

Control + S to save, refresh the page with F5 and... it looks great!
We also need to add a margin top to the images.
Pause the video now and do it.

	margin-top: 10px;

This looks freaking awesome! We're getting there!

Now, for each menu item, let's add its name.
Do that on your own - pause the video now.

It's very simple: all we need to add is a div:

	<div [we'll call it menu-item-name] class="menu-item-name">Big Burger</div>

Put this in the other divs as well. Let's see what it looks like.
It's a bit small and the font should probably be the same as our title font, here.
Pause the video now and do it.

	font-size: 16px;
	font-family: "title-font";
	[and we make it more to the right by giving it either padding or margin; let's give it a padding this time, just to practice it] padding-left: 10px;
	padding-top: 10px;

I think 10px is not enough. Let's make it 15px.
Save and refresh.
Looks better now.

You see, it's all a process of trial and error. You try a margin, just by approximating, then you make it smaller or larger, depending on how it is.

Next up, this one might look tricky, but honestly, it's just the same thing we've done so far.
We simply have 2 boxes: one for stars, and one for the price, one after another.
We just make 2 boxes with some thing inside, and, if we want to have them on the same line, do you remember how we do it? [pause] If you said display flex, you're right!

	[we'll call it...]
	<div class="menu-item-bottom-box">

	</div>

Inside, we have 2 boxes: one on the left with stars and one on the right with prices:

	<div class="menu-item-bottom-box">
		<div class="stars-box">
		
		</div>
		<div class="price-box"></div>
	</div>

Let's write the CSS for this to start with:

	.menu-item-bottom-box {
		display: flex;
	}

Now, you might be wondering: Dave, how the hell do we make those stars?
The obvious answer is... they're all just images. We can go to google, find a small star image and put it there. Yes, you'll have 5 images one after another. It's not pretty, but what can you do.
I want you to do that: go to Google, find an image of a star and put it here 5 times. You will need to copy and paste the same thing.
Pause the video now.

	<div class="menu-item-bottom-box">
		<div class="stars-box">
			<img src="images/star.png">
			<img src="images/star.png">
			<img src="images/star.png">
			<img src="images/star.png">
			<img src="images/star.png">
		</div>
		<div class="price-box"></div>
	</div>

It's quite ugly, but hey what can you do.
Let's give it a class to make it small with CSS.
Let me show you a trick: You can put your cursor here, press and hold the mousewheel of your mouse, and drag down to literally write on multiple lines.

	<div class="menu-item-bottom-box">
		<div class="stars-box">
			<img class="star" src="images/star.png">
			<img class="star" src="images/star.png">
			<img class="star" src="images/star.png">
			<img class="star" src="images/star.png">
			<img class="star" src="images/star.png">
		</div>
		<div class="price-box"></div>
	</div>

	.star {
		width: 20px;
		height: 20px;
	}

Awesome. Finally, let's write something in the price box too:

	<div class="menu-item-bottom-box">
		<div class="stars-box">
			<img class="star" src="images/star.png">
			<img class="star" src="images/star.png">
			<img class="star" src="images/star.png">
			<img class="star" src="images/star.png">
			<img class="star" src="images/star.png">
		</div>
		<div class="price-box">$12</div>
	</div>

The right part is still not well aligned.
Let's give it a margin and a proper font...

Perfect! Now, we take this and we copy it and paste it to the other white boxes.
Ahh, look at that! Our website is coming together really really well!

Finally, the last thing we need to do is make the second row of our menu items.
We select alllll of this and we copy it and paste it right underneath. The CSS is the same, so no need to add anything to the CSS.

Looks great! Only one small part remains to be done for our website - this bottom part.
But before we do that, we should fix these images being stretched like that, cause they're quite ugly like that.

See you in the next video!

## Image Fitting
Our images look quite off, but luckily it's very easy to fix.
You can use this magical CSS rule:

On your image in CSS, give it another rule called object-fit: cover;
Save, refresh with F5 and now we can see our images are automatically cropped to fit the width and height we gave them.

That's it. In the lesson, we'll start the bottom part of our page.

## The Bottom Side
[Show the image in paint]
We'll now start working on this side of the page.
You can try to do it on your own, but you'll need a few new CSS rules.
However, you can think of how you do it.

When building a website, always, always think in terms of boxes. And the more boxes, the better!
So let's look at this side of the page: it's all a big box.
This left side is another box. This right side is another box.
On the right side, there are 2 boxes. And each box is also split into 2 more boxes.

[code]
Let's first create the layout that we want.

	<div class="bottom-big-box">
		<div class="bottom-left-box"></div>
		<div class="bottom-right-box"></div>
	</div>

We want them to be on the same line, so let's give the big box a display flex:

	.bottom-big-box {
		display: flex;
	}

We also see that the left box is roughtly the same width as the right box.
We can force them to be the same, exactly half of our big box:

	.bottom-left-box {
		width: 50%;
	}
	.bottom-right-box {
		width: 50%;
	}

We don't have anything inside the boxes, so they don't appear.
I think the big box should also have a height of about 450px;

	height: 450px;

The image is cut away on the left and bottom, so it might be tricky. Let's do it in the next lesson.

## Cropping/Cutting Boxes

For the image, we'll Google food on plate image png. Make the image is a PNG, not JPEG, not GIF, only PNG. Because ONLY PNG has transparency.

[Show folder]
I found this image, I put it in my images folder in my website folder, and now let's add it to the page code, on the left side.

[Show page image]

	<img class="plate-image" src="plate.png">

Notice how this one looks cut here? It goes out of the page. Let's do that ourselves.
Since our big box is 450px high, we should make our plate taller than that.
Let's say 750px;
We should also make it wide: 900px;

	height 750px;
	width: 900px;

Save and refresh. But oh no! What's happening! The image is larger than its box!
We could do the same as we did with our menu items and give them an [write it] object-fit: cover, but it won't look nice at all. It won't be cropped properly. [and delete it after]
Don't worry, we can make the box say "nope, if something doesn't fit this box, crop it".
We can go to the box on the left and say:

	overflow: hidden;

This makes it so that if the contents of the box are too big for the box, they will simply be cut.
Now our image looks much better. But it's too much to the right. Do you remember what we can do to make it more to the left?
Pause the video and make it more to the left.
Pause the video now.

	margin-left: -300px;

Aha! Now it looks great!

Last thing we need to do is make the part on the right and the project will be finished!


## Align Right
[Paint]
Let's take a look at the bottom right side: it has 2 boxes...
Each of those 2 boxes has 2 boxe boxes inside...

The easiest way to do this is to give this first box a margin-top, and give this big box a padding-right.
You'll need to find some images for the phone and the internet on google.
Can you do that?
Pause the video and try to do it... now.

Let's do just that:
[code + image]

	<div class="phone-big-box">
		<div class="text-side">+123-456-7890</div>
		<div class="icon-side"><img src="images/phone.png"></div>	[I found this image for a phone online]
	</div>
	<div class="site-big-box">
		<div class="text-side">www.reallygreatsite.com</div>
		<div class="icon-side"><img src="images/internet.png"></div>	[this one is from google as well]
	</div>

This box and this box are very similar, so is this one and this one.
I think we can have the same class on both of them.

(Save + Refresh)


	.bottom-right-box {
		padding-right: 100px;
	}

	.phone-big-box {
		margin-top 100px;
	}

Next, we want to align these boxes [show] and these ones [show] on the same line.
We do that with... try to guess... display flex!

	.phone-big-box {
		display: flex;
	}
	.site-big-box {
		display: flex;
	}

So far so good.
But how do we make them aligned to the right?
One way to do it is to give them a margin-left, but that can be weird.
The easiest way is to just align them to the right with a special trick.

Remember how you can center things inside a box with justify content center?
Well, outside of justify content center, there are also justify content right and justify content left!
Let's try those things!

	.phone-big-box {
		display: flex;
		justify-content: right;
	}
	.site-big-box {
		display: flex;
		justify-content: right;
	}

This makes it so that the content is aligned to the right side!
Let's also make the images the same size...

Perfect!

That's honestly it!
It's a really cool website!

If you managed to get to this point in the course, seriously well done. You're on the right track and enormous props to you.

I NEED to congratulate you and tell you that the hard stuff has passed, and it will only get easier and easier from now on, especially when we start combining HTML and CSS with JavaScript!

Let me know in the comments or on our Discord group what you think! Was it difficult? Was it easy? And feel free to let the others know you did it as well!

In the next lesson, we'll look at how to make our website "responsive" and how to host it on the internet for free. There will be a project assignment too, which I really, really want you to do. It will be some

# CSS: Important Tips
## Key Takeaway
## Responsive CSS
## Hosting The Website
## Things You'll See Online
## Animations
## FAQ
## Project Assignment (choose one of 5 websites)




Googling... (w3schools mostly)
Iterative process... fail... trial and error
Refresh the page by clicking on this button or pressing F5.
Learn by examples...


## If it doesn't work...
- Semicolons?
- px?


Menus: https://marketplace.canva.com/EAFJgMSOsNY/1/0/1131w/canva-red-and-yellow-modern-fast-food-menu-8KbN0csxDcE.jpg

## Hosting your website


# JavaScript, Part 2

## Interaction with HTML

## We programmers google things a lot
- homework: find out how to do <something> and write it in the comment section

## How to work with other people's code (black box API's)

## Map/Reduce/Filter
Dollars to euro


# Practice Ideas
1. Make a function that takes a string and checks if it's a valid email. Returns true if it's valid, false if not.
	- dave.doublee@mydomain.tr (valid)
	- dave.doublee@gmail (invalid)
	- dave@doublee@gmail.com (invalid)
 	- dave.gmail.com (invalid)
 2. Make a function that takes an array of strings and finds the longest 'chain' of another given string. Returns the length of the longest 'chain'
	 - ['SHOP', 'COMBAT', 'COMBAT', 'EVENT', 'SHOP', 'COMBAT', 'SHOP', 'COMBAT', 'COMBAT', 'COMBAT', 'EVENT'] (returns 3)
2. Make a function that removes the duplicate elements from a list
3. We have a list where each element is either a number, or another list. Make a function that takes this and returns the sum of ALL numbers inside the list (directly AND indirectly inside the main list). This should be done with a recursive function.
	- e.g. for [1, 5, 4, [5, [1, -5], 9], 4, [1, 3], -2] it will return 26
4. Implement a **tree**. This is a graph where each _node_ has a _value_ (string, number, etc) and _children nodes_. Example [here](https://cdn.programiz.com/sites/tutorial2program/files/tree_0.png): 
	- There should be a class Node
	- Nodes should have a method `node.add(value)`, which creates a new child for the node and gives it the `value`
	- Improve this tree by adding a _parent_ field to Nodes; whenever you add a new node, each node knows its parent (`None` if it's the root node)
	- Make a method `node.find_root()` for Node which finds the root node of the tree the node is in. For the example in the link, for node with number 6, this method will return the node with number 1.ital letter
5. Really cool (optional) trick with strings (backticks)

