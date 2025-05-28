<h1>🧮 Lesson 1: Basics of R</h1>

<h2>🔹 Summary</h2>
<p>In this lesson, you’ll learn how to:</p>
<ul>
  <li>Assign values to variables</li>
  <li>Understand and work with different data types (numeric, character, logical)</li>
  <li>Check and convert data types</li>
  <li>Perform arithmetic and comparisons in R</li>
</ul>

<hr>

<h2>📘 Section 1: Variables and Assignment</h2>
<p>Variables store data so you can reuse and manipulate it. In R, assignment is done using <code>&lt;-</code> (preferred) or <code>=</code>.</p>

<pre><code># Using the assignment operator
x &lt;- 10            # numeric
name &lt;- "Alice"    # character
is_active &lt;- TRUE  # logical

# Print values
x
name
is_active
</code></pre>

<p><strong>Tip:</strong> Use <code>&lt;-</code> instead of <code>=</code> for better R style.</p>

<hr>

<h2>📘 Section 2: Data Types in R</h2>
<p>R has several basic data types:</p>
<ul>
  <li><strong>Numeric</strong>: numbers (e.g., 42, 3.14)</li>
  <li><strong>Character</strong>: text strings in quotes (e.g., "hello")</li>
  <li><strong>Logical</strong>: <code>TRUE</code> or <code>FALSE</code></li>
</ul>

<pre><code># Numeric
age &lt;- 29
height &lt;- 1.75

# Character
city &lt;- "Toronto"

# Logical
is_tall &lt;- height &gt; 1.8

# View outputs
age
height
city
is_tall
</code></pre>

<hr>

<h2>📘 Section 3: Type Coercion &amp; Type Checking</h2>
<p>R tries to make all elements in a vector the same type — this is called <em>type coercion</em>. You can also check and manually convert types.</p>

<pre><code># Type coercion example
mixed &lt;- c(1, "hello", TRUE)
mixed  # all become characters

# Type checking
typeof(age)       # "double"
typeof(city)      # "character"
typeof(is_tall)   # "logical"

# Logical test functions
is.numeric(age)
is.character(city)
is.logical(is_tall)

# Explicit type conversion
as.numeric("5")       # 5
as.logical(0)         # FALSE
as.character(TRUE)    # "TRUE"
</code></pre>

<hr>

<h2>📘 Section 4: Arithmetic and Comparison Operators</h2>

<h3>Arithmetic Operators:</h3>
<ul>
  <li><code>+</code> Addition</li>
  <li><code>-</code> Subtraction</li>
  <li><code>*</code> Multiplication</li>
  <li><code>/</code> Division</li>
  <li><code>^</code> Exponentiation</li>
</ul>

<pre><code>a &lt;- 5
b &lt;- 2

sum &lt;- a + b        # 7
diff &lt;- a - b       # 3
product &lt;- a * b    # 10
quotient &lt;- a / b   # 2.5
power &lt;- a ^ b      # 25

sum
diff
product
quotient
power
</code></pre>

<h3>Comparison Operators:</h3>
<ul>
  <li><code>==</code> equal to</li>
  <li><code>!=</code> not equal to</li>
  <li><code>&gt;</code> greater than</li>
  <li><code>&lt;</code> less than</li>
  <li><code>&gt;=</code> greater than or equal</li>
  <li><code>&lt;=</code> less than or equal</li>
</ul>

<pre><code>a == b     # FALSE
a != b     # TRUE
a &gt; b      # TRUE
a &lt; b      # FALSE
a &gt;= b     # TRUE
a &lt;= b     # FALSE
</code></pre>

<p>These return logical values: <code>TRUE</code> or <code>FALSE</code>.</p>

<hr>

<h2>🧪 Practice Challenge</h2>
<p>Try creating your own variables and testing their types:</p>

<pre><code>temperature &lt;- 23.5
weather &lt;- "sunny"
is_hot &lt;- temperature &gt; 30

# Check values and types
temperature
typeof(temperature)

weather
typeof(weather)

is_hot
typeof(is_hot)
</code></pre>

<hr>

<h2>📌 What’s Next?</h2>
<p>In the next lesson, you'll learn:</p>
<ul>
  <li>How to create, access, and manipulate <strong>vectors</strong></li>
  <li>How to work with <strong>factors</strong> (categorical data)</li>
  <li>How to build and navigate <strong>lists</strong> (multi-type containers)</li>
</ul>

<p>Stay tuned and happy coding! 🚀</p>

</body>
</html>
