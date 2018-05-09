## how to responsive?

<section>
    <h2>?</h2>
    <small class="fragment">Media Query</small>
</section>
<section>
    <pre>
        <code class="css">
            .box {
                width: 100%;
                background-color: black;
                ....
            }
        </code>
    </pre>
    <small>通常我们的代码是这样的</small>
</section>
<section>
    <pre>
        <code class="css">
@media (max-width:  512px) {
  .box {
    background-color: red;
  }
}

@media (min-width: 513px) and (max-width: 1024px) {
  .box {
    background-color: yellow;
  }
}
        </code>
    </pre>
    <small>加上媒体查询后我们的效果应该是这样的</small>
</section>
<section>
    <a href="https://codepen.io/Gougougogogo/pen/jxZLOo?editors=1100" target="_blank">Let's try</a>
</section>
<section> 
    <a href="https://www.w3schools.com/cssref/css3_pr_mediaquery.asp" target="_blank">Learn More</a>
</section>