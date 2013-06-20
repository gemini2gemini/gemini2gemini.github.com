---
layout: post
title: "Google-OpenID"
date: 2013-06-20 20:19
comments: true
categories: [OpenID,Google]
---

### GoogleのOpenIDについて

某サイトで、OpenIDでログインというのがあり、GoogleアカウントでもOpenID使えるよ、ということが載っていたので、自分のOpenIDを調べる方法を探したけど、それらしき記事がすぐに見つからなかったのでメモ。

OpenIDというと、それぞれ違うIDがあり、Googleのアカウント情報の中にあると思っていたのですが、全然違いました。知らないことが多いが、本当に知らないと辛い・・・

ということで、以下が GoogleのOpenID。これで、Googleアカウントにログインしていれば、紐づけてもらえます。

{% highlight ruby %}
# Google OpenID
google.com/accounts/o8/id
{% endhighlight %}