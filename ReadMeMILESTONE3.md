# Milestone 3

<i> Note that the build script was handled by IntelliJ</i>


Adjusted Files
- XML.java
- XMLTest.java

The latest update to the JSON library reads an XML file and transforms the 
keys to a value indicated by the user. This is done <i>while the XML file is still being parsed</i>. 
Dynamically transforming the key improves time and space performance 
from making transformations <i>after</i> processing an entire XML file. 
With this implementation, the XML file must only be processed once, rather than multiple times.