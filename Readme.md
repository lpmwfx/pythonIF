
# This Project is about Interactive Fiction
# Some Thoughts and History
I have fooled around with IF for some time now. I tried some of the systems out there for text-based games. The system I liked the most was TWINE from [Twinery](#). It had most of what I needed but I still ended up having to tweak it too much and I could not change the output format easily. So I set out looking for other ideas. 
I found some of the other sources compilers out there, like [Tweego](https://www.motoslave.net/tweego/ "Twego") written in GO.  A command-line Twine compiler using some kind of markdown input format. I really liked the way to work with this. I could write my story in several markdown files and in the end compile them to the final HTML Twine story. However, I do not like the single HTML file format, and I above all do not like that the story progress is saved to the browser history. 
# My Project
The Twine system has a lot of good things going for it, but I think I might have to make my own version in Python. Maybe I'll use Tweego because it can compile to JSON format. Which is easy to work with. Maybe I write my own compiler and my own template. Who knows. For now, my project is in the thinking phase, 

## Goals
- I want an interactive fiction system that like Twine produces a book like result. Not an RPG system
- I must handle multimedia well like audio, pictures, SVG and video
- I want a sort of TOC system like in a book that can be crossed of like a course sheet. 
- I must save online 
- It must have a game-system usable for games and courses and books
- I must have a user login to some kind of bookshelf. 
- It must have building payment
- I must have an admin backend
- I must have a bookstore frontend for books, games and courses
- All must be usable on mobiles, tablets and computers
- All must be in an app format from Appstore and Google Play and an online format via a browser from Chrome apps Store and Windows Store, maybe some Linux app stores. 
## Thoughts
- I will code it all in Python and some JS and HTML/CSS
- I need some UI like Kivy for all apps

## Projects
This will not be one single project but several small projects. 

1. A project doing the compiler like Tweego or its output in JSON
2.  A project doing the front and back of the store
3.  A project making the store into apps and find publishing options
4. A pub project of each book/course or game