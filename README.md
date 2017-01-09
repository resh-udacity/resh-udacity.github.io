## Website Performance Optimization portfolio project


####Part 1: Optimize PageSpeed Insights score for index.html

**Optimizations performed**

* Inlined *style.css*
* Added media='print' for print.css
* Removed link of the google font
* Added async for the js script files
* Moved the script files to the bottom
* Optimized images , including *pizzeria.jpg* in *views/images*
* Applied similar optimisations in the three links in *index.html*

**Page-speed Insights score**

https://resh-udacity.github.io/
Mobile : 92 / 100
Desktop : 95 / 100

####Part 2: Optimize Frames per Second in pizza.html

**Optimizations performed**

* `changePizzaSizes()` edited so that unnecessary calculations are avoided (line 425 in *main.js*)
* Reduced the number of iterations for pizzas from 200 to 50 (line 516 in *main.js*)
* Added css style `will-change:transform` to create layers to optimize paint time (line 36 in *style.css*)

Other possible optimizations
* Minify html
* Minify CSS

### Optimization Tips and Tricks
* [Optimizing Performance](https://developers.google.com/web/fundamentals/performance/ "web performance")
* [Analyzing the Critical Rendering Path](https://developers.google.com/web/fundamentals/performance/critical-rendering-path/analyzing-crp.html "analyzing crp")
* [Optimizing the Critical Rendering Path](https://developers.google.com/web/fundamentals/performance/critical-rendering-path/optimizing-critical-rendering-path.html "optimize the crp!")
* [Avoiding Rendering Blocking CSS](https://developers.google.com/web/fundamentals/performance/critical-rendering-path/render-blocking-css.html "render blocking css")
* [Optimizing JavaScript](https://developers.google.com/web/fundamentals/performance/critical-rendering-path/adding-interactivity-with-javascript.html "javascript")
* [Measuring with Navigation Timing](https://developers.google.com/web/fundamentals/performance/critical-rendering-path/measure-crp.html "nav timing api"). We didn't cover the Navigation Timing API in the first two lessons but it's an incredibly useful tool for automated page profiling. I highly recommend reading.
* <a href="https://developers.google.com/web/fundamentals/performance/optimizing-content-efficiency/eliminate-downloads.html">The fewer the downloads, the better</a>
* <a href="https://developers.google.com/web/fundamentals/performance/optimizing-content-efficiency/optimize-encoding-and-transfer.html">Reduce the size of text</a>
* <a href="https://developers.google.com/web/fundamentals/performance/optimizing-content-efficiency/image-optimization.html">Optimize images</a>
* <a href="https://developers.google.com/web/fundamentals/performance/optimizing-content-efficiency/http-caching.html">HTTP caching</a>

### Customization with Bootstrap
The portfolio was built on Twitter's <a href="http://getbootstrap.com/">Bootstrap</a> framework. All custom styles are in `dist/css/portfolio.css` in the portfolio repo.

* <a href="http://getbootstrap.com/css/">Bootstrap's CSS Classes</a>
* <a href="http://getbootstrap.com/components/">Bootstrap's Components</a>
