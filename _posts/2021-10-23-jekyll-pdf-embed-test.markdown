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

{% highlight ruby %}
{% raw %}
{% pdf "https://mihajlonesic.gitlab.io/files/loremipsum.pdf" no_link height=300px %}
{% endraw %}
{% endhighlight %}

{% pdf "https://mihajlonesic.gitlab.io/files/loremipsum.pdf" no_link height=300px %}