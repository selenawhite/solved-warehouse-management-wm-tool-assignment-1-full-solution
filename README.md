Download Link: https://assignmentchef.com/product/solved-warehouse-management-wm-tool-assignment-1-full-solution
<br>
<strong>TASKS</strong>

Your tasks are to:

<ul>

 <li>Form and structure your group, allocating roles and responsibilities to your members</li>

 <li>Elicit and specify requirements for the system ( see <strong>Appendix A</strong> ), including:

  <ul>

   <li>all <strong>detailed</strong> <em>functional and non-functional</em> requirements for the new system</li>

   <li>the data that the system will need to manage,</li>

   <li>interfaces to other systems, and</li>

   <li>interfaces and functionalities for different classes of users</li>

  </ul></li>

</ul>

The lecturer and tutor will act as clients for this project. You would also need to explore existing similar systems that are available online

<ul>

 <li>Complete the planning and the requirements analysis for the system that is described in the attached informal specification document</li>

 <li>Use a versioning system of your choice (e.g. Netbeans subversion, TortiseSVN)</li>

 <li>Produce a report detailing the group’s work</li>

</ul>

The book <em>“The rational unified process: an introduction”</em> by P. Kruchten<a href="#_ftn1" name="_ftnref1">[1]</a> contains explanations of the Rational Unified Process (RUP) roles. Details include lists of artifacts that are the responsibility of a person holding a particular role, and workflow diagrams. Students should check these outlines to gain guidance as to what they are to do in the project.

Each group will hold formal “minut-ed” meetings. The group member holding the “manager” role is responsible for these meetings, in particular preparing agendas and keeping meetings on track, and is also responsible for the reports on meetings. The meeting structure should be along the following lines:

<ul>

 <li>Reports from individuals who were allocated “urgent action items” in the previous meeting; discussion of issues related to these “urgent action items”</li>

 <li>Manager reviews his/her perception of the current status of the project; this review is to use data from bug reports and feature tests as created by the systems integrator</li>

 <li>Scheduled agenda items are discussed – in the early meetings this will involve resolution of open design issues, later it will involve review of progress on implementation elements and integration</li>

 <li>Reports by individual members on progress in their areas of responsibility (“code walkthroughs” may be used) and identification of any problems</li>

 <li>Identification of any “urgent action items” and allocation of responsibility for these</li>

 <li>Proposals for agenda items for the subsequent meeting</li>

</ul>

Each group member will maintain a work diary. This should cover: planned work schedule, actual work times, summary of work completed, report on “defects” in own work. The purpose of a work diary is really to provide data that identify ineffective work practices so that remedial action can be taken<a href="#_ftn2" name="_ftnref2">[2]</a>.

Often you will find planned and actual work times differ significantly; such differences may point to poor work management practices. Every developer has his/her own blind spots that lead to defects in code.  Analysis of defect patterns can help identify weaknesses and thus lead to a pre-emptive approach where the developer checks for their typical errors prior to running code.

( Note : for further details on RUP, roles and meetings, please refer to <strong>Appendix B</strong> )

<strong>REPORT</strong>

The work of the group is to be presented in a report. The report is the basis for your assessment. The report should briefly present the product that you are developing and provide evidence for a competently handled development process.

It should use grammatically correct English and should not contain innumerable spelling errors. You should use the spelling and grammar checkers in your word processor application.

The report should consists of the following:

<ul>

 <li>Business case:  What is this system that you are to build?  Who will it serve?  What will it do for them?</li>

 <li>Detailed plans for the whole project (from requirements until implementation)</li>

 <li>Risks and counter measures</li>

 <li>Software Requirements Specification ( refer to <strong>SRS_Template.pdf</strong> )</li>

 <li>Use cases (including use case diagrams and detailed description for each use case)</li>

 <li>A domain model with detailed description of each class</li>

</ul>

<strong>The “meta-report” part should include:</strong>

<ul>

 <li>A tabular summary of the group structure identifying group members, the roles that they filled, the artefacts that they successfully delivered</li>

 <li>Group meeting records and individual diaries:

  <ul>

   <li>There should be a summary detailing the work done at each group meeting</li>

   <li>There should be agendas and reports from all group meetings</li>

   <li>There should be work diaries of all members of the group</li>

  </ul></li>

</ul>

<strong> </strong>Provide evidence for the appropriate use of version control software; this would typically take the form of excerpts from subversion’s logs of commit operations. Subversion (or equivalence) statistical reports, showing overall contributions by different members, should be included in the report

For further information on the report and delivery, please refer to <strong>Appendix C</strong>.

<strong> </strong><strong>DELIVERABLES &amp; SUBMISSION</strong>

Please refer to <strong>Appendix D</strong>.

<strong>MARKING SCHEME</strong>

<ul>

 <li>Overall presentation of report (2 marks)</li>

 <li>Requirements elicitation and analysis efforts as evidenced by your report (9 marks)</li>

 <li>Project management (4 marks)</li>

</ul>

These marks are based on evidence for the use of an effective software development process. Factors contributing to this part of the assessment will include:

<ul>

 <li>evidence for an effective group structure and adoption of roles</li>

 <li>effective group collaboration as evidenced by meaningful group meetings</li>

 <li>well-planned and disciplined work processes of individuals and</li>

 <li>effective use of a versioning system</li>

</ul>

Individual marks are based on the group mark. Individual marks are adjusted in accord with the “member’s contribution assessment” document submitted by the group. Individual marks <em>cannot</em> be greater than the group mark.

<u>APPENDIX A</u>

(Warehouse Management (WM) Tool)

An effective Warehouse Management (WM) Tool is essential for streamlining process, long range planning and optimization. It gives a better understanding of day-to-day operation with its summary information of how a warehouse is performing. The managers could use this data for making critical management decisions.

It is critical for the warehouse management to have an effective system in place due to various reasons such as security, accuracy, availability and so on. Therefore, you are asked to use a <em>test-driven</em> approach to develop the warehouse management tool which needs to meet the following requirements.

<u>Functional Requirements</u>

List of features include:

<ul>

 <li>Ability to add/update records on the incoming stock and outgoing stock easily.</li>

 <li>Track the stock in accordance to their category and sub-category.</li>

 <li>Ability to search and display available stock for a particular category and/or sub-category.</li>

 <li>Ability to search and display stock in accordance to price range and quantity in ascending and descending order.</li>

 <li>Daily, weekly or monthly summary report of total incoming and outgoing stock details.</li>

 <li>Provide login authentication process.</li>

 <li>Login security feature with option of encrypting the data stored.</li>

 <li>If there are three unsuccessful login attempts, the record will be marked as “locked” and one is not allowed to login to the system.</li>

 <li>The system shall encrypt and decrypt the password.</li>

 <li>Provide stock item alerts when it drops below a threshold set previously.</li>

</ul>

The WM may have the following interactive menu:

<ol>

 <li><strong><em>Add new stock</em></strong></li>

 <li><strong><em>Remove stock</em></strong></li>

 <li><strong><em>Edit stock item </em></strong></li>

 <li><strong><em>Search stock item</em></strong></li>

 <li><strong><em>Daily stock summary report</em></strong></li>

 <li><strong><em>Weekly stock summary report</em></strong></li>

 <li><strong><em>Monthly stock summary report</em></strong></li>

 <li><strong><em>Yearly stock summary report</em></strong></li>

 <li><strong><em>Quit</em></strong></li>

</ol>

The WM allows new stock item’s details to be individually entered and then stored in a text file as the following format:

[Item ID]:[Item Description]:[Item Category]: [Item Sub-category]:[Amount Per Unit]:[Qty]: [Transacted date]

eg:

023:Samsung Phone XYZ:Electronics:Mobile Phone:300:100:15-Dec-12

053:Dan Sofa:Furniture:Sofa:1200:-10:15-Dec-12

045:Nike ABC:Shoes:Trainers:50:60:22-Dec-12

023:Samsung Phone XYZ:Electronics:Mobile Phone:300:-50:15-Dec-12

045:Nike ABC:Shoes:Trainers:50:-10:22-Dec-12

<strong> </strong>The colon (:) character is used to separate each piece of information.




<table>

 <tbody>

  <tr>

   <td width="718">

    <table width="100%">

     <tbody>

      <tr>

       <td><strong>Stock item     In          Out         Amount(Per Unit)   Total Amount</strong><strong>023            100         0           300               -30,000</strong><strong>053            0           10          1200              12,000</strong><strong>045            60          0           50                -3,000</strong><strong>023            0           50          300               15,000</strong><strong>045            0           10          50                500</strong><strong> </strong></td>

      </tr>

     </tbody>

    </table></td>

  </tr>

 </tbody>

</table>

A sample of the daily stock transacted is shown below.

You can also provide more information such as the total number of stock items available in the warehouse at any point in time.

<u>Non-Functional Requirements</u>

<ol>

 <li>The system is to be implemented in C++ and is to run on a Linux OS.</li>

 <li>The system is to use a simple textual “menu-select” style of user interface.</li>

</ol>

You need to elicit further requirements and specify them in much more detail in Software Requirement Specification by doing a further requirement analysis with your supervisor.

<u>Note:</u> The first part of this project (Assignment 1) involves planning and eliciting and analyzing requirements. The second part (Assignment 2) will involve designing, implementing and testing the system.

<u>APPENDIX B</u>

( Requirement / Task – Extra info )

<ol>

 <li>The purpose of this assignment is to simulate the RUP approach to software development, starting with the requirements gathering, all the way to system analysis and design. (Note: for this Assignment, there is no need to implement (i.e. code) your system). However, your team must produce the necessary artifacts (i.e. documents) covering this aspect of your system development.</li>

 <li>Form a group of 6 members, adhering to the following criteria:</li>

</ol>

<ul>

 <li>group members must come from the SAME class, absolutely no “inter-class” group members</li>

 <li>the no. of members in each group MUST BE EXACTLY THE SAME : 6, except in <strong>special situations</strong> where (# of students in a class) mod 6 != 0 (i.e. got remainder)</li>

 <li>if possible, try to achieve a balanced gender ratio of 1 : 1, (no boy-bands / girl-generation)</li>

 <li>in the event of <strong>special situations</strong>, the tutor will step in to assign “remainder students” to registered groups (i.e. some groups will have 7 members)</li>

</ul>

<ol>

 <li>In general, your team should undergo (at least):</li>

 <li>a) Inception phase : 1-2 iterations</li>

 <li>b) Elaboration phase : 2-3 iterations</li>

 <li>c) Construction phase : 2-3 iterations</li>

 <li>d) Transition : 1-2 iterations</li>

</ol>

However, since this Assignment is mainly focusing on activities from <strong><u>Inception</u></strong> and <strong><u>Elaboration</u></strong> phases only, the iterations in Construction and Transition should be of lower priority

<ol>

 <li>Based on the above, your team should have undergone a total of 3-5 iterations (in Inception + Elaboration phases). Therefore, the min. no. of:</li>

 <li>a) <strong>formal meeting minutes</strong> should be &gt;= 3 !</li>

 <li>b) <strong>formal work diary</strong> should be &gt;= 3  (for <u>each</u> team member, hence</li>

</ol>

5 team members x 3 = 15 work diaries for the whole team)

<ol>

 <li>As mentioned in pgs 1-2 of this Qn Paper, each meeting minutes should cover the following points / decisions:</li>

 <li>a) Progress status from individual members, who were allocated urgent action                             items in previous meeting [ ‘N’ paragraphs ]</li>

 <li>b) Manager summarizes the overall progress of the entire system [ 1 paragraph ]</li>

 <li>c) Brainstorm and discuss on any un-resolved issues / urgent action items from                          previous meeting [ ‘N’ paragraphs ]</li>

 <li>d) Brainstorm and discuss on the remaining tasks (e.g. research / exploration /</li>

</ol>

development / testing / deployment ) to be done [ ‘N’ paragraphs ]

<ol>

 <li>e) Decide how much time should be allocated to each issue / task [ 1 paragraph                         of bulleted points ]</li>

 <li>f) Allocate tasks to team members [ use a table ]</li>

 <li>g) Decide on the agenda (items/issues to discuss) for the next meeting [ 1                                    paragraph of bulleted points ]</li>

</ol>

Note : the paragraphs in “[ ]” is just a guideline on the format / usual length of the content!

<ol>

 <li>As mentioned in pgs 1-2 of this Qn Paper, each work diary is like a “personal log” that tracks of a team member’s personal progress. The diary should cover the following information:</li>

 <li>a) The start + end date the period covers</li>

 <li>b) What were the list of tasks allocated to you, (should be smiilar to the tasks  allocated to you in the previous formal meeting)</li>

 <li>c) For each task, discuss the following:</li>

</ol>

–           how much “actual time” you spent on it

–           did you breakdown the task into smaller sub-tasks?

–           are all the sub-tasks completed?

–           which sub-task(s) you faced difficulties, and how do you resolve it?

–           did you discuss your problems with fellow colleagues? What were the                                       remedial actions taken?

<ol>

 <li>The roles required for this group assignment are:</li>

</ol>

<ul>

 <li>Manager (1) – the “Team Leader”</li>

 <li>Lead designer / implementer (1) – probably the same person, but the “lead” role could be split;</li>

 <li>Designer / Implementer / Documentation (many)</li>

 <li>Systems Integration and Testing (1)</li>

</ul>

The designated team leader should take the role of manager or of lead designer /             implementer. Each implementer is responsible for unit testing of his/her code.<u>APPENDIX C</u>

(Report Details)

<ol>

 <li>A document “<strong><em>A1_Sample_Report_Format.doc</em></strong>” has been provided for you. All teams are to follow its recommendations to organize the contents in a structured manner.</li>

 <li>Another document “<strong><em>SRS_Template.pdf</em></strong> ” has been provided for you. It gives you an idea of the information required produce the Software Requirements Specification. Please adhere to the format and section headings in this template.</li>

 <li>For all documentation produced, factors like how you communicate your ideas, how you organize your information and the “professionalism” (i.e. overall presentation) plays an important role in capturing your system’s requirements and design.</li>

</ol>

<ul>

 <li>In order to communicate better in your report, where applicable, you should make use of visual elements like graphs, diagrams, charts, screen-shots, tables, appendices, glossary, etc. to help clarify your ideas</li>

 <li>In order to make your report content more professional and organized, you should have the following in your documents: Cover page, Table of Contents, Formatted document header and/or footer, proper paragraph indentation and alignment, consistent bulleted points, page numbering, etc.</li>

</ul>

<ol>

 <li>During lab session, time will be allocated for each team to present their ideas. All teams are to:</li>

</ol>

<ul>

 <li>use power-point slides as the main presentation aid (optional : ‘other’ multi-media elements like video clips, role play, etc)</li>

 <li>ensure all members has “equal exposure” in presentation</li>

 <li>adhere strictly to the allocated time for presentation</li>

</ul>

( Note : In a real working environment, factors like starting presentation on time, adhering to time limits for presentation, being professionally dressed and not using Notepad to present your ideas, etc are crucial towards creating a good impression in the minds of CEO and senior management towards your project! )

<u>APPENDIX D</u>

Submission Instructions  (V. IMPT!!)

<ul>

 <li><strong>Deliverables</strong></li>

</ul>

<ol>

 <li>Download “PeerAssess and GrpWrkContributionStmnt.pdf”, fill it up and submit in HARDCOPY during the lab session.</li>

 <li>All other submissions should be in <strong>softcopy</strong>, unless otherwise instructed</li>

 <li>For the actual files to be submitted, you need to include the following:</li>

 <li>MAIN REPORT word document (e.g. <strong>A1_</strong><strong>doc</strong>), save as <u>MS Word 97-2003</u> format</li>

 <li>MAIN REPORT in <u>PDF format</u> (e.g. <strong>A1_</strong><strong>pdf</strong>)</li>

</ol>

<ul>

 <li>Software Requirements Specifications word document (e.g. <strong>doc</strong>), save as <u>MS Word 97-2003</u> format</li>

</ul>

<ol>

 <li>Software Requirements Specifications in <u>PDF format</u> (e.g. <strong>pdf</strong>)</li>

 <li>Powerpoint Presentation (e.g. <strong>ppt</strong>), save as <u>MS Powerpoint 97-2003</u> format</li>

</ol>




<ul>

 <li><strong>How to package</strong></li>

</ul>

Compress all your assignment files into a <u>single zip file</u>. Please use the following naming             format :

<strong>&lt;FT</strong><strong>/</strong><strong>PT&gt;</strong>_Assn<strong>1</strong>_<strong>&lt;Team Leader’s Stud. No.&gt;_&lt;Team Leader’s Name&gt;.zip</strong>

<em>Example : </em> <strong>FT</strong>_Assn<strong>1</strong>_<strong>1234567_JohnDoeAnderson.zip</strong>

<ul>

 <li><strong>&lt;FT</strong><strong>/</strong><strong>PT&gt;</strong> Use “<strong>FT</strong>” for <strong>F</strong>ull-<strong>T</strong>ime student, “<strong>PT</strong>” if you are <strong>P</strong>art-<strong>T</strong>ime student</li>

 <li>Assn<strong>1</strong> if you are submitting assignment <strong>1</strong>, Assn<strong>2</strong> if submitting assignment <strong>2</strong></li>

 <li><strong>&lt;Team Leader’s Stud. No.&gt;</strong> refers to team leader’s UOW student number (e.g. 1234567)</li>

 <li><strong>&lt;Team Leader’s Name&gt;</strong> refers to team leader’s UOW registered name (e.g. JohnDoeAnderson)</li>

 <li><strong>Where to submit </strong></li>

</ul>

Please submit your assignment via Moodle eLearning site.

<strong>In the event of UNFORSEEN SITUATIONS : </strong>

( E.g.  Student’s moodle account not ready, cannot login to moodle, eLearning site down on submission day, unable to upload assignment, etc )

Please email your single zip file to your tutor at :

<a href="/cdn-cgi/l/email-protection#2043534349121014554f57605941484f4f0e434f4d"><span class="__cf_email__" data-cfemail="1a796979732828286f756d5a637b72757534797577">[email protected]</span></a>      for<em> <strong>FULL</strong></em> TIME students

<table>

 <tbody>

  <tr>

   <td width="498"></td>

  </tr>

  <tr>

   <td></td>

   <td></td>

  </tr>

 </tbody>

</table>

(To be announced)                      for <strong><em>PART</em></strong> TIME students

In your email <strong>subject</strong> line, type in the following information :

&lt;<strong>FT</strong><strong>/</strong><strong>PT</strong>&gt; &lt;assignment info&gt; &lt;<strong>Team Leader’s student number</strong>&gt; and &lt;<strong>Team Leader’s name</strong>&gt;

<table>

 <tbody>

  <tr>

   <td width="0"></td>

   <td width="213"></td>

   <td width="60"></td>

   <td width="47"></td>

   <td width="35"></td>

   <td width="164"></td>

  </tr>

  <tr>

   <td></td>

   <td colspan="4"></td>

   <td rowspan="4"></td>

  </tr>

  <tr>

   <td></td>

   <td rowspan="4"></td>

  </tr>

  <tr>

   <td></td>

   <td></td>

   <td></td>

  </tr>

  <tr>

   <td></td>

  </tr>

  <tr>

   <td></td>

  </tr>

 </tbody>

</table>

Example:

<strong>            To</strong>                   :           <strong><a href="/cdn-cgi/l/email-protection#167565757f242622637961566f777e79793875797b">tutor’s</a> email</strong> (see above)

<strong>            Subject</strong>          :           <strong>FT</strong> Assn<strong>1</strong> <strong>1234567</strong> <strong>JohnDoeAnderson</strong>

<strong><em>Note 1 : </em></strong>        The timestamp shown on tutor’s email Inbox will be used to determine if the                               assignment is late or not.

<strong><em>Note 2 : </em></strong>        After email submission, your mailbox’s  <strong><em>sent folder</em></strong>  would have a copy                                    (record) of your sent email, please <strong><u>do not delete</u></strong> that copy !!  It could be used                                    prove your timely submission, in case the Tutor did not receive your email!

<ul>

 <li><strong>When to submit</strong></li>

</ul>

<ol>

 <li>Depending on the time-table, a <u>demo / evaluation for your lab submission</u> may be scheduled during the:</li>

</ol>

<ul>

 <li>3<sup>rd</sup> – 5<sup>th</sup> lab session for the semester (i.e. lab 3 – 5), for Full Time (<strong>FT</strong>) students</li>

 <li>2<sup>nd</sup> – 4<sup>th</sup> lab session for the semester (i.e. lab 2 – 4), for Part Time (<strong>PT</strong>) students</li>

</ul>

Please consult your tutor for further details. Some time may be allocated for each student to present / explain your system design during the session.

<ol>

 <li>Please refer to the following table on the different submission events and deadlines</li>

</ol>




<table>

 <tbody>

  <tr>

   <td width="93"><strong>Assessment</strong><strong>Component</strong></td>

   <td width="221"><strong>Submission Deadline</strong><strong>(latest by 2300 hrs)</strong></td>

   <td width="145"><strong>Assessment</strong><strong>Presentation / Evaluation</strong></td>

   <td width="194"><strong>Email Evaluation files by :</strong></td>

  </tr>

  <tr>

   <td width="93">Lab</td>

   <td width="221">01 / 02 / 2017</td>

   <td width="145">Lab 2(PT), 3(FT)</td>

   <td width="194">End of Lab 2(PT), 3(FT)</td>

  </tr>

  <tr>

   <td width="93"><strong>Assn 1</strong></td>

   <td width="221">20 / 02 / 2017</td>

   <td width="145">Lab 3(PT), 4(FT)</td>

   <td width="194">End of Lab 3(PT), 4(FT)</td>

  </tr>

  <tr>

   <td width="93">Assn 2</td>

   <td width="221">27 / 02 / 2017</td>

   <td width="145">Lab 4(PT), 5(FT)</td>

   <td width="194">End of Lab 4(PT), 5(FT)</td>

  </tr>

 </tbody>

</table>




Note: (PT) = Part Time Students, (FT) = Full Time Students !

<ol>

 <li><strong>Example #1</strong>, for Full Time (<strong>FT</strong>) students submitting Lab Exercises …</li>

</ol>

<ul>

 <li>Submit your zip file to Tutor by <strong>01</strong> / <strong>02</strong> / <strong>2017</strong>, 2300 hrs</li>

 <li>Setup your Lab Exercises submission for presentation / evaluation <u>on the date</u> of : <strong>Lab 3</strong></li>

 <li>Finish evaluation tasks, email <u>Lab Ex</u> evaluation files <u>by end</u> of : <strong>Lab 3</strong></li>

</ul>

<ol>

 <li><strong>Example #2</strong>, for Full Time (<strong>FT</strong>) students submitting Assignment <strong>2</strong> …</li>

</ol>

<ul>

 <li>Submit your zip file to Tutor by <strong>27</strong> / <strong>02</strong> / <strong>2017</strong>, 2300 hrs</li>

 <li>Setup your <u>Assn2</u> submission for presentation / evaluation <u>on the date</u> of : <strong>Lab 5</strong></li>

 <li>Finish evaluation tasks, email <u>Assn2</u> evaluation files <u>by end</u> of : <strong>Lab 5</strong></li>

</ul>

<ol>

 <li>Some time will be allocated for each team to present / explain your system design during the session. The tutor will inform you on the presentation schedule as the deadline draws near.</li>

</ol>

<ul>

 <li><strong>Please help by paying attention to the following …</strong></li>

</ul>




<strong>! VERY IMPORTANT !</strong>




PLEASE FOLLOW THE GUIDELINES IN ALL ASSIGNMENT APPENDICES !!




PLEASE FOLLOW THE SUBMISSION INSTRUCTIONS FROM <strong>1</strong> TO <strong>4</strong> !!




IF YOU ARE NOT SURE,




PLEASE CHECK WITH YOUR TUTOR DURING LABS / LECTURES !




OR …




PLEASE EMAIL YOUR ENQUIRIES TO YOUR TUTOR !




MARKS <u>WILL BE DEDUCTED</u> IF YOU FAIL TO FOLLOW INSTRUCTIONS !!







Example :




<ul>

 <li>Your report document or zip file does not follow naming convention</li>

 <li>Your email address does not include your name (i.e. cannot be used to identify sender)</li>

 <li>You have no email subject</li>

</ul>




<ul>

 <li>Wrong naming or <strong>misleading information</strong> given</li>

</ul>

(e.g. putting “Assn2” in email subject, when you are submitting “Assn1”)

(e.g. naming “Assn1” in your zip file, but inside contains Assn2 files )




<ul>

 <li>Your submission cannot be downloaded and unzipped</li>

 <li>Your report cannot be opened by Microsoft Word / Powerpoint / Adobe Acrobat</li>

 <li>Your program cannot be re-compiled and/or executable file cannot run</li>

</ul>







<strong> </strong>

<ul>

 <li><strong>Re-submission administration</strong></li>

</ul>




After the deadline, (on case-by-case basis), some students / grp may be granted an             opportunity for an un-official resubmission by the tutor. If this is so, please adhere to the             following instructions carefully:




&lt;Step 1&gt;




Zip up for re-submission files according to the following format :




<strong>&lt;FT</strong><strong>/</strong><strong>PT&gt;</strong>_Assn<strong>1</strong>_<strong>Resubmit_v1</strong>_<strong>&lt;Team Leader’s Stud. No.&gt; _&lt;Team Leader’s Name&gt;.zip</strong>




<em>    Example : </em> <strong>FT</strong> _ Assn<strong>1</strong>_Resubmit_v1_<strong>1234567_JohnDoeAnderson. zip</strong>




<ul>

 <li><strong>&lt;FT</strong><strong>/</strong><strong>PT&gt;</strong> Use “<strong>FT</strong>” for <strong>F</strong>ull-<strong>T</strong>ime student, “<strong>PT</strong>” if you are <strong>P</strong>art-<strong>T</strong>ime student</li>

 <li>Assn<strong>1</strong> if you are submitting assignment <strong>1</strong>, Assn<strong>2</strong> if submitting assignment <strong>2</strong></li>

 <li><strong>Resubmit_v1 </strong>if this is your <strong>1<sup>st</sup> </strong>re-submission</li>

 <li><strong>Resubmit_v2</strong> if this is your <strong>2<sup>nd</sup> </strong>re-submission</li>

 <li><strong>&lt;Team Leader’s Stud. No.&gt;</strong> refers to team leader’s UOW student number (e.g. <strong>1234567</strong>)</li>

 <li><strong>&lt;Team Leader’s Name&gt;</strong> refers to team leader’s UOW registered name (e.g. <strong>JohnDoeAnderson</strong>)</li>

 <li>IMPT – To prevent Tutor’s Inbox from blowing up in his face, each student is <u>only allowed to re-submit twice</u>, for each assignment only!</li>

</ul>




&lt;Step 2&gt;




Please email your single zip file to your tutor’s email (refer to section 3) – Where to submit)




In your email <strong>subject</strong> line, type in the following information :




&lt;<strong>FT</strong><strong>/</strong><strong>PT</strong>&gt; &lt;assn info&gt;  &lt;re-submission ver.&gt; &lt;<strong>Team Leader’s student number</strong>&gt; and &lt;<strong> Team                                                                                                                                       Leader’s name</strong>&gt;

<table>

 <tbody>

  <tr>

   <td width="495"></td>

  </tr>

  <tr>

   <td></td>

   <td></td>

  </tr>

 </tbody>

</table>










Example:




<strong>            To</strong>                   :           <strong>tutor’s email</strong> (refer to section 3) – Where to submit)




<strong>            Subject</strong>          :           <strong>FT</strong> Assn<strong>1</strong> <strong>Resubmit_v1</strong> <strong>1234567</strong> <strong>JohnDoeAnderson</strong>




<a href="#_ftnref1" name="_ftn1">[1]</a> The Kruchten book is available as an electronic resource through the University library’s subscription to Safari.

<a href="#_ftnref2" name="_ftn2">[2]</a> Take a look at Humphrey’s Personal Software Process; it will give you helpful suggestions as to what data to record, and how to use such data to improve your work practices.