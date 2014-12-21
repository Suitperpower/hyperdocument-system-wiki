#Background

This project is a hyperdocument system based on the ideas of [Doug Engelbart](https://en.wikipedia.org/wiki/Douglas_Engelbart). Doug Engelbart. Doug Engelbart was one of the pioneers in computing and is responsible for inventing most of the technologies the we use related to the web and collaborative software. Engelbert realized early on that computing technologies would increase in an exponential fashion and would bring with it an exponential increase in both problems and opportunities. The problem is that human beings are not well adapted to living in an exponential world where everything is constantly changing. So we as a society must change the way we think and work in order to keep up with the changes in technology and do it quickly before the challenges brought about by technological change overwhelm our ability as a society to deal with them.

Engelbart set out to research this problem in the 1960s. He developed an organizational strategy, which he called the "Bootstrap Framework" that provides a comprehensive outline about how we need to change the way we work together to keep up with all of our new challenges. He then used this framework to invent many of the technologies that we take for granted today.

The challenges of living in an ever changing world are really becoming hard to ignore. I originally start this project to try and understand Engelbart's ideas behind trying to solve these problems. More about these ideas can be found on the [Doug Engelbart Institute website](http://www.dougengelbart.org/). This project uses these ideas to guide its development.

#Goals:

Besides better understanding the ideas of Doug Engelbart. There are a few other broad, but interconnected goals that I have for this project.

##GOAL 1
The first goal of this project is to satisfy an immediate need of mine. I write a lot, I have ideas in text files scattered all over my hard drive. Every time I start a new program project I also end up with a lot of text files describing requirements, design decisions, implementation details, todo lists, etc. I need a better program to organize my thoughts.

I like using text files because I can sit down and just start typing without the computer getting in the way. I start typing at the keyboard and let the ideas just flow, like the computer isn't even there. However, I always run into problems such as:
* As the text file becomes bigger it becomes harder to navigate over, which usually limits the size of the text file I can work with. 
* When I am writing I always divided everything in different sections using indent levels and dashes. I am constantly creating new sections and rearranging old sections. This is slow and cumbersome using text files, especially as the size of the text file grows.
* I want to be able to link together all of my different thoughts in different files.

##GOAL 2
The second goal of this project is to support a new programming paradigm that I have been slowly developing. The goal of this paradigm is to separate out the business and application rules from the execution code and put the information in descriptive data structures. Each object in the hyperdocument system is defined by a set of data attributes. These attributes can be used to guide the execution of the program in a data driven fashion. This data is rendered by the hyperdocument gui to display it in a way that is understandable to humans. I use this paradigm to build the hyperdocument system itself. This means that the hyperdocument system is partially written in itself. I intend to flesh this out in further details using the hyperdocument system to document the ideas.

##GOAL 3
The third goal of this project is to make all of the documents, both text and domain rules, shareable. Something like a github for ideas. The goal is to be able to iterate, improve and build upon ideas, in a similar fashion that we do with code on github. This is a vague goal and I am not sure how this would work yet. I have not done anything concrete yet with this idea.

#Current Status:
Currently I have implemented enough features that I find the hyperdocument system useful to write and organize my thoughts with. I am currently focusing on writing more about all of my ideas and what I have done so far within the hyperdocument system. You can look at the user documentation to see what features have been implemented so far and tutorials about how to use the system. These documents are located in the system itself.

Right now the system runs in the browser but only works locally because it has no features for multi-user use yet. I am working on making a version of the system that you can use online, in a limited way, without downloading anything, so you can try the system out and read the documentation. In the meantime see the getting started section about how the download and install the system and how to load the tutorial file to get you started.

#Getting Started
##Installing The System
The hyperdocument system is a client/server system where the client is written in javascript in the browser and go for the server (it is currently a very simple server).

First download the javascript client source code [located here](https://github.com/smarks159/hyperdocument-system-js-client)

Next download an install the server following the instructions here [located here](https://github.com/smarks159/hyperdocument-system-go-server). 

##Loading the tutorial file
After loading the system the next thing to do is to load the document with the tutorial that will walk you through how to use the system.

1. To start the system, run the server executable to start the server. The enter the address http://localhost/html/TestInteractiveInterpreter.html to load the system.

2. To load the tutorial file type "f" then "l", the system will the ask you to type in the name of a file to load. Type user_documentation into the form and hit the submit button.

3. Next to navigate to the start of the tutorial type "j" then "e" and click of the section that says "(start here)" to get started. Then follow the instructions written in the document.

# Project Code
There are two parts to this project a web based client written in javascript [located here](https://github.com/smarks159/hyperdocument-system-js-client) and a server written in go [located here](https://github.com/smarks159/hyperdocument-system-go-server). 

To install download or checkout the client code first and the build the server as specified in the instructions in the project.

# Forum
I set up a google group [here](https://groups.google.com/forum/#!forum/hyperdocumentsystem) to talk about this project or any of the ideas relating to it.

# Documentation
All of the documentation, including the user documentation are written in the system itself. A version you can view online will be implemented sometime in the future, for now you must download and install the system first to use it. See the getting started section for the instructions on how to do that.

# License
All code is licensed under the MIT license.
