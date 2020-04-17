# Sprint Challenge: Advanced CSS and Intro to JavaScript - Influential Artists

**Read these instructions carefully. Understand exactly what is expected _before_ starting this Sprint Challenge.**

This challenge allows you to practice the concepts and techniques learned over the past week and apply them in a concrete project. This Sprint explored Advanced CSS and JavaScript fundamentals. During this Sprint, you studied studied preprocessing, variable declaration, conditionals, loops, functions, arrays, and objects. In your challenge this week, you will demonstrate proficiency by creating a website for artisits with data from a `JSON` object.

This is an individual assessment. All work must be your own. Your challenge score is a measure of your ability to work independently using the material covered through this sprint. You need to demonstrate proficiency in the concepts and objectives introduced and practiced in preceding days.

You are not allowed to collaborate during the Sprint Challenge. However, you are encouraged to follow the twenty-minute rule and seek support from your TL if you need direction. Your work reflects your proficiency in Preprocessing, and JavaScript Basics.

> You have **three hours** to complete this challenge. Plan your time accordingly.

## Introduction

In this challenge, you will use a data set of influential artists to build a "influential artists" webpage. This data comes from a set of "50 influential artists" on [kaggle](https://www.kaggle.com/ikarus777/best-artworks-of-all-time). We have reduced the data to just 20 artists to make it slightly easier to work with. You can work with the full dataset as a stretch goal.

### Commits

Commit your code regularly and meaningfully. This helps both you (in case you ever need to return to old code for any number of reasons) and your team lead.

## Self-Study Questions

Demonstrate your understanding of this week's concepts by answering the following free-form questions.

Edit this document to include your answers after each question. Make sure to leave a blank line above and below your answer so it is clear and easy to read by your project manager

1. How would you describe preprocessing to someone new to CSS?

- Preprocessing allows you to better organize your styles via nesting, make widespread changes more easily, and reduce repetition. With a preprocessor you can create variables to store information you use on a regular basis (such as a main and accent colors) in one location, making it easier to update them all at once by changing a single hex code. If you have a h2 in a certain section that needs to look different from the others on your page, you can nest it within that section and style it as normal -- that will be the only one changed.

Then, the preprocessor takes all of this organized code and converts it into a regular CSS file that can be read by the browser as usual, without you having to deal with all the extra lines of code.

2. What is your favorite concept in preprocessing? What is the concept that gives you the most trouble?

- My favorite concept is the nesting. I think it's incredibly useful to be able to see ALL of the information for the header in one spot, even including the media queries. The concept that I need to get more comfortable with is mixins. I see their value but have not quite figured out when I should and should not be using them.

3. How would you explain the concept of a variable to someone new to programming?

- A variable is something that stores information for you. You can think of it as a shoebox with a label. Inside the shoebox is whatever item/information you need, and you find/access it by reading the label on the outside.

4. What is the purpose of using functions in code?

- Functions allow us to repeat actions without having to write out all of the lines over and over again. They allow us to complete tasks throughout the code and also contain related information in one spot.

5. What is a JSON data?

- JSON stands for "JavaScript Object Notation" and is used to transport data on the web as JavaScript objects, which is easy to understand. It's written in key/value pairs and contained in curly brackets.

You may need to look up an answer but, you are expected to be able to answer all these questions. Your responses contribute to your Sprint Challenge grade. Skipping this section _will_ prevent you from passing this challenge.

## Instructions

### Task 1: Project and Pre-processer Set Up

Follow these steps to set up your project:

#### Git Set up

- [ ] Create a forked copy of this project.
- [ ] Add your Team Lead as collaborator on Github.
- [ ] Clone your OWN version of the repository (Not Lambda's by mistake!).
- [ ] Create a new branch: git checkout -b `<firstName-lastName>`.

#### Preprocessor Set up

- [ ] Verify that you have LESS installed correctly by running `lessc -v` in your terminal, if you don't get a version message back, reach out to your project manager for help.
- [ ] In your project's root folder, run the following command `less-watch-compiler less css index.less`
- [ ] Verify your compiler is working correctly by changing the `background-color` on the `body` selector to `red` in your `index.less` file.
- [ ] Once you see the red screen, you can delete that style and you're ready to start on the next task

### Task 2a: Minimum Viable Product - PreProcessing

#### Import LESS Files

- [ ] Navigate to your `index.less` file. Notice the file is blank. You have been asked to use a certain import order. That order is as follows:

```markdown
1.variables.less
2.mixins.less
3.reset.less
4.general.less
5.navigation.less
6.main.less
7.cta.less
```

_You will know everything is working properly when you see the styles enabled for the provided content._

#### Home Page - Desktop HTML & LESS

- [ ] Take 10 minutes to review the code that has already been provided for you. Take time to see how the home page was built.
- [ ] Add a viewport meta tag to the head of your index.html page
- [ ] [Review the provided home desktop design file](design/Desktop.png). You are to build the missing navigation system and header image. You have been provided all content necessary in the [index.html file](index.html)
- [ ] Navigation Styles: Use the `navigation.less` file for styling.
- [ ] Main Content Styles: Use the `main.less` file for styling
- [ ] LESS Mixins: Create and use 2 different mixins to aid your styling. Use the `mixins.less` file for your mixins
- [ ] LESS Parametric Mixin: create a parametric mixin that is used to create the `contact us` button styles.
- [ ] Use at least 2 parameters to create your button
- [ ] Create a hover state that changes the opacity of images to 80%
- [ ] Use good coding practices including adding responsive breakpoints to your code with media queries

### Task 2b: Minimum Viable Product - JavaScript

Navigate to `index.js` and complete the MVP challenges. Note that you need to scroll past data (or collapse data in VScode) to find the challenges.

### Task 3: Stretch Problems

After finishing your required elements, you can push your work further. These goals may or may not be things you have learned in this module but they build on the material you just studied. Time allowing, stretch your limits and see if you can deliver on the following optional goals, also listed in `index.js`, where applicable:

- [ ] Use JavaScript to programmatically create HTML elements in the console and copy them to display all 20 artists on the page
- [ ] Create a function called `randomize` that takes a data array as an argument and returns a the same array in a randomized order.
- [ ] Use advanced array methods (.map, .reduce, .filer) to refactor your MVP code (create an array of all artists born in the 1900s with .filter, for example)
- [ ] Add responsive breakpoints to your code by using media queries
- [ ] Add CSS animations

## Resources

📚[Best Practices for Responsive Design](https://www.browserstack.com/guide/responsive-design-breakpoints)

🤝[W3 Schools - Responsive Design](https://www.w3schools.com/html/html_responsive.asp)

👀 [Styling with HTML and CSS](https://www.w3schools.com/html/html_css.asp)

## Submission format

Follow these steps for completing your project.

- [ ] Submit a Pull-Request to merge <firstName-lastName> Branch into master (student's Repo). **Please don't merge your own pull request**
- [ ] Add your team lead as a reviewer on the pull-request
- [ ] Your team lead will count the project as complete by merging the branch back into master
