# An Opinionated Guide for Aspiring Developers
by: Coleman Word

**There are many like it, but this one is mine**

Table of Contents
=================

   * [An Opinionated Guide for Aspiring Developers](#an-opinionated-guide-for-aspiring-developers)
   * [Table of Contents](#table-of-contents)
   * [Essential skills for every carreer path](#essential-skills-for-every-carreer-path)
      * [Integrated Development Environments](#integrated-development-environments)
      * [Version Control](#version-control)
      * [Documentation](#documentation)
      * [Experimentation](#experimentation)
   * [Choosing a Career Path](#choosing-a-career-path)
      * [I am interested in designing user-interfaces](#i-am-interested-in-designing-user-interfaces)
      * [I am interested in programming business logic](#i-am-interested-in-programming-business-logic)
      * [I am interested in data science](#i-am-interested-in-data-science)
      * [I am interested in hacking](#i-am-interested-in-hacking)

When I first began my journey into software development, I was overwhelmed
by the complexity of software development and the level of fragmentation 
amongst common jobs in the market. 

Because of this, I spent hundreds of hours mastering computer science, computer
networking, linux, windows, 4 seperate programming languages, 3 major cloud 
platform vendors, and MANY command line interface tools before finally deciding
the route I wanted to take with my career. 

This document is meant to highlight some of the advice and general information
I would give to myself if I could go back in time..

Keep in mind, that I place a high emphasis on where the market is moving and de-emphasize
skills/jobs that are prevelant today, but, in my opinion, are being actively 
replaced by skills/technologies that have come out in the last few years.

*******************************************************************************************

# Essential skills for every carreer path
Start using the following tools and technologies as soon as possible. They are tools that 
will make developing your projects much easier and should be thought of as supplements to 
your development workflow.

## Integrated Development Environments

<details><summary>show</summary>
<p>

**Overview**


An integrated development environment is an application you can download onto your 
PC for actively developing your projects. They generally have many features like 
an integrated terminal, file organization, debugging, and extensions that can help you
develop clean code faster.

**Tips**

* VScode is free and by far my favorite IDE. 

**Resources**

* [Getting Started w/ VScode](https://code.visualstudio.com/docs/introvideos/basics)

</p>
</details>

## Version Control
<details><summary>show</summary>
<p>

**Overview**

Version control is a system that records changes to a file or set of files over time so that you can recall specific versions later. The most popular tool for code version control is Git. A Git repository is where you will keep the files that make up your application.
**Tips**

* Get a github account
* Keep all your projects in seperate git repositories
* Master the git cli
* Use GitHub as a search engine to explore projects- A good source for inspiration.

**Resources**

* [Git Tutorial](https://guides.github.com/activities/hello-world/)
* [GitHub](https://github.com/)

</p>
</details>

## Documentation
<details><summary>show</summary>
<p>

**Overview**

Once you have a Github account set up, it will be essential to create documentation
for your projects/code. This is done by creating a README.md file in the root of the project
folder. The file extension for README is generally markdown. Markdown is a markup language that
allows you quickly format documents and insert elements like headings, lists, code blocks, and much 
more. 

**Tips**

* Markdown is easy, take a day or two to learn it
* Creating documentation is a good way to learn- Document every step of your development workflow so that
you have a very clear understanding of what it is you're doing.
* Documentation will turn your GitHub repository into your future resume
* Documenation allows others to understand and reuse your code.
* Code without documentation is useless

**Resources**

* [Markdwon Cheatsheet](https://guides.github.com/pdfs/markdown-cheatsheet-online.pdf)
* [Markdown Newtab](https://chrome.google.com/webstore/detail/markdown-new-tab/demppioeofcekpjcnlkmdjbabifjnokj?hl=en)

</p>
</details>

## Experimentation
<details><summary>show</summary>
<p>

**Overview**

Once you're ready to start programming, you'll immediately start wondering where your code is 
supposed to run. Programs in development are generally run on your personal PC, while finished
projects are generally run on dedicated servers. A problem many developers encounter is "My code runs
on my PC, but it doesn't work on a dedicated server!". This is because when you're developing on your
PC, you download code dependencies(libraries/frameworks) which your code relies on to execute. When you 
move your files to a server, the dependencies are no longer in place. 

To solve this problem, I recommend using a portable sandbox environment on your PC so that you can 
transfer your project AND all of it's dependencies to other computers. 

**Tips**
* Learn and use Docker to stage your programs. 
* Docker has created a paradigm shift within the industry and is very popular
* Create a dockerhub account
* Learn how to create dockerfiles
* Setup an Amazon Web Services account once you want to deploy your project on a dedicated server
* This will take time to master
* This will drastically improve your marketability in the application process

**Resources**

* [Getting Started](https://docs.docker.com/get-started/)
* [DockerHub](https://hub.docker.com/)
* [Interactive Tutorials](https://www.katacoda.com/courses/docker)
* [Amazon Web Services](https://aws.amazon.com/)
* [Docker Certification](https://success.docker.com/certification)
* [AWS Solutions Architect Certification](https://aws.amazon.com/certification/certified-solutions-architect-associate/)
* [Docker Online Courses](https://www.udemy.com/topic/docker/)
* [AWS Online Course](https://www.udemy.com/aws-certified-solutions-architect-associate/)
</p>
</details>


If you master the aforementioned tools/methodologies, you will be able to get a job as an intern/jr level
devops engineer which will earn you around a $70-90,000 salary right off the bat. These skills are desperately needed in the industry.

If you also acquire the Docker and Solutions Architect certifications, you will be looking at postions
in the $100-$125,000 range.

Skip the experimentation portion of the methodologies listed above if you want to focus on a programming
language right off the bat. If you want nothing to do with computer networking and application deployment,
look into a solution like [Heroku](https://signup.heroku.com/?c=70130000001xDpdAAE&gclid=CjwKCAjw85zdBRB6EiwAov3RinnYvtomxd8gs31O7l4-c7YEOLptqTaPq9rMl86sxBnXc1fr4apWjBoCxvMQAvD_BwE) which
will magically deploy your code so you can focus on strictly programming.

---

# Choosing a Career Path

**Please navigate to the statement that most descibes your current interests**


## I am interested in designing user-interfaces
>> “Rule of thumb for UX: More options, more problems.”

**Difficulty: 3/5**

**Timeline: 6 months**

* You're creative
* You want to create projects that users directly interact with
* You like websites and applications that are easy and intuitive

<details><summary>show</summary>
<p>

**Overview**

The positions you'd be interested involve designing and programming what we call the
"frontend" of applications. The front-end is what users see, and directly interact 
with. 
The frontend of an application, whether is a website, desktop app, or mobile app,
communicates with the "backend" which executes the "business logic" of the application.

The front-end should be designed to be visually appealing, and intuitive for it's users.

In my opinion, the goal of a frontend developer should be to create a user interface that
can be used without any training. The design makes the business logic of the application
self-explanatory. 

For example: Instagram doesn't require users to read through documentation to begin using
it. It is popular because anyone can download the application and immediately start using
it.

**Job Titles**

 * UI Designer
 * UX designer
 * Front-end Developer
 * Front-end Designer

**Average Salary: $85,000**

**Programming Languages**

* HTML 
* CSS
* Javascript

**Certifications**

* [Lambda School](https://lambdaschool.com/courses/cs/web/)
* [Galvanize](https://www.galvanize.com/denver-platte/javascript-accelerated)
* [Pluralsight](https://www.pluralsight.com/paths/javascript)

**Tips**

There are many "flavors" of javascript. I'd highly recommend learning the framework "React" after
learning the basics of javascript, HTML, and CSS since it is the most popular, it's in high demand, and you can use it to program the front-end of websites AND mobile apps.

**Resources**

* [HTML & CSS Course](https://www.udemy.com/html-tutorial/)
* [Playground](https://stackblitz.com/)
* [React Javascript](https://reactjs.org/)

</p>
</details>

## I am interested in programming business logic
>> "Why do we never have time to do it right, but always have time to over?"

**Difficulty: 4/5**

**Timeline: 1 year**

* You're a natural problem solver
* You're incredibly logical
* You want to learn how to program
* You're more interested in the functional portion of applications, as opposed to the appearance

<details><summary>show</summary>
<p>

**Overview**


**Job Titles**
* Backend Engineer
* API Developer
* Software Developer

**Average Salary: $100,000**

**Programming Languages**

* Python
* Node.js
* Golang

**Certifications**


**Tips**

* Learn SQL(database language)
* Understand what a REST API is
* Learn node.js if you want to program web applications
* Learn node.js if you want to become a "full stack" developer by just learning javascript
* Learn python if you want to learn programming quickly
* Learn python if you may want to transition into data science in the future
* Learn golang if you want to develop API's
* Learn golang if you are interested in "microservices"
* Programming languages in descending order by market demand: node.js, python, golang
* Programming languages in descending order by average salary: golang, python, node.js
* Programming languages in descending order by future job growth: 3-way tie

**Resources**

* [Node.js](https://nodejs.org/en/)
* [Node Playground](https://www.katacoda.com/courses/nodejs/playground)
* [Python](https://www.python.org/)
* [Python-Playground](https://www.pythonanywhere.com/)
* [Golang](https://golang.org/)
* [Golang-Playground](https://play.golang.org/)

</p>
</details>



## I am interested in data science
>> "Data is what we collect and store. It becomes information once we analyze it. It becomes knowledge once we understand it."

**Difficulty: 4/5**

**Timeline: 1 Year**

* You've always been good at math
* You've excelled in collegiate-level math classes
* You're interested in artificial intelligence
* You understand how data can be used to create insight into business processes

<details><summary>show</summary>
<p>

**Overview**

Data science is exploding right now. With the amount of data being produced at an exponential rate, companies need specialists that can turn "dark data" into actionable insights. A career in data science can also lead to machine learning and artificial intelligence as well. Computers can be used to analyze large datasets, perform tasks, and correct themselves based on the outcome of their behavior in relation to the desired outcome. Start with basic data analysis -> data engineering -> data science -> machine learning. This will take time.

**Job Titles**

* Data Analyst
* Data Engineer
* Business Intelligence Developer
* Data Scientist
* Machine Learning Engineer

**Average Salary: $60-$200,000**

**Programming Languages**

* Python

**Certifications**

* [Top 15](https://www.cio.com/article/3222879/certifications/15-data-science-certifications-that-will-pay-off.html)

**Tips**

* Your integrated development environment is now the Jupyter Notebook
* Learn Numpy, Pandas, SQL, Scikit, and Matplotlib
* You need a large amount of data to do data analytics/science
* Social media APIs like Twitter(tweepy) are a good source of data
* Stock Exchanges are a good source of data
* Learn Tensorflow if you want to get into machine learning
* Use Python 3 
* Use Anaconda- package for python that includes everything you need to get started.

**Resources**

* [Colaboratory Notebook](https://colab.research.google.com/notebooks/welcome.ipynb#recent=true)
* [Numpy](https://www.machinelearningplus.com/python/numpy-tutorial-part1-array-python-examples/)
* [Anaconda](https://www.anaconda.com/enterprise/?gclid=CjwKCAjw85zdBRB6EiwAov3RioX6LlRXDdamtUy229SGilN_oFWUVGxf-W5lwdUTk_xgrvBK4Y5ehRoCOLkQAvD_BwE)
* [Tensorflow Tutorial](https://www.tensorflow.org/tutorials/)

</p>
</details>



## I am interested in hacking
>> "The Internet is a worldwide platform for sharing information. It is a community of common interests. No country is immune to such global challenges as cybercrime, hacking, and invasion of privacy.


**Difficulty: 5/5**

**Timeline: 1 year**

* You have a strong understanding of computer networking
* You're patient
* You're more interested in utilizing already developed"tools" as opposed to programming the tools themselves
* You're manipulative

<details><summary>show</summary>
<p>

**Overview**
If you're interested in hacking, you'll want need to become extremely well-versed
in computer networking. Generally, you will want to master certain tools that 
are available to perform attacks on vulnerable networks. You should never perform attacks on real systems, rather, there are ways to setup vulnerable servers to 
practice. There are many jobs in cybersecurity that will be available to you if
you become fluent in computer networking and penetration testing. 

**Job Titles**

* Ethical Hacker
* Penetration Tester
* Cybersecurity Analyst
* Network Engineer
* Systems Administrator

**Average Salary: $100,000**

**Programming Languages**

* Python
* Bash
* Powershell

**Tools**

* Wireshark
* Shodan
* Metasploit
* Nmap

**Certifications**

* Comptia Network +
* Comptia Security +
* Comptia PenTest +
* Cisco Certified Network Associate Security

**Tips**

* Hacking is hard and takes patience
* Hacking very often requires social engineering and/or physical proxemity to the target

**Key Terms**

* The OSI Model
* Malware
* Encryption
* Tor
* Social Engineering
* Phishing
* Root Kit
* Remote Access Trojan
* Ransomware
* Crypto-malware


**Resources**

* [Comptia Certifications](https://certification.comptia.org/)
* [Metasploit](https://www.metasploit.com/)
* [Wireshark](https://www.wireshark.org/)

</p>
</details>



---
