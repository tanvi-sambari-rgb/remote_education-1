# TeacherAssist - Amplifying Learning

TeacherAssist is a tool to track the students attentiveness and effectiveness. 

## Contents

1. [Short description](#short-description)
1. [Demo video](#demo-video)
1. [The architecture](#the-architecture)
1. [Long description](#long-description)
1. [Project roadmap](#project-roadmap)
1. [Getting started](#getting-started)
1. [Running the tests](#running-the-tests)
1. [Live demo](#live-demo)
1. [Built with](#built-with)
1. [Contributing](#contributing)

## Short description

Amplifying Learning by empowering the teachers to deliver better content

### What's the problem?

Covid-19 pandemic caused the education to move online. Teachers and students are facing a lot of challenges. In a class of roughly 30-40 students monitoring each one using media devices is not easy. One of the major challenges we identified is that the attention span of the students is on a decline, which in turn reduces their effectiveness. Teacher is no control.

### How can technology help?

To address this issue, we moved back to the physical classrooms, where the same problem does exist. When a teacher feels a student is not paying attention, she would buzz the student by asking a question! This is what TeacherAssist does. 


### The idea

TeacherAssist prompts questions to students at regular intervals. These intervals correspond to their attention span. The max duration is 15minutes which is less than the TED benchmark. These questions are pre-loaded by the teacher relevant to the given topic. Based on the response, we capture the student’s attentiveness and effectiveness. 

Attentiveness is the time taken by the student to respond to a question. Effectiveness is the accuracy of the response. 

## Demo video

[![Watch the video](https://github.com/hr109sh/remote_education/blob/master/images/TeacherAssist_Logo.png)](https://youtu.be/qUVb7TxNaMo)

## The architecture

![Video transcription/translation app](https://github.com/hr109sh/remote_education/blob/master/images/TeacherAssist_Architecture.png)

User (Teacher)
1. The user logs in to the web application
2. Updates question for the topic 
3. Host meeting for a subject
4. Provided with a mini dashboard to track real-time the class attendance, student attentiveness and effectiveness

User (Student)
1. The user logs in to the web application
2. Join meeting based on the meeting id
3. Prompted for questions at attention span intervals

## Long description

[More detail is available here](DESCRIPTION.md)

## Project roadmap

![Roadmap](roadmap.jpg)

## Getting started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Prerequisites

What things you need to install the software and how to install them

```bash
dnf install wget
wget http://www.example.com/install.sh
bash install.sh
```

### Installing

A step by step series of examples that tell you how to get a development env running

Say what the step will be, for example

```bash
export TOKEN="fffd0923aa667c617a62f5A_fake_token754a2ad06cc9903543f1e85"
export EMAIL="jane@example.com"
dnf install npm
node samplefile.js
Server running at http://127.0.0.1:3000/
```

And repeat

```bash
curl localhost:3000
Thanks for looking at Code-and-Response!
```

End with an example of getting some data out of the system or using it for a little demo

## Running the tests

Explain how to run the automated tests for this system

### Break down into end to end tests

Explain what these tests test and why, if you were using something like `mocha` for instance

```bash
npm install mocha --save-dev
vi test/test.js
./node_modules/mocha/bin/mocha
```

### And coding style tests

Explain what these tests test and why, if you chose `eslint` for example

```bash
npm install eslint --save-dev
npx eslint --init
npx eslint sample-file.js
```

## Live demo

You can find a running system to test at [remote-e.eu-gb.mybluemix.net](http://remote-e.eu-gb.mybluemix.net/)

## Built with

* [IBM Cloud Foundry](https://cloud.ibm.com/catalog?search=cloud%20foundry#search_results) - Used for solution deployment
* [Python](https://www.python.org/) - Developed using Python
* [Django](https://www.djangoproject.com/) - The web framework used
* [Jitsi.org](https://jitsi.org/) - deploy secure video conferencing solutions 

## Contributing

Please read [CONTRIBUTING.md](CONTRIBUTING.md) for details on our code of conduct, and the process for submitting pull requests to us.
