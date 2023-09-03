---
tags:
  softwaredd
  flashcards
---
### Useful notes made by other students:
___
[[SDD Accelerated HSC Notes 2022-compressed.pdf]]
[[SDD Notes - From class of 2015.pdf]]
[[SDD Notes - MrBrightside.pdf]]
___

### Indigo's Docs 
___
(Online)
- https://docs.google.com/document/d/14bkIojjNiuHqU2XLi-LF9PwnWFqXByup-w7UwBg9SmI/edit
- https://docs.google.com/document/d/1BUiIBV3jRgQu_25kAn7RnJZm4NhxIxVfzrI6pkqAdDc/edit#heading=h.5q4t78orcivm
(Local - 3/8/2023)
- [[Pseudocode and Flowchart Cheatsheet.pdf]]
___
### Need to Know
___
- [ ] Identifying Issues in Pseudocode
- [ ] System/Solution Models
	- [[#System/Solution Models|Flashcards]]
	- What are the different ways to model a system?;</br> [Context Diagram](https://docs.google.com/presentation/d/1N50Sd64Cpz3iV9PCGc_Q2Xg1r1Mw5tbVkIET9jfpZk0/edit#slide=id.p4) (AKA [Data Flow Diagram](https://docs.google.com/presentation/d/1N50Sd64Cpz3iV9PCGc_Q2Xg1r1Mw5tbVkIET9jfpZk0/edit#slide=id.p5)Level 0)</br> [Data Flow Diagram](https://docs.google.com/presentation/d/1N50Sd64Cpz3iV9PCGc_Q2Xg1r1Mw5tbVkIET9jfpZk0/edit#slide=id.p5)(AKA [Data Flow Diagram](https://docs.google.com/presentation/d/1N50Sd64Cpz3iV9PCGc_Q2Xg1r1Mw5tbVkIET9jfpZk0/edit#slide=id.p5)Level 1)</br> System Flow Chart</br>[Structure Chart](https://docs.google.com/presentation/d/1N50Sd64Cpz3iV9PCGc_Q2Xg1r1Mw5tbVkIET9jfpZk0/edit#slide=id.p11) </br>[IPO Chart](https://docs.google.com/presentation/d/1N50Sd64Cpz3iV9PCGc_Q2Xg1r1Mw5tbVkIET9jfpZk0/edit#slide=id.p13)</br> [Data Dictionary](https://docs.google.com/presentation/d/1N50Sd64Cpz3iV9PCGc_Q2Xg1r1Mw5tbVkIET9jfpZk0/edit#slide=id.p15) </br>[Screen Design](https://docs.google.com/presentation/d/1N50Sd64Cpz3iV9PCGc_Q2Xg1r1Mw5tbVkIET9jfpZk0/edit#slide=id.p16) </br>Storyboards
- [ ] Flow Chart
- [ ] Sorting Algorithms 
	- [ ] Quick Sort
	- [ ] Recognising from Consecutive Sort Steps
- [ ] Searching Algorithms 
	- [ ] Searching Algorithm 1;; Sequential <!--SR:!2023-09-07,17,267-->
	- [ ] Searching Algorithm 2;; Binary <!--SR:!2023-08-31,4,275-->
- [ ] Streams (start and end)(parity)
	- The Data Stream sections are;; The Header, the Data Block, and the Trailer Information <!--SR:!2023-10-05,39,267-->
	- Trailer Information
		- [Parity Bit Infomation](https://www.tutorialspoint.com/what-is-a-parity-bit)
		- The Trailer Information Contains;; Error checking bits and a stop bit
		- What are the differences between odd and even parity bits?;; <br>Even Parity − Here the total number of 1 bits in the message is made even. <br>Odd Parity − Here the total number of 1 bits in the message is made odd. <!--SR:!2023-08-19,2,227-->
		- What is the value of an even parity bit in a data stream if the number of 1's is even;; 0   <!--SR:!2023-10-04,38,267-->
		- What is the value of an even parity bit in a data stream if the number of 1's is odd;; 1 <!--SR:!2023-10-10,44,285-->
		- What is the value of an odd parity bit in a data stream if the number of 1's is even;; 1   <!--SR:!2023-08-19,2,228-->
		- What is the value of an odd parity bit in a data stream if the number of 1's is odd;; 0  <!--SR:!2023-09-08,18,285-->
		- 
		- What is the value of an even parity bit in a data stream if the number of 0's is even;; 1   <!--SR:!2023-10-09,43,287-->
		- What is the value of an even parity bit in a data stream if the number of 0's is odd;; 0 <!--SR:!2023-10-08,42,267-->
		- What is the value of an odd parity bit in a data stream if the number of 0's is even;; 0   <!--SR:!2023-10-01,35,247-->
		- What is the value of an odd parity bit in a data stream if the number of 0's is odd;; 1  <!--SR:!2023-10-06,40,267-->
- [ ] Software Development Cycle
	- [[#^7f1dfa|Flashcards]]
	- Software Development Cycle Stage 1;; Defining and Understanding the Problem <!--SR:!2023-10-01,35,267-->
		- Determine the requirements of the system and needs of client
		- Study existing systems and consult with users
		- Feasibility study undertaken
		- Design specifications are made
		- Development plan is constructed
	- Software Development Cycle Stage 2;; Planning and Designing the Solution <!--SR:!2023-10-02,36,267-->
		- Design of data structures
		- Algorithms are created
		- Interface design in consultation with client
		- Project is broken down into modules
	- Software Development Cycle Stage 3;; Implementing the Solution
		- Solution is coded in a programming language
		- Each module is tested as it is coded and then tested in combination with others
		- Documentation is made
	- Software Development Cycle Stage 4;; Testing and Evaluating the Solution <!--SR:!2023-10-05,39,267-->
		- Testing for errors as well as performance under live conditions
		- Evaluate the system to ensure that all requirements have been met
	- Software Development Cycle Stage 5;; Modifying/Maintaining the Solution <!--SR:!2023-08-31,4,275-->
		- Upgrading to correct errors, add new functionality, improve current functionality
		- Each modification uses the steps of the software development cycle
- [ ]  Installation Methods 
	- [[#Methods of Installation|Flashcards]]
	- Direct cut-over
		- Old system is dropped and new system installed at the same time.
		- Used when not feasible to run both systems at the same time
		- Data must be converted and imported from old system.
		- Users must be trained on new system prior to installation
	- Parallel
		- Both systems operate together for a period of time.
		- Allows major problems with new system to be sorted without loss of data
		- Users have time to familiarise themselves with new system.
		- Used when system is crucial
	- Phased
		- Gradual change from old system to new.
		- New product introduced one part at a time
		- Often used when product is still under development.
	- Pilot
		- New system is initially installed for a small number of users.
		- Users can test system - often considered final test
		- Users can learn system so they can teach others
- [ ] [Development approaches ](https://docs.google.com/document/d/1ERizOVF-W1DvU94htrm94IBvACSJAhlsorZSezkkJEA/edit#heading=h.gjdgxs)
	- ![[#Development Approaches Table]]
- [ ] Rights of software developers 
	- Categories of the Rights of software developers;; Intellectual Property, and Quality
	- 
	- What is Intellectual Property?; Property resulting from mental labour
	- Intellectual Property Rights of Developers; work must be acknowledged and fairly compensated by publishers
	- 
	- Developer Rights Regarding Quality; Developer has the right to expect that the hardware and operating systems both operates reliably. 
- [ ] Responsibilities of software developers 
	- Categories of the responsibilities of software developers; Intellectual Property, Quality, Response to Problems, Malware  
	- 
	- Intellectual Responsibilities of developers; Developers have the responsibility to acknowledge the work of others. 
	- 
	- What are the factors which determine a software's quality?; reliability, integrity of data, efficiency, + more
	- Responsibilities of the Developer Related to Quality; Solutions should be high quality (especially when involving important data) to reduced the inconvenience of errors 
	- How is the quality of software ensured?; Through planning, testing, and QA (eg. Discussion with client to ensure software is satisfactory)
	- 
	- Responsibilities of the Developer Related the Response to Problems; timely, accurate, and efficient response to problems
	- How can a Software Developer Ensure a timely, accurate, and efficient response to problems?; Have a method to assist identification and resolution of errors. Have unambiguous error messages. Have a way to respond to user problems such as a support department
	- 
	- Responsibilities of the Developer Related Malware; Ensure their products do not generate, feature, or transmit malware.
	- How can a Software Developer ensure that their products do not generate, feature, or transmit malware?; Check new data and software added for viruses. Scan all emails and attachments received by employees. Update antivirus software regularly. Scan all software before distribution. Use firewalls and other security mechanisms.
- [ ] [Translation](https://docs.google.com/presentation/d/1pfuyVXSHoOIv913PNJ6H7WufqFIkzfSIHmdtwVroCNA/edit#slide=id.p1) 
	- Compilation
	- Interpretation
	- Incremental Compilation
- [x] CASE tools
- [x] Software licenses 
- [x] CPU instructions 
- [x] Fetch Execute Cycle
- [x] Relative files
- [x] Sequential files pseudo code

- [ ] Binary
	- Is 0 True or False?;; False <!--SR:!2023-08-31,4,275-->
	- is 1 True or False?;; True <!--SR:!2023-08-31,4,275-->
	- What is the binary digit representation of False?;; 0 <!--SR:!2023-09-15,19,267-->
	- What is the binary digit representation of True?;; 1 <!--SR:!2023-08-31,4,275-->

The steps / actions that are a part of the 'Defining and Understanding the Problem' Software Development Cycle stage are:
?
- Determine the requirements of the system and needs of client
- Study existing systems and consult with users
- Feasibility study undertaken
- Design specifications are made
- Development plan is constructed <!--SR:!2023-08-28,7,227-->

___
The following steps / actions are a part of which Software Development Cycle:</br> ^0d76f8
- Design of data structures
- Algorithms are created
- Interface design in consultation with client
- Project is broken down into modules
?
2 - Planning and Designing the Solution <!--SR:!2023-09-04,14,267-->

The steps / actions that are a part of the 'Planning and Designing the Solution' Software Development Cycle stage are:
?
- Design of data structures
- Algorithms are created
- Interface design in consultation with client
- Project is broken down into modules

___
The following steps / actions are a part of which Software Development Cycle:</br> ^0d76f8
- Solution is coded in a programming language
- Each module is tested as it is coded and then tested in combination with others
- Documentation is made
?
3 - Implementing the Solution <!--SR:!2023-10-02,36,267-->

The steps / actions that are a part of the 'Implementing the Solution' Software Development Cycle stage are:
?
- Solution is coded in a programming language
- Each module is tested as it is coded and then tested in combination with others
- Documentation is made

___
The following steps / actions are a part of which Software Development Cycle:</br> ^0d76f8
- Testing for errors as well as performance under live conditions
- Evaluate the system to ensure that all requirements have been met
?
4 - Testing and Evaluating the Solution <!--SR:!2023-10-07,41,267-->

The steps / actions that are a part of the 'Testing and Evaluating the Solution' Software Development Cycle stage are:
?
- Testing for errors as well as performance under live conditions
- Evaluate the system to ensure that all requirements have been met <!--SR:!2023-09-11,15,227-->

___
The following steps / actions are a part of which Software Development Cycle:</br> ^0d76f8
- Upgrading to correct errors, add new functionality, improve current functionality
- Each modification uses the steps of the software development cycle <!--SR:!2023-10-04,38,267-->
?
Modifying/Maintaining the Solution

The steps / actions that are a part of the 'Modifying/Maintaining the Solution' Software Development Cycle stage are:
?
- Upgrading to correct errors, add new functionality, improve current functionality
- Each modification uses the steps of the software development cycle

___ 

#### Methods of Installation
___
What are the installation methods?
?
- Direct Cut-Over
- Parallel
- Phased
- Pilot <!--SR:!2023-09-30,34,267-->

___
What is the Direct Cut-Over Installation method?
?
- Old system is dropped and new system installed at the same time.
- Used when not feasible to run both systems at the same time
- Data must be converted and imported from old system.
- Users must be trained on new system prior to installation <!--SR:!2023-09-10,14,227-->

Which Method of Installation is described by the following characteristics?
- Old system is dropped and new system installed at the same time.
- Used when not feasible to run both systems at the same time
- Data must be converted and imported from old system.
- Users must be trained on new system prior to installation
?
Direct Cut-Over <!--SR:!2023-10-07,41,287-->

___
What is the Parallel Installation method?
?
- Both systems operate together for a period of time.
- Allows major problems with new system to be sorted without loss of data
- Users have time to familiarise themselves with new system.
- Used when system is crucial <!--SR:!2023-08-31,4,275-->

Which Method of Installation is described by the following characteristics?
- Both systems operate together for a period of time.
- Allows major problems with new system to be sorted without loss of data
- Users have time to familiarise themselves with new system.
- Used when system is crucial
?
Parallel <!--SR:!2023-10-06,40,268-->

___
What is the Phased Installation method?
?
- Gradual change from old system to new.
- New product introduced one part at a time
- Often used when product is still under development. <!--SR:!2023-10-03,37,267-->

Which Method of Installation is described by the following characteristics?
- Gradual change from old system to new.
- New product introduced one part at a time
- Often used when product is still under development.
?
Phased <!--SR:!2023-10-03,37,267-->

___
What is the Pilot Installation method?
?
- New system is initially installed for a small number of users.
- Users can test system - often considered final test
- Users can learn system so they can teach others <!--SR:!2023-09-30,34,267-->

Which Method of Installation is described by the following characteristics?
- New system is initially installed for a small number of users.
- Users can test system - often considered final test
- Users can learn system so they can teach others
?
Pilot <!--SR:!2023-09-10,14,227-->

___

___

#### System/Solution Models
___
##### [Context Diagram](https://docs.google.com/presentation/d/1N50Sd64Cpz3iV9PCGc_Q2Xg1r1Mw5tbVkIET9jfpZk0/edit#slide=id.p4)

What is a [Context Diagram](https://docs.google.com/presentation/d/1N50Sd64Cpz3iV9PCGc_Q2Xg1r1Mw5tbVkIET9jfpZk0/edit#slide=id.p4)?
?
![[Context Diagram.jpg]] ^63d7e2
- A [Context Diagram](https://docs.google.com/presentation/d/1N50Sd64Cpz3iV9PCGc_Q2Xg1r1Mw5tbVkIET9jfpZk0/edit#slide=id.p4) is used to represent an overview of the system.
- It does not show sequence of events but order can be implied based on scenario

What type of diagram is depicted in the following image?
![[Context Diagram.jpg]]
?
[Context Diagram](https://docs.google.com/presentation/d/1N50Sd64Cpz3iV9PCGc_Q2Xg1r1Mw5tbVkIET9jfpZk0/edit#slide=id.p4) <!--SR:!2023-08-31,4,275-->

In a [Context Diagram](https://docs.google.com/presentation/d/1N50Sd64Cpz3iV9PCGc_Q2Xg1r1Mw5tbVkIET9jfpZk0/edit#slide=id.p4), what shape is used to represent external entities?; A circle

In a [Context Diagram](https://docs.google.com/presentation/d/1N50Sd64Cpz3iV9PCGc_Q2Xg1r1Mw5tbVkIET9jfpZk0/edit#slide=id.p4), what shape is used to represent processes?; A rectangle

Are flow direction arrows required on a [Context Diagram](https://docs.google.com/presentation/d/1N50Sd64Cpz3iV9PCGc_Q2Xg1r1Mw5tbVkIET9jfpZk0/edit#slide=id.p4)?; Yes

Are data labels required on a [Context Diagram](https://docs.google.com/presentation/d/1N50Sd64Cpz3iV9PCGc_Q2Xg1r1Mw5tbVkIET9jfpZk0/edit#slide=id.p4)?; Yes

Are databases needed in a [Context Diagram](https://docs.google.com/presentation/d/1N50Sd64Cpz3iV9PCGc_Q2Xg1r1Mw5tbVkIET9jfpZk0/edit#slide=id.p4)?; No

Can [Context Diagram](https://docs.google.com/presentation/d/1N50Sd64Cpz3iV9PCGc_Q2Xg1r1Mw5tbVkIET9jfpZk0/edit#slide=id.p4)lines be curved?; Yes 

Does a [Context Diagram](https://docs.google.com/presentation/d/1N50Sd64Cpz3iV9PCGc_Q2Xg1r1Mw5tbVkIET9jfpZk0/edit#slide=id.p4) show the sequence of operations?; No

___
##### [Data Flow Diagram](https://docs.google.com/presentation/d/1N50Sd64Cpz3iV9PCGc_Q2Xg1r1Mw5tbVkIET9jfpZk0/edit#slide=id.p5)

What is a [Data Flow Diagram](https://docs.google.com/presentation/d/1N50Sd64Cpz3iV9PCGc_Q2Xg1r1Mw5tbVkIET9jfpZk0/edit#slide=id.p5)?
?
![[Data Flow Diagram.png]]
-  Represents the system as a number of processes, External Entities and Data stores.
- A [Data Flow Diagram](https://docs.google.com/presentation/d/1N50Sd64Cpz3iV9PCGc_Q2Xg1r1Mw5tbVkIET9jfpZk0/edit#slide=id.p5) is a refinement of a [Context Diagram](https://docs.google.com/presentation/d/1N50Sd64Cpz3iV9PCGc_Q2Xg1r1Mw5tbVkIET9jfpZk0/edit#slide=id.p4)used to show the sources and destinations of data along with the flow the data takes between processes <!--SR:!2023-08-31,4,275-->

What symbols are used in [Data Flow Diagrams](https://docs.google.com/presentation/d/1N50Sd64Cpz3iV9PCGc_Q2Xg1r1Mw5tbVkIET9jfpZk0/edit#slide=id.p5)?
?
- Circles for processes
- Rectangles for external entities
- 3 sided rectangles for data stores.

Do the lines in [Data Flow Diagrams](https://docs.google.com/presentation/d/1N50Sd64Cpz3iV9PCGc_Q2Xg1r1Mw5tbVkIET9jfpZk0/edit#slide=id.p5) need arrows indicating the direction of data flow?; Yes

Can the lines in [Data Flow Diagrams](https://docs.google.com/presentation/d/1N50Sd64Cpz3iV9PCGc_Q2Xg1r1Mw5tbVkIET9jfpZk0/edit#slide=id.p5) be curved?; Yes

Do [Data Flow Diagrams](https://docs.google.com/presentation/d/1N50Sd64Cpz3iV9PCGc_Q2Xg1r1Mw5tbVkIET9jfpZk0/edit#slide=id.p5) need labels for the data?; Yes

Can [Data Flow Diagrams](https://docs.google.com/presentation/d/1N50Sd64Cpz3iV9PCGc_Q2Xg1r1Mw5tbVkIET9jfpZk0/edit#slide=id.p5) have two directional arrows?; No

Can a data store in a [Data Flow Diagram](https://docs.google.com/presentation/d/1N50Sd64Cpz3iV9PCGc_Q2Xg1r1Mw5tbVkIET9jfpZk0/edit#slide=id.p5) be a non-computer storage file e.g. Paper folder?; Yes

Does a [Data Flow Diagram](https://docs.google.com/presentation/d/1N50Sd64Cpz3iV9PCGc_Q2Xg1r1Mw5tbVkIET9jfpZk0/edit#slide=id.p5)show the sequence of operations?; No

___
##### [System Flow Chart](https://docs.google.com/presentation/d/1N50Sd64Cpz3iV9PCGc_Q2Xg1r1Mw5tbVkIET9jfpZk0/edit#slide=id.p8)

What is a [System Flow Chart](https://docs.google.com/presentation/d/1N50Sd64Cpz3iV9PCGc_Q2Xg1r1Mw5tbVkIET9jfpZk0/edit#slide=id.p8)
?
![[System Flow Chart.png]]
- Shows the flow of data
- Shows the individual system modules 
- Shows the media used <!--SR:!2023-08-30,3,255-->

Can the lines in [System Flow Charts](https://docs.google.com/presentation/d/1N50Sd64Cpz3iV9PCGc_Q2Xg1r1Mw5tbVkIET9jfpZk0/edit#slide=id.p8) be curved?; No

Do the lines in [System Flow Charts](https://docs.google.com/presentation/d/1N50Sd64Cpz3iV9PCGc_Q2Xg1r1Mw5tbVkIET9jfpZk0/edit#slide=id.p8) need arrows to indicate direction of flow?; Yes

Can the lines in [System Flow Charts](https://docs.google.com/presentation/d/1N50Sd64Cpz3iV9PCGc_Q2Xg1r1Mw5tbVkIET9jfpZk0/edit#slide=id.p8) have two directional arrows? (on line with an arrow on each end); Yes

What is the symbol used in [System Flow Charts](https://docs.google.com/presentation/d/1N50Sd64Cpz3iV9PCGc_Q2Xg1r1Mw5tbVkIET9jfpZk0/edit#slide=id.p8) to indicate 'input and output'?
?
Parallelogram
![[System Flow Chart - Input and Output.png]]

What is this symbol used to indicate in [System Flow Charts](https://docs.google.com/presentation/d/1N50Sd64Cpz3iV9PCGc_Q2Xg1r1Mw5tbVkIET9jfpZk0/edit#slide=id.p8)?
![](https://i.imgur.com/3k9UZVM.png)
?
Input and Output <!--SR:!2023-08-31,4,275-->

What is the symbol used in [System Flow Charts](https://docs.google.com/presentation/d/1N50Sd64Cpz3iV9PCGc_Q2Xg1r1Mw5tbVkIET9jfpZk0/edit#slide=id.p8) to indicate 'Paper Document'?
?
Rectangle with a squiggly base
![](https://i.imgur.com/kOj90iV.png)

What is this symbol used to indicate in [System Flow Charts](https://docs.google.com/presentation/d/1N50Sd64Cpz3iV9PCGc_Q2Xg1r1Mw5tbVkIET9jfpZk0/edit#slide=id.p8)?
![](https://i.imgur.com/0davMlx.png)
?
Paper document <!--SR:!2023-08-31,4,275-->

What is the symbol used in [System Flow Charts](https://docs.google.com/presentation/d/1N50Sd64Cpz3iV9PCGc_Q2Xg1r1Mw5tbVkIET9jfpZk0/edit#slide=id.p8) to indicate 'online display'?
?
Left angle bracket with two lines to coming of the top and bottom of the angled bracket to connect it to a right parenthesise.
![](https://i.imgur.com/JFC7qSb.png)

What is this symbol used to indicate in [System Flow Charts](https://docs.google.com/presentation/d/1N50Sd64Cpz3iV9PCGc_Q2Xg1r1Mw5tbVkIET9jfpZk0/edit#slide=id.p8)?
![](https://i.imgur.com/WHERfv0.png)
?
Online Display <!--SR:!2023-08-31,4,275-->

What is the symbol used in [System Flow Charts](https://docs.google.com/presentation/d/1N50Sd64Cpz3iV9PCGc_Q2Xg1r1Mw5tbVkIET9jfpZk0/edit#slide=id.p8) to indicate 'online input'?
?
Rectangle with a positively slanted top.
![](https://i.imgur.com/63AP3ZW.png)

What is this symbol used to indicate in [System Flow Charts](https://docs.google.com/presentation/d/1N50Sd64Cpz3iV9PCGc_Q2Xg1r1Mw5tbVkIET9jfpZk0/edit#slide=id.p8)?
![](https://i.imgur.com/uh6Pf0p.png)
?
Input and Output

What is the symbol used in [System Flow Charts](https://docs.google.com/presentation/d/1N50Sd64Cpz3iV9PCGc_Q2Xg1r1Mw5tbVkIET9jfpZk0/edit#slide=id.p8) to indicate 'punched card'?
?
Rectangle with the top left corner cut off.
![](https://i.imgur.com/KWWG4Ja.png) <!--SR:!2023-08-31,4,275-->

What is this symbol used to indicate in [System Flow Charts](https://docs.google.com/presentation/d/1N50Sd64Cpz3iV9PCGc_Q2Xg1r1Mw5tbVkIET9jfpZk0/edit#slide=id.p8)?
![](https://i.imgur.com/pRSR0BC.png)
?
Punched Card <!--SR:!2023-08-31,4,275-->

What is the symbol used in [System Flow Charts](https://docs.google.com/presentation/d/1N50Sd64Cpz3iV9PCGc_Q2Xg1r1Mw5tbVkIET9jfpZk0/edit#slide=id.p8) to indicate 'process'?
?
Rectangle
![](https://i.imgur.com/fVPqS3d.png)

What is this symbol used to indicate in [System Flow Charts](https://docs.google.com/presentation/d/1N50Sd64Cpz3iV9PCGc_Q2Xg1r1Mw5tbVkIET9jfpZk0/edit#slide=id.p8)?
![](https://i.imgur.com/LpwJUOt.png)
?
Process

What is the symbol used in [System Flow Charts](https://docs.google.com/presentation/d/1N50Sd64Cpz3iV9PCGc_Q2Xg1r1Mw5tbVkIET9jfpZk0/edit#slide=id.p8) to indicate 'manual operation'?
?
Point down isosceles triangle with the point cut off
![](https://i.imgur.com/nZmLNgW.png)

What is this symbol used to indicate in [System Flow Charts](https://docs.google.com/presentation/d/1N50Sd64Cpz3iV9PCGc_Q2Xg1r1Mw5tbVkIET9jfpZk0/edit#slide=id.p8)?
![](https://i.imgur.com/elxmPXT.png)
?
Manual Operation <!--SR:!2023-08-30,3,255-->

What is the symbol used in [System Flow Charts](https://docs.google.com/presentation/d/1N50Sd64Cpz3iV9PCGc_Q2Xg1r1Mw5tbVkIET9jfpZk0/edit#slide=id.p8) to indicate 'Magnetic Tape'?
?
Circle with the base extruded into a rectangle that vertically aligns to the right side of the circle.
![](https://i.imgur.com/aAAsNtP.png) <!--SR:!2023-08-31,4,275-->

What is this symbol used to indicate in [System Flow Charts](https://docs.google.com/presentation/d/1N50Sd64Cpz3iV9PCGc_Q2Xg1r1Mw5tbVkIET9jfpZk0/edit#slide=id.p8)?
![](https://i.imgur.com/zsOoRil.png)
?
Magnetic Tape <!--SR:!2023-08-31,4,275-->

What is the symbol used in [System Flow Charts](https://docs.google.com/presentation/d/1N50Sd64Cpz3iV9PCGc_Q2Xg1r1Mw5tbVkIET9jfpZk0/edit#slide=id.p8) to indicate 'Disk Drive'?
?
Cylinder viewed from a front-top angle
![](https://i.imgur.com/5wbigAR.png)

What is this symbol used to indicate in [System Flow Charts](https://docs.google.com/presentation/d/1N50Sd64Cpz3iV9PCGc_Q2Xg1r1Mw5tbVkIET9jfpZk0/edit#slide=id.p8)?
![](https://i.imgur.com/ObbMBSQ.png)
?
Disk Drive

What is the symbol used in [System Flow Charts](https://docs.google.com/presentation/d/1N50Sd64Cpz3iV9PCGc_Q2Xg1r1Mw5tbVkIET9jfpZk0/edit#slide=id.p8) to indicate 'Decision'?
?
Diamond
![](https://i.imgur.com/Ef9qult.png)

What is this symbol used to indicate in [System Flow Charts](https://docs.google.com/presentation/d/1N50Sd64Cpz3iV9PCGc_Q2Xg1r1Mw5tbVkIET9jfpZk0/edit#slide=id.p8) (apparently largly depricated / unused ?
![](https://i.imgur.com/5CiGfUw.png)
?
Decision

What is the symbol used in [System Flow Charts](https://docs.google.com/presentation/d/1N50Sd64Cpz3iV9PCGc_Q2Xg1r1Mw5tbVkIET9jfpZk0/edit#slide=id.p8) to indicate 'Telecommunications'?
?
An elongated 'Z'
![](https://i.imgur.com/TFL535s.png) <!--SR:!2023-08-31,4,275-->

What is this symbol used to indicate in [System Flow Charts](https://docs.google.com/presentation/d/1N50Sd64Cpz3iV9PCGc_Q2Xg1r1Mw5tbVkIET9jfpZk0/edit#slide=id.p8)?
![](https://i.imgur.com/Z0fVkai.png)
?
Telecommunications




##### [Structure Chart](https://docs.google.com/presentation/d/1N50Sd64Cpz3iV9PCGc_Q2Xg1r1Mw5tbVkIET9jfpZk0/edit#slide=id.p11)

What is a [Structure Chart](https://docs.google.com/presentation/d/1N50Sd64Cpz3iV9PCGc_Q2Xg1r1Mw5tbVkIET9jfpZk0/edit#slide=id.p11)?
?
System model to represent the separate modules and subroutines and their relationships to one each other
![[Structure Chart.png]]

Can [Structure Charts](https://docs.google.com/presentation/d/1N50Sd64Cpz3iV9PCGc_Q2Xg1r1Mw5tbVkIET9jfpZk0/edit#slide=id.p11) have curved lines?; No

Do [Structure Charts](https://docs.google.com/presentation/d/1N50Sd64Cpz3iV9PCGc_Q2Xg1r1Mw5tbVkIET9jfpZk0/edit#slide=id.p11) need arrows to indicate direction of data flow?; No

What is the symbol used to represent a module in a [Structure Chart](https://docs.google.com/presentation/d/1N50Sd64Cpz3iV9PCGc_Q2Xg1r1Mw5tbVkIET9jfpZk0/edit#slide=id.p11)?; Rectangle

How is data movement represented in a structure chart?; By Labelled Parameters

How are parameters represented in [Structure Charts](https://docs.google.com/presentation/d/1N50Sd64Cpz3iV9PCGc_Q2Xg1r1Mw5tbVkIET9jfpZk0/edit#slide=id.p11)?; As small not filled in circles with connected arrows indicating the direction of data movement. Text labels are next to each parameter to describe the data.

What are parameters in [Structure Charts](https://docs.google.com/presentation/d/1N50Sd64Cpz3iV9PCGc_Q2Xg1r1Mw5tbVkIET9jfpZk0/edit#slide=id.p11)?; Data movement variables that are parsed between subroutines. 

What are flags in [Structure Charts](https://docs.google.com/presentation/d/1N50Sd64Cpz3iV9PCGc_Q2Xg1r1Mw5tbVkIET9jfpZk0/edit#slide=id.p11)?; A control parameter. Like a normal parameter but can only be a Boolean value.

How are flags represented in [Structure Charts](https://docs.google.com/presentation/d/1N50Sd64Cpz3iV9PCGc_Q2Xg1r1Mw5tbVkIET9jfpZk0/edit#slide=id.p11)?; As filled in circles with a connected arrow indicating the direction that the flag is being passed. Has a text label to describe the flag.

How are optional subroutine / module calls represented in [Structure Charts](https://docs.google.com/presentation/d/1N50Sd64Cpz3iV9PCGc_Q2Xg1r1Mw5tbVkIET9jfpZk0/edit#slide=id.p11)?; As Diamonds overlaying the connection line.

How are binary decisions represented in [Structure Charts](https://docs.google.com/presentation/d/1N50Sd64Cpz3iV9PCGc_Q2Xg1r1Mw5tbVkIET9jfpZk0/edit#slide=id.p11)?; as a right angle symbol between the two connection lines of the models/processes that follow the decision.

How are loops / repetition represented in structure charts?; As an arced arrow forming half an oval around the connection line or lines.


##### [IPO Chart](https://docs.google.com/presentation/d/1N50Sd64Cpz3iV9PCGc_Q2Xg1r1Mw5tbVkIET9jfpZk0/edit#slide=id.p13)

What is an [IPO Chart](https://docs.google.com/presentation/d/1N50Sd64Cpz3iV9PCGc_Q2Xg1r1Mw5tbVkIET9jfpZk0/edit#slide=id.p13)?
?
![](https://i.imgur.com/YzQmepR.png)
- An IPO (Input, Process, Output) Chart is a way of documenting the data in a system.
- The Input for each major process is recorded 
- Major processors are described
- The outputs to the major processes are recorded <!--SR:!2023-08-31,4,275-->

Can an [IPO Charts](https://docs.google.com/presentation/d/1N50Sd64Cpz3iV9PCGc_Q2Xg1r1Mw5tbVkIET9jfpZk0/edit#slide=id.p13) process section have multiple instructions?; Yes. Describes all the instructions in the process

Are the data types of inputs and outputs required in an [IPO Chart](https://docs.google.com/presentation/d/1N50Sd64Cpz3iV9PCGc_Q2Xg1r1Mw5tbVkIET9jfpZk0/edit#slide=id.p13)?; No


##### [Data Dictionary](https://docs.google.com/presentation/d/1N50Sd64Cpz3iV9PCGc_Q2Xg1r1Mw5tbVkIET9jfpZk0/edit#slide=id.p15)

What is a [Data Dictionary](https://docs.google.com/presentation/d/1N50Sd64Cpz3iV9PCGc_Q2Xg1r1Mw5tbVkIET9jfpZk0/edit#slide=id.p15)?
?
- A [Data Dictionary](https://docs.google.com/presentation/d/1N50Sd64Cpz3iV9PCGc_Q2Xg1r1Mw5tbVkIET9jfpZk0/edit#slide=id.p15) contains a comprehensive description of each data item in the system
- Commonly Required Fields:
	- Data Item (Variable name)
	- Data Type
	- Format
	- Number of Bytes Required for Storage
	- Size for Display
	- Description
	- Example
- Other Data Fields:
	- Validation
![](https://i.imgur.com/VbnTZF8.png)

What are the fields required in a [Data Dictionary](https://docs.google.com/presentation/d/1N50Sd64Cpz3iV9PCGc_Q2Xg1r1Mw5tbVkIET9jfpZk0/edit#slide=id.p15)?
?
- Data Item (Variable name)
- Data Type
- Format
- Number of Bytes Required for Storage
- Size for Display
- Description
- Example

How many commonly required fields in a [Data Dictionary](https://docs.google.com/presentation/d/1N50Sd64Cpz3iV9PCGc_Q2Xg1r1Mw5tbVkIET9jfpZk0/edit#slide=id.p15)?
?
7:
- Data Item (Variable name)
- Data Type
- Format
- Number of Bytes Required for Storage
- Size for Display
- Description
- Example <!--SR:!2023-08-28,1,235-->


##### [Screen Design](https://docs.google.com/presentation/d/1N50Sd64Cpz3iV9PCGc_Q2Xg1r1Mw5tbVkIET9jfpZk0/edit#slide=id.p16)

What is a [Screen Design](https://docs.google.com/presentation/d/1N50Sd64Cpz3iV9PCGc_Q2Xg1r1Mw5tbVkIET9jfpZk0/edit#slide=id.p16)?
?
- A depiction of the design and layout of the user interface
- Focus on usability and making user interactions as simple as possible.
- Should use common interface elements. e.g. checkboxes
- Consider the screen size and dimensions
- Identify the required data fields and screen elements along with their placement.
- Should be consistent
- May use labels with arrows to provide description of elements such as colour, images, or text font
![](https://i.imgur.com/Rm8iecy.png) <!--SR:!2023-08-31,4,275-->


##### [Storyboard](https://docs.google.com/presentation/d/1N50Sd64Cpz3iV9PCGc_Q2Xg1r1Mw5tbVkIET9jfpZk0/edit#slide=id.p17)

What is a storyboard?
?
- Shows the interfaces (screens) in a system and the links between them
- Input and output areas should be clearly defined
- Navigation elements such as buttons should be clearly defined
- Linking lines should originate from the element that triggers the change in screen
- Should be detailed enough to determine purpose 
![](https://i.imgur.com/sahzNp4.png)

How are the links between screens in a storyboard depicted?; With straight arrows between the button that directs you to the screen and the screen.

Can you use labels to indicate moving to a screen that is incontinent to connect to. e.g. (back to home screen); Yes

Can you have labels next to screens in a storyboard to indicate extra information about the screen?; Yes

### Table Config
___
#### Development Approaches Table

| Development Approach | Characteristics                                             | Suited for                                          |
| -------------------- | ----------------------------------------------------------- | --------------------------------------------------- |
| Structured           | 5 stages, detailed planning, large team, long timeline      | Large, complex projects with high budget and time   |
| Agile                | Fast, iterative, small team with client, planning as needed | Software that is regularly modified and updated     |
| Prototyping          | Client involvement, successive prototypes                   | UI/user-focused projects, unique needs/small budget |
| RAD                  | Fast, cheap, uses existing modules, client involvement      | Low budget, small scale projects, quick timeline    |
| End-User             | End user developer, cheap, fast, no documentation           | Small long-term projects for the end user           |

