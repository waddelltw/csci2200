# Welcome to the CSCI 2200 repository!
---
`Code repositories` are an important technology in IT. They provide several things:
1. Code sharing across geographically dispersed team members
2. Versioning of software
3. A (relatively) safe, 'central' storage location for collections of software

'Relatively safe' means that the code base is safe from the failure of a single (local) machine.
The code is stored on a distributed set of servers, which appear as a single, central location
to end users. This makes things even safer -- if one datacenter goes down, another can pick
up the load. Theoretically, the whole distributed system _could_ come down, but it's highly
unlikely

It's common practice these days for teams to use repositories (or, 'repos') to store and
version their software. You will here at ETSU, if you haven't already. As such, Visual Studio
Code has built-in functionality for interacting with repos. This is nice, since the command line
interface ('git') isn't very user friendly
