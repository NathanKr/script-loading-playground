<h2>Motivation</h2>
Script loading can have significat imapct on page loading. This is part of my new course 'boost your website performance' so lets get a feeling of it

<h2>leading questions</h2>
<ul>
<li>async vs defer vs blocking (default) and use cases</li>
<li>preload vs prefetch and use cases --> not directly with scripts</li>
<li>does it refer also to css file </li>
<li>good samples to make me feel what is going on</li>
</ul>

<h2>Usage</h2>
simply load index.html

<h2>Results</h2>
<h3>async vs vs defer blocking (default)</h3>
check directory add-loaded-time
<ul>
 <li>defer provide better page load time compare to blocking because it is not blocking and it does perserve scripts order and does wait for dom to be ready - check index-script-in-head-defer</li>
 <li>async provide better page load time compare to blocking because it is not blocking but it does not perserve scripts order and does not wait for dom to be ready - check index-script-last-in-body-async</li>
 <li>script in head might be too early - check index-script-in-head</li>
</ul>

<h2>References</h2>
<ul>
<li><a href='https://web.dev/articles/critical-rendering-path/adding-interactivity-with-javascript'>Adding Interactivity with JavaScript
</a></li>
</ul>
