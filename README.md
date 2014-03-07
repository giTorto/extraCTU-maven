ExtraCTU-maven
==============

This maven allows to extract from a String e-mails, telephone numbers and urls

##Installation
0. Compile the maven project or take the already compiled jar
0. Add the jar file to the project

##Usage
0. Import the extractor class
0. Initialize an object extractor and call a constructor choosing which kind of object you want to extract (telephone numbers,e-mails,urls), if the constructor is called with the wrong parameter(the first parameter must be "numbers" or "e-mails" or "urls") the extract function will return null
0. The extract function, given a String, will extract different kind of objects depending on the initialization parameter
