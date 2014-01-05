From the Lynda.com video series “Foundations of Programming: Object-Oriented
Design”, watch each (short) video and answer the correlating questions:


Section 0: Introduction
=======================
[0.1] What to expect from this course (3:06)
--------------------------------------------
What is the intended purpose and potential advantage of learning object oriented
design?

When learning Object Oriented design and Objective C as a whole, you are learning to build native iPhone and iPad applications which is what the devices themselves are built on. The native applications use the phone to full extent and operate better as whole opposed to other ways of building applications. 

[0.2] Exploring object-oriented analysis, design, and development (1:41)
------------------------------------------------------------------------
Why might it be advantageous to analyze and design before beginning programming?

You want to focus on what your trying to build or the problem you are trying to solve first.You should try your best to fully understand your problem or what it is you are trying to accomplish. Second, you want to design your first version of the app so you can focus on that when finally sitting down in front of XCode. This step should not include code but mostly whiteboard and paper. In short Simon sums this up perfectly with "What do we need to do and how are we going to do it?" 

[0.3] Reviewing software development methodologies (4:08)
---------------------------------------------------------
What is the difference between a "waterfall" and an "agile" approach to
development? What is an iteration and how do we to use them to build software?

The main difference between the two is that with the "Waterfall" approach, you have determined set of instructions or steps to building the software. With the "Agile" approach, there is not a defined way to build your app and your able to be more responsive to the customer,to platform changes,new features,etc. A iteration would be a pivot in the software building,where maybe you throw in a new feature or design upgrade in your software. 


Section 1: Core Concepts
========================
[1.1] Why we use object-orientation (2:42)
------------------------------------------
What are the various types of programming languages and in which domain is each
used?

Object oriented languages are used to build today's most up to date and common web applications,mobile applications and video games. In the academic world, there are other types of languages that are more popular for their various reasons, such as ProLog and Haskhell which are logic programming languages. 

[1.2] What is an object? (5:22)
-------------------------------
Describe in your own words the three properties of a computing object.

A computing object would be the object istelf,such as a person. Second the would be the describing features of the said object or variables, for the the object person, it would be sex,hair color,eye color and so on. The third property would be how the object is behaving, such as is the person running or walking,does the person have glasses or not,does the person live close by or not? Those in my words would be what an object is for a computer language. 

[1.3] What is a class? (4:43)
-----------------------------
Explain how classes are analogous to blueprints. Include the relationship
between a class and an object. Can you think of how the analogy breaks down?

Classes are to programming as blueprints are to construction. Once you have your class defined and written, you can then make as many objects as you'd like for that class. Such as blueprints, once completed, you can then build 1 or thousands of homes going off that one set of defined instructions or in thise case, the blueprints. The class is the parent of the object just as a Father is to a son. That class defines the object and how it behaves. 

[1.4] What is abstraction? (2:45)
---------------------------------
When a developer uses the term “abstraction” what are they describing?

The describing the essential qualities of the idea itself. Such as, when I think of a truck, I think of a big truck with a bed that is 4 wheel drive,i don't immediately think of a Ford f-150 or a Dodge Ram. That same idea applies to programming and software development, in the case of classes, Truck would be my object,and make/model/color would be my describing features and weather it does well in the snow or not would be a behavior. 

[1.5] What is encapsulation? (3:45)
-----------------------------------
What does encapsulation prevent? What does it enable?

Encapsulation prevents other parts of your program or application from reaching into a class/object and tampering with the data. It also enables us to change the inner workings of said data and the guts of the program and not having to completely redesign and redefine the whole program itself.

[1.6] What is inheritance? (3:35)
---------------------------------
Describe the inheritance relationship between classes. When would this
relationship be advantageous to establish?

Classes are already defined and are there to use when you need them. Such as an example from the BNR Objective C book when we needed to print out our computers hostname, we used the SuperClass of NSHost and used the subclass of currentHost to get out computers name. This relationship would be best used when you have two or more similar classes but with a little bit of data in each one, Such as our Superclass is "company" with all the relevant information on it, and then a subclass would be "divisions", which would list the companies many divisions or entities because each one is it own separate standing company. This allows you to reuse the code you have already wrote for the "company" class and then added your desired data forms in the "divisions" class.  

[1.7] What is polymorphism? (3:22)
----------------------------------
What is the basic idea behind polymorphism? How can it make the classes we
create more flexible?

The basic concept behind it is that we are able to change our programs(classes) on the fly when inheriting from a superClass. They make our classes more flexible because when we inherit from a superClass we are able to polymorph some of the variables in the said class to better fit a solution within the subClass. 


Section 2: Object-Oriented Analysis and Design
==============================================
[2.1] Understanding the object-oriented analysis and design processes (4:13)
----------------------------------------------------------------------------
What are the steps of analysis that come before writing code for an application?
Why do you think these steps make writing the code easier?

1.Gather the Requirements 2.Describe the Application 3. Identify the main objects 4. Describe the Interactions 5.Create a Class Diagram
These steps make it easier because when you finally get to the point of sitting at the computer and coding out your idea, you have a sense of direction of where you are heading rather than sitting down right off the bat and letting your mind run wild with ideas with no path in front of you. The main result you should have from this process should be a class diagram.

[2.2] Defining requirements (6:09)
----------------------------------
What should you have after you've completed the first phase of defining your
requirements?

You should both the functional and non-functional requirements of what your app or apps intend to do in it's most basic form. You are going for the most minimum set of requiremnts here.

[2.3] Introduction to the Unified Modeling Language (UML) (1:54)
----------------------------------------------------------------
What is UML? Why Is it useful to visualize your application before coding it?

This is not a computer language, it is a set way to go about designing your application from a Graphical point of view using an object oriented system. 

Section 3: Utilizing Use Cases
==============================
[3.1] Understanding use cases (6:11)
------------------------------------
Write a use case for creating an event on your phone's calendar.

When a family member or friend has a birthday,you create an event for the said day so you can remember it. A 2nd case would be if you have a monthly meeting at the same time, you can then create a reminder on that day for the meeting. 

[3.2] Identifying the actors (4:16)
-----------------------------------
Can you think of a use case for a mobile application in which the actor is not
the user of the mobile device?

When your application interacts with an external API to get data from. Such as if I was building an application that used information from Facebook, it would then interact with Facebook's servers to get the information I need. Therefore, the actor in this case is the Facebook server.

[3.3] Identifying the scenarios (5:07)
--------------------------------------
Write another use case for a mobile device user interacting with a calendar
application. This time include a couple extensions when crafting your scenario.

Another use case for a user/calendar would be to remember the anniversary of a date of a wedding or birth. An extension of this case might be if you want to add a reminder for a week in advance,or maybe buy a gift automatically using some type of program. 

[3.4] Diagramming use cases (4:18)
----------------------------------
Do a google image search for "use case diagram." Notice how many variations
there are. What do they all generally have in common?

They all have multiple users pointing to multiple use case scenarios.  

[3.5] Employing user stories (3:43)
-----------------------------------
Write 5 user stories to describe a mobile user interacting with his or her maps
application.

1. User opens maps to find the nearest Starbucks. 2. User opens maps to find the quickest way to drive to point b. 3. User opens maps to find out the distance between two cities. 4. User opens maps to the map out his run for the morning. 5. User opens maps to find the nearest auto repair shop.


Section 4: Domain Modeling (Modeling the App)
=============================================
[4.1] Creating a conceptual model (1:59)
----------------------------------------
What’s your favorite color?

Blue

[4.2] Identifying the classes (2:27)
------------------------------------
Identify the classes in the use case you constructed for a user interacting with
his or her calendar application in chapter 3.

User Date Event Gift

[4.3] Identifying class relationships (2:38)
--------------------------------------------
Identify the relationships among the classes you found above. Create a
conceptual model where you diagram these relationships and then upload a picture
of your model below.

![Screen Shot](../../Pictures/Screen Shot.jpg) (I don't know if this will work or not, It this does not could you please help me to figure it out. At the very least I have it saved on my computer for you to look at on Monday)

[4.4] Identifying class responsibilities (6:43)
-----------------------------------------------
Identify the responsibilities of the classes you found above. List them here.

User Class = Name of user,Date of Birth,Dates to remember
Date Class = Year,Month,Date,Day,Hour,Minute Sub Classes =When was original event,how long until next event,multiple times a year
Event Class = Wedding Anniversary,Birthday,Meeting,Travel,etc. Sub Classes = Does this event happen multiple times a year,What do i need,how long has it been since original,reminder
Gift Class = Yes,No Sub Class = Type of Gift,Budget,Reminder to buy gift

Each class should handle its own operations. An object should always be responsible for itself. Responsibilities of the classes should always be well distributed between the classes and not put all the work on one class itself.


[4.5] Using CRC cards (2:49)
----------------------------
If you’d like, try creating CRC cards for the model you made above. There's no
need to respond here, just try it out and see if you like this form of
organization.

I like the idea,but I will soak this in at a later time maybe. I also like the ways that were taught before this one.(UML)

Section 5: Creating Classes
===========================
[5.1] Creating class diagrams (6:11)
------------------------------------
Construct Class Diagrams for the classes you imagine exist in a twitter app, a
maps app, a calendar app, or any other app you would like to make. Do you find
that it is easier to come up with the attributes or with the behaviors? Why do
you think that is?

For me, I think it was easier to figure out what classes should have the certain attributes to them. The behaviors of the class is not all that harder for me,but i feel more comfortable with the attributes of each class.

[5.2] Converting class diagrams to code (4:57)
----------------------------------------------
How might the separation of interface and implementation in Objective-C be an
advantage when working with class diagrams?

You would be able to figure out what attributes belong to what classes in my opinion. 

[5.3] Exploring object lifetime (5:55)
--------------------------------------
What are the constructors and destructors in Objective-C? Why do we use them?

A constructor is a method that exists to create the object in your program,it can also make sure that any variables belonging to that object are immediately set to the right values as soon as the object is created.The destructors do exactly the opposite,when we do not need the said object, it is destroyed. We use them to make best use of "the heap" or memory in our iPhone application. We want to give the phone as much memory as possible so our apps can respond faster and update quicker.

[5.4] Using static or shared members (5:22)
-------------------------------------------
Like the interest rate example in the video, give three additional examples of
data that would be the same for all instances of a class.

If you were making an app that lists all the companies of a multi-national conglomerate, the parent company would be same,because they are all owned by that company
If you were making a schedule app for the Chicago Bulls, all of the home games would be the same because they are all played at the United Center
If you were making an app for Chase Bank, all of the bank names would be the same,just the address and services provided would vary from branch to branch,

Section 6: Inheritance and Composition
======================================
6.1 Identifying inheritance situations (6:49)
---------------------------------------------
Describe in your own words what inheritance is and how it is useful when
constructing classes.

Inheritance is a subclass that inherits from a superclass. It is useful in object oriented programming because it really allows you to think about the object in a way that you would naturally speak about the object when talking to another person.You should let inheritance come to you naturally. It should also be noted here that you are always inheriting in some kind of way from a class. In Objective C, the programmer is always inheriting from the NSObject class.Should try to never go beyond one of two levels of inheritance with your classes. 

[6.2] Using inheritance (2:43)
------------------------------
Referring to the apps on your phone, come up with three examples where you
believe methods are being inherited from superclasses and called by subclasses.

On my Facebook application, I believe a status update would be a subclass of User superclass.
On my weather channel application, I believe a city would be a superclass and the forecast for that given city would called by a subclass.
On the Instagram application, I would guess that the User would be a superclass and pictures a subclass that uses some kind of "get pictures" method to obtain their pictures when looking at a users profile.





