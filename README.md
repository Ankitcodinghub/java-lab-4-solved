# java-lab-4-solved
**TO GET THIS SOLUTION VISIT:** [Java Lab 4 Solved](https://www.ankitcodinghub.com/product/java-lab-4-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;95417&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;Java Lab 4 Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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

<div class="kksr-stars-active" style="width: 0px;">
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
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">
Starting from this week…:

<ul>
<li>Use appropriate collections in order to represent data (otherwise: -0.5 points)</li>
<li>Use Java Stream API in order to perform aggregate operations on data.
The Student / High School Admission Problem (SAP)

An instance of SAP involves a set of students and a set of high schools, each student seeking admission to one school, and each school h aving a number of available places (its capacity). Each student ranks some (acceptable) schools in strict order, and each school ranks its applicants in some order. A matching is a set of pairs (student, school) such that each student is assigned to at most one school and the capacities of the schools are not exceeded. A matching is stable if there is no pair (s, h) such that s is assigned to h’ but s prefers h better than h’ and h prefers s better than some of its assigned students. We consider the problem of creating a stable matching between students and schools.

Example: 4 students S0,S1,S2,S3, 3 high schools H0,H1,H2, capacity(H0)=1, capacity(H1)=2, capacity(H2)=2.
</li>
</ul>
</div>
</div>
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
students preferences

S0: (H0, H1, H2) S1: (H0, H1, H2) S2: (H0, H1)

S3: (H0, H2)

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
schools preferences

H0: (S3, S0, S1, S2) H1: (S0, S2, S1) H2: (S0, S1, S3)

</div>
</div>
</td>
</tr>
</tbody>
</table>
<div class="layoutArea">
<div class="column">
A solution for this example might be: [(S0:H1),(S1:H2),(S2:H1),(S3:H0)] The main specifications of the application are:

Compulsory (1p)

</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
<ul>
<li>Create an object-oriented model of the problem. You should have at least the following classes: Student, School and the main class.</li>
<li>Create all the objects in the example using streams.</li>
<li>Create a list of students, using LinkedList implementation. Sort the students,
using a comparator.
</li>
<li>Create a set of schools, using a TreeSet implementation. Make sure
that School objects are comparable.
</li>
<li>Create two maps (having different implementations) describing the students
and the school preferences and print them on the screen. Optional (2p)
</li>
</ul>
<ul>
<li>Create a class that describes the problem and one that describes a solution (a matching) to this problem.</li>
<li>Using Java Stream API, write queries that display the students who find acceptable a given list of schools, and the schools that have a given student as their top preference.</li>
<li>Use a third-party library in order to generate random fake names for students and schools.</li>
<li>Implement an algorithm for creating a matching, considering that each student has a score obtained at the evaluation exam and the schools rank students based on this score.</li>
<li>Test your algorithm. Bonus (2p)</li>
</ul>
<ul>
<li>Consider the case in which a school can rank the students based on their specific criteria.</li>
<li>Implement the Gale Shapley algorithm in order to find a stable matching.</li>
<li>Consider the case in which preferences are not necessarily strict. Some
consecutive preferences in an element’s list may form a tie.

For example S1: H1, [H2,H3] means that S1 prefers H1 over H2 and H3, but H2 and H3 have no precedence one over the other.
</li>
<li>Prove that in the case of SAP with ties, a problem may have multiple stable matchings, not all of the same size.</li>
<li>Check out other examples of matching in practice. Resources</li>
</ul>
</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="layoutArea">
<div class="column">
<ul>
<li>Slides</li>
<li>Aggregate Operations</li>
<li>The Java Tutorials: Collections ( Know Thy Complexities! )</li>
<li>Setting the class path</li>
<li>Creating, Importing, and Configuring Java Projects in Netbeans</li>
<li>Packaging Programs in JAR Files
Objectives
</li>
</ul>
<ul>
<li>Use various collections and polymorphic algorithms.</li>
<li>Use Java Stream API.</li>
<li>Use Optional class and var keyword.</li>
<li>Understand the notion of CLASSPATH.</li>
<li>Use external JAR libraries.</li>
<li>Create a Maven Project.</li>
<li>Package all project classes as an executable JAR file.</li>
</ul>
</div>
</div>
</div>
