---
layout: post
title:  "comment test"
date:   2023-07-22 12:27:00 +0700
categories: test
comments: true
---

{% if page.comments %}
<div id="disqus_thread"></div>
<script>
    var disqus_config = function () {
    this.page.url = "https://achia70.github.io/test/2023/07/22/comment-test.html";  // Replace PAGE_URL with your page's canonical URL variable
    this.page.identifier = "2023-07-22-comment-test"; // Replace PAGE_IDENTIFIER with your page's unique identifier variable
    };
    (function() { // DON'T EDIT BELOW THIS LINE
    var d = document, s = d.createElement('script');
    s.src = 'https://achia70-github-io.disqus.com/embed.js';
    s.setAttribute('data-timestamp', +new Date());
    (d.head || d.body).appendChild(s);
    })();
</script>
<noscript>Please enable JavaScript to view the <a href="https://disqus.com/?ref_noscript">comments powered by Disqus.</a></noscript>
{% endif %}