# Setting up a Professional Data Science Environment

## Introduction

If you want to become a professional data scientist, it’s important to take a little time to “set yourself up for success” by installing and learning to use the right tools on your computer. 

## Objectives

You will be able to:

 - Compare and contrast local environment setup vs. using a cloud environment
 - List the professional data science tools used in the Flatiron School DS program
 - Describe the computer prerequisites for a professional data science environment setup

## Local Environment Setup

Whether at Flatiron School or in previous educational or tutorial contexts, you have probably encountered a ***cloud environment***. In a cloud environment, you connect using your browser to some external server that hosts the necessary software and "just works". Cloud environments are helpful for getting a quick start, and some companies are even moving towards using them for everyday work!

However cloud environments also have some major limitations. One is that they **require a stable internet connection**, even though many coding and data analysis tasks do not need to use the internet. Another is that their **configuration and installed software tends not to be customizable by the user**. If you want to use the latest version of a library, but your cloud tool doesn't have that version, you are usually out of luck and just need to wait for the next system upgrade. Finally, **you are dependent on the computational resources available** on the cloud platform. Unless you are paying a premium for these services, your personal computer is likely to have more (dedicated) storage space and memory capacity than a cloud environment.

For these (and other) reasons, many data scientists and other tech professionals prefer to work in a ***local environment***. This means installing all of the relevant tools and libraries onto your laptop or desktop computer. It takes more time and sometimes some troubleshooting than using a cloud environment, but allows you more freedom! With a local environment setup, you'll be able to work without an internet connection, customize your software, and utilize the full power of your machine.

## What Tools Do Professional Data Scientists Use?

- **Git** - Git is a version control system. It’s a way of keeping track of all the changes made across your project. Think of it like “track changes” in Word - but with the ability to track changes across multiple documents. At Flatiron School, we use Git to keep track of all of the lessons we create and all the changes we make to them.
- **GitHub** - GitHub is a website where data scientists (and programmers) can save their work in case their computer breaks, and share it with their team or the world! At Flatiron School, we store all of our lessons on GitHub.
- **Python** - There are many languages that can be used for data science, but these days most data scientists are using Python to write their code.
- **Jupyter Notebook** - Most of those data scientists use Jupyter Notebook for writing their Python code. Jupyter Notebook is a tool that allows you to mix comments in-between your code snippets so you can document and share your thought process and make it easier for others to review, replicate, and expand on your work. It's also what we're using for almost all of our lessons in this course!
- **Anaconda** - Anaconda is one of the most popular ways for data scientists to install Python and Jupyter on their computers. It also provides package management and virtual environments so you can get all the latest data science tools running, like NumPy, Scikit-Learn, and Tensorflow, and so you can use different versions of Python and your packages for different projects without them conflicting with each other.

In the following lessons you'll first install and configure Git, then you'll use Anaconda to set up a Python environment that includes compatible versions of Jupyter Notebook and the other libraries used for data science.

## Computer Prerequisites

There are many amazing computing devices available these days, but not all of them will allow you to do data science. We love smartphones, flip phones, Chromebooks, tablets (including iPads), Game Boys, Nintendo Switches, Rokus and Arduinos. But you’re not going to be able to complete this course on any of those devices.

You’re going to need a computer (laptop or desktop). It should be running a recent (last 3-4 years) version of MacOS, Windows or Linux, and ideally, it should have 8Gb of RAM and at least 20Gb free hard drive space.

## Summary

Cloud environments make a great "quickstart" but most data science professionals prefer a local environment setup. In the next few lessons you'll set up your own local environment and configure some of the primary tools that you'll use as a data scientist!
