a.	What is unit testing, how is it implemented, and why is it important?

Unit testing uses isolation to test the module so that only its behavior is verified.  This method is important because it gives the tester a better idea how the module will respond to external conditions by testing it under controlled conditions. By performing this type of test one would be able to determine if a particular module would work with the entire project. Unit tests are implemented in some type of artificial environment in which the mould would be thoroughly tested off of its routines and functions.  The code should be located in an area easily accessed by developers, either located in the module itself or in a subdirectory of the unit being tested.

Where initially unit testing might add more work and isn't necessarily easy, it will provide the programmer with instant gratification by allowing them to execute their code and know that it works right away.  This allows the programmers to get their product to market quicker by avoiding ongoing problems within the code that take a long time to fix.  As a result, higher quality programs are produced quicker despite having to take the extra time to produce unit tests initially.
 
b.	What is functional testing, how is it implemented, and why is it important?

Functional testing is performed by testing the functional requirements of the software being tested.  The hope of functional testing is that the program physically performs the tasks that it was intended to do and conforms to industry standards. Functional testing works by feeding user input that validate particular use cases and then examines the output.
Functional testing has become invaluable because they often pick up failures that your unit tests may miss. This can occur when new features added to the system interact with existing features when it is not expected.   
c.	What is the significance and usage of automated unit testing in software development?

Automated unit testing executes tests without manual intervention which provides a low cost re-testing solution that controls risk when code is changed.   This usually results in better stability, portability and efficient interface designs. By providing automatic and repeatable tests, the code can be thoroughly tested throughout the entire process without much interaction from the programmer.   It is also can be self-documenting which allows a developer to look into the history of their or another developer's code. This also helps with respect to having a successful build, one would be able to test earlier and more often thus ensure that the code is working properly throughout. Another benefit is that if one makes a change to the code the automated unit testing would determine if the changes caused errors or not.

d.	Where would you commonly find automated unit testing implemented?  Can you find any documentation online that describes this and post a link to it? 

Automated unit testing is useful in test driven environments where the new code needs to pass predefined tests and are run repeatedly until it passes. 

 http://www.renaissancesoftware.net/files/articles/ESC-241Paper_Grenning-v1r1.pdf

e.	 What is test driven development and how can it improve the management and quality of software projects.

This style of development involves the test being written prior to the code that will run the software.  The new code is only accepted after it passes the tests written specifically for it. This helps the programmer meet the detailed specifications and requirements.  Test driven development often reduces regression significantly, improves interface design and makes implementation easier. Another major benefit is that the code becomes simple, since most bugs in software programming are from complexity. 


