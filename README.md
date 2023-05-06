Download Link: https://assignmentchef.com/product/solved-ecs140a-assignment-5
<br>
For each of the following problems, provide a pattern-matching solution in Erlang. Do not resort to just giving a new name to an existing Erlang function that already does what we want your function to do.




<ul>

 <li>myremoveduplicates</li>

</ul>




myremoveduplicates(“abacad”) =&gt; “bcad” myremoveduplicates([3,2,1,3,2,2,1,1]) =&gt; [3,2,1]




<ul>

 <li>myintersection</li>

</ul>




myintersection(“abc”, “bcd”) =&gt; “bc” myintersection([3,4,2,1], [5,4,1,6,2]) =&gt; [4,2,1] myintersection([], [1,2,3]) =&gt; [] myintersection(“abc”, “”) =&gt; “”




<ul>

 <li>mylast mylast(“”) =&gt; “” mylast(“b”) =&gt; “b” mylast(“abcd”) =&gt; “d” mylast([1,2,3,4]) =&gt; [4] mylast([]) =&gt; []</li>

</ul>




<ul>

 <li>myreverse</li>

</ul>

myreverse(“”) =&gt; “” myreverse(“abc”) =&gt; “cba” myreverse([1,2,3]) =&gt; [3,2,1] myreverse([]) =&gt; []




<ul>

 <li>myreplaceall</li>

</ul>

myreplaceall(3,7,[7,0,7,1,7,2,7]) =&gt; [3,0,3,1,3,2,3] myreplaceall(3,9,[7,0,7,1,7,2,7]) =&gt; [7,0,7,1,7,2,7]


