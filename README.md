# chatbot

I'm making a native JS bot that could be used as a way to guide you through a website.

I started this as a little project for my portfolio, but it turned into a school project aswell.

The bot works by checking the input a user sends.
Once the bot knows what input is given, it will check if the input is the same as one of the pre programmed commands.
If that's the case then the bot will output what corresponds the input.
If the input is not a command then the bot will output something like: "I didn't quite get that".

I've added some responses to certain commands. After an input the bot will ask you a "yes or no" question to which you can respond.
Example: when the command "about" is given, the bot will ask "Would you like to know about Mees' vision? (Yes/No)". If the answer is "yes" the bot will output more, if not it resets.

It's built with a premade gulpfile and directory setup called Yeoman Web-app generator

***
## Live:
### See it in action on [my portfolio website](http://meesrutten.me)
### Or check out the most up to date version on [my CodePen](https://codepen.io/meesrutten/full/wgvpQM/)

## Current commands with outputs:
### - help
### - about
### - best work
### - vision
### - experience
### - CV
### - hobbies or interests
### - contact
### - rick roll (just try it)

***
## Features:
- You can send a command to the bot to which it will respond with a corresponding answer or a message that it doesn't recognize the input.
- It recognizes commands in sentences.
- It can output images, redirect you to websites, respond with a yes or no question and output according to your answer.
- The bot has a Levenshtein formula for recognizing spelling errors
***
## Known bugs:
- Check out the issues section.

by Mees Rutten, 2017
@MeesRutten
