Download Link: https://assignmentchef.com/product/solved-cecs328-hw2
<br>
<ol>

 <li>Prove that <em>f</em>(<em>n</em>) = 10 · <em>n</em><sup>4 </sup>+ 2 · <em>n</em><sup>2 </sup>+ 3 is <em>O</em>(<em>n</em><sup>4</sup>), provide the appropriate <em>C </em>and <em>k </em></li>

</ol>

<em>f</em>(<em>n</em>) = <em>O</em>(<em>g</em>(<em>n</em>))         ⇐⇒             ∃<em>c &gt; </em>0<em>,</em>∃<em>k </em>≥ 0<em>s.tf</em>(<em>n</em>) ≤ <em>c </em>· <em>g</em>(<em>n</em>)∀<em>n </em>≥ <em>k</em>

10 · <em>n</em><sup>4 </sup>+ 2 · <em>n</em><sup>2 </sup>+ 3       ≤       10 · <em>n</em><sup>4 </sup>+ 2 · <em>n</em><sup>4 </sup>+ 3

≤        10 · <em>n</em><sup>4 </sup>+ 2 · <em>n</em><sup>4 </sup>+ 3 · <em>n</em><sup>4</sup>

=       15 · <em>n</em><sup>4</sup><em>,n </em>≥ 1

Let <em>c </em>= 15 and <em>k </em>= 1 then the statement translates to

<em>f</em>(<em>n</em>)       ≤       <em>c </em>· <em>g</em>(<em>n</em>)<em>,n </em>≥ <em>k</em>

By the definition of <em>O </em>notation <em>f</em>(<em>n</em>) = <em>O</em>(<em>g</em>(<em>n</em>))

<ol start="2">

 <li>Prove that <em>f</em>(<em>n</em>) = 2·<em>n</em><sup>2</sup>−<em>n</em><em>log</em><sub>2</sub>(<em>n</em>)+3·<em>log</em><sub>2</sub>(<em>n</em>) is <em>O</em>(<em>n</em><sup>2</sup>), provide the appropriate <em>C </em>and <em>k </em>constants.</li>

</ol>

<em>f</em>(<em>n</em>) = <em>O</em>(<em>g</em>(<em>n</em>))         ⇐⇒             ∃<em>c &gt; </em>0<em>,</em>∃<em>k </em>≥ 0<em>s.tf</em>(<em>n</em>) ≤ <em>c </em>· <em>g</em>(<em>n</em>)∀<em>n </em>≥ <em>k</em>

2 · <em>n</em><sup>2 </sup>− <em>n </em>· <em>log</em><sub>2</sub>(<em>n</em>) + 3 · <em>log</em><sub>2</sub>(<em>n</em>)        ≤        2 · <em>n</em><sup>2 </sup>+ <em>n</em><sup>2 </sup>+ 3 · <em>log</em><sub>2</sub>(<em>n</em>)

≤        2 · <em>n</em><sup>2 </sup>+ <em>n</em><sup>2 </sup>+ 3 · <em>n</em><sup>2</sup>

=       6 · <em>n</em><sup>2</sup><em>,n </em>≥ 1

Let <em>c </em>= 6 and <em>k </em>= 1, then the statement translates to

<em>f</em>(<em>n</em>)       ≤       <em>c </em>· <em>g</em>(<em>n</em>)<em>,n </em>≥ <em>k</em>

which by the definition of <em>O </em>notation <em>f</em>(<em>n</em>) = <em>O</em>(<em>g</em>(<em>n</em>)).

<ol start="3">

 <li>Prove that <em>f</em>(<em>n</em>) = 2·<em>n</em><sup>4</sup><em>log</em><sub>2</sub>(<em>n</em><sup>4</sup>)−<em>n</em><sup>2</sup>+3·<em>log</em><sub>2</sub>(<em>n</em>) is <em>O</em>(<em>n</em><sup>4</sup><em>log</em><sub>2</sub>(<em>n</em>)), provide the appropriate <em>C </em>and <em>k </em>constants.</li>

</ol>

<em>f</em>(<em>n</em>) = <em>O</em>(<em>g</em>(<em>n</em>))         ⇐⇒             ∃<em>c &gt; </em>0<em>,</em>∃<em>k </em>≥ 0<em>s.tf</em>(<em>n</em>) ≤ <em>c </em>· <em>g</em>(<em>n</em>)∀<em>n </em>≥ <em>k</em>

2 · <em>n</em><sup>4 </sup>· <em>log</em><sub>2</sub>(<em>n</em><sup>4</sup>) − <em>n</em><sup>2 </sup>+ 3 · <em>log</em><sub>2</sub>(<em>n</em>)           =        8 · <em>n</em><sup>4 </sup>· <em>log</em><sub>2</sub>(<em>n</em>) − <em>n</em><sup>2 </sup>+ 3 · <em>log</em><sub>2</sub>(<em>n</em>)

≤         8 · <em>n</em><sup>4 </sup>· <em>log</em><sub>2</sub>(<em>n</em>) + <em>n</em><sup>4 </sup>· <em>log</em><sub>2</sub>(<em>n</em>) + 3 · <em>log</em><sub>2</sub>(<em>n</em>)

≤         8 · <em>n</em><sup>4 </sup>· <em>log</em><sub>2</sub>(<em>n</em>) + <em>n</em><sup>4 </sup>· <em>log</em><sub>2</sub>(<em>n</em>) + 3 · <em>n </em>· <em>log</em><sub>2</sub>(<em>n</em>)

=        12 · <em>n</em><sup>4 </sup>· <em>log</em><sub>2</sub>(<em>n</em>)<em>,n </em>≥ 1

Let <em>c </em>= 12 and <em>k </em>= 1 then the statement translates to

2 · <em>n</em><sup>4 </sup>· <em>log</em><sub>2</sub>(<em>n</em><sup>4</sup>) − <em>n</em><sup>2 </sup>+ 3 · <em>log</em><sub>2</sub>(<em>n</em>)         ≤        <em>c </em>· <em>n</em><sup>4 </sup>· <em>log</em><sub>2</sub>(<em>n</em>)<em>,n </em>≥ 1

which by the definition <em>O </em>notation <em>f</em>(<em>n</em>) = <em>O</em>(<em>g</em>(<em>n</em>)).

<ol start="4">

 <li>Prove or disprove <em>f</em>(<em>n</em>) = 5 · <em>n</em><sup>3 </sup>− <em>n </em>+ 3</li>

 <li><em>f</em>(<em>n</em>) = <em>O</em>(<em>n</em><sup>2</sup>)</li>

</ol>

<em>f</em>(<em>n</em>) = <em>O</em>(<em>n</em><sup>2</sup>)          ⇐⇒                    ∃<em>c &gt; </em>0<em>,</em>∃<em>k </em>≥ 0<em>s.tf</em>(<em>n</em>) ≤ <em>c </em>· <em>n</em><sup>2 </sup>∀<em>n </em>≥ <em>k</em>

Which is a contradiction, hence <em>f</em>(<em>n</em>) 6= <em>O</em>(<em>n</em><sup>2</sup>).

<ol start="2">

 <li><em>f</em>(<em>n</em>) = Ω(<em>n</em>)</li>

</ol>

<em>f</em>(<em>n</em>) = Ω(<em>n</em>)         ⇐⇒             ∃<em>c &gt; </em>0<em>,</em>∃<em>k </em>≥ 0<em>s.tf</em>(<em>n</em>) ≥ <em>c </em>· <em>n</em>∀<em>n </em>≥ <em>k</em>

5 · <em>n</em><sup>3 </sup>− <em>n </em>+ 3           ≥           5 · <em>n </em>− <em>n </em>+ 3

≥          5 · <em>n </em>− <em>n</em>

=           4 · <em>n,n </em>≥ 1

Let <em>c </em>= 4 and <em>k </em>= 1 then the statement translate to

5 · <em>n</em><sup>3 </sup>− <em>n </em>+ 3       ≥       <em>c </em>· <em>n,n </em>≥ <em>k</em>

which by the definition of Ω notation, 5 · <em>n</em><sup>3 </sup>− <em>n </em>+ 3 is Ω(<em>n</em>).

<ol start="3">

 <li><em>f</em>(<em>n</em>) = Θ(<em>n</em><sup>3</sup>)</li>

</ol>

<em>f</em>(<em>n</em>) = Θ(<em>n</em><sup>3</sup>)          ⇐⇒             <em>f</em>(<em>n</em>) = <em>O</em>(<em>n</em><sup>3</sup>)<em>andf</em>(<em>n</em>) = Ω(<em>n</em><sup>3</sup>)

Showing <em>f</em>(<em>n</em>) = <em>O</em>(<em>n</em><sup>3</sup>)

<em>f</em>(<em>n</em>) = <em>O</em>(<em>n</em><sup>3</sup>)         ⇐⇒             ∃<em>c &gt; </em>0<em>,</em>∃<em>k </em>≥ 0<em>s.tf</em>(<em>n</em>) ≤ <em>c </em>· <em>g</em>(<em>n</em>)∀<em>n </em>≥ <em>k</em>

5 · <em>n</em><sup>3 </sup>− <em>n </em>+ 3        ≤        5 · <em>n</em><sup>3 </sup>+ <em>n</em><sup>3 </sup>+ 3 · <em>n</em><sup>3</sup>

=        9 · <em>n</em><sup>3</sup><em>,n </em>≥ 1

Let <em>c </em>= 9 and <em>k </em>= 1 then the statement translates to

5 · <em>n</em><sup>3 </sup>− <em>n </em>+ 3       ≤        <em>c </em>· <em>n</em><sup>3</sup><em>,n </em>≥ <em>k</em>

which by the definition of <em>O </em>notation, 5 · <em>n</em><sup>3 </sup>− <em>n </em>+ 3 = <em>O</em>(<em>n</em><sup>3</sup>).

Showing <em>f</em>(<em>n</em>) = Ω(<em>n</em><sup>3</sup>) <em>f</em>(<em>n</em>) = Ω(<em>n</em><sup>3</sup>)        ⇐⇒          ∃<em>c &gt; </em>0<em>,</em>∃<em>k </em>≥ 0<em>s.tf</em>(<em>n</em>) ≥ <em>c </em>· <em>g</em>(<em>n</em>)∀<em>n </em>≥ <em>k</em>

5 · <em>n</em><sup>3 </sup>− <em>n </em>+ 3       ≥        5 · <em>n</em><sup>3 </sup>− <em>n</em><sup>3 </sup>+ 3

≥       4 · <em>n</em><sup>3 </sup>+ 3

≥       4 · <em>n</em><sup>3</sup><em>,n </em>≥ 1

Let <em>c </em>= 4 and <em>k </em>= 1 then the statement translate to

5 · <em>n</em><sup>3 </sup>− <em>n </em>+ 3       ≥        <em>c </em>· <em>n</em><sup>3</sup><em>,n </em>≥ <em>k</em>

which by the definition of Ω notation, 5 · <em>n</em><sup>3 </sup>− <em>n </em>+ 3 is Ω(<em>n</em><sup>3</sup>).

Since 5 · <em>n</em><sup>3 </sup>− <em>n </em>+ 3 is <em>O</em>(<em>n</em><sup>3</sup>) and 5 · <em>n</em><sup>3 </sup>− <em>n </em>+ 3 is Ω(<em>n</em><sup>3</sup>) we conclude that 5 · <em>n</em><sup>3 </sup>− <em>n </em>+ 3 is Θ(<em>n</em><sup>3</sup>).

<ol start="4">

 <li><em>f</em>(<em>n</em>) = <em>ω</em>(<em>n</em>)</li>

</ol>

which by the definition of <em>ω </em>notation, 5 · <em>n</em><sup>3 </sup>− <em>n </em>+ 3 is <em>ω</em>(<em>n</em>).

<ol start="5">

 <li><em>f</em>(<em>n</em>) = <em>o</em>(<em>n</em><sup>2</sup>)</li>

</ol>

hence <em>f</em>(<em>n</em>) 6= <em>o</em>(<em>n</em><sup>2</sup>).

<ol start="5">

 <li>Prove that (<em>n </em>+ 5)<sup>100 </sup>= Θ(<em>n</em><sup>100</sup>)</li>

</ol>

<em>f</em>(<em>n</em>) = Θ(<em>g</em>(<em>n</em>))         ⇐⇒            <em>f</em>(<em>n</em>) = <em>O</em>(<em>g</em>(<em>n</em>))<em>andf</em>(<em>n</em>) = Ω(<em>g</em>(<em>n</em>))

<ol>

 <li>Showing (<em>n </em>+ 5)<sup>100 </sup>= <em>O</em>(<em>n</em><sup>100</sup>)</li>

</ol>

<em>f</em>(<em>n</em>) = <em>O</em>(<em>g</em>(<em>n</em>))         ⇐⇒             ∃<em>c &gt; </em>0<em>,</em>∃<em>k </em>≥ 0<em>s.tf</em>(<em>n</em>) ≤ <em>c </em>· <em>g</em>(<em>n</em>)∀<em>n </em>≥ <em>k</em>

Let and <em>k </em>= 1 then the statements translates to

<em>f</em>(<em>n</em>)       ≤       <em>c </em>· <em>g</em>(<em>n</em>)<em>,n </em>≥ <em>k</em>

which by the definition of <em>O </em>notation <em>f</em>(<em>n</em>) = <em>O</em>(<em>g</em>(<em>n</em>)).

<ol start="2">

 <li>Showing (<em>n </em>+ 5)<sup>100 </sup>= Ω(<em>n</em><sup>100</sup>)</li>

</ol>

<em>f</em>(<em>n</em>) = Ω(<em>g</em>(<em>n</em>))         ⇐⇒             ∃<em>c &gt; </em>0<em>,</em>∃<em>k </em>≥ 0<em>s.tf</em>(<em>n</em>) ≥ <em>c </em>· <em>g</em>(<em>n</em>)∀<em>n </em>≥ <em>k</em>

Let <em>c </em>= 1 and <em>k </em>= 1 then the statement translates to

<em>f</em>(<em>n</em>)       ≥       <em>c </em>· <em>g</em>(<em>n</em>)<em>,n </em>≥ <em>k</em>

which by the definition of Ω notation <em>f</em>(<em>n</em>) = Ω(<em>g</em>(<em>n</em>)).

Since <em>f</em>(<em>n</em>) = <em>O</em>(<em>g</em>(<em>n</em>)) and <em>f</em>(<em>n</em>) = Ω(<em>g</em>(<em>n</em>)) by the definition of Θ notation <em>f</em>(<em>n</em>) = Θ(<em>n</em><sup>100</sup>).

<ol start="6">

 <li>Prove transitivity of big-<em>O</em>: if <em>f</em>(<em>n</em>) = <em>O</em>(<em>g</em>(<em>n</em>)), and <em>g</em>(<em>n</em>) = <em>O</em>(<em>h</em>(<em>n</em>)), then <em>f</em>(<em>n</em>) = <em>O</em>(<em>h</em>(<em>n</em>)).</li>

</ol>

Since <em>f</em>(<em>n</em>) = <em>O</em>(<em>g</em>(<em>n</em>)) and <em>g</em>(<em>n</em>) = <em>O</em>(<em>h</em>(<em>n</em>)) we have the equalities

<em>f</em>(<em>n</em>)            ≤               <em>c</em><sub>1 </sub>· <em>g</em>(<em>n</em>)<em>,n </em>≥ <em>k</em><sub>1 </sub><em>g</em>(<em>n</em>)               ≤               <em>c</em><sub>2 </sub>· <em>h</em>(<em>n</em>)<em>,n </em>≥ <em>k</em><sub>2</sub>

From this we obtain

<em>f</em>(<em>n</em>)       ≤        <em>c</em><sub>1 </sub>· <em>c</em><sub>2 </sub>· <em>h</em>(<em>n</em>)<em>,n </em>≥ <em><sup>k</sup></em><sup>0</sup>

where <em>k</em><sup>0 </sup>= <em>max</em>(<em>k</em><sub>1</sub><em>,k</em><sub>2</sub>). Let <em>c </em>= <em>c</em><sub>1 </sub>·<em>c</em><sub>2 </sub>and <em>k </em>= <em>k</em><sup>0 </sup>the statement then translate to

<em>f</em>(<em>n</em>)       ≤        <em>c </em>· <em>h</em>(<em>n</em>)<em>,n </em>≥ <em>k</em>

which by the definition of <em>O </em>notation, <em>f</em>(<em>n</em>) = <em>O</em>(<em>h</em>(<em>n</em>)).

<ol start="7">

 <li>Prove that <em>f</em>(<em>n</em>) = <em>O</em>(<em>g</em>(<em>n</em>)) ⇐⇒ <em>g</em>(<em>n</em>) = Ω(<em>f</em>(<em>n</em>)).</li>

</ol>

Forward direction: <em>f</em>(<em>n</em>) = <em>O</em>(<em>g</em>(<em>n</em>)) =⇒ <em>g</em>(<em>n</em>) = Ω(<em>f</em>(<em>n</em>)).

Since <em>f</em>(<em>n</em>) = <em>O</em>(<em>g</em>(<em>n</em>)) there exists a number <em>c </em>and a number <em>k </em>such that <em>f</em>(<em>n</em>) ≤ <em>c </em>· <em>g</em>(<em>n</em>)<em>,n </em>≥ <em>k </em>where <em>c &gt; </em>0 and <em>k </em>≥ 0. From this we obtain <em>g</em>(<em>n</em>)<em>,n </em>≥ <em>k</em>. Which by the definition of Ω notation, <em>g</em>(<em>n</em>) = Ω(<em>f</em>(<em>n</em>)).

Backward direction: <em>g</em>(<em>n</em>) = Ω(<em>f</em>(<em>n</em>)) =⇒ <em>f</em>(<em>n</em>) = <em>O</em>(<em>g</em>(<em>n</em>))

Since <em>g</em>(<em>n</em>) = Ω(<em>f</em>(<em>n</em>)) there exists a number <em>c </em>and a number <em>k </em>such that <em>g</em>(<em>n</em>) ≥ <em>c </em>· <em>f</em>(<em>n</em>)<em>,n </em>≥ <em>k </em>where <em>c &gt; </em>0 and <em>k </em>≥ 0. From this we obtain <em>f</em>(<em>n</em>)<em>,n </em>≥ <em>k</em>. Which by the definition of <em>O </em>notation, <em>f</em>(<em>n</em>) = <em>O</em>(<em>g</em>(<em>n</em>)).

We conclude <em>f</em>(<em>n</em>) = <em>O</em>(<em>g</em>(<em>n</em>)) ⇐⇒ <em>g</em>(<em>n</em>) = Ω(<em>f</em>(<em>n</em>)).

<ol start="8">

 <li>Compare the growth of

  <ol>

   <li><em>f</em>(<em>n</em>) = <em>n </em>and <em>g</em>(<em>n</em>) = <em>n</em><sup>1+<em>sin</em>(<em>n</em>)</sup></li>

  </ol></li>

</ol>

<em>f</em>(<em>n</em>) = <em>O</em>(<em>g</em>(<em>n</em>))         ⇐⇒             ∃<em>c &gt; </em>0<em>,</em>∃<em>k </em>≥ 0<em>s.tf</em>(<em>n</em>) ≤ <em>c </em>· <em>g</em>(<em>n</em>)∀<em>n </em>≥ <em>k</em>

No analysis can be described for <em>f</em>(<em>n</em>) and <em>g</em>(<em>n</em>).

√

<ol start="2">

 <li><em>f</em>(<em>n</em>) = <em>n </em>and <em>g</em>(<em>n</em>) = <em>n </em>+ <em>sin</em>(<em>n</em>)</li>

</ol>

√                                                                         √

Thus           <em>n </em>is <em>o</em>(<em>n </em>+ <em>sin</em>(<em>n</em>)). This implies                <em>n </em>is <em>O</em>(<em>n </em>+ <em>sin</em>(<em>n</em>)). We also

√

have then that <em>n </em>+ <em>sin</em>(<em>n</em>) is Ω( <em>n</em>).

<ol start="3">

 <li><em>f</em>(<em>n</em>) = <em>n </em>and <em>g</em>(<em>n</em>) = <em>n </em> |<em>sin</em>(<em>n</em>)|</li>

</ol>

<em>f</em>(<em>n</em>) = <em>O</em>(<em>g</em>(<em>n</em>))         ⇐⇒             ∃<em>c &gt; </em>0<em>,</em>∃<em>k </em>≥ 0<em>s.tf</em>(<em>n</em>) ≤ <em>c </em>· <em>g</em>(<em>n</em>)∀<em>n </em>≥ <em>k</em>

<em>n </em>· |<em>sin</em>(<em>n</em>)|      ≤      <em>c </em>· <em>n</em>

|<em>sin</em>(<em>n</em>)|      ≤      <em>c</em>

Let <em>c </em>= 2 and <em>k </em>= 0 then the following equality holds

<em>n </em>· |<em>sin</em>(<em>n</em>)|       ≤       <em>c </em>· <em>n </em>≥ <em>k</em>

by the definition of <em>O </em>notation <em>n </em>· |<em>sin</em>(<em>n</em>)| is <em>O</em>(<em>n</em>). by part (7) we also have that <em>n </em>is Ω(<em>n </em>· |<em>sin</em>(<em>n</em>)|).

<ol start="9">

 <li>Prove or disprove 2<em><sup>n</sup></em><sup>+1 </sup>= <em>O</em>(2<em><sup>n</sup></em>)</li>

</ol>

<em>f</em>(<em>n</em>) = <em>O</em>(<em>g</em>(<em>n</em>))         ⇐⇒             ∃<em>c &gt; </em>0<em>,</em>∃<em>k </em>≥ 0<em>s.tf</em>(<em>n</em>) ≤ <em>c </em>· <em>g</em>(<em>n</em>)∀<em>n </em>≥ <em>k</em>

2<em>n</em>+1       =      2 · 2<em>n</em>

≤        3 · 2<em><sup>n</sup>,n </em>≥ 1

Let <em>c </em>= 3 and <em>k </em>= 1 then the statement translates to

2<em><sup>n</sup></em><sup>+1       </sup>≤        <em>c </em>· 2<em><sup>n</sup>,n </em>≥ <em>k</em>

which by the definition of <em>O </em>notation, 2<em><sup>n</sup></em><sup>+1 </sup>= <em>O</em>(2<em><sup>n</sup></em>).

<ol start="10">

 <li>Prove or disprove 2<sup>2·<em>n </em></sup>= (2<em><sup>n</sup></em>)</li>

</ol>

hence 2<sup>2·<em>n </em></sup>6= <em>o</em>(2<em><sup>n</sup></em>).

<ol start="11">

 <li>Prove that if <em>f</em>(<em>n</em>) ≤ Θ(<em>g</em>(<em>n</em>)).</li>

</ol>




, for some constant <em>C &gt; </em>0 then




Since, for every <em> &gt; </em>0, there exists <em>k </em>≥ 0 such that, for all

. From this we obtain

Since <em>C &gt; </em>0 and <em> &gt; </em>0, the equality implies <em>f</em>(<em>n</em>) = Θ(<em>g</em>(<em>n</em>)) so long as ( 0. Let then the equality holds and by the definition of Θ notation, <em>f</em>(<em>n</em>) = Θ(<em>g</em>(<em>n</em>)).