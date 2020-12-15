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

<textarea id="json">[
   { title: "foo", id: 1 },
   { title: "bar", id: 2}
]</textarea>
<textarea id="code"><h1>Posts</h1>
<ul>
{% for item in items %}
  <li>{{ item.title }}</li>
{% else %}
  <li>This would display if the 'item' collection were empty</li>
{% endfor %}
</ul></textarea></ul>
<pre id="output">hello nunjucks</pre>
<!-- partial -->
  <script src='https://mozilla.github.io/nunjucks/bower_components/jquery/jquery.min.js'></script>
<script src='https://mozilla.github.io/nunjucks/files/nunjucks.js'></script><script  src="{{site.url}}{{site.baseurl}}/external_assets/nunjuck-online/script.js"></script>
