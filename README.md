# programming-paradigms-lab-11-lists-and-arithmetic-in-prolog-solved
**TO GET THIS SOLUTION VISIT:** [Programming Paradigms Lab 11-Lists and arithmetic in Prolog Solved](https://www.ankitcodinghub.com/product/programming-paradigms-lab-11-lists-and-arithmetic-in-prolog-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;100219&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;Programming Paradigms Lab 11-Lists and arithmetic in Prolog Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Programming Paradigms

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Lab 11. Lists and arithmetic in Prolog

</div>
</div>
</td>
</tr>
</tbody>
</table>
</div>
<div class="page" title="Page 2">
<div class="section">
<div class="layoutArea">
<div class="column">
Understanding member Exercise 11.1(a)

Draw the search tree for the query member(3, [X, 3, Y]).

<pre>      (X, [X|_]).
      (X, [_|T]) :- member(X, T).
</pre>
</div>
</div>
<div class="layoutArea">
<div class="column">
<pre>member
member
</pre>
</div>
</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="section">
<div class="layoutArea">
<div class="column">
Understanding member

Exercise 11.1(b)

Verify your solution to Exercise 11.1(a):

Run the following query in SWISH and hit “Step into” button repeatedly.

?- trace, member(X, [X|_]).

</div>
</div>
</div>
</div>
<div class="page" title="Page 4">
<div class="section">
<div class="layoutArea">
<div class="column">
List prefix

Exercise 11.2

Implement a predicate prefix/2 that checks if a given list is a prefix of another list. ?- prefix([1, 2], [1, 2, 3, 4])

true

<pre>?- prefix(X, [1, 2, 3])
X = []
X = [1]
X = [1, 2]
</pre>
X = [1, 2, 3]

</div>
</div>
</div>
</div>
<div class="page" title="Page 5">
<div class="section">
<div class="layoutArea">
<div class="column">
Interleaving lists

Exercise 11.3

Implement a predicate interleave/3 that checks if first two lists give the third when interleaved.

?- interleave([1, 2], [a, b], X) X = [1, a, 2, b]

?- interleave([1, 2], [a, b, c], X) X = [1, a, 2, b, c]

?- interleave(X, Y, [1, 2, 3, 4]) X = [1, 3], Y = [2, 4]

</div>
</div>
</div>
</div>
<div class="page" title="Page 6">
<div class="section">
<div class="layoutArea">
<div class="column">
Squares

Exercise 11.4

Implement a predicate squares/2 that checks

if the second list is a list of squares of numbers from the first list (in the same order).

?- squares([1, 2, 3, 4], X) X = [1, 4, 9, 16]

</div>
</div>
</div>
</div>
<div class="page" title="Page 7">
<div class="section">
<div class="layoutArea">
<div class="column">
Selecting elements from lists

Exercise 11.5

Implement a predicate select/3 that splits a list into its element a list of remaining elements.

?- select([6, 3, 8, 5], X, R) H = 6, R = [3, 8, 5]

H = 3, R = [6, 8, 5]

H = 8, R = [6, 3, 5]

<pre>H = 5, R = [6, 3, 8]
</pre>
</div>
</div>
</div>
</div>
<div class="page" title="Page 8">
<div class="section">
<div class="layoutArea">
<div class="column">
Permutations

Exercise 11.6

Implement a predicate anagram/2 that checks whether a list is a permutation of another list.

?- anagram([d,o,r,m,i,t,o,r,y], [d,i,r,t,y, r,o,o,m]) true

?- anagram([1, 2], X) X = [1, 2]

X = [2, 1]

</div>
</div>
</div>
</div>
<div class="page" title="Page 9">
<div class="section">
<div class="layoutArea">
<div class="column">
A logic puzzle

Exercise 11.7

There is a street with three neighbouring houses that all have a different colour, namely red, blue, and green. People of different nationalities live in the different houses and they all have a different pet. Here are some more facts about them:

<ul>
<li>● &nbsp;The Englishman lives in the red house.</li>
<li>● &nbsp;The jaguar is the pet of the Spanish family.</li>
<li>● &nbsp;The Japanese lives to the right of the snail keeper.</li>
<li>● &nbsp;The snail keeper lives to the left of the blue house.
Who keeps the zebra? Don’t work it out for yourself:

define a predicate zebra/1 that tells you the nationality of the owner of the zebra!

Hint: Think of a representation for the houses and the street.

Code the four constraints in Prolog. You may find member/2 and sublist/2 useful.
</li>
</ul>
</div>
</div>
</div>
</div>
<div class="page" title="Page 10">
<div class="section">
<div class="layoutArea">
<div class="column">
Sorted lists

Exercise 11.8

Implement a predicate sorted/1 that checks if a list is sorted. ?- sorted([6, 3, 8, 5])

false

?- sorted([3, 5, 6, 8]) true

</div>
</div>
</div>
</div>
<div class="page" title="Page 11">
<div class="section">
<div class="layoutArea">
<div class="column">
Sorted lists

Exercise 11.9

Implement a predicate sort/2 that checks

if the second list is a sorted version of the first one.

?- sort([6, 3, 8, 5], X) X = [3, 5, 6, 8]

</div>
</div>
</div>
</div>
<div class="page" title="Page 12">
<div class="section">
<div class="layoutArea">
<div class="column">
Shuffling both ways

Exercise 11.10 (***)

Examine current implementation of shuffled/2. Explain why it’s not working in one direction. Update the implementation of shuffled/2 to work in both directions:

?- shuffled([1, 2], X) X = [1, 2]

X = [2, 1]

?- shuffled(X, [1, 2]) X = [1, 2]

X = [2, 1]

</div>
</div>
</div>
</div>
