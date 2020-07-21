# js-exercises


Udemy web dev z2m javascript exercises

Type Coercion table
https://dorey.github.io/JavaScript-Equality-Table/

MDN - Equality comparisons
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Equality_comparisons_and_sameness

ECMA comparison algo
https://www.ecma-international.org/ecma-262/5.1/#sec-11.9.3

https://hacks.mozilla.org/2018/03/es-modules-a-cartoon-deep-dive/

Extra Javascript Practice
I get a lot of questions about how you can practice and learn more Javascript (the core concept that you really want to master if you want to be a Developer). Anyway, I wanted to share with you the 3 free resources that I recommend. In my opinion they offer incredible insight into Javascript and are better than most paid options out there. They will really solidify your knowledge if you do them along with the course, in your spare time, or throughout your career:

1. https://github.com/getify/You-Dont-Know-JS
2. http://javascript.info/
3. http://dmitrysoshnikov.com/ecmascript/javascript-the-core-2nd-edition/

or... you can scroll all the way to the bottom of this course to Extras: Bonus Part 2 to see some more Advanced JS that I teach :)




Optional Exercise: Javascript Logic
What is the Challenge?
Solve the below 3 javascript puzzles. The goal of this challenge is to practice our logic skills. Something that is useful not only in interviews when you get challenging problems, but also in your day to day work as a developer. First, start off by reading this article: https://medium.freecodecamp.org/how-to-think-like-a-programmer-lessons-in-problem-solving-d1d8bf1de7d2

Question 1: Clean the room function: given an input of [1,2,4,591,392,391,2,5,10,2,1,1,1,20,20], make a function that organizes these into individual array that is ordered. For example answer(ArrayFromAbove) should return: [[1,1,1,1],[2,2,2], 4,5,10,[20,20], 391, 392,591]. Bonus: Make it so it organizes strings differently from number types. i.e. [1, "2", "3", 2] should return [[1,2], ["2", "3"]]

Question 2: Write a javascript function that takes an array of numbers and a target number. The function should find two different numbers in the array that, when added together, give the target number. For example: answer([1,2,3], 4)should return [1,3]

Question 3: Write a function that converts HEX to RGB. Then Make that function auto-dect the formats so that if you enter HEX color format it returns RGB and if you enter RGB color format it returns HEX.

You can see the solution files by other students here



For WINDOWS Users ONLY
If you are on a Windows Machine (so you can skip this section if your computer is Mac or Linux based), you will need to install something called Git Bash for you to be able to follow the next lesson.

Here is a detailed guide for you to get set up:

1. Download Git for Windows (we will be using this for future lessons as well so make sure you download it!)

2. Once Git Bash is downloaded, run the downloaded .exe file. You will get a prompt that says “Do you want to allow this app to make changes to your device?” Click Yes.

3. Run through the installer: We will use the default settings for everything in this installation, so all you need to do now is keep clicking Next, and finally Finish. (If you want more details on what each option does, you can read about it here and read the Git Bash Windows Installation section)

4. Congratulations! You have just finished the setup. You can now open “Git Bash” from your computer so you can follow the lesson in the next video. You now have the same setup as any Mac or Linux user where we call this the "Terminal".

Ps Windows has recently announced that you will be able to download an actual Terminal from their online store for free. However, this is still in preview mode so for now, I recommend the above setup.




Quick Note: For Windows Users
In the next video, please ignore the text at the bottom. Instead, you will find all of the equivalent Windows commands below. The text at the bottom of the next lecture is for another option for Windows users which is Command Prompt which I do not recommend for this course (I left the text in the video for reference only):



ls

pwd

cd 

cd ..

clear

cd / **—> root director**

cd ~

cd <folder/folder/folder> ** <> means to add your own folder names that exist on your computer.

mkdir <folder>
 
open <folder> **for windows use: start <folder>
 
touch index.html  **for windows use: echo "" > index.html

open index.html **for windows use: start index.html

open -a “Sublime Text”  **for windows see the note about this at the bottom of this lecture!!

open . **for windows use: start .

mv index.html about.html

*Try using the Up and Down arrow.

 
rm <file>
 
rm -r <folder>
 
say hello **(only on Mac)**


Windows ONLY: How to open -a “Sublime Text”  in windows?

**Assuming your Sublime Text 3 was located in the "C:\Program Files\Sublime Text 3" directory**

1. In Git Bash copy paste and run:

echo 'alias subl="/C/Program\ Files/Sublime\ Text\ 3/sublime_text.exe"' >> ~/.bashrc



2. Close Git Bash and Open it again.



3. In Git bash type:

subl



Resources: Customizing Sublime Text 3

Here are my recommended resources to get your Sublime Text personalized:

1.  Material Theme
2.  Oceanic Next Colour Scheme
3.  Package Control
4.  A great article going over sublime text 3 setup

My recommended packages to install (command + shift +p):

Babel

SidebarEnhancements

A File Icon

GitGutter

BracketHighlighter

Other options other than Sublime Text 3 (Both are free):

Atom

Visual Studio Code
