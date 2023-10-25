<style>
.blink1 {
    animation-name: colorchange1;
    animation-duration: 3s;
    animation-timing-function: ease-in-out;
    animation-iteration-count: infinite;
}
.blink2 {
    animation-name: colorchange2;
    animation-duration: 3s;
    animation-timing-function: ease-in-out;
    animation-iteration-count: infinite;
}
.blink3 {
    animation-name: colorchange3;
    animation-duration: 3s;
    animation-timing-function: ease-in-out;
    animation-iteration-count: infinite;
}
.blink4 {
    animation-name: colorchange4;
    animation-duration: 3s;
    animation-timing-function: ease-in-out;
    animation-iteration-count: infinite;
}
.blink5 {
    animation-name: colorchange5;
    animation-duration: 3s;
    animation-timing-function: ease-in-out;
    animation-iteration-count: infinite;
}
.x-mas-light {
    animation-name: xmas;
    animation-duration: 2s;
    animation-timing-function: linear; /*ease-in-out;*/
    animation-iteration-count: infinite;
}

@keyframes colorchange1 {
  0%   {color: red;}
  25%  {color: green;}
  50%  {color: gold;}
  75%  {color: white;}
  100% {color: blue;}
}
@keyframes colorchange2 {
  0%   {color: green;}
  25%  {color: gold;}
  50%  {color: white;}
  75%  {color: blue;}
  100% {color: red;}
}
@keyframes colorchange3 {
  0%   {color: gold;}
  25%  {color: white;}
  50%  {color: blue;}
  75%  {color: red;}
  100% {color: green;}
}
@keyframes colorchange4 {
  0%   {color: white;}
  25%  {color: blue;}
  50%  {color: red;}
  75%  {color: green;}
  100% {color: gold;}
}
@keyframes colorchange5 {
  0%   {color: blue;}
  25%  {color: red;}
  50%  {color: green;}
  75%  {color: gold;}
  100% {color: white;}
}
@keyframes xmas {
  0%   {color: white;}
  50%  {color: yellow;}
  100%  {color: red;}
}
.container {
    display: block;
    position: relative;
    width: 100%;
}
.test {
    /*background-color: #a67;*/
    display: inline-block;
    padding: 0;
    margin: 0;
  animation-name: moveRight;
  animation-duration: 16s;
  animation-iteration-count: infinite;
  animation-timing-function: linear; /*ease-in-out;*/
}
@keyframes moveRight {
  0%   {transform: translateX(-130%); opacity: 1.0;}
  90% {opacity: 1.0;}
  100% {transform: translateX(230%); opacity: 0.1;}
}
</style>

<div class="container">
<p class="test">
  <span class="x-mas-light">&star;</span> <span class="blink1">Javascript</span> <span class="x-mas-light">&heartsuit;</span> <span class="blink2">React.js</span> <span class="x-mas-light">&star;</span> <span class="blink3">Next</span> <span class="x-mas-light">&heartsuit;</span> <span class="blink4">Vue.js</span> <span class="x-mas-light">&heartsuit;</span> <span class="blink5">Nuxt</span> <span class="x-mas-light">&star;</span> <span class="blink1">AI</span> <span class="x-mas-light">&heartsuit;</span> <span class="blink2">Three.js</span> <span class="x-mas-light">&star;</span>
</p>
</div>

<!---
supershaneski/supershaneski is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
