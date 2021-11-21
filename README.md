# Who I am

Someone that since a long time love technology. I learned to program with BASIC in 1985, when I was 12 years old and never stopped learning about everything related with computers, specially software. Now I have a BS in CS and a MSc in *Computer Forensic and Information Security* and I still love to learn new things.

<a href="https://github.com/itamarc" alt="github" target="_blank">
<img src="https://img.shields.io/badge/GitHub-000000?&style=flat-square&logo=GitHub&logoColor=white">
</a>
<a href="https://www.linkedin.com/in/itamarc" alt="linkedin" target="_blank">
<img src="https://img.shields.io/badge/LinkedIn-%230077B5.svg?&style=flat-square&logo=linkedin&logoColor=white">
</a>

# Highlighted Projects

Below you can find some of the open source projects I developped and that are available in repositories here at GitHub.

## ITemplate

ITemplate is a Java library to fill text templates with variable content.

Purely in Java.

- [https://itamarc.github.io/itemplate/](https://itamarc.github.io/itemplate/)

## action-itemplate-ghpages

Action to publish GitHub Pages for a repository automatically using themes or custom templates (using ITemplate).

Made with Java, Docker, some bash, git, HTML, CSS and JavaScript.

The pages of my repositories are made with it, using the pre-build themes.

- [https://itamarc.github.io/action-itemplate-ghpages/](https://itamarc.github.io/action-itemplate-ghpages/)

## DirSynch

DirSynch is a tool to synchronize directory contents.

It's made with Java and Swing and even support comparing files with the hash values of their content.

- [https://itamarc.github.io/dirsynch/](https://itamarc.github.io/dirsynch/)

## Hangman

It's a very simple hangman game I created to show my daughters a little bit of what it's like to create a web app.

It uses only HTML, CSS, JavaScript and SVG.

To access the game:

- [https://itamarc.github.io/hangman/](https://itamarc.github.io/hangman/)

To see the source:

- [https://github.com/itamarc/hangman](https://github.com/itamarc/hangman)

## Hangman - React Edition

While learning React, I re-created the Hangman game using ReactJS.

To access the game:

- [https://itamarc.github.io/hangman-react/](https://itamarc.github.io/hangman-react/)

To see the source:

- [https://github.com/itamarc/hangman-react](https://github.com/itamarc/hangman-react)

## Jobs Data Dashboard

⚠️ This project is a work in progress! ⚠️

My personal project to create a system with various technologies, just for knowledge. A job seeker system to grab data from several sources, compile them and shows it in graphical ways.

I'm using different technologies and tools in each part of this system, to be able to learn more.

There are some documentation of what I plan to build and some parts are already made.

So far, I used Python, MongoDB, a REST API, a Lambda Function made in Java and AWS SQS. The JDD Grabber runs in an AWS EC2 machine with Linux.

You can check the docs repository at:
- [https://itamarc.github.io/JobsDataDashboard/](https://itamarc.github.io/JobsDataDashboard/)

(See the [README](https://itamarc.github.io/JobsDataDashboard/README.html) for details about the project)

### JDD LogFunc

This is a AWS Lambda Function made in Java to receive the log messages through a AWS SQS messages queue and insert them into a MongoDB collection.

The idea was to centralize in it log messages comming from all other components in the system.

Source code repository:

- [https://github.com/itamarc/JobsDataDashboard-jddlogfunc](https://github.com/itamarc/JobsDataDashboard-jddlogfunc)

### JDD Grabber

This is a component made in Python to grab data from jobs online services using their APIs.

The Grabber saves the grabbed data into a MongoDB collection and used JDD LogFunc to save the logging messages, putting them in the SQS queue.

Source code repository:

- [https://github.com/itamarc/JobsDataDashboard-jddgrabber](https://github.com/itamarc/JobsDataDashboard-jddgrabber)

## Mogno

Mogno Lib for web applications development in Java (a project from a long time ago).

[https://github.com/itamarc/mogno](https://github.com/itamarc/mogno)

## Mogno-Studio

Mogno Studio, an environment to visually build an application with Mogno lib.

[https://github.com/itamarc/mogno-studio](https://github.com/itamarc/mogno-studio)
