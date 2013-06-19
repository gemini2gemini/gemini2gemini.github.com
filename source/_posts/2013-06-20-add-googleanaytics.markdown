---
layout: post
title: "Octopressに、Google Anayticsを追加"
date: 2013-06-20 00:18
comments: true
categories: [Octopress,Google Analytics]
---

### Octopressに、Google Analyticsを追加

Github pagesを使って、ブログを書いていくことにしたので、Octopressに、Google Analyticsを追加することにした。

追加方法

1:　Octopress内にある`_config.yml`の中にある Google Analyticsのトラッキングコードを記載する部分に、トラッキングコードを追加。

{% highlight ruby %}
# Google Analytics
google_analytics_tracking_id: UA-XXXXXXXX-X
{% endhighlight %}

2:　通常通り、自動生成とデプロイを行う

{% highlight ruby %}
rake gen_deploy
{% endhighlight %}

3:　Githubにコミットしておく

{% highlight ruby %}
git push origin source
{% endhighlight %}