---
layout: post
title: "hello world"
description: ""
category: 
tags: [hello,world]
excerpt: hello world
---
{% include JB/setup %}

{% highlight ruby %}
	def show
	  @widget = Widget(params[:id])
	  respond_to do |format|
	    format.html # show.html.erb
	    format.json { render json: @widget }
	  end
	end
{% endhighlight %}