#Description and Rationale

This project is my version of a hyperdocument system, largely based on the ideas of Doug Engelbart. I wrote a brief summary of who he was with links to learn more [here](https://github.com/smarks159/hyperdocument-system-wiki/wiki/DougEngelbartIntro)

There are two main ideas of Doug Engelbart that were really appealing to me:

###Efficient User Interface
The first idea is the idea of an efficient user interface. One goal of this project is to build tools that I use everyday to make myself more productive. For my needs, I found that most of the gui interfaces were clunky to use and focused on being easy to learn. The alternatives are usually to do away with a gui interface and focus on a more text like interface for efficiency purposes. The problem is that computer is capable of so much more that just text.  I want to build tools that are at least as efficient to use as text and take full advantage of what a computer is capable of.

###Bootstrapping
The second idea, that is even more important, is Engelbart's approach to solving problems called bootstrapping. The problem that this approach aims to address is that technology and the problems associated with it increase at an exponential rate while humans ability to solve these problems do not, especially as the number of people involved increases. This is true in the field of software development and even worse in bioinformatics, the field in which I work. The solution to this problem requires a fundamental shift in the way in which we think and approach problems. Engelbart invented such an a approach and used in to invent many of the technologies related to modern day computers that we use today. This project project is an experiment in applying the conceptual framework Engelbart developed to try and address these problems. I intend on writing more about what I have learned about applying these ideas.

###Spec Driven Programming
Spec Driven Programming is not an idea originally developed by Doug Engelbart. It is a way of programming that a co-worker and I discovered while building a sequencing LIMS that seemed to work really well. The main idea is that you have nested descriptive data structures that describe the facts and rules associated with a particular domain. These data structures are then used to drive different parts of the program in a data driven way.

All objects in the document are implemented as a spec data structure. Of course, for the most part, they are not rendered that way to the user. The operations related to manipulating these objects can be domain specific as well, so the user does not have to see or manipulate raw data. So the documents are all readable and able to be manipulated by both humans and machines.

Engelbart's hyperdocument system, the NLS, was originally designed to be an integrated environment that supported multiple types of objects. All the principles from the hyperdocument system apply to specs as well.
 

#Current Status
This project is currently experimental and there are a lot of key features missing, but I use the system frequently and find it useful. Currently, the most useful thing I find it useful for is for taking notes instead of using a text editor. Think of if as a basic structured text editor, where you can navigate over documents with many sections and manipulate the structure just as efficiently as writing plain text.

The system also uses specs that can be defined and manipulated in the system. The specs, at the moment, are used to defined the commands and actions take by the command interpreter, similar to how the original NLS system used a DSL called the command meta language.

# Project Code
There are two parts to this project a web based client written in javascript [located here](https://github.com/smarks159/hyperdocument-system-js-client) and a server written in go [located here](https://github.com/smarks159/hyperdocument-system-go-server). 

To install download or checkout the client code first and the build the server as specified in the instructions in the project.

# Forum
I set up a google group [here](https://groups.google.com/forum/#!forum/hyperdocumentsystem) to talk about this project or any of the ideas relating to it.

#User Documentation
User Documentation can be found [here](https://github.com/smarks159/hyperdocument-system-wiki/wiki/userdocs_toc).

# License
All code is licensed under the MIT license.
