---
layout: page
title: "Nunjucks editor online"
subtitle: "For testing quickly nunjuck code"
subtitle: Convert
permalink: /github-colab
---

👉 Source code from [this url](https://codepen.io/netwjx/pen/xOPVKx). <br />
👉 [Nunjuck official document](https://mozilla.github.io/nunjucks/templating.html).

<link rel="stylesheet" href="{{site.url}}{{site.baseurl}}/external_assets/nunjuck-online/style.css">

<!-- partial:index.partial.html -->
<textarea id="json">[
   { title: "foo", id: 1 },
   { title: "bar", id: 2}
]</textarea>
<textarea id="code"><h1>Posts</h1>
<ul>
&#123;&#37;&#32;&#102;&#111;&#114;&#32;&#105;&#116;&#101;&#109;&#32;&#105;&#110;&#32;&#105;&#116;&#101;&#109;&#115;&#32;&#37;&#125;&#10;&#32;&#32;&#60;&#108;&#105;&#62;&#123;&#123;&#32;&#105;&#116;&#101;&#109;&#46;&#116;&#105;&#116;&#108;&#101;&#32;&#125;&#125;&#60;&#47;&#108;&#105;&#62;&#10;&#123;&#37;&#32;&#101;&#108;&#115;&#101;&#32;&#37;&#125;&#10;&#32;&#32;&#60;&#108;&#105;&#62;&#84;&#104;&#105;&#115;&#32;&#119;&#111;&#117;&#108;&#100;&#32;&#100;&#105;&#115;&#112;&#108;&#97;&#121;&#32;&#105;&#102;&#32;&#116;&#104;&#101;&#32;&#39;&#105;&#116;&#101;&#109;&#39;&#32;&#99;&#111;&#108;&#108;&#101;&#99;&#116;&#105;&#111;&#110;&#32;&#119;&#101;&#114;&#101;&#32;&#101;&#109;&#112;&#116;&#121;&#60;&#47;&#108;&#105;&#62;&#10;&#123;&#37;&#32;&#101;&#110;&#100;&#102;&#111;&#114;&#32;&#37;&#125;
</ul></textarea>
<pre id="output">hello nunjucks</pre>
<!-- partial -->
<script src='https://mozilla.github.io/nunjucks/bower_components/jquery/jquery.min.js'></script>
<script src='https://mozilla.github.io/nunjucks/files/nunjucks.js'></script><script  src="{{site.url}}{{site.baseurl}}/external_assets/nunjuck-online/script.js"></script>
