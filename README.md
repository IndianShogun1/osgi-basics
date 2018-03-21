# osgi-basics

Create service ClassConfigurationService that allows two configuration :<br>
No. of students allowed in the class<br>
marks required by the student to pass the class<br>
also it exposes two methods :<br>
isClassLimitReached(List) // returns true if the list size is less than the configured allowed size<br>
getPassingMarks() // returns the passing marks required<br>

Create another service StudentClassService that maintains the list of students in the class and make use of ClassConfigurationService and exposes the following methods :<br>
addStudent(student values)<br>
deleteStudent(id)<br>
isStudentPassed(id)<br>
getStudent(id)<br>
getAllStudents()<br>

A student may have id,name , marks obtained,age etc<br>
Access the service and print a students information.<br>


