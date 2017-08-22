<h1 align="center">Final Year Project JAR (CRAWLER)</h1>
<h4>Categorising the .mu domain using MapReduce</h4>
<p>This project was created in order to complete my <b>BSc(Hons) Applied Computing</b> at the <a href="www.uom.ac.mu">University of Mauritius</a></p>
<p>The aim behind this project is to build a web crawler whose dataset is generated using multi-threaded programming and to crawl websites in the .mu domain.
After the crawling process is over, then the results are passed into Hadoop's MapReduce Algorithm which then categorises all the URLs based on their keywords or frequent (non-stop) words.
</p>
<p>This repository contains the jar for the web crawler only</p>
<br/>
<b>Instructions</b>
<ol>
  <li>Download the JAR and open your terminal in that directory</li>
  <li>Run this command <i> java -jar crawler.jar [domain-length] [domain-level] </i>
    <br/>
    <p> <b>Example:<b> <i>java -jar crawler.jar 3 1</i>
      <br/>
      The crawler will then build urls with different cominations of alphabets and then test each of them multi-threadedly. After successful identification of each URL, the crawler will then look for keywords or top words in the websites and insert them in a database.
    </p>
  </li>
</ol>
