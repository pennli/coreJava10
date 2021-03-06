<< core java 10th vol One>> with JDK 1.8
## Ch 1: An Introduction to Java	1
	1.1 Java as a Programming Platform	1
	1.2 The Java “White Paper” Buzzwords	2
		1.2.1 Simple	3
		1.2.2 Object-Oriented	4
		1.2.3 Distributed	4
		1.2.4 Robust	4
		1.2.5 Secure	4
		1.2.6 Architecture-Neutral	5
		1.2.7 Portable	6
		1.2.8 Interpreted	7
		1.2.9 High-Performance	7
		1.2.10 Multithreaded	7
		1.2.11 Dynamic	8
	1.3 Java Applets and the Internet	8
	1.4 A Short History of Java	10
	1.5 Common Misconceptions about Java	13
## Ch 2: The Java Programming Environment	17
	2.1 Installing the Java Development Kit	18
		2.1.1 Downloading the JDK	18
		2.1.2 Setting up the JDK	20
		2.1.3 Installing Source Files and Documentation	22
	2.2 Using the Command-Line Tools	23
	2.3 Using an Integrated Development Environment	26
	2.4 Running a Graphical Application	30
	2.5 Building and Running Applets	33
## Ch 3: Fundamental Programming Structures in Java	41
	3.1 A Simple Java Program	42
	3.2 Comments	46
	3.3 Data Types	47
		3.3.1 Integer Types	47
		3.3.2 Floating-Point Types	48
		3.3.3 The char Type	50
		3.3.4 Unicode and the char Type	51
		3.3.5 The boolean Type	52
	3.4 Variables	53
		3.4.1 Initializing Variables	54
		3.4.2 Constants	55
	3.5 Operators	56
		3.5.1 Mathematical Functions and Constants	57
		3.5.2 Conversions between Numeric Types	59
		3.5.3 Casts	60
		3.5.4 Combining Assignment with Operators	61
		3.5.5 Increment and Decrement Operators	61
		3.5.6 Relational and boolean Operators	62
		3.5.7 Bitwise Operators	63
		3.5.8 Parentheses and Operator Hierarchy	64
		3.5.9 Enumerated Types	65
	3.6 Strings	65
		3.6.1 Substrings	66
		3.6.2 Concatenation	66
		3.6.3 Strings Are Immutable	67
		3.6.4 Testing Strings for Equality	68
		3.6.5 Empty and Null Strings	69
		3.6.6 Code Points and Code Units	70
		3.6.7 The String API	71
		3.6.8 Reading the Online API Documentation	74
		3.6.9 Building Strings	77
	3.7 Input and Output	78
		3.7.1 Reading Input	79
		3.7.2 Formatting Output	82
		3.7.3 File Input and Output	87
	3.8 Control Flow	89
		3.8.1 Block Scope	89
		3.8.2 Conditional Statements	90
		3.8.3 Loops	94
		3.8.4 Determinate Loops	99
		3.8.5 Multiple Selections—The switch Statement	103
		3.8.6 Statements That Break Control Flow	106
	3.9 Big Numbers	108
	3.10 Arrays	111
		3.10.1 The “for each” Loop	113
		3.10.2 Array Initializers and Anonymous Arrays	114
		3.10.3 Array Copying	114
		3.10.4 Command-Line Parameters	116
		3.10.5 Array Sorting	117
		3.10.6 Multidimensional Arrays	120
		3.10.7 Ragged Arrays	124
## Ch 4: Objects and Classes	129
	4.1 Introduction to Object-Oriented Programming	130
		4.1.1 Classes	131
		4.1.2 Objects	132
		4.1.3 Identifying Classes	133
		4.1.4 Relationships between Classes	133
	4.2 Using Predefined Classes	135
		4.2.1 Objects and Object Variables	136
		4.2.2 The LocalDate Class of the Java Library	139
		4.2.3 Mutator and Accessor Methods	141
	4.3 Defining Your Own Classes	145
		4.3.1 An Employee Class	145
		4.3.2 Use of Multiple Source Files	149
		4.3.3 Dissecting the Employee Class	149
		4.3.4 First Steps with Constructors	150
		4.3.5 Implicit and Explicit Parameters	152
		4.3.6 Benefits of Encapsulation	153
		4.3.7 Class-Based Access Privileges	156
		4.3.8 Private Methods	156
		4.3.9 Final Instance Fields	157
	4.4 Static Fields and Methods	158
		4.4.1 Static Fields	158
		4.4.2 Static Constants	159
		4.4.3 Static Methods	160
		4.4.4 Factory Methods	161
		4.4.5 The main Method	161
	4.5 Method Parameters	164
	4.6 Object Construction	171
		4.6.1 Overloading	172
		4.6.2 Default Field Initialization	172
		4.6.3 The Constructor with No Arguments	173
		4.6.4 Explicit Field Initialization	174
		4.6.5 Parameter Names	175
		4.6.6 Calling Another Constructor	176
		4.6.7 Initialization Blocks	177
		4.6.8 Object Destruction and the finalize Method	181
	4.7 Packages	182
		4.7.1 Class Importation	183
		4.7.2 Static Imports	185
		4.7.3 Addition of a Class into a Package	185
		4.7.4 Package Scope	189
	4.8 The Class Path	190
		4.8.1 Setting the Class Path	193
	4.9 Documentation Comments	194
		4.9.1 Comment Insertion	194
		4.9.2 Class Comments	195
		4.9.3 Method Comments	195
		4.9.4 Field Comments	196
		4.9.5 General Comments	196
		4.9.6 Package and Overview Comments	198
		4.9.7 Comment Extraction	198
	4.10 Class Design Hints	200
## Ch 5: Inheritance	203
	5.1 Classes, Superclasses, and Subclasses	204
		5.1.1 Defining Subclasses	204
		5.1.2 Overriding Methods	206
		5.1.3 Subclass Constructors	207
		5.1.4 Inheritance Hierarchies	212
		5.1.5 Polymorphism	213
		5.1.6 Understanding Method Calls	214
		5.1.7 Preventing Inheritance: Final Classes and Methods	217
		5.1.8 Casting	219
		5.1.9 Abstract Classes	221
		5.1.10 Protected Access	227
	5.2 Object: The Cosmic Superclass	228
		5.2.1 The equals Method	229
		5.2.2 Equality Testing and Inheritance	231
		5.2.3 The hashCode Method	235
		5.2.4 The toString Method	238
	5.3 Generic Array Lists	244
		5.3.1 Accessing Array List Elements	247
		5.3.2 Compatibility between Typed and Raw Array Lists	251
	5.4 Object Wrappers and Autoboxing	252
	5.5 Methods with a Variable Number of Parameters	256
	5.6 Enumeration Classes	258
	5.7 Reflection	260
		5.7.1 The Class Class	261
		5.7.2 A Primer on Catching Exceptions	263
		5.7.3 Using Reflection to Analyze the Capabilities of Classes	265
		5.7.4 Using Reflection to Analyze Objects at Runtime	271
		5.7.5 Using Reflection to W rite Generic Array Code	276
		5.7.6 Invoking Arbitrary Methods	279
	5.8 Design Hints for Inheritance	283
## Ch 6: Interfaces, Lambda Expressions, and Inner Classes	287
	6.1 Interfaces	288
		6.1.1 The Interface Concept	288
		6.1.2 Properties of Interfaces	295
		6.1.3 Interfaces and Abstract Classes	297
		6.1.4 Static Methods	298
		6.1.5 Default Methods	298
		6.1.6 Resolving Default Method Conflicts	300
	6.2 Examples of Interfaces	302
		6.2.1 Interfaces and Callbacks	302
		6.2.2 The Comparator Interface	305
		6.2.3 Object Cloning	306
	6.3 Lambda Expressions	314
		6.3.1 Why Lambdas?	314
		6.3.2 The Syntax of Lambda Expressions	315
		6.3.3 Functional Interfaces	318
		6.3.4 Method References	319
		6.3.5 Constructor References	321
		6.3.6 Variable Scope	322
		6.3.7 Processing Lambda Expressions	324
		6.3.8 More about Comparators	328
	6.4 Inner Classes	329
		6.4.1 Use of an Inner Class to Access Object State	331
		6.4.2 Special Syntax Rules for Inner Classes	334
		6.4.3 Are Inner Classes Useful? Actually Necessary? Secure?	335
		6.4.4 Local Inner Classes	339
		6.4.5 Accessing Variables from Outer Methods	339
		6.4.6 Anonymous Inner Classes	342
		6.4.7 Static Inner Classes	346
	6.5 Proxies	350
		6.5.1 When to Use Proxies	350
		6.5.2 Creating Proxy Objects	350
		6.5.3 Properties of Proxy Classes	355
## Ch 7: Exceptions, Assertions, and Logging	357
	7.1 Dealing with Errors	358
		7.1.1 The Classification of Ex ceptions	359
		7.1.2 Declaring Checked Exceptions	361
		7.1.3 How to Throw an Exception	364
		7.1.4 Creating Exception Classes	365
	7.2 Catching Exceptions	367
		7.2.1 Catching an Exception	367
		7.2.2 Catching Multiple Exceptions	369
		7.2.3 Rethrowing and Chaining Exceptions	370
		7.2.4 The finally Clause	372
		7.2.5 The Try-with-Resources Statement	376
		7.2.6 Analyzing Stack Trace Elements	377
	7.3 Tips for Using Exceptions	381
	7.4 Using Assertions	384
		7.4.1 The Assertion Concept	384
		7.4.2 Assertion Enabling and Disabling	385
		7.4.3 Using Assertions for Parameter Checking	386
		7.4.4 Using Assertions for Documenting Assumptions	387
	7.5 Logging	389
		7.5.1 Basic Logging	389
		7.5.2 Advanced Logging	390
		7.5.3 Changing the Log Manager Configuration	392
		7.5.4 Localization	393
		7.5.5 Handlers	394
		7.5.6 Filters	398
		7.5.7 Formatters	399
		7.5.8 A Logging Recipe	399
	7.6 Debugging Tips	409
## Ch 8: Generic Programming	415
	8.1 Why Generic Programming?	416
		8.1.1 The Advantage of Type Parameters	416
		8.1.2 Who Wants to Be a Generic Programmer?	417
	8.2 Defining a Simple Generic Class	418
	8.3 Generic Methods	421
	8.4 Bounds for Type Variables	422
	8.5 Generic Code and the Virtual Machine	425
		8.5.1 Type Erasure	425
		8.5.2 Translating Generic Expressions	426
		8.5.3 Translating Generic Methods	427
		8.5.4 Calling Legacy Code	429
	8.6 Restrictions and Limitations	430
		8.6.1 Type Parameters Cannot Be Instantiated with Primitive Types	430
		8.6.2 Runtime Type Inquiry Only Works with Raw Types	431
		8.6.3 You Cannot Create Arrays of Parameterized Types	431
		8.6.4 Varargs Warnings	432
		8.6.5 You Cannot Instantiate Type Variables	433
		8.6.6 You Cannot Construct a Generic Array	434
		8.6.7 Type Variables Are Not Valid in Static Contexts of Generic Classes	436
		8.6.8 You Cannot Throw or Catch Instances of a Generic Class	436
		8.6.9 You Can Defeat Checked Exception Checking	437
		8.6.10 Beware of Clashes after Erasure	439
	8.7 Inheritance Rules for Generic Types	440
	8.8 Wildcard Types	442
		8.8.1 The Wildcard Concept	442
		8.8.2 Supertype Bounds for Wildcards	444
		8.8.3 Unbounded Wildcards	447
		8.8.4 Wildcard Capture	448
	8.9 Reflection and Generics	450
		8.9.1 The Generic Class Class	450
		8.9.2 Using Class<T> Parameters for Type Matching	452
		8.9.3 Generic Type Information in the Virtual Machine	452
## Ch 9: Collections	459
	9.1 The Java Collections Framework	460
		9.1.1 Separating Collection Interfaces and Implementation	460
		9.1.2 The Collection Interface	463
		9.1.3 Iterators	463
		9.1.4 Generic Utility Methods	466
		9.1.5 Interfaces in the Collections Framework	469
	9.2 Concrete Collections	472
		9.2.1 Linked Lists	474
		9.2.2 Array Lists	484
		9.2.3 Hash Sets	485
		9.2.4 Tree Sets	489
		9.2.5 Queues and Deques	494
		9.2.6 Priority Queues	495
	9.3 Maps	497
		9.3.1 Basic Map Operations	497
		9.3.2 Updating Map Entries	500
		9.3.3 Map Views	502
		9.3.4 Weak Hash Maps	504
		9.3.5 Linked Hash Sets and Maps	504
		9.3.6 Enumeration Sets and Maps	506
		9.3.7 Identity Hash Maps	507
	9.4 Views and Wrappers	509
		9.4.1 Lightweight Collection Wrappers	509
		9.4.2 Subranges	510
		9.4.3 Unmodifiable V iews	511
		9.4.4 Synchronized Views	512
		9.4.5 Checked Views	513
		9.4.6 A Note on Optional Operations	514
	9.5 Algorithms	517
		9.5.1 Sorting and Shuffling	518
		9.5.2 Binary Search	521
		9.5.3 Simple Algorithms	522
		9.5.4 Bulk Operations	524
		9.5.5 Converting between Collections and Arrays	525
		9.5.6 Writing Your Own Algorithms	526
	9.6 Legacy Collections	528
		9.6.1 The Hashtable Class	528
		9.6.2 Enumerations	528
		9.6.3 Property Maps	530
		9.6.4 Stacks	531
		9.6.5 Bit Sets	532
## Ch 10: Graphics Programming	537
	10.1 Introducing Swing	538
	10.2 Creating a Frame	543
	10.3 Positioning a Frame	546
		10.3.1 Frame Properties	549
		10.3.2 Determining a Good Frame Size	549
	10.4 Displaying Information in a Component	554
	10.5 Working with 2D Shapes	560
	10.6 Using Color	569
	10.7 Using Special Fonts for Text	573
	10.8 Displaying Images	582
## Ch 11: Event Handling	587
	11.1 Basics of Event Handling	587
		11.1.1 Example: Handling a Button Click	591
		11.1.2 Specifying Listeners Concisely	595
		11.1.3 Example: Changing the Look-and-Feel	598
		11.1.4 Adapter Classes	603
	11.2 Actions	607
	11.3 Mouse Events	616
	11.4 The AWT Event Hierarchy	624
		11.4.1 Semantic and Low-Level Events	626
## Ch 12: User Interface Components with Swing	629
	12.1 Swing and the Model-View-Controller Design Pattern	630
		12.1.1 Design Patterns	630
		12.1.2 The Model-View-Controller Pattern	632
		12.1.3 A Model-View-Controller Analysis of Swing Buttons	636
	12.2 Introduction to Layout Management	638
		12.2.1 Border Layout	641
		12.2.2 Grid Layout	644
	12.3 Text Input	648
		12.3.1 Text Fields	649
		12.3.2 Labels and Labeling Components	651
		12.3.3 Password Fields	652
		12.3.4 Text Areas	653
		12.3.5 Scroll Panes	654
	12.4 Choice Components	657
		12.4.1 Checkboxes	657
		12.4.2 Radio Buttons	660
		12.4.3 Borders	664
		12.4.4 Combo Boxes	668
		12.4.5 Sliders	672
	12.5 Menus	678
		12.5.1 Menu Building	679
		12.5.2 Icons in Menu Items	682
		12.5.3 Checkbox and Radio Button Menu Items	683
		12.5.4 Pop-Up Menus	684
		12.5.5 Keyboard Mnemonics and Accelerators	686
		12.5.6 Enabling and Disabling Menu Items	689
		12.5.7 Toolbars	694
		12.5.8 Tooltips	696
	12.6 Sophisticated Layout Management	699
		12.6.1 The Grid Bag Layout	701
			12.6.1.1 The gridx, gridy, gridwidth, and gridheight Parameters	703
			12.6.1.2 Weight Fields	703
			12.6.1.3 The fill and anchor Parameters	704
			12.6.1.4 Padding	704
			12.6.1.5 Alternative Method to Specify the gridx, gridy, gridwidth, and gridheight Parameters	705
			12.6.1.6 A Helper Class to Tame the Grid Bag Constraints	706
		12.6.2 Group Layout	713
		12.6.3 Using No Layout Manager	723
		12.6.4 Custom Layout Managers	724
		12.6.5 Traversal Order	729
	12.7 Dialog Boxes	730
		12.7.1 Option Dialogs	731
		12.7.2 Creating Dialogs	741
		12.7.3 Data Exchange	746
		12.7.4 File Dialogs	752
		12.7.5 Color Choosers	764
	12.8 Troubleshooting GUI Programs	770
		12.8.1 Debugging Tips	770
		12.8.2 Letting the AWT Robot Do the Work	774
## Ch 13: Deploying Java Applications	779
	13.1 JAR Files	780
		13.1.1 Creating JAR files	780
		13.1.2 The Manifest	781
		13.1.3 Executable JAR Files	782
		13.1.4 Resources	783
		13.1.5 Sealing	787
	13.2 Storage of Application Preferences	788
		13.2.1 Property Maps	788
		13.2.2 The Preferences API	794
	13.3 Service Loaders	800
	13.4 Applets	802
		13.4.1 A Simple Applet	803
		13.4.2 The applet HTML Tag and Its Attributes	808
		13.4.3 Use of Parameters to Pass Information to Applets	810
		13.4.4 Accessing Image and Audio Files	816
		13.4.5 The Applet Context	818
		13.4.6 Inter-Applet Communication	818
		13.4.7 Displaying Items in the Browser	819
		13.4.8 The Sandbox	820
		13.4.9 Signed Code	822
	13.5 Java Web Start	824
		13.5.1 Delivering a Java Web Start Application	824
		13.5.2 The JNLP API	829
## Ch 14: Concurrency	839
	14.1 What Are Threads?	840
		14.1.1 Using Threads to Give Other Tasks a Chance	846
	14.2 Interrupting Threads	851
	14.3 Thread States	855
		14.3.1 New Threads	855
		14.3.2 Runnable Threads	855
		14.3.3 Blocked and Waiting Threads	856
		14.3.4 Terminated Threads	857
	14.4 Thread Properties	858
		14.4.1 Thread Priorities	858
		14.4.2 Daemon Threads	859
		14.4.3 Handlers for Uncaught Exceptions	860
	14.5 Synchronization	862
		14.5.1 An Example of a Race Condition	862
		14.5.2 The Race Condition Explained	866
		14.5.3 Lock Objects	868
		14.5.4 Condition Objects	872
		14.5.5 The synchronized Keyword	878
		14.5.6 Synchronized Blocks	882
		14.5.7 The Monitor Concept	884
		14.5.8 Volatile Fields	885
		14.5.9 Final Variables	886
		14.5.10 Atomics	886
		14.5.11 Deadlocks	889
		14.5.12 Thread-Local Variables	892
		14.5.13 Lock Testing and Timeouts	893
		14.5.14 Read/Write Locks	895
		14.5.15 Why the stop and suspend Methods Are Deprecated	896
	14.6 Blocking Queues	898
	14.7 Thread-Safe Collections	905
		14.7.1 Efficient Maps, Sets, and Queues	905
		14.7.2 Atomic Update of Map Entries	907
		14.7.3 Bulk Operations on Concurrent Hash Maps	909
		14.7.4 Concurrent Set Views	912
		14.7.5 Copy on Write Arrays	912
		14.7.6 Parallel Array Algorithms	912
		14.7.7 Older Thread-Safe Collections	914
	14.8 Callables and Futures	915
		14.9.1 Thread Pools	921
		14.9.2 Scheduled Execution	926
		14.9.3 Controlling Groups of Tasks	927
		14.9.4 The Fork-Join Framework	928
		14.9.5 Completable Futures	931
	14.9 Executors	920
	14.10 Synchronizers	934
		14.10.1 Semaphores	935
		14.10.2 Countdown Latches	936
		14.10.3 Barriers	936
		14.10.4 Exchangers	937
		14.10.5 Synchronous Queues	937
	14.11 Threads and Swing	937
		14.11.1 Running Time-Consuming Tasks	939
		14.11.2 Using the Swing Worker	943
		14.11.3 The Single-Thread Rule	951
Appendix A: Java Keywords	953
Index	957
	A	958
	B	961
	C	962
	D	968
	E	970
	F	972
	G	974
	H	977
	I	978
	J	981
	K	986
	L	986
	M	989
	N	991
	O	992
	P	993
	Q	995
	R	995
	S	997
	T	1002
	U	1005
	V	1005
	W	1006
	X	1007
	Y	1007
	Z	1007
