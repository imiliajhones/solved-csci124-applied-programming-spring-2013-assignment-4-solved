Download Link: https://assignmentchef.com/product/solved-csci124-applied-programming-spring-2013-assignment-4-solved
<br>
In this task, you are going to write a C++ class to handle very large numbers. The following prototype is given.class LLONG{public:LLONG();LLONG(int);LLONG(const LLONG &amp;);~LLONG();void add(const LLONG &amp;);void subtract(const LLONG &amp;);void multiply(const LLONG &amp;);void divide(const LLONG &amp;);void mod(const LLONG &amp;);std::ostream &amp; output (std::ostream &amp;);int compare(const LLONG &amp;);// return 0 for equal, 1 for &gt;, -1 for &lt;private:… // your design here… // you are not allowed to use string here};GUIDELINESDo not alter the public part of the class. Design is important. You are not allowed to use the string class as the underlying storage of the large integers. Note that there will be no upper limit on the size of numbers provided that the computer has sufficient memory.Do not hesitate to ask your lecturer or lab tutor if you are unsure of anything or encounter any difficulties. (Remember it is typically the software developer’s responsibility to clarify the requirements of the software with the client.)Important: YOU MUST SUBMIT A MAKE FILE that compiles your code on Banshee.To show all the warnings, you should compile with the -Wall option. Your code should compile without any warnings.As usual, please start early. I am always happy to discuss with you about the idea.SUBMISSIONSubmit your program (and Makefile, if any) via the submit command.submit –u userid –c CSCI124 –a ass4 filenamesPlease make sure you receive the submission receipt after submitting your files.Remember that you have to put the following information on the header of each source file you will be submitting in this assignment:• Student name• Student number• LabPlease also submit a hard copy of your code to one of your tutors or the lecturer anytime before wednesday in week 11 or (during the lecture or the consultation time of the lecturer) after you obtained your submission receipt.An extension of time for the completion of the assignment may be granted in certain circumstances. A request for an extension must be made to the Subject Coordinator before the due date. Supporting documentation must accompany the request for extension. Late assignments without granted extension will be marked but the mark awarded will be reduced by 1 mark for each day late. Assignments more than 3 days late will not be accepted.For late submission, please use the command:submit –u userid –c CSCI124 –a ass4-late filenames