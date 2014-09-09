#Description and Rationale

I currently work as a programmer in bioinformatics and the biggest problem by far is the rate at which everything is changing. These changes are being driven by the fact that the amount of data is increasing at a rate 5X that of Moores law. Dealing with the size of the data is just the tip to the iceberg, after processing the big raw data sets there are many different types of much smaller data sets. All this information needs to be managed and integrated together in a way the is accessible to people in order for the to get the data they need to do the analysis. The types of analysis you can do on the data are increasing as well, besides generating more data, other technological advances have enable new fields of research that could not be done before. So where I work I have to deal with the changes in software development, an ever increasing number of different data types and formats, new types of research and make it all manageable by other human beings. This is just where I work, there are lots of other changes going on as well but you get the point.

Something needs to be done about this problem, something big. Enter [Doug Engelbart](https://github.com/smarks159/hyperdocument-system-wiki/wiki/DougEngelbartIntro), who foresaw the problems that would be brought about be the rapid changes in technology related to computers in the 1950s. He realized that we would need to develop an new approach to solving problems that keeps pace with the rate at which technology changes and that we would need to do it collectively as all of these problems are too big to be solved by any one person alone. He used this framework in the 1960s and 70s to invent many of the technologies that we associate with modern day computing.

The main idea behind the bootstrapping framework is to take a guided evolutionary approach. More than that was must constantly get better at this guided evolution, becoming ever faster and smarter about how we change in order to keep up with the exponential rate of change brought about be the change in technology.

In hopes of better understanding this approach and other ideas of Doug Engelbart, I built a primitive hyperdocument system. I intend on writing more about what I have learned regarding these ideas. Long term, I hope to continue building a better hyperdocument system. Along the way there are going to be many interesting applications and ideas that will can help deal with many of the problems that I am facing. 

#Current Status
Currently, I have built a working version of a primitive hyperdocument system, see the user documentation for a list of some of the features implemented. The project and the code are should be considered highly experimental. I feel the system is stable enough to demonstrate some ideas and generate some discussion. However, there are a lot of key features missing.

Personally, I find it most useful for taking notes instead of using a text editor. Think of if as a basic structured text editor, where you can navigate over documents with many sections and manipulate the structure in an efficient manner.

The system also is partially written using itself. The command interpreter behavior can be defined by creating and manipulating a executable document in the same manner you can manipulate text. In the original NLS system these specs were written in a DSL called the command meta language.

#Future Plans

Currently is just me working on this in my spare time, which varies. My first goal is to document more about what I have learned working on this project, there are a lot of important ideas that require further explanation. Ideally, these ideas would be documented in the hyperdocument system itself rather then as a github wiki.

On the technical side of things, long term I feel that the web browser is not a good platform for this project. I am quickly running up against the technological limitations of the browser even in the projects primative state, even more importantly the browser is too slow to evolve. I feel that the goals [newspeak programming language](http://www.newspeaklanguage.org/) are more in line with the type of platform I would want to build future versions of this. Right now, however, the project is still incomplete and there is a lot of work to do just to even be able to port over what I have done, but longer term this is the direction the platform should take from a technological perspective.



# Project Code
There are two parts to this project a web based client written in javascript [located here](https://github.com/smarks159/hyperdocument-system-js-client) and a server written in go [located here](https://github.com/smarks159/hyperdocument-system-go-server). 

To install download or checkout the client code first and the build the server as specified in the instructions in the project.

# Forum
I set up a google group [here](https://groups.google.com/forum/#!forum/hyperdocumentsystem) to talk about this project or any of the ideas relating to it.

#User Documentation
User Documentation can be found [here](https://github.com/smarks159/hyperdocument-system-wiki/wiki/userdocs_toc).

# License
All code is licensed under the MIT license.
