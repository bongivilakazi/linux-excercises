# linux-excercises
Search...
Umuzi Remote work
1. Syllabus
2. Topics
3. Workshops
4. Projects
Android with Kotlin Projects
Constraint Layout Using Layout Editor
Data Binding Basics
Linear layout using the Layout Editor
User Activity
Androids
Incremental Counter
Information Page
Angular Tutorial
Assertive programming kata
Bootcamp Writing Assignment
Build your first personal website
Capstone project
Gmail Text Scraper
Pair Stairs
Spaced Repitition machine to help you remember what you read
The Quizmaster
build a Chrome Extension that measures time spent in meetings
Consume Github API
DAGs with Airflow
Data-science-specifics
MEDIUM: Cross-validation & Simple Linear Regression
Dashboard Assignment
EASY: Google Data Studio Assignment
HARD: Live Dashboard Assignment
EASY: Plotly Dashboard Assignment
HARD: Webscraping and Live Dashboard Assignment
Data Modelling Challenges
HARD: Network Intrusion
Data Visualisation Projects
MEDIUM: Evolution of Linux Visualisation
MEDIUM: Financial Services Use in Tanzania
MEDIUM: Data Wrangling
MEDIUM: Decision Trees
Introduction to Jupyter Notebooks
MEDIUM: K-Means Clustering Assignment
Logistic regression
MEDIUM: Predict breast cancer
MEDIUM: Predict credit card approvals
MEDIUM: Multivariate Linear Regression
MEDIUM: Natural language processing
MEDIUM: OOP for data science
MEDIUM: Statistical Thinking
Webscraping Assignment
Distributed workloads with ZeroMQ
Email random inspirational quote
Expose a simple REST api for your game
ExpressJS
Game of life: Angular elements
Git Basic Exercises
How to submit your project
Java Projects
Consume own api using curl
File IO + Logging + Errors
Introduction to Spring Boot
Introduction to Spring Boot - part 1
Introduction to Spring Boot - part 2
Introduction to Spring Boot - part 3
Introduction to Spring Boot - part 4
Introduction to Spring Infrastructure
Introduction to Spring Infrastructure part 1
Introduction to Spring Infrastructure part 2
Introduction to Spring Infrastructure part 3
Java Generics
Java collections
Java data structures
SQL Extended
Level 1 programming katas
Linux challenges
Advanced Linux challenges
Beginner Linux challenges
Memory Game: rebuild using a modern web frontend framework
Memory game in vanilla js
Memory game using Angular Material
Nodejs Challenges
1: Node & File IO
2 (alt): Node & mongoDB assignment
3: Express, forms and templates
4: Expose a JSON API
Add a little Ajax
Node & SQL assignment
OOP Excercises
Animals
Animals Part 1. OOP basics
Animals Part 2. Adding Tests
Bank Accounts
Dice
Person
Pre bootcamp challenges
Python projects
Database migrations with SQLAlchemy
Django - exposing a REST api with a real database
Getting to know Python
Python and Kafka
Python and MongoDB
Python and Spark
create a REST api to interact with actual database
expose a simple JSON rest api
RabbitMQ
SQL
Semitone Challenge
1. semitone difference - basic algorithm
1. Make a simple GUI
3. Advanced algorithm
4. A gui that is more...awesome
Add Redux to your semitone game
Test Driven Development
Password Checker
Add logging to password checker
password-checker
MEDIUM: Resturaunt menu system
EASY: factorials
MEDIUM: lots and lots of tdd katas
MEDIUM: recursive search
EASY: simple-calculator part 1
MEDIUM: simple-calculator part 2
string-calculator
HARD: ten-pin bowling scoring system
Validating user input for web
consuming APIs with the requests module
iOS Mobile
Codable, File Manager, URL
Drag and Drop, Multithreading and Delegation
More Swift, Gestures and Animations
Multithreading Layout and Other Functionality - Animated Set
Multithreading Layout and Other Functionality - Graphical Set
Swift and More
5. Katas
6. Department Processes
Code Review Feedback Notes
Contact
Credits
How to Contribute
Online Learning and bootcamp
More
 Github repo
 Credits
  
 Edit this page Umuzi Tech Department > Projects > Linux challenges > Beginner Linux challenges
BEGINNER LINUX CHALLENGES
Story points	1
Tags	bash
Hard Prerequisites	
TOPICS: Introduction to Linux
TOPICS: Introduction to Bash and the terminal
Soft Prerequisites	
WORKSHOPS: [TODO] Introduction to Linux: Live demo
To submit this project follow the link below: TILDE
Submission guidelines
While you work through this project you will save your script commands in a number of files called shell scripts, name them by task and sub task number i.e. 1-2, they have the extension .sh. You’ll be handing those in later. In general we use a tool called Git and a platform called Github for project submissions but this will be covered later in the course.

Task 1 : Basic Task
Open a linux terminal. Now do the following from the command line.

type in ls and press enter. What do you see? What does this mean?
type in pwd and press enter. What do you see? What does this mean?
Make a new directory called workspace then cd into your new directory
type in ls and press enter. What do you see? What does this mean?
Make a new file called README.md (you can use the touch command to do this)
Make a copy of README.md, name your copy CHANGELOG.md
Resources
Linux basic commands
Task 2 : Absolute and Relative Paths
Create an empty file named exercise.md and move this file to the /tmp directory, using a relative pathname. Then, delete this file using an absolute pathname.

Resources
Paths in linux
Absolute and Relative Paths (video)
Task 3 : cat commands
Create 3 files namely umuzi.md, recruits.md and cohort.md.
Fill all 3 files with contents of your choice. Maybe some nice poems about you MUB experience.
Write a script that concatenates the content of umuzi.md, recruit.md, cohort.md and displays the result on the screen.
Write a script that takes the content of umuzi.md, cohort.md and recruits.md to print/store the output into a new file named summary.md.
use the command line to append the words “The End” to summary.md. Be careful not to overwrite the exiting contend
Resources
Standard File Streams (video)
The cat commands
Task 7 Text editor
Using nano text editor create a file named my_bio.md
Save the file and close the editor
Create a folder named my_files and move my_bio.md within.
Resources
https://www.lifewire.com/beginners-guide-to-nano-editor-3859002
Task 8 Update and Upgrade
Update your system with sudo apt update.
Use the sudo apt upgrade to apply the updates downloaded and select Y for Yes.
When installing a package you use sudo apt install package_name.
Install a specific package called tree; using sudo apt install tree. You might ask what is sudo? Sudo allows you to run programs with the security privileges of another user, it is also referred to as a superuser. It is often used to install, start and stop applications that require root priviledges.
dpkg is a tool to install, build remove and manage Debian Packages. This is how you use dpkg, we will install VS Code in this example. Firstly download VS Code VS Code Download then open your terminal in the current folder of the item you just downloaded, type in sudo dpkg -i filename.deb, you will then enter your password and the package will install.
Resources
https://www.youtube.com/watch?v=o2JyzCH8tlM
RAW CONTENT URL

