# Java-Naming-Convention
Use short enough and long enough variable names in each scope of code. Generally length may be 1 char for loop counters, 1 word for condition/loop variables, 1-2 words for methods, 2-3 words for classes, 3-4 words for globals.
Use specific names for variables, for example "value", "equals", "data", ... are not valid names for any case.
Use meaningful names for variables. Variable name must define the exact explanation of its content.
Don't start variables with o_, obj_, m_ etc. A variable does not need tags which states it is a variable.
Obey company naming standards and write variable names consistently in application: e.g. txtUserName, lblUserName, cmbSchoolType, ... Otherwise readability will reduce and find/replace tools will be unusable.
Obey programming language standards and don't use lowercase/uppercase characters inconsistently: e.g. userName, UserName, USER_NAME, m_userName, username, ...
 
use Camel Case (aka Upper Camel Case) for classes: VelocityResponseWriter
use Lower Case for packages: com.company.project.ui
use Mixed Case (aka Lower Camel Case) for variables: studentName
use Upper Case for constants : MAX_PARAMETER_COUNT = 100
use Camel Case for enum class names and Upper Case for enum values.
don't use '_' anywhere except constants and enum values (which are constants).
For example for Java, 
Don't reuse same variable name in the same class in different contexts: e.g. in method, constructor, class. So you can provide more simplicity for understandability and maintainability.
Don't use same variable for different purposes in a method, conditional etc. Create a new and different named variable instead. This is also important for maintainability and readability.
Don't use non-ASCII chars in variable names. Those may run on your platform but may not on others.
Don't use too long variable names (e.g. 50 chars). Long names will bring ugly and hard-to-read code, also may not run on some compilers because of character limit.
Decide and use one natural language for naming, e.g. using mixed English and German names will be inconsistent and unreadable.
Use meaningful names for methods. The name must specify the exact action of the method and for most cases must start with a verb. (e.g. createPasswordHash)
Obey company naming standards and write method names consistently in application: e.g. getTxtUserName(), getLblUserName(), isStudentApproved(), ... Otherwise readability will reduce and find/replace tools will be unusable.
Obey programming language standards and don't use lowercase/uppercase characters inconsistently: e.g. getUserName, GetUserName, getusername, ...
For example for Java, 
use  Mixed Case  for method names: getStudentSchoolType 
use  Mixed Case  for method parameters: setSchoolName(String schoolName)
Use meaningful names for method parameters, so it can documentate itself in case of no documentation.
