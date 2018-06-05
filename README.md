# Source Code for MAPC 2016

### About MAPC

This code was intended to be used in the 2016's Multi Agent Programming Contest (MAPC). For more information, please check https://multiagentcontest.org/2016/.

### Tech

This work uses a number of open source projects to work properly:

* [JaCaMo] - framework for Multi-Agent Programming 

### Importing project into Eclipse IDE

*File > Import > General > Existing project into workspace*.

### Running

Using Eclipse:  
1. open src/util/StartServer.java and execute it  
2. open src/util/StartTeams.java and execute it  
3. Select the StartServer console and press ENTER to start the simulation  
4. open and run src/util/StartMonitor.java **(optional)**.

Using Ant (each command should be executed in a different terminal):  
1. *ant server*  
2. *ant java-team*  
3. *ant jcm-team*  
4. *ant monitor* **(optional)**.

License
----

GPLv3


   [Eduardo Bertassi]: <mailto:&#098;&#101;&#114;&#116;&#097;&#115;&#115;&#105;&#064;&#121;&#097;&#104;&#111;&#111;&#046;&#099;&#111;&#109;>
   [jacamo]: <http://jacamo.sourceforge.net/>
