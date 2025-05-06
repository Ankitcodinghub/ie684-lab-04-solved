# ie684-lab-04-solved
**TO GET THIS SOLUTION VISIT:** [IE684 Lab 04 Solved](https://www.ankitcodinghub.com/product/ie684-lab-04-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;97611&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;IE684 Lab 04 Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
Exercise 1: Newton’s method

Recall that in the last lab, we had implemented Newton’s method as a specific case of gradient descent with scaling. In this lab, we will focus on the performance of Newton’s method on some problems. We consider the Newton’s method implementation illustrated in Algorithm 1.

Input: Starting point x0, Stopping tolerance τ Initialize k = 0

while ∥∇f(xk)∥2 &gt; τ do

ηk = arg minη≥0 f(xk − η(∇2f(xk))−1∇f(xk)) xk+1 = xk − ηk(∇2f(xk))−1∇f(xk)

k=k+1

end

Output: xk .

Algorithm 1: Newton’s method

1. Please reuse the code you had written in the past labs to implement the Newton’s method in Algorithm 1.

2. Consider the function f(x) = 400×21 +0.004×42. Write code for implementing all relevant modules necessary for Newton’s method and gradient descent method to solve minx f(x).

3. [R] Consider ηk = 1, ∀k = 1, 2, . . . in Algorithm 1. With starting point x0 = (2, 2) and a stopping tolerance τ = 10−9, find the number of iterations taken by the Newton’s method. Compare the number of iterations with that taken by Newton’s method (with backtracking line search) in Algorithm 1. Note the minimizer and minimum objective function value in each case. Comment on your observations.

4. [R] Compare the number of iterations obtained for the two variants of Newton’s method in the previous question, with that of gradient descent algorithm (without scaling) with backtracking line search, gradient descent algorithm (with scaling using a diagonal matrix) with backtracking line search (implemented in previous labs), with starting point (2, 2). For backtracking line search, use α0 = 1, ρ = 0.5, γ = 0.5. Also compare the minimizer and minimum objective function value in each case. Comment on your observations.

</div>
</div>
<div class="layoutArea">
<div class="column">
2

</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="layoutArea">
<div class="column">
IE684, IEOR Lab Lab 04

Exercise 2:

Consider the function

</div>
<div class="column">
02-February-2022

</div>
</div>
<div class="layoutArea">
<div class="column">
q(x)=􏰃x21 +4+􏰃x2 +4.

<ol>
<li>Write code for implementing all relevant modules necessary for Newton’s method and gradient descent method
to solve minx q(x).
</li>
<li>[R] Consider ηk = 1, ∀k = 1, 2, . . . in Algorithm 1. With starting point x0 = (2, 2) and a stopping tolerance τ = 10−9, find the number of iterations taken by the Newton’s method. Compare the number of iterations with that taken by Newton’s method (with backtracking line search) in Algorithm 1. Note the minimizer and minimum objective function value in each case. Comment on your observations.</li>
<li>[R] Compare the number of iterations obtained for the two variants of Newton’s method in the previous question, with that of gradient descent algorithm (without scaling) with backtracking line search (implemented in previous labs), with starting point (2, 2). For backtracking line search, use α0 = 1, ρ = 0.5, γ = 0.5. Also compare the minimizer and minimum objective function value in each case. Comment on your observations.</li>
<li>[R] Consider ηk = 1, ∀k = 1, 2, . . . in Algorithm 1. With starting point x0 = (8, 8) and a stopping tolerance τ = 10−9, find the number of iterations taken by the Newton’s method. Compare the number of iterations with that taken by Newton’s method (with backtracking line search) in Algorithm 1. Note the minimizer and minimum objective function value in each case. Comment on your observations.</li>
<li>[R] Compare the number of iterations obtained for the two variants of Newton’s method in the previous question, with that of gradient descent algorithm (without scaling) with backtracking line search (implemented in previous labs), with starting point (8, 8). For backtracking line search, use α0 = 1, ρ = 0.5, γ = 0.5. Also compare the minimizer and minimum objective function value in each case. Comment on your observations.</li>
</ol>
</div>
</div>
<div class="layoutArea">
<div class="column">
3

</div>
</div>
</div>
