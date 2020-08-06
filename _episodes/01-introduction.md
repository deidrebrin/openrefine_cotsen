---
title: "Introduction"
teaching: 10
exercises: 0
questions:
- "What is OpenRefine useful for?"
objectives:
- "Describe OpenRefine’s uses and applications."
- "Introduce some of OpenRefine's features."
- "Locate helpful resources to learn more about OpenRefine."
keypoints:
- "OpenRefine is a powerful, free and open source tool that can be used for data cleaning."
- "OpenRefine will automatically track any steps allowing you to backtrack as needed and providing a record of all work done"
---

# Lesson

## What is data cleaning exactly?

* Errors in the data are identified and corrected.
  * Typos, incorrect units
* Formatting is made consistent across the entire dataset.
  * Standardize spellings or date formats
* Changes to terms across the entire dataset.


## Motivations for the OpenRefine Lesson

* Data are often messy. OpenRefine provides a set of tools to allow you to identify and amend what is making the mess.
* It is important to know what you did to your data, as you are doing it and in the future.
*  It is important for your colleagues and the field to know what you did to your data. Cultural heritage domains are dependent on reusing data - understanding and trusting data requires knowledge of collection and processing procedures.
* Additionally, journals, granting agencies, and other institutions are requiring documentation of the steps you took when working with your data. With OpenRefine, you can capture all actions applied to your raw data and share them with your publication as supplemental material.
* All actions are easily reversed in OpenRefine.
* When you save your work it will be to a new file. OpenRefine always uses a copy of your data and _does not_ modify your original dataset.
* Data cleaning steps often need repeating with multiple files. OpenRefine keeps track of all of your actions and allows them to be applied to different datasets (aka new data from the latest field season).
* Some concepts such as clustering algorithms are quite complex, but OpenRefine makes it easy to use them and harness their power.

## Features

* Open source ([source on GitHub](https://github.com/OpenRefine/OpenRefine)).
* A large growing community, from novice to expert, ready to help. See Getting
  Help section below.
* Works with large-ish datasets (100,000 rows). Can adjust memory allocation to
  accommodate larger datasets.

## Before we get started

Note: this is a Java program that runs on your machine (not in the cloud). It runs inside your browser, but no web connection is needed.

Follow the [Setup]({{ site.baseurl }}/setup.html) instructions to install OpenRefine.

If after installation and running OpenRefine, it does not automatically open for you, point your browser at http://127.0.0.1:3333/ or http://localhost:3333 to launch the program.


## Getting help for OpenRefine.

You can find out a lot more about OpenRefine at [http://openrefine.org](http://openrefine.org) and check out some great introductory videos. These videos and other on OpenRefine can also be found on YouTube, search under 'OpenRefine' There is a [Google Group](https://groups.google.com/forum/?hl=en#!forum/openrefine) that can answer a lot of beginner questions and problems. As with other programs of this type, OpenRefine libraries are available too, where you can find a script you need and copy it into your OpenRefine instance to run it on your dataset.

## What should I know when working with OpenRefine?

* No internet connection is needed, and none of the data or commands you enter in OpenRefine are sent to a remote server.
* You are NOT modifying original/raw data.
* Saving will happen automatically, but it’s important to [properly shut down OpenRefine](https://github.com/OpenRefine/OpenRefine/wiki/Installation-Instructions) to ensure this.
* Files are saved locally such that if you are working on two computers you will have to export/import files/projects.

{% include links.md %}
