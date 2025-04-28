# cop3530-project-1-gator-avl-solved
**TO GET THIS SOLUTION VISIT:** [COP3530 Project 1-Gator AVL Solved](https://www.ankitcodinghub.com/product/cop3530-gator-avl-project-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;118914&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;3&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (3 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;COP3530  Project 1-Gator AVL Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (3 votes)    </div>
    </div>
Binary Search Trees (BST) can often be an efficient and useful way to store and retrieve sorted data. However, the efficiency of these data trees relies heavily on how balanced a BST is. For example, searching through the BST on the left is much more efficient than searching through the BST on the right, despite both figures showing valid BST with the exact same elements.

&nbsp;

To avoid inefficient binary search trees, we use balanced Binary Search Trees.&nbsp; A balanced BST has a balance factor of less than ±<em>threshold</em>, where the balance factor is the difference in heights of the left and right subtrees at any given tree node. One such balanced tree is an AVL tree that maintains a&nbsp;<em>threshold</em>&nbsp;of&nbsp;<strong>1</strong>. As soon as a node in an AVL tree has a balance factor of +2/-2, “tree rotations” are performed to maintain balance in the tree.

In this project, you will be designing a custom AVL tree to organize UF student accounts based on GatorIDs. You will build methods for insertion, deletion, search, and traversals for an AVL tree data structure. These methods would be called based on certain commands that are invoked in the main method. You are responsible for

<ul>
<li>Designing the interface/modules/functions of the standard AVL Tree and the operations required to execute the respective commands.</li>
<li>Parsing the input and ensuring data and command validation,</li>
<li>Building the main function to parse the inputs and calling the respective functions to match the output.</li>
<li>Testing your code within the constraints.</li>
</ul>
&nbsp;

Functionality

Your program must support the following commands:

<table width="772">
<tbody>
<tr>
<td width="152"><strong>Command</strong></td>
<td width="609"><strong>Function</strong></td>
</tr>
<tr>
<td width="152">insert&nbsp;<em>NAME ID</em></td>
<td width="591">·&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Add a Student object into the tree with the specified name,&nbsp;<em>NAME&nbsp;</em>and GatorID number,&nbsp;<em>ID</em>.

·&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Balance the tree automatically if necessary.

·&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; The&nbsp;<em>ID&nbsp;</em>must be unique.

·&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; The&nbsp;<em>ID&nbsp;</em>and&nbsp;<em>NAME&nbsp;</em>must satisfy the constraints stated below.

·&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Also, prints “successful” if insertion is successful and prints “unsuccessful” otherwise.

·&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; <em>NAME&nbsp;</em>identifier will be separated by double inverted commas for parsing, e.g. “Josh Smith”.
</td>
</tr>
<tr>
<td width="152">remove&nbsp;<em>ID</em></td>
<td width="591">·&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Find and remove the account with the specified&nbsp;<em>ID&nbsp;</em>from the tree.

·&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [<strong>Optional</strong>: Balance the tree automatically if necessary.&nbsp;We will test your code only on cases where the tree will be balanced before and after the deletion. So you can implement a BST deletion and still get full credit]

·&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; If deletion is successful, print “successful”.

·&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; If the&nbsp;<em>ID&nbsp;</em>does not exist within the tree, print “unsuccessful”.

·&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; <strong>You must prioritize replacing a removed node with its inorder&nbsp;<em>successor</em>&nbsp;for the case where the deleted node has two children.</strong>
</td>
</tr>
<tr>
<td width="152">search&nbsp;<em>ID</em></td>
<td width="591">·&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Search for the student with the specified&nbsp;<em>ID&nbsp;</em>from the tree.

·&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; If the&nbsp;<em>ID&nbsp;</em>was found, print out their&nbsp;<em>NAME</em>.

·&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; If the&nbsp;<em>ID</em>&nbsp;does not exist within the tree, print “unsuccessful”.
</td>
</tr>
<tr>
<td width="152">search&nbsp;<em>NAME</em></td>
<td width="591">·&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Search for the student with the specified name,&nbsp;<em>NAME&nbsp;</em>in the tree.

·&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; If the student name was found, print the associated&nbsp;<em>ID</em>.

·&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; If the tree has more than one object with the same&nbsp;<em>NAME</em>, print each&nbsp;<em>ID&nbsp;</em>on a new line with no other spaces and in the same relative order as a pre-order traversal.

·&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; If the name does not exist within the tree, print “unsuccessful”.

·&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; <em>NAME&nbsp;</em>identifier will be surrounded by double quotes for parsing, e.g. “Josh Smith”.
</td>
</tr>
<tr>
<td width="152">printInorder</td>
<td width="591">·&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Print out a comma separated inorder traversal of the names in the tree.</td>
</tr>
<tr>
<td width="152">printPreorder</td>
<td width="591">·&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Print out a comma separated preorder traversal of the names in the tree.</td>
</tr>
<tr>
<td width="152">printPostorder</td>
<td width="591">·&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Print out a comma separated postorder traversal of the names in the tree.</td>
</tr>
<tr>
<td width="152">printLevelCount</td>
<td width="591">·&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Prints the number of levels that exist in the tree.

·&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Prints 0 if the head of the tree is null. For example, the tree in&nbsp;<strong><em>Fig. 1</em></strong>&nbsp;has 4 levels.
</td>
</tr>
<tr>
<td width="152">removeInorder&nbsp;<em>N</em></td>
<td width="591">·&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Remove the&nbsp;<em>N</em><sup>th</sup>&nbsp;GatorID from the inorder traversal of the tree (<em>N&nbsp;</em>= 0 for the first item, etc).

·&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; If removal is successful, print “successful”.

·&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [<strong>Optional</strong>: Balance the tree automatically if necessary.&nbsp;We will test your code only on cases where the tree will be balanced before and after the deletion. So you can implement a BST deletion and still get full credit]

·&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; If the&nbsp;<em>N</em><sup>th</sup>&nbsp;GatorID does not exist within the tree, print “unsuccessful”.
</td>
</tr>
</tbody>
</table>
&nbsp;

AVL Tree Data Structure

In order to receive full credit for this project, you must attempt to create an AVL Tree data structure/object class that is used in your main program. Additionally, this AVL tree should:

<ul>
<li>Also meet the requirements for a Binary Search Tree (BST)</li>
<li>Be sorted by numerical GatorID, not lexical Name</li>
<li>Be sorted from least to greatest (nodes of lesser value are in the left subtree, nodes of greater value are in the right subtree)</li>
<li>Make appropriate use of public and private methods</li>
</ul>
&nbsp;

Testing Constraints (We will ensure we test within these limits)

<ul>
<li>1 &lt;=&nbsp;<em> of Commands</em>&lt;=&nbsp;<em>1000</em></li>
<li>6 &lt;=&nbsp;<em>Length of a command &lt;= 1000</em></li>
<li>A command will always run for a single line and will never contain new line characters (‘\n’), except at the end.</li>
</ul>
&nbsp;

Data Validation and Design Requirements&nbsp;(You need to ensure these on your end)

<ul>
<li>Data (You need to validate the following and print “unsuccessful” if data or commands are invalid and move to the next command)
<ul>
<li>UFIDs are strictly 8 digits long and must be unique.</li>
<li>Names must include only alphabets from [a-z, A-Z, and spaces]</li>
<li>Any invalid or misspelled commands must be ignored with an&nbsp;“unsuccessful”&nbsp;message followed by the execution of the next command.</li>
</ul>
</li>
<li>Design/Implementation
<ul>
<li>You must design your own AVL tree from scratch.</li>
<li>You must use the four standard AVL rotations to keep all results standardized for our test cases.</li>
<li>You must use C++14 and ensure that your code runs public test cases on Gradescope.</li>
<li>Additionally a starter template is provided which you can use for locally testing your code which can help you in saving some delay time if you were to repeatedly use a cloud based grader:&nbsp;<a href="https://ufl.instructure.com/courses/500074/files/84164349?wrap=1">zip</a><a href="https://ufl.instructure.com/courses/500074/files/84164349/download?download_frd=1">Download Project1.zip</a>
<ul>
<li><a href="https://github.com/COP3530/P1-Catch-Template">https://github.com/COP3530/P1-Catch-TemplateLinks to an external site.</a>is the updated CMake-based template for Codespaces or faster local development, instructions in repo</li>
</ul>
</li>
</ul>
</li>
</ul>
&nbsp;

Sample Input/Output

<strong>Input</strong>

8

insert “Brandon” 45679999

insert “Brian” 35459999

insert “Briana” 87879999

insert “Bella” 95469999

printInorder

remove 45679999

removeInorder 2

printInorder

*&nbsp;<strong>Note</strong>: Line 1 denotes the number of lines or the total number of commands that follow.

&nbsp;

<strong>Output</strong>

successful

successful

successful

successful

Brian, Brandon, Briana, Bella

successful

successful

Brian, Briana

&nbsp;

Testing

Test your code on Starter template and/or Gradescope. You have five available test cases and you can submit any number of times.

In addition to the 5 public test cases, after the due date your submission will be tested with 10 additional test cases.

Additionally, in this project, you will need to&nbsp;<strong>create your own test cases</strong>&nbsp;and optionally, run them against your code&nbsp;in the&nbsp;<a href="https://ufl.instructure.com/courses/500074/files/84164349?wrap=1"><strong>Starter Template</strong></a><a href="https://ufl.instructure.com/courses/500074/files/84164349/download?download_frd=1"><strong>&nbsp;Download Starter Template</strong></a><strong>(or use the new and improved&nbsp;</strong><a href="https://github.com/COP3530/P1-Catch-Template"><strong>Catch templateLinks to an external site.</strong></a><strong>)</strong>.

&nbsp;

<strong>Video Tutorial</strong>&nbsp;for setting up Catch2 (<strong>Recommended</strong>):

<a href="https://github.com/COP3530/Quiz-3-Catch-Template">Links to an external site.</a>

Project 1 Helper Files

<ul>
<li>Breakdown by Andrew Penton
<ul>
<li>Slides can be found&nbsp;<a href="https://docs.google.com/presentation/d/1llw2u6PmbgUjE1nQM_Qyc4lVMeb84_UVINRpQvrycqE/edit#slide=id.p">hereLinks to an external site.</a></li>
<li>Video can be found&nbsp;<a href="https://youtu.be/BjH_Pdu_2W4">hereLinks to an external site.</a></li>
</ul>
</li>
<li>Regex sample code:&nbsp;<a href="https://onlinegdb.com/x9xvFQIcG">https://onlinegdb.com/x9xvFQIcGLinks to an external site.</a></li>
<li>Catch test example:&nbsp;<a href="https://onlinegdb.com/Ih4XEhD80w">https://onlinegdb.com/Ih4XEhD80wLinks to an external site.</a></li>
<li>Faster catch testing template with CMake:&nbsp;<a href="https://github.com/COP3530/P1-Catch-Template">https://github.com/COP3530/P1-Catch-TemplateLinks to an external site.</a>
<ul>
<li>Works for any editor, including cloud-based Github Codespaces, CLion, VSCode, and potentially Visual Studio (may require extra configuration)</li>
</ul>
</li>
<li>Wrapped BST example:&nbsp;<a href="https://onlinegdb.com/vWp_hhaQlC">https://onlinegdb.com/vWp_hhaQlCLinks to an external site.</a></li>
<li><a href="https://ufl.instructure.com/courses/500074/files/84164349?wrap=1">Starter Template</a><a href="https://ufl.instructure.com/courses/500074/files/84164349/download?download_frd=1">Download Starter Template</a>. (Works, but testing is a bit slower. See&nbsp;<a href="https://github.com/COP3530/P1-Catch-Template">https://github.com/COP3530/P1-Catch-TemplateLinks to an external site.</a>&nbsp;for a faster template.)</li>
</ul>
&nbsp;

FAQs

The course staff will maintain an active FAQ Google document to answer your questions.&nbsp;<a href="https://docs.google.com/document/d/1X1giXYQStDsqXYawDLNuEJaucUcHsmr9kgSIVnwC_Z4/edit">Post your questions in Slack, but we will answer in this document and send you the link.Links to an external site.</a>

&nbsp;

Grading

<ul>
<li><strong>Implementation [75 points]</strong>
<ul>
<li>Your code will be tested on 15 test cases each worth 5 points:
<ul>
<li>5 publicly available test cases that are a part of Starter template and/or Gradescope</li>
<li>10 test cases that will be added by the course staff during grading</li>
</ul>
</li>
<li><strong>Documentation [12 Points]</strong>
<ul>
<li>Submit a document addressing these prompts:
<ul>
<li>What is the time complexity of each method (<strong>corresponding to a command</strong>) in your implementation? Reflect on the worst case time complexity represented in Big O notation.
<ul>
<li><strong>Note&nbsp;</strong>that the methods here refer to the methods you call for the respective commands. You don’t need to analyze the time complexities of helper methods, constructors, etc. although you have to account for helper methods’ time complexities when you analyze a command that calls those helper functions. [10 points]</li>
</ul>
</li>
<li>What did you learn from this assignment and what would you do differently if you had to start over? [2 points]</li>
</ul>
</li>
<li><strong>Code Style and Design [8 Points]</strong>
<ul>
<li>4 points for design decisions and code modularity
<ul>
<li>We inspect the following in your code:
<ul>
<li>Appropriate modularity</li>
<li>Proper memory management</li>
<li>Efficient mechanisms for passing parameters in your function signatures</li>
<li>The client (your int main() method) should not have objects that interact with memory directly – or a well defined API for your AVL Tree</li>
</ul>
</li>
<li>1 point for appropriate comments</li>
<li>1 point for consistent whitespace mechanism</li>
<li>2 points for consistent naming conventions</li>
</ul>
</li>
<li><strong>Unit tests [5 points]</strong>
<ul>
<li>Submit a file containing the following 5 tests using the Catch Framework:
<ul>
<li>
<ul>
<li>Test at least 5 incorrect commands. Ex:&nbsp;insert “A11y” 45679999 [0.5 points]</li>
<li>Test at least 3 edge cases for various functions. Ex: removing a node that doesn’t exist [0.5 points]</li>
<li>Test all four rotation cases [1 point]</li>
<li>Test all three deletion cases (no children, 1 child, two children) [1 points]</li>
<li>Insert at least 100 nodes, remove 10 random nodes using any delete operation and check in order. Hint: Use a loop to verify the 100 insertions and the 90 nodes after removal. Setup example seen&nbsp;<a href="https://onlinegdb.com/Ih4XEhD80w">hereLinks to an external site.</a>[2 points]</li>
</ul>
</li>
</ul>
</li>
</ul>
</li>
</ul>
</li>
</ul>
</li>
</ul>
</li>
</ul>
&nbsp;

Submission

<ul>
<li>You are required to upload on Gradescope the following:
<ul>
<li>at least&nbsp;<strong><em>one</em></strong>.cpp file that has your implementation of the entire project including the main. If you use header files or more than one .cpp file, upload all of them together on Gradescope. Feel free to choose the names for your header and .cpp files.&nbsp;<strong>Make sure at least one .cpp file contains the main() method.</strong></li>
<li>one pdf file that has your documentation and your name on the front page of the pdf. Name this pdf as&nbsp;<strong><em>pdf</em></strong>.</li>
<li>one&nbsp;<strong>cpp</strong>file that has your 5 test cases using the&nbsp;<strong>Catch2</strong>&nbsp;<strong>framework</strong>&nbsp;and a screenshot image of the passing tests titled&nbsp;<strong>Test</strong>.&nbsp;<strong>Make sure to comment out your entire test.cpp file</strong></li>
</ul>
</li>
<li><strong>Failure to follow these instructions will lead to a 10% non-negotiable penalty.</strong></li>
</ul>
&nbsp;

<strong>Project Authors:</strong> Andres Holguin, Joshua Zimmerman, Andrew Penton, Tianwei Xie, Leon Kwan, Yair Temkin, Santiago Barrios, and Amanpreet Kapoor

Version: 2.1

Last Modified: 09/04/2023

<strong>Last Edited by:</strong> Yair Temkin &amp; Santiago Barrios

<strong>Change Log: </strong>Updating unit test requirements

The following content is partner provided

The preceding content is partner provided

Rubric

<strong>AVL Tree</strong>

<table width="840">
<thead>
<tr>
<td colspan="3">AVL Tree</td>
</tr>
<tr>
<td><strong>Criteria</strong></td>
<td><strong>Ratings</strong></td>
<td><strong>Pts</strong></td>
</tr>
</thead>
<tbody>
<tr>
<td>This criterion is linked to a Learning OutcomeImplementation</td>
<td>
<table width="535">
<tbody>
<tr>
<td><strong>75&nbsp;to &gt;0.0&nbsp;pts</strong>

<strong>Test Cases</strong>

5 point per correct test case
</td>
<td><strong>0&nbsp;pts</strong>

<strong>No test cases passed</strong>
</td>
</tr>
</tbody>
</table>
</td>
<td>75&nbsp;pts</td>
</tr>
<tr>
<td>This criterion is linked to a Learning OutcomeReflection

What would you do differently?
</td>
<td>
<table width="535">
<tbody>
<tr>
<td><strong>2&nbsp;pts</strong>

<strong>Full Marks</strong>

Reflection on what you would do differently
</td>
<td><strong>0&nbsp;pts</strong>

<strong>No Marks</strong>
</td>
</tr>
</tbody>
</table>
</td>
<td>2&nbsp;pts</td>
</tr>
<tr>
<td>This criterion is linked to a Learning OutcomeComplexity Analysis

insert NAME ID

remove ID

search ID

search NAME

printInorder

printPreorder

printPostorder

printLevelCount

removeInorder N
</td>
<td>
<table width="535">
<tbody>
<tr>
<td><strong>10&nbsp;to &gt;0.0&nbsp;pts</strong>

<strong>Describing worst case Big O time complexity of each method</strong>

1. State the variable under consideration (33.3%) 2. Define the variable (33.3%) 3. Justify complexities (33.3%) Note: The complexities must match what you did in the program
</td>
<td><strong>0&nbsp;pts</strong>

<strong>No Marks</strong>
</td>
</tr>
</tbody>
</table>
</td>
<td>10&nbsp;pts</td>
</tr>
<tr>
<td>This criterion is linked to a Learning OutcomeComments</td>
<td>
<table width="535">
<tbody>
<tr>
<td><strong>1&nbsp;to &gt;0.0&nbsp;pts</strong>

<strong>Full Marks</strong>

Code has appropriate comments
</td>
<td><strong>0&nbsp;pts</strong>

<strong>No Marks</strong>
</td>
</tr>
</tbody>
</table>
</td>
<td>1&nbsp;pts</td>
</tr>
<tr>
<td>This criterion is linked to a Learning OutcomeWhitespace</td>
<td>
<table width="535">
<tbody>
<tr>
<td><strong>1&nbsp;to &gt;0.0&nbsp;pts</strong>

<strong>Full Marks</strong>

Code has appropriate whitespace
</td>
<td><strong>0&nbsp;pts</strong>

<strong>No Marks</strong>
</td>
</tr>
</tbody>
</table>
</td>
<td>1&nbsp;pts</td>
</tr>
<tr>
<td>This criterion is linked to a Learning OutcomeNaming convention</td>
<td>
<table width="535">
<tbody>
<tr>
<td><strong>2&nbsp;to &gt;0.0&nbsp;pts</strong>

<strong>Full Marks</strong>

Code follows a naming convention that is coherent and consistent
</td>
<td><strong>0&nbsp;pts</strong>

<strong>No Marks</strong>
</td>
</tr>
</tbody>
</table>
</td>
<td>2&nbsp;pts</td>
</tr>
<tr>
<td>This criterion is linked to a Learning OutcomeDesign Decisions

1. Appropriate modularity

2. Proper memory management

3. Efficient mechanisms for passing parameters in your function signatures

4. The client (your int main() method, should not have objects that interact with memory directly)
</td>
<td>
<table width="535">
<tbody>
<tr>
<td><strong>4&nbsp;to &gt;0.0&nbsp;pts</strong>

<strong>Full Marks</strong>

All four aspects meet expectation Appropriate modularity Proper memory management Efficient mechanisms for passing parameters in your function signatures The client (your int main() method, should not have objects that interact with memory directly)
</td>
<td><strong>0&nbsp;pts</strong>

<strong>No Marks</strong>
</td>
</tr>
</tbody>
</table>
</td>
<td>4&nbsp;pts</td>
</tr>
<tr>
<td>This criterion is linked to a Learning OutcomeUnit Test Implementation

Create five passing unit tests using the Catch2 test framework.
</td>
<td>
<table width="535">
<tbody>
<tr>
<td><strong>5&nbsp;to &gt;0.0&nbsp;pts</strong>

<strong>Full Marks</strong>

Tests 1 and 2 are worth 0.5 points, tests 3 and 4 are worth 1 point, and test 5 is worth 2 points.
</td>
<td><strong>0&nbsp;pts</strong>

<strong>No Marks</strong>
</td>
</tr>
</tbody>
</table>
</td>
<td>5&nbsp;pts</td>
</tr>
<tr>
<td colspan="3">Total Points:&nbsp;100</td>
</tr>
</tbody>
</table>
&nbsp;
