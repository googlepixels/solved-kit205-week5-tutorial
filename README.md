Download Link: https://assignmentchef.com/product/solved-kit205-week5-tutorial
<br>
In this tutorial you will be implementing a hash table using separate chaining.  The separate chaining will make use of the linked list data structure that you implemented in week 2.  However, you will be storing strings in your hash table, so the list will need to be modified to store strings.  A new project is provided to get you started.

<h2>Hash Table Implementation</h2>

<ol>

 <li>Download zip and unzip to your working directory</li>

 <li>Open the project and modify the h and list.c files so that the list stores strings instead of ints. There are some hints in the comments.  The most important point is that you should allocate just enough memory for the string to be added (you will use a similar technique for the assignment).  You will also need to make use of the string functions strlen, strcpy, and strcmp.  You can find documentation for these functions here: <a href="https://en.wikibooks.org/wiki/C_Programming/Strings">https://en.wikibooks.org/wiki/C_Programming/Strings</a></li>

 <li>Open h and familiarise yourself with the hash table interface.</li>

 <li>Now open c. You will see that some functions have been implemented and some have not.  Make sure that you understand the existing functions.</li>

 <li>Now implement create_hashtable. This function should create an array of lists of length size.  Each list needs to be initialised to NULL.</li>

 <li>Next implement hash_insert. This function will simply call insert_at_front after determining which list to insert into using the hash function (make sure you pass a <em>pointer</em> to the list).</li>

 <li>Open the c file and familiarise yourself with the main program loop (this will also be similar to your assignment loop).</li>

 <li>Add some code to case 3 that simply calls the hash_print</li>

 <li>Test your work so far by running the program, inserting some strings, and printing the resulting hash table.</li>

 <li>If you have time, implement and test the remaining functions</li>

</ol>


