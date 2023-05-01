Download Link: https://assignmentchef.com/product/solved-ch231a-assignment1-template-array-search
<br>
First write a generic … array_search(…) function using templates. The array search function should receive an array of elements, the corresponding number of elements, the element searched for and should determine if that element is in the array or not by returning its index or -1 if not in the array. Then write a test program with a main function which uses the function above for multiple types (some example basic data types and Complex objects).

<em>You can assume that the array will contain at least one element. Make sure that your code works not only with basic data types but also with a simple Complex class.</em>

<em>you can assume that the array will contain at least one element. Make sure that your code works not only with basic data types but also with a simple Complex class.</em>

<h1><strong>Problem 1.2 </strong>Stack with templates</h1>

<h2>Language: C++</h2>

Design and implement a generic stack class. By using templates your stack has to be able to store any type of data. The underlying data structure should be an array.

While designing and implementing your class you cannot use any of the container classes from the Standard Template Library (STL).

Your class should support the following operations (read all the requirements before starting to write code):

<ul>

 <li>Stack(): this constructor initializes the stack to a size of 10.</li>

 <li>Stack(const Stack&amp;): copy constructor, create a real copy of the stack.</li>

 <li>Stack(int size): this constructor sets the stack’s size to the given size.</li>

 <li>bool push(T element): adds element to the top of the stack. It should return true, if the element has been successfully pushed. So as long as you do not provide an extend() method, you need to check for available space and return false if there is no more space.</li>

 <li>bool pop(T&amp; out): pops an element from the top of the stack. The element is put into out. It should not crash if there are no elements on the stack, but rather return false, otherwise it should return true.</li>

 <li>T back(void): returns the data on the top of the stack, without changing the stack.</li>

 <li>int getNumEntries(): returns the number of entries of the stack at a given moment.</li>

 <li>Destructor for the template class.</li>

</ul>

Finally, write a simple program which tests the functionality of your stack.

Name the files Stack.h and testStack.cpp. <em>You can assume that the input will be valid.</em>

<h1><strong>Problem 1.3 </strong>List with templates as doubly linked list</h1>

<h2>Language: C++</h2>

Implement a generic list using templates using a doubly linked list instead of an array. Provide constructors, destructor and methods for returning (with and without remove) the first and last element as well as adding a new element at the front and at the end of the list. Also implement a method which returns the amount of elements in the list.

Name the files LinkedList.h and testLinkedList.cpp. <em>You can assume that the input will be valid.</em>

<h1><strong>Problem 1.4 </strong>Using vectors I</h1>

<h2>Language: C++</h2>

Write a program which does the following using a vector object:

<ol>

 <li>Read words from the keyboard (one per line) until the entered word is equal to the word“END”. You can assume that the words do not contain whitespace.</li>

 <li>Insert these words into the vector at the end (excluding the word “END”).</li>

 <li>Print the words on the standard output separated by spaces using the index operator.</li>

 <li>Print the words on the standard output separated by comma using a corresponding iterator.Make sure that you do not print a comma after the last word.</li>

</ol>

<em>You can assume that the input will be valid.</em>

<h1><strong>Problem 1.5 </strong>Using vectors II</h1>

<h2>Language: C++</h2>

Write a program which does the following using a vector object:

<ol>

 <li>Read strings from the keyboard (one per line) until the string is equal to the string “END”. Make sure that you can read strings which contain spaces and/or tabs as well.</li>

 <li>Insert these strings into the vector at the end (excluding the string “END”).</li>

 <li>If the second and fifth elements (i.e., strings) exist, swap the second and fifth element. Ifone of them or both do not exist then print a message on the standard output.</li>

 <li>Replace the last element with the string “???”.</li>

 <li>Print the strings on the standard output separated by comma using the index operator.Make sure that you do not print a comma after the last string.</li>

 <li>Print the strings on the standard output separated by semicolons using a correspondingiterator. Make sure that you do not print a semicolon after the last string.</li>

 <li>Print the strings on the standard output in the reversed order separated by space using aniterator.</li>

</ol>