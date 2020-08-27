XSS
cross site scripting
eg <script>alert("hello")</script>
test script >'>"><img src=x onerror=alert(0)>.
unit tests - escape input > &gt; < &lt;
" &quot; & &amp; / &#x2f; ' &#x27; &#039;

always validate code on client and server when using inputs

never pass unsafe data without escaping
use element.textContent
React + Angular escape as default
