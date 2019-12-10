---


---

<h1 id="python-program-to-add-two-numbers">Python program to add two numbers</h1>
<pre class=" language-python"><code class="prism  language-python"><span class="token keyword">def</span> <span class="token function">add</span><span class="token punctuation">(</span>a<span class="token punctuation">,</span>b<span class="token punctuation">)</span><span class="token punctuation">:</span>
    <span class="token keyword">return</span> a<span class="token operator">+</span>b
x<span class="token punctuation">,</span>y <span class="token operator">=</span> <span class="token builtin">map</span><span class="token punctuation">(</span><span class="token builtin">int</span><span class="token punctuation">,</span><span class="token builtin">input</span><span class="token punctuation">(</span><span class="token string">"Enter two numbers"</span><span class="token punctuation">)</span><span class="token punctuation">.</span>split<span class="token punctuation">(</span><span class="token punctuation">)</span><span class="token punctuation">)</span>
<span class="token keyword">print</span><span class="token punctuation">(</span><span class="token string">"{}+{}={}"</span><span class="token punctuation">.</span><span class="token builtin">format</span><span class="token punctuation">(</span>x<span class="token punctuation">,</span>y<span class="token punctuation">,</span>add<span class="token punctuation">(</span>x<span class="token punctuation">,</span>y<span class="token punctuation">)</span><span class="token punctuation">)</span><span class="token punctuation">)</span>
</code></pre>
<h1 id="python-program-for-factorial-of-number">Python program for factorial of number</h1>
<pre class=" language-python"><code class="prism  language-python"><span class="token keyword">def</span> <span class="token function">fact</span><span class="token punctuation">(</span>n<span class="token punctuation">)</span><span class="token punctuation">:</span>
    fac <span class="token operator">=</span> <span class="token number">1</span> 
    <span class="token keyword">for</span> i <span class="token keyword">in</span> <span class="token builtin">range</span><span class="token punctuation">(</span><span class="token number">1</span><span class="token punctuation">,</span>n<span class="token operator">+</span><span class="token number">1</span><span class="token punctuation">)</span><span class="token punctuation">:</span>
        fac <span class="token operator">*=</span> i
    <span class="token keyword">return</span> fac
x <span class="token operator">=</span> <span class="token builtin">int</span><span class="token punctuation">(</span><span class="token builtin">input</span><span class="token punctuation">(</span><span class="token string">"Enter numbers"</span><span class="token punctuation">)</span><span class="token punctuation">)</span>
<span class="token keyword">print</span><span class="token punctuation">(</span><span class="token string">"Factorial of {} is {}"</span><span class="token punctuation">.</span><span class="token builtin">format</span><span class="token punctuation">(</span>x<span class="token punctuation">,</span>fact<span class="token punctuation">(</span>x<span class="token punctuation">)</span><span class="token punctuation">)</span><span class="token punctuation">)</span>
</code></pre>
<h1 id="simple-interest">Simple interest</h1>
<pre class=" language-python"><code class="prism  language-python"><span class="token keyword">def</span> <span class="token function">si</span><span class="token punctuation">(</span>p<span class="token punctuation">,</span>r<span class="token punctuation">,</span>t<span class="token punctuation">)</span><span class="token punctuation">:</span>
    <span class="token keyword">return</span> <span class="token punctuation">(</span>p<span class="token operator">*</span>r<span class="token operator">*</span>t<span class="token punctuation">)</span><span class="token operator">/</span><span class="token number">100</span>
p<span class="token punctuation">,</span>r<span class="token punctuation">,</span>t <span class="token operator">=</span> <span class="token builtin">map</span><span class="token punctuation">(</span><span class="token builtin">int</span><span class="token punctuation">,</span><span class="token builtin">input</span><span class="token punctuation">(</span><span class="token string">"Enter prt"</span><span class="token punctuation">)</span><span class="token punctuation">.</span>split<span class="token punctuation">(</span><span class="token punctuation">)</span><span class="token punctuation">)</span>
<span class="token keyword">print</span><span class="token punctuation">(</span><span class="token string">"Simple interest: "</span><span class="token punctuation">,</span>si<span class="token punctuation">(</span>p<span class="token punctuation">,</span>r<span class="token punctuation">,</span>t<span class="token punctuation">)</span><span class="token punctuation">)</span>
</code></pre>
<h1 id="compound-interest">Compound interest</h1>
<pre class=" language-python"><code class="prism  language-python"><span class="token keyword">def</span> <span class="token function">compound_interest</span><span class="token punctuation">(</span>c<span class="token punctuation">,</span>r<span class="token punctuation">,</span>t<span class="token punctuation">,</span>n<span class="token punctuation">)</span><span class="token punctuation">:</span>
    <span class="token keyword">return</span> c<span class="token operator">*</span><span class="token punctuation">(</span><span class="token number">1</span><span class="token operator">+</span>r<span class="token operator">/</span>n<span class="token punctuation">)</span><span class="token operator">**</span><span class="token punctuation">(</span>n<span class="token operator">*</span>t<span class="token punctuation">)</span>
c<span class="token punctuation">,</span>r<span class="token punctuation">,</span>t<span class="token punctuation">,</span>n <span class="token operator">=</span> <span class="token builtin">map</span><span class="token punctuation">(</span><span class="token builtin">int</span><span class="token punctuation">,</span><span class="token builtin">input</span><span class="token punctuation">(</span><span class="token string">"Enter c r t n: "</span><span class="token punctuation">)</span><span class="token punctuation">.</span>split<span class="token punctuation">(</span><span class="token punctuation">)</span><span class="token punctuation">)</span>
<span class="token keyword">print</span><span class="token punctuation">(</span><span class="token string">"Compound interest: "</span><span class="token punctuation">,</span>compound_interest<span class="token punctuation">(</span>c<span class="token punctuation">,</span>r<span class="token punctuation">,</span>t<span class="token punctuation">,</span>n<span class="token punctuation">)</span><span class="token punctuation">)</span>
</code></pre>
<h1 id="armstrong-number">Armstrong number</h1>
<pre class=" language-python"><code class="prism  language-python"><span class="token keyword">def</span> <span class="token function">armstrong</span><span class="token punctuation">(</span>n<span class="token punctuation">)</span><span class="token punctuation">:</span>
    x <span class="token operator">=</span> n
    arm <span class="token operator">=</span> <span class="token number">0</span>
    <span class="token keyword">while</span> x<span class="token operator">&gt;</span><span class="token number">0</span><span class="token punctuation">:</span>
        rem <span class="token operator">=</span> x<span class="token operator">%</span><span class="token number">10</span>
        x <span class="token operator">=</span> x<span class="token operator">//</span><span class="token number">10</span>
        arm <span class="token operator">+=</span> rem<span class="token operator">**</span><span class="token number">3</span> 
    <span class="token keyword">print</span><span class="token punctuation">(</span><span class="token string">"Armstrong number"</span><span class="token punctuation">)</span> <span class="token keyword">if</span> arm <span class="token operator">==</span> n <span class="token keyword">else</span> <span class="token keyword">print</span><span class="token punctuation">(</span><span class="token string">"Not armstrong number"</span><span class="token punctuation">)</span>
    
num <span class="token operator">=</span> <span class="token builtin">int</span><span class="token punctuation">(</span><span class="token builtin">input</span><span class="token punctuation">(</span><span class="token string">"Enter number: "</span><span class="token punctuation">)</span><span class="token punctuation">)</span>
armstrong<span class="token punctuation">(</span>num<span class="token punctuation">)</span>
</code></pre>
<h1 id="area-of-a-circle">Area of a circle</h1>
<pre class=" language-python"><code class="prism  language-python"><span class="token keyword">import</span> math
<span class="token keyword">def</span> <span class="token function">area</span><span class="token punctuation">(</span>r<span class="token punctuation">)</span><span class="token punctuation">:</span>
    <span class="token keyword">return</span> math<span class="token punctuation">.</span>pi<span class="token operator">*</span>r<span class="token operator">*</span>r
rad <span class="token operator">=</span> <span class="token builtin">float</span><span class="token punctuation">(</span><span class="token builtin">input</span><span class="token punctuation">(</span><span class="token string">"Enter radius: "</span><span class="token punctuation">)</span><span class="token punctuation">)</span>
<span class="token keyword">print</span><span class="token punctuation">(</span>area<span class="token punctuation">(</span>rad<span class="token punctuation">)</span><span class="token punctuation">)</span>
</code></pre>
<h1 id="prime-number-in-interval">Prime number in interval</h1>
<pre class=" language-python"><code class="prism  language-python"><span class="token keyword">def</span> <span class="token function">prime</span><span class="token punctuation">(</span>s<span class="token punctuation">,</span>e<span class="token punctuation">)</span><span class="token punctuation">:</span>
    <span class="token keyword">for</span> i <span class="token keyword">in</span> <span class="token builtin">range</span><span class="token punctuation">(</span>s<span class="token punctuation">,</span>e<span class="token operator">+</span><span class="token number">1</span><span class="token punctuation">)</span><span class="token punctuation">:</span>
        <span class="token keyword">for</span> j <span class="token keyword">in</span> <span class="token builtin">range</span><span class="token punctuation">(</span><span class="token number">2</span><span class="token punctuation">,</span>i<span class="token punctuation">)</span><span class="token punctuation">:</span>
            <span class="token keyword">if</span> i<span class="token operator">%</span>j <span class="token operator">==</span> <span class="token number">0</span><span class="token punctuation">:</span>
                <span class="token keyword">break</span>
        <span class="token keyword">else</span><span class="token punctuation">:</span>
            <span class="token keyword">print</span><span class="token punctuation">(</span>i<span class="token punctuation">)</span>
x<span class="token punctuation">,</span>y <span class="token operator">=</span> <span class="token builtin">map</span><span class="token punctuation">(</span><span class="token builtin">int</span><span class="token punctuation">,</span><span class="token builtin">input</span><span class="token punctuation">(</span><span class="token string">"Enter start and end: "</span><span class="token punctuation">)</span><span class="token punctuation">.</span>split<span class="token punctuation">(</span><span class="token punctuation">)</span><span class="token punctuation">)</span>
prime<span class="token punctuation">(</span>x<span class="token punctuation">,</span>y<span class="token punctuation">)</span>
    
</code></pre>
<h1 id="check-prime-number">Check prime number</h1>
<pre class=" language-python"><code class="prism  language-python"><span class="token keyword">def</span> <span class="token function">primen</span><span class="token punctuation">(</span>n<span class="token punctuation">)</span><span class="token punctuation">:</span>
    flag <span class="token operator">=</span> <span class="token number">0</span>
    <span class="token keyword">for</span> i <span class="token keyword">in</span> <span class="token builtin">range</span><span class="token punctuation">(</span><span class="token number">2</span><span class="token punctuation">,</span>n<span class="token punctuation">)</span><span class="token punctuation">:</span>
        <span class="token keyword">if</span> n<span class="token operator">%</span>i <span class="token operator">==</span> <span class="token number">0</span><span class="token punctuation">:</span>
            flag <span class="token operator">=</span> <span class="token number">1</span>
    <span class="token keyword">print</span><span class="token punctuation">(</span><span class="token string">"Not Prime"</span><span class="token punctuation">)</span> <span class="token keyword">if</span> flag <span class="token keyword">else</span> <span class="token keyword">print</span><span class="token punctuation">(</span><span class="token string">"Prime"</span><span class="token punctuation">)</span>
primen<span class="token punctuation">(</span><span class="token builtin">int</span><span class="token punctuation">(</span><span class="token builtin">input</span><span class="token punctuation">(</span><span class="token string">"Enter number: "</span><span class="token punctuation">)</span><span class="token punctuation">)</span><span class="token punctuation">)</span>
</code></pre>
<h1 id="nth-fibonacci-number">nth fibonacci number</h1>
<pre class=" language-python"><code class="prism  language-python"><span class="token keyword">def</span> <span class="token function">nfibb</span><span class="token punctuation">(</span>n<span class="token punctuation">)</span><span class="token punctuation">:</span>
    f <span class="token operator">=</span> <span class="token punctuation">[</span><span class="token number">0</span><span class="token punctuation">,</span><span class="token number">1</span><span class="token punctuation">]</span>
    <span class="token punctuation">[</span>f<span class="token punctuation">.</span>append<span class="token punctuation">(</span>f<span class="token punctuation">[</span>i<span class="token punctuation">]</span><span class="token operator">+</span>f<span class="token punctuation">[</span>i<span class="token number">-1</span><span class="token punctuation">]</span><span class="token punctuation">)</span> <span class="token keyword">for</span> i <span class="token keyword">in</span> <span class="token builtin">range</span><span class="token punctuation">(</span><span class="token number">1</span><span class="token punctuation">,</span>n<span class="token punctuation">)</span><span class="token punctuation">]</span>
    <span class="token keyword">return</span> f<span class="token punctuation">[</span>n<span class="token number">-1</span><span class="token punctuation">]</span>
nfibb<span class="token punctuation">(</span><span class="token builtin">int</span><span class="token punctuation">(</span><span class="token builtin">input</span><span class="token punctuation">(</span><span class="token string">"Enter number: "</span><span class="token punctuation">)</span><span class="token punctuation">)</span><span class="token punctuation">)</span>
</code></pre>
<h1 id="check-fibonacci-number">Check fibonacci number</h1>
<pre class=" language-python"><code class="prism  language-python"><span class="token keyword">def</span> <span class="token function">check_fibb</span><span class="token punctuation">(</span>n<span class="token punctuation">)</span><span class="token punctuation">:</span>
    f <span class="token operator">=</span> <span class="token punctuation">[</span><span class="token number">0</span><span class="token punctuation">,</span><span class="token number">1</span><span class="token punctuation">]</span>
    <span class="token punctuation">[</span>f<span class="token punctuation">.</span>append<span class="token punctuation">(</span>f<span class="token punctuation">[</span>i<span class="token punctuation">]</span><span class="token operator">+</span>f<span class="token punctuation">[</span>i<span class="token number">-1</span><span class="token punctuation">]</span><span class="token punctuation">)</span> <span class="token keyword">for</span> i <span class="token keyword">in</span> <span class="token builtin">range</span><span class="token punctuation">(</span><span class="token number">1</span><span class="token punctuation">,</span>n<span class="token punctuation">)</span><span class="token punctuation">]</span>
    <span class="token keyword">print</span><span class="token punctuation">(</span><span class="token string">"Fibonacci number"</span><span class="token punctuation">)</span> <span class="token keyword">if</span> n <span class="token keyword">in</span> f <span class="token keyword">else</span> <span class="token keyword">print</span><span class="token punctuation">(</span><span class="token string">"Not fibonacci"</span><span class="token punctuation">)</span>
check_fibb<span class="token punctuation">(</span><span class="token builtin">int</span><span class="token punctuation">(</span><span class="token builtin">input</span><span class="token punctuation">(</span><span class="token string">"Enter number: "</span><span class="token punctuation">)</span><span class="token punctuation">)</span><span class="token punctuation">)</span>
</code></pre>
<h1 id="nth-multiple-of-a-number-in-fibonacci-series">nth multiple of a number in Fibonacci Series</h1>
<pre class=" language-python"><code class="prism  language-python"><span class="token keyword">def</span> <span class="token function">nthnum</span><span class="token punctuation">(</span>k<span class="token punctuation">,</span>n<span class="token punctuation">)</span><span class="token punctuation">:</span>
    f <span class="token operator">=</span> <span class="token punctuation">[</span><span class="token number">0</span><span class="token punctuation">,</span><span class="token number">1</span><span class="token punctuation">]</span>
    i <span class="token operator">=</span> <span class="token number">1</span>
    cnt <span class="token operator">=</span> <span class="token number">1</span>
    <span class="token keyword">while</span> <span class="token number">1</span><span class="token punctuation">:</span>
        f<span class="token punctuation">.</span>append<span class="token punctuation">(</span>f<span class="token punctuation">[</span>i<span class="token punctuation">]</span><span class="token operator">+</span>f<span class="token punctuation">[</span>i<span class="token number">-1</span><span class="token punctuation">]</span><span class="token punctuation">)</span>
        <span class="token keyword">if</span> f<span class="token punctuation">[</span>i<span class="token operator">+</span><span class="token number">1</span><span class="token punctuation">]</span><span class="token operator">%</span>k <span class="token operator">==</span> <span class="token number">0</span><span class="token punctuation">:</span>
            <span class="token keyword">if</span> cnt <span class="token operator">==</span> n<span class="token punctuation">:</span>
                <span class="token keyword">return</span> f<span class="token punctuation">[</span>i<span class="token operator">+</span><span class="token number">1</span><span class="token punctuation">]</span>  
            <span class="token keyword">else</span><span class="token punctuation">:</span> 
                cnt<span class="token operator">+=</span><span class="token number">1</span>
        i <span class="token operator">+=</span> <span class="token number">1</span>
    <span class="token keyword">print</span><span class="token punctuation">(</span>f<span class="token punctuation">)</span>
    <span class="token keyword">return</span>
x<span class="token punctuation">,</span>y <span class="token operator">=</span> <span class="token builtin">map</span><span class="token punctuation">(</span><span class="token builtin">int</span><span class="token punctuation">,</span><span class="token builtin">input</span><span class="token punctuation">(</span><span class="token string">"Enter multiplier and multiple: "</span><span class="token punctuation">)</span><span class="token punctuation">.</span>split<span class="token punctuation">(</span><span class="token punctuation">)</span><span class="token punctuation">)</span>
<span class="token keyword">print</span><span class="token punctuation">(</span>nthnum<span class="token punctuation">(</span>x<span class="token punctuation">,</span>y<span class="token punctuation">)</span><span class="token punctuation">)</span>
</code></pre>
<pre><code>Enter multiplier and multiple: 3 2
21
</code></pre>
<h1 id="print-ascii-number">Print ASCII number</h1>
<pre class=" language-python"><code class="prism  language-python">x <span class="token operator">=</span> <span class="token builtin">input</span><span class="token punctuation">(</span><span class="token string">"Enter character: "</span><span class="token punctuation">)</span>
<span class="token keyword">print</span><span class="token punctuation">(</span><span class="token builtin">ord</span><span class="token punctuation">(</span>x<span class="token punctuation">)</span><span class="token punctuation">)</span>
</code></pre>
<pre><code>Enter character: d
100
</code></pre>
<h1 id="sum-of-square-of-first-n-numbers">Sum of square of first n numbers:</h1>
<pre class=" language-python"><code class="prism  language-python"><span class="token keyword">def</span> <span class="token function">sum2</span><span class="token punctuation">(</span>n<span class="token punctuation">)</span><span class="token punctuation">:</span>
    <span class="token keyword">return</span> n<span class="token operator">*</span><span class="token punctuation">(</span>n<span class="token operator">+</span><span class="token number">1</span><span class="token punctuation">)</span><span class="token operator">*</span><span class="token punctuation">(</span><span class="token number">2</span><span class="token operator">*</span>n<span class="token operator">+</span><span class="token number">1</span><span class="token punctuation">)</span><span class="token operator">/</span><span class="token number">6</span>
sum2<span class="token punctuation">(</span><span class="token builtin">int</span><span class="token punctuation">(</span><span class="token builtin">input</span><span class="token punctuation">(</span><span class="token string">"Enter number: "</span><span class="token punctuation">)</span><span class="token punctuation">)</span><span class="token punctuation">)</span>
</code></pre>
<pre><code>Enter number: 3





14.0
</code></pre>
<h1 id="sum-of-cubes-of-first-n-numbers">Sum of cubes of first n numbers:</h1>
<pre class=" language-python"><code class="prism  language-python"><span class="token keyword">def</span> <span class="token function">sum3</span><span class="token punctuation">(</span>n<span class="token punctuation">)</span><span class="token punctuation">:</span>
    <span class="token keyword">return</span> <span class="token punctuation">(</span>n<span class="token operator">*</span><span class="token punctuation">(</span>n<span class="token operator">+</span><span class="token number">1</span><span class="token punctuation">)</span><span class="token operator">/</span><span class="token number">2</span><span class="token punctuation">)</span><span class="token operator">**</span><span class="token number">2</span>
sum3<span class="token punctuation">(</span><span class="token builtin">int</span><span class="token punctuation">(</span><span class="token builtin">input</span><span class="token punctuation">(</span><span class="token string">"Enter number: "</span><span class="token punctuation">)</span><span class="token punctuation">)</span><span class="token punctuation">)</span>
</code></pre>
<pre><code>Enter number: 3





36.0
</code></pre>
<pre class=" language-python"><code class="prism  language-python">
</code></pre>

