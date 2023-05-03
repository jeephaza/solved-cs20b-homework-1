Download Link: https://assignmentchef.com/product/solved-cs20b-homework-1
<br>
<ol>

 <li>What is the difference between an object and a class? Give two examples.</li>

 <li>Explain the difference between

  <ul>

   <li>int a = 3;</li>

  </ul></li>

</ol>

and

<ul>

 <li>Integer a = new Integer(3);</li>

</ul>

<ol start="3">

 <li>For the following concepts/classes define/write at least one method:

  <ul>

   <li>Animal</li>

  </ul></li>

</ol>

<ul>

 <li>Dog</li>

 <li>User</li>

 <li>File</li>

 <li>Database</li>

</ul>

<ol start="4">

 <li><strong>Q. </strong>For the following concepts/classes write at least one instance variable/attribute and an associated constructor you can define taking <strong>more than one input argument/parameter</strong>:</li>

</ol>

(a) MobilePhone

(b) User <strong>A.</strong>

(c) File

(d)Database

(e) Webpage

<ol start="5">

 <li>What is the output of the following program:</li>

</ol>

class T { private int t = 20;

T(){

t = 40;

}

} class Main {

public static void main (String args []) {

T t1 = new T();

System.out.println(t1.t);

}

}

6. Is there any compiler error in the below Java program? Please explain your answer.

I don’t accept only yes or no.

class Point {

int m_x, m_y; public Point (int x, int y) {m_x = x; m_y = y;} public static void main (String args []) { Point p = new Point();

}

}

7. Some aspects of each of the following can be modeled with a graph (network) structure. Describe, in each case what the nodes would represent and what the edges would represent. In general, nodes represent concepts/entities, and edges explain what the relationship is between the entities. For example, for navigation, nodes would represent locations (cities, towns, …) and edges between cities represent if a road exists between them (a weight can be added to denote the distance).

<ul>

 <li style="list-style-type: none;">

  <ul>

   <li>Airline</li>

  </ul></li>

 <li>Social networks such as Facebook</li>

 <li>The Internet</li>

 <li>Movie industry</li>

</ul>

<ul>

 <li>Avengers (the movie/comic)</li>

 <li>Amazon.com recommendation system (where a system recommends to you what to buy)</li>

</ul>

<ol start="8">

 <li>Describe and specify the order of growth of each of the following code sections, using big-O notation (explain your answer!):</li>

</ol>

(a) int count = 0; for (int i = 1; i &lt; = N; i++) count ++;

(b) int count = 0; for (int i = 1; i &lt;= N; i++)

for ( int j = 1; j &lt;= N; j++) count ++;

(c) int count = 0; for (int i = 1; i &lt;= N; i++) count ++;

for (int j = 1; j &lt;= N; j++) count ++;

(d) int count = 0; for (int i = 1; i &lt;= N/2; i++)

for ( int i = 1; i &lt;= N/2; i++) count ++;

(e) public static String reverse ( String s) { int n = s.length(); char [] a = new char[n]; for (int i = 0; i &lt; n; i++) a[i] = s.charAt(n-i-1); String reverse = new String (a); return reverse;

}




9. Describe the order of growth of each of the following functions using O notation:

(a) <em>N</em><sup>2 </sup>+ 3 <em>∗ N</em>.

(b) 3 <em>∗ N </em>+ <em>N</em>

(c) <em>N ∗ </em>(<em>N − </em>1) + 2