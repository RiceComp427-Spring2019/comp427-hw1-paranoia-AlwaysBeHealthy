# <img src="http://www.rice.edu/_images/rice-logo.jpg" width=180> Comp427, Spring 2018, Homework 1
## Rational Paranoia
The homework specifications, as well as the corresponding course slide decks,
can be found on the [Comp427 Piazza](https://piazza.com/class/jqifhp864b37ju).
This assignment is due **Thursday, January 17 at 6 p.m.**

You will do this homework by editing the _README.md_ file. It's in
[MarkDown format](https://guides.github.com/features/mastering-markdown/)
and will be rendered to beautiful HTML when you visit your GitHub repo.

## Student Information
Please also edit _README.md_ and replace your instructor's name and NetID with your own:

_Student name_: Hanzhang Song

_Student NetID_: hs50

Your NetID is typically your initials and a numeric digit. That's
what we need here.

_If you contacted us in advance and we approved a late submission,
please cut-and-paste the text from that email here._

## Problem 1
- Scenario: Grading
- Assumptions:
  - I do not have enough time to grade all 200+ students' homework, so I will have several TAs to help me.
  - The type of homework is a C++ project, which will be saved on a server. Grader needs to check the correctness of the program and the quality of the code.
  - The server which the homework is committed to can be considered absolutely safe.
- Assets:
  - The integrity of the grades, only my TAs and I can make or change the students' grades.
  - The confidentiality of the homework. The homework cannot be seen by students who will take the course in the future.
  - The integrity of the homework. The homework should be read-only.
  - The computers which the students' projects will run on. The homework needs to be compiled and executed to check their correctness so that they can undermine the computers.
  - The availability of the homework. I need to save the homework until the end of the course just in case that some students will argue the grades.
- Threats:
  - The students have a motivation to change their grades by hacking or wrecking my TAs' or my computers, bribing my TAs, and changing their submitted homework.
  - My TAs may sell the homework to the students who will take the course in the future.
  - Some evil students may want to do something bad on my computer with their executable homework.
  - Natural disasters like earthquake and fire.
- Countermeasures:
  - To protect the homework' integrity and availability, I will make a backup of them and make the homework read only by only give my TA the read permission of the server.
  - I can prevent my TAs make copies of the by only permit TAs to do the work in my office. However, it may be too strict for my TAs. An alternative way is to set limitation of TAs' work time, which make TAs have no time copy.
  - To prevent that some of my TAs are bribed I will make homework be graded by two TAs, which will increase the cost of bribing.
  - I will set up a virtual environment for the homework to run on to avoid possible damage to my computer.
  - The grades are also saved on the server which is considered completely safe, and I will make the grade read-only after my TAs and I finish our work. Thus I do not worry about the integrity of the homework and the grades.
  - For natural disasters, it is obviously overthinking to consider them.

## Problem 2
- Scenario: Stadium
- Assumptions:
  - The football team will use this stadium both for training and match, so the stadium is used frequently.
  - The stadium is so large that it is not possible to entirely prevent people from sneaking in.
- Assets:
  - The equipment of the stadium, some of which are necessary for the game some of which are necessary for the audience.
  - The equipment of the team which will be used by the athletes during the game.
  - The athletes' personal safety.
  - The audience‘s safety.
  - The match which is held in this stadium should not be disturbed easily.
- Threats:
  - Thieves may break into the dresser room to steal valuable things.
  - Terrorists may want to massacre when there are many people in the stadium.
  - The opponents of the team may want to win the game by destroying the team's equipment.
  - Crazy fans from both teams may want to stop the game or hurt each other during the game.
- Countermeasures:
  - There are three different states of the stadium: match, training and free. I also have three different levels of security for each of the states: 
    1. During the match, I will hire extra security staff, use the metal detector and turn on all the monitors.
    2. When the stadium is used for training, I will only use monitors for security.
    3. When the stadium is free, I will turn off some monitors.
  - To make the game uninterruptible, I will separate fans of different teams and employ security staffs to prevent unrelated people from entering the field. Check both the equipment of the stadium and the athletes before the game. Some important equipment should have a spare one. 
  - For some expensive equipment of the stadium I will use proper insurance.
  - The doors/gates of the stadium also have different levels of security. The ascending order is: the door of the locker, the gates of the stadium, the door of the athletes' dresser room. The lockers of the doors should be different types.

## Problem 3
- Scenario: When I study in the library I often leave my computer on my seat and go to drink water or use the restroom. How can I keep my computer safe while I was away?
- Assumptions:
  - I will leave my seat for at most 5 minutes.
  - My computer has a password that is unhackable.
- Assets:
  - The physical safety of my laptop, which means it should be uneasy or costly to steal it or destroy it.
  - The software safety of my laptop, which means people cannot get the files from my computer or input information into my computer.
- Threats:
  - Thieves may want to steal my laptop for the money.
  - Bad guys may want to kidnap my computer by install virus on it.
  - The voyeur may want to obtain files on my computer.
  - Accidents like fallen cup may damage my computer.
- Countermeasures:
  - One perfect safe way is to bring my laptop with me all the time. However, it is too inconvenient or costly to do this.
  - To make myself always be able to hold someone accountable, I can always choose a seat under the watch of a monitor.
  - There are three ways to protect both the physical and software safety of my computer. I consider they have the same security level but have different limitation. In other words, they can take the place of others. If I use these three ways alternatively I can have a good method whose limitation is lower than any of the three.
    1. I can use the room on the 6th floor of our Fondren library. The room has an independent security door, I can have a private table and the restroom is very near. The disadvantage is the position is limited.
    2. I can also use the study room which is very safe because I have a private room with locker and keys, the disadvantage is that I can only use 4 hours a day and the place is also limited and should be reserved.
    3. I can keep myself accompanied by my friends, but my friends will not always have the same schedule as me.
  - I consider that the accidents are numerous and unpredictable, it will cost too much to avoid all accidents. I will only make an effort to avoid obvious accidents like never put the cup near my computer.

