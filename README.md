java cSchool of Engineering 
 
Coursework Title: State Driven Design of a Sequential Ladder Diagram Program. 
Module Name: Automation and IoT 
Module Code: 6570USST 
Level: 6 
Credit Rating: 20 
Weighting: Pass/Fail to Support the 20% Quiz Component 
Lecturer: Ping Liu 
Contact: If you have any issues with this coursework you may contact 
your lecturer. Contact details are: 
Room: T606 
Issue Date: Week 10 
Hand-in Date: Week 12 
Hand-in Method: Submission on Moodle 
Feedback Date: Week 12 
Feedback Method: Feedback will be via the associated Moodle Quiz 
Programmes: MBEng EEE Suite 

 Introduction 
This assignment is an exercise in State Driven Design using ladder software 
Learning Outcomes to be assessed 
LO2, LO3 
 
Coursework Specification 
State Driven Design of a Sequential Ladder Diagram Program. 
 
Assignment 2 – Ladder Based State Design Exercise, PUFFIN Crossing 
 
The objective of this exercise is to use State Design methods to produce a simple sequential system 
using Ladder Diagram programming. 
A system that should be familiar to most people will be used, the PUFFIN pedestrian crossing. The 
PUFFIN crossing replaced the earlier PELICAN crossing and is now the standard UK pedestrian 
crossing. 
The crossing is called PUFFIN to reflect its behaviour as a Pedestrian User Friendly INtelligent 
Crossing (and clearly to give it a silly bird’s name like the previous crossing). 
The objectives of the change were to: 
• Remove the PELICAN crossing’s flashing amber / flashing green man state, which led to 
pedestrian confusion and accidents due to over aggressive driving. 
• Have the same light sequence for car drivers as other UK traffic lights. 
• Move the pedestrian lights from the far side of the road to the near side, in a position where 
pedestrians are more likely to see traffic approaching from the right (fig.1). 
• Introduce sensors to detect when pedestrians had completed crossing, so that drivers are 
not held waiting at an empty crossing. 
 
 
Figure 1. PUFFIN Pedestrian display and control unit The crossing you are to program is known as a “Mid-block” crossing, which is the simplest type 
where the crossing is situated well away from a road junction. 
You are to make the following assumptions about the crossing hardware. 
The pedestrian buttons are normally open, momentary action push-buttons. The buttons on each 
side of the road are connected together in a “wired OR” configuration, so that only a single PLC input 
is required. TRUE means one of the buttons is currently pressed. 
The pedestrian detection circuit is designed to give a TRUE signal when there are no pedestrians 
waiting on either side or on the crossing. Again, a single PLC input is used. 
The system is mains powered, single phase 240VAC. No output requires more than 1 amp. 
Figure 2. This State Diagram describes the required behaviour of the system. 
  
Traffic light abbreviations R = RED, A = AMBER, G = GREEN 
Pedestrian display abbreviations RM = RED MAN, GM = GREEN MAN, W = WAIT 
TNen = 1 means enable timer TN, TN elapsed means timer TN Present Value has reached Set Point 
 Task. 
Use PicoSoft6 Software to program the PUFFIN crossing described by the State Diagram in figure 2 
using Ladder Programming language. You can add clear comments in your program. 
If you are unfamiliar with PUFFIN Crossings this video might help. 
http://58.247.255.82:8125/moodle/mod/resource/view.php?id=42558 
Before you start programming, set up the Configuration to assign an appropriate PLC and any 
extension modules required. 
Your solution ladder program must produce the behaviour specified by the State Diagram given, 
even if you think the State Diagram is not a perfect match to the behaviour of a real PUFFIN crossing! 
It has been simplified deliberately. Don’t add any extra “features”. 
No timer Set Points are indicated on the State Diagram. You should choose sensible values. It might 
be a good idea to use shorter than normal values while developing the system, only changing to 
realistic values when the system is working properly. 
 
Create a single PDF report that includes: 
1) Cover sheet. 
2) Choose an appropriate controller and provide reasons. 
3) STATE/OUTPUT table. 
4) Briefly describe the procedures you used to test your program. 
5) Formal printout of your program in ANSI format from Picosfot. 
Note: The total number of pages for sections 2) to 4) should not exceed two pages. 
Assessment. 
This is a Pass/Fail component. You must demonstrate your program and submit report to Moodle in 
PDF format to be successful. 
The associated quiz will test you on the process, programming and advantages/disadvantages etc. of 
sequential logic design methods. 
 
Guide to Performance Criteria 
70% and above: 
Your work must be of outstanding quality and fully meet the requirements of the coursework 
specification and learning outcomes stated. You must show independent thinking and apply 
this to your work showing originality and consideration of key issues. There must be evidence 
of wider reading on the subject. 
 
60% - 70%: 
Your work must be of good quality and meet the requirements of the coursework specification 
and learning outcomes stated. You must demonstrate some originality in your work and show 
this by applying new learning to the key issues of the coursework代 写6570USST、c/c++，Java
代做程序编程语言. There must be evidence of 
wider reading on the subject. 
 
 
50% - 60%: 
Your work must be comprehensive and meet all of the requirements stated by the coursework 
specification and learning outcomes. You must show a good understanding of the key 
concepts and be able to apply them to solve the problem set by the coursework. There must 
be enough depth to your work to provide evidence of wider reading. 
 
 
40% - 50%: 
Your work must be of a standard that meets the requirements stated by the coursework 
specification and learning outcomes. You must show a reasonable level of understanding of 
the key concepts and principles and you must have applied this knowledge to the coursework 
problem. There should be some evidence of wider reading. 
 
Below 40%: 
Your work is of poor quality and does not meet the requirements stated by the coursework 
specification and learning outcomes. There is a lack of understanding of key concepts and 
knowledge and no evidence of wider reading. 
 
 AHEP4 Outcomes to be assessed 
M4 Select and critically evaluate technical literature and other sources of information 
to solve complex problems. 
M6 Apply an integrated or systems approach to the solution of complex problems. M10 
Adopt a holistic and proportionate approach to the mitigation of security risks. 
M11 Adopt an inclusive approach to engineering practice and recognise the 
responsibilities, benefits and importance of supporting equality, diversity and 
inclusion. 
 
Extenuating Circumstances 
If something serious happens that means that you will not be able to complete this 
assignment, you need to contact the module leader as soon as possible. There are a number 
of things that can be done to help, such as extensions, waivers and alternative assessments, 
but we can only arrange this if you tell us. To ensure that the system is not abused, you will 
need to provide some evidence of the problem. 
Any coursework submitted late without the prior agreement of the module leader will 
receive 0 marks. 
 
Academic Misconduct 
The University defines Academic Misconduct as ‘any case of deliberate, premeditated 
cheating, collusion, plagiarism or falsification of information, in an attempt to deceive and gain 
an unfair advantage in assessment’. The School takes Academic Misconduct very seriously 
and any suspected cases will be investigated through the University’s standard policy. If you 
are found guilty, you may be expelled from the University with no award. 
It is your responsibility to ensure that you understand what constitutes Academic 
Misconduct and to ensure that you do not break the rules. If you are unclear about what 
is required, please ask.  
Cheating includes: 
 
(i) any form of communication with, or copying from, any other source during an 
examination; 
(ii) communicating during an examination with any person other than an authorised 
member of staff; 
(iii) introducing any written, printed or other material into an examination (including 
electronically stored information) other than that specified in the rubric of the 
examination paper; 
(iv) gaining access to unauthorised material in any way during or before an 
assessment; 
(v) the use of mobile phones or any other communication device during an 
assessment or examination; 
(vi) the submission of false claims of previously gained qualifications, research or 
experience in order to gain credit for prior learning; 
(vii) the falsification of research data, the presentation of another’s data as one’s own, 
and any other forms of misrepresentation in order to gain advantage; 
(viii) the submission of work for assessment that has already been submitted as all or 
part of the assessment for another module without the prior knowledge and 
consent of the Module Leader for the subsequent assessments; 
(ix) the submission of material purchased or commissioned from a third party, such 
as an essay-writing service, as one’s own. 
 
 
Plagiarism is defined as the representation of the work, artefacts or designs, written or 
otherwise, of any other person, from any source whatsoever, as the student's own. 
Examples of plagiarism may be as follows: 
 
i) the verbatim copying of another's work without clear identification and 
acknowledgement including the downloading of materials from the Internet 
without proper referencing of materials; 
ii) the paraphrasing of another's work by simply changing a few words or altering 
the order of presentation, without clear identification and acknowledgement; 
iii) the unidentified and unacknowledged quotation of phrases from another's work; 
iv) the deliberate and detailed presentation of another's concept as one's own. 
 
Collusion includes: 
 
(i) the conscious collaboration, without official approval, between two or more 
students in the preparation and production of work which is ultimately submitted 
by each in an identical or substantially similar form and/or is represented by 
each to be the product of his or her individual efforts; (ii) collusion also occurs where there is unauthorised co-operation between a 
student and another person in the preparation and production of work which is 
presented as the student's own. 
 
For more information you are directed to following the University web pages 
 
 
 
         
加QQ：99515681  WX：codinghelp  Email: 99515681@qq.com
