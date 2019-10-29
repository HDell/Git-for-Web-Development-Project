# Git for Web Development Project
In this project you will be using the concepts learned in the Git for Web Development lesson to fork/clone/push/and submit a PR for each project during this sprint.

This project consists of two parts:

## Part One:
You will need to follow the Lambda School Git Workflow to add a file to this project follow the steps below:

- [ ] Create your own version of this repo - Fork
- [ ] Add your TL as a collaborator
- [ ] Clone this repo
- [ ] Create a branch `git checkout -b 'firstName-lastName'`
  - [ ] Add a file to the project called `yourFirstName-yourLastName`.txt. This file can contain anything.
  - [ ] Run your usual git commands for adding/committing and pushing **Be sure to push to your branch!**
- [ ] Create a Pull-Request to submit your work
  - [ ] Use your own student fork as the base (compare across forks, base-fork -> master).
  - [ ] Add your TL as a reviewer on the Pull-Request
- [ ] TL then will count the Assignment as done by merging the HW back into master "STUDENT FORK".

## Part Two:
Go back and follow the same steps for your [UI-III-Flexbox project](https://github.com/LambdaSchool/UI-III-Flexbox) and your [User Interface - Great Idea Project](https://github.com/LambdaSchool/User-Interface).

In order to do this, you **do not** need to create new forks of these projects. Follow the steps below for each project:

- [ ] Add your TL as a collaborator to your fork. 
- [ ] Go into your project folder, make a new branch `firstname-lastname`
- [ ] Add your first and last name to the `README.md` file in the project and save.
- [ ] add/commit/and push to your own branch  **Be sure to push to your branch!**
- [ ] Create a Pull-Request to submit your work
  - [ ] Use your own student fork as the base (compare across forks, base-fork -> master).
  - [ ] Add your TL as a reviewer on the Pull-Request
- [ ] TL then will count the Assignment as done by merging the HW back into master "STUDENT FORK".

## Stretch
- [ ] While the processes learned here will set you up to be successful in most situations, they are just the tip of the iceberg in learning Git. Independently research the following topics to learn more about Git.
  - [ ] Research and understand what a `merge conflict` is and how to resolve it.
  - [ ] Research the Git commands `pull`, `rebase`, `merge`. These commands will allow you to bring in changes that other developers push to the master branch.
  - [ ] Research the Git commands `reset `, `revert`, `clean`. These commands will allow you to go back and amends previous commits you have made.

- [ ] Research and set up a Graphical User Interface (GUI) Git console. 

- [ ] Research and setup SSH keys with GitHub, so that you do not need to input your username/password each time you push. 


## CodePen URL
[CSS + HTML Practice](https://codepen.io/hdell/pen/jOOGbmM?editors=1100)

## Questions and Answers
    1. What is Semantic HTML?
	- Semantic HTML are tags that imply meaning.
    2. What is HTML used for? 
	- HTML is the language used to describe the layout of a browser webpage.
    3. What is an attribute and where do we put it? 
	- An attribute goes within a tag (between < & >).
    4. What is the h1 tag used for? How many times should I use it on a page?
	- An h1 tag is akin to a title in the body. It should only be used once.
    5. Name two tags that have required attributes
	- img tags and input tags.
    6. What do we put in the head of our HTML document? 
	- meta tags, script tags, title tags are some
    7. What is an id? 
	- A unique tag identifier
    8. What elements can I add an id to? 
	- Every element.
    9. How many times can I use the same id on a page? 
	- Once
    10. What is a class? 
	- An attribute used to group elements (to be referenced together)
    11. What elements can I add a class to? 
	- Every element.
    12. How many times can I use the same class on a page? 
	- No limit
    13. How do I get my link to open in a new tab?
	- Use an href with a target="_blank" attribute
    14. What is the alt attribute used for? 
	- It's used to make content accessible to those with disabilities
    15. How do I reference an id?
	- Use a #
    16. What is the difference between a section and a div
	- A section is a semantic divider, whereas a div is a presentational (structural) divider
    17. What is CSS used for? 
	- Adding visual design to plain HTML
    18. How do we select an element? Example - every h2 on the page
	- call the tag (h2 {})
    19. What is the difference between a class and an id? - Give me an example of when I might use each one
	- They are defined differently. An id is specifically for one element (tag), whereas a class is for a group of elements (tags)
    20. How do we select classes in CSS?
	- Use a .
    21. How do we select a p element with a single class of “human””?
	- p.human {}
    22. What is a parent child selector? When would this be useful? 
	- A parent child selector is a way of calling all of the elements within another element (e.g. h2 p {} - which selects all the p tags under an h2 tag).
    23. How do you select all links within a div with the class of sidebar?
	- div a.sidebar (if by link, the question was referring to an anchor tag)
    24. What is a pseudo selector?
	- a descriptive part/state of an element that doesn't specifically refer to an html element/attribute (e.g. "first-child")
    25. What do we use the change the spacing between lines?
	- span tag
    26. What do we use to change the spacing between letters?
	- the letter-spacing (with a size value) property in css can be used
    27. What do we use to to change everything to CAPITALS? lowercase? Capitalize?
	- the text-transform: uppercase, lowercase, and capitalize properties in css can be used respectively
    28. How do I add a 1px border around my div that is dotted and black?
	- div.myDiv { border: 1px dashed black; }
    29. How do I select everything on the page? 
	- * {}
    30. How do I write a comment in CSS?
	- /* comment here */
    31. How do I find out what file I am in, when I am using the command line? 
	- (file?) pwd would be used to find out what *directory* you are in
    32. Using the command line - how do I see a list of files/folders in my current folder?
	- ls
    33. How do I remove a file via the command line? Why do I have to be careful with this? 
	- rm <filename> (permanently deletes)
    34. Why should I use version control? 
	- to keep a detailed record of reversible changes on solo or group projects
    35. How often should I commit to github?
	- often (every ~20 min was recommended by Brit)
    36. What is the command we would use to push our repo up to github? 
	- git push
    37. Walk me through Lambda's git flow. 
	- The git flow follows a process of: 
		- forking a project
		- adding your TL as a collaborator
		- cloning the repo to your local environment
		- creating a branch with your first and last name (separated by a dash)
		- and then adding, committing, and pushing as well
		- finally, making a pull request to your own master branch
		- and adding your TL (now a collaborator) as a reviewer on the request

### Stretch Questions
    1. What is the difference between an inline element and a block element?
	- A block corresponds to the box model and refers to elements such as divs, whereas inline elements work within blocks and refer to elements such as spans
    2. What happens when an element is positioned absolutely? 
	- The element does not take the window-size or nearby elements into account and is forcefully positioned
    3. How do I make an element take up only the amount of space it needs but also have the ability to give it a width?
    -  Give the selector a "box-sizing: border-box" property.
    4. Name 3 elements that are diplay block by default, 2 elements that are display inline by default and 1 element that is display inline-block by default
    - Display Blocks:
    	- <div>
    	- <section>
    	- <h1>
	- Display Inline:
		- <span>
		- <a>
	- Inline Block:
		- <img>
    5. In your own words, explain the box model. What is the fix for the box model?
    - The box model describes how every single element in CSS is a (sqaure-shaped) box. Boxes include content and surrounding space (padding, margins, border, & backgrounds). In order to keep things within a specified height/width, one must use "box-sizing: border-box" property.

