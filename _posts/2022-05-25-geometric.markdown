---
title:  "Geometric"
subtitle: "'At first you don't succeed, try, try again.' This distribution maps the number of times you need to attempt something before finally succeeding."
avatar: "img/authors/city's_night_square.jpg"
image: "img/geometric.jpg"
---
The geometric distribution is discrete, meaning that you can only give it natural numbers. It has only one parameter, p, the probability of a "success" on a given attempt. The distribution graphs the probability that you succeed on a given trial.
\
The simple structure of scenarios that follow the geometric distribution is "number of X until you Y". Some examples are: the number of coin flips until you get heads (a Geometric with probability 0.5), the number of die rolls until you roll a 6 (p = 1/6), the number of basketball shots attempted until you make it (let's say you're really good at basketball, so your probability of making any given shot is 0.8), and there is even Geometric to be found in the popular TV show [**Squid Game**](https://medium.com/geekculture/succeed-at-the-squid-games-glass-bridge-using-statistics-26635415de00){:target="_blank"}.
### Geometree-c art
Try creating a forest of trees that follows the geometric distribution. In this special, enchanted probability forest, each tree starts at the same height. A tree has a probability of p of growing one additional unit. For instance, if p = 0.5, then around 50% of all trees would be the minimum height, 50% of the remaining taller trees would be one unit above the minimum height, 50% of the trees that grow past that would be two units above the minimum height, and so on. Basically, at each growing phase, there's a probability of p that a tree stops growing. 
<p class="codepen" data-height="614" data-theme-id="dark" data-default-tab="result" data-slug-hash="GRQybOV" data-user="worldsenddunce" style="height: 556px; box-sizing: border-box; display: flex; align-items: center; justify-content: center; border: 2px solid; margin: 1em 0; padding: 1em;">
  <span>See the Pen <a href="https://codepen.io/worldsenddunce/pen/GRQybOV">
  Geometree-c</a> by Ari (<a href="https://codepen.io/worldsenddunce">@worldsenddunce</a>)
  on <a href="https://codepen.io">CodePen</a>.</span>
</p>
<script async src="https://cpwebassets.codepen.io/assets/embed/ei.js"></script>
Notice that as p gets larger, on average, the trees get shorter.
\
\
\
\
Check out the generative art of [**<ins>other distributions!</ins>**](https://zoo-of-distributions.github.io/)
