---
layout: single
title:  "jekyll-pdf-embed test"
date:   2021-10-23 07:25:53 +0200
categories: jekyll plugin
---

{% highlight ruby %}
{% raw %}
{% pdf "https://mihajlonesic.gitlab.io/files/loremipsum.pdf" %}
{% endraw %}
{% endhighlight %}

{% pdf "https://mihajlonesic.gitlab.io/files/loremipsum.pdf" %}

---

Base URL must be present if `baseurl` is set in `_config.yml`.
In this example, `minimal-mistakes-pdf-example` is prepended to file location `/files/dummy.pdf`.


{% highlight ruby %}
{% raw %}
{% pdf "/minimal-mistakes-pdf-example/files/dummy.pdf" no_link height=300px %}
{% endraw %}
{% endhighlight %}

{% pdf "/minimal-mistakes-pdf-example/files/dummy.pdf" no_link height=300px %}