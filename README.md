GuardianBeamAPI
===========
![GuardianBeamAPI Image Credit ArcLumX](http://i.imgur.com/oWfQVvg.png)

An easy solution for manipulating Guardian's beams in Spigot!
What is GuardianBeamAPI?
--------
GuardianBeamAPI is an open source library and plugin licensed under the permissive MIT license that allows you to seamlessly manipulate the beams emitted by Guardians when they target another entity. The project was founded out of my realization that there were no clean libraries for manipulating these beams.
It is recommended that you use GuardianBeamAPI as a dependency.

How do I use it?
--------
First, include GuardianBeamAPI as a dependency in your project.
<Maven Dependency and Repository coming soon>

Next, add to your plugin.yml:
```
depend: [GuardianBeamAPI]
```

Using the library is simple:
```java
Beam beam = new Beam(locationOne, locationTwo);
beam.start();
//Changing the target of the beam is easy:
beam.setStartingPosition(newLocation);
```
And all of the code is documented.

Download: https://gitlab.com/johnnywoof/GuardianBeamAPI/-/jobs/artifacts/master/download?job=build

Contributing
--------
I encourage anyone with an idea to fork this project and submit a pull request! I want this to be a community driven project, so I'd be glad to accept any PRs that meet reasonable quality standards.

Contributors:
* Jaxon Brown, Author
* Johnnywoof, Maintainer
