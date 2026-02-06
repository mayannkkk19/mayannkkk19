/* CSS for scrolling text */
.scrolling-text {
  display: inline-block;
  white-space: nowrap;
  animation: scroll-left 10s linear infinite;
}

@keyframes scroll-left {
  0% { transform: translateX(100%); }
  100% { transform: translateX(-100%); }
}


<h1>Hello There👋</h1>

<!-- HTML Structure -->
<div style="overflow: hidden;">
  <span class="scrolling-text">Your scrolling text here</span>
</div>


<p>🔭 I’m currently working on javascript based beginner projects.</p> 
<p>🌱 I’m currently learning DSA in order to solve coding problems efficiently.</p>
<p>👯 I’m looking to collaborate on more html-css-js based projects.</p>

<p>📫 How to reach me: mayankkyadav76@gmail.com </p>
<p>😄 Pronouns: he/him</p>
