akkaSniffer
===========

akkaSniffer is a message sniffer for akka. I.e it protocols any message sent from one actor to another actor. It also traces which actor creates which other actor.
akkaSniffer consists of two parts. First, a information gathering parts and second, a visualization part.
For the visualzation part, the product <a href='http://www.visual-paradigm.com/'>Visual Paradigm</a> is used. The reason for this is, that there is an easy plug-in api and there is also a free community edition available.

More information soon...

Installation
------------
akkaSniffer requires ASM for bytecode manipulation (version 5.x, <a href='http://forge.ow2.org/projects/asm/'>download</a>, download the latest version of asm-bin). The asm-all-X.X.X.jar is needed. Copy the file asm-all-X.X.X.jar to %JAVA_HOME%/jre/lib/ext or add this file to the boot classpath by adding the <code>-Xbootclasspath/a:<PATH to asm-all-X.X.X.jar></code> option to the java command when starting your akka application (for sbt users <code>sbt -J-Xbootclasspath/a:<PATH to asm-all-X.X.X.jar>"</code>)

More information soon...

Usage
-----
More information soon...
