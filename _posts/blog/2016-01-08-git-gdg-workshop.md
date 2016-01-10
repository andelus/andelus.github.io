---
layout: post
title:  "Git workshop GDG Tlemcen"
date:   2016-01-08 18:03:02 +0100
categories: blog
tags: git
author: Tasfaout Yassine
image: "/assets/works/workshop-git.png"
comments: true
---

At some point of your **development career**, you will realize that git is not just a good skill to learn. But a **must have** for any developer.

I did this workshop in purpose of introducing **Git** to our **Google Developer Group Tlemcen** new members.

**Here is what we covered so far:**

1. Brief Introduction of **Git**.
2. Installing **Git** in different **Operating Systems**.
3. **Git** Global configuration.
4. Initializing repository.
5. How to commit your changes.
6. How to see and manage history.
7. Branches.

**What was not covered :**

1. Setting up your remote repository at (Github and Bitbucket) & (SSH Configuration)
2. Issues
3. Fork & Pull requests
4. GUI Git clients.

**What we need to get started**

* Terminal :black_medium_square:
* Code Editor **Atom** or **Sublime Text**
* Cup of coffee :coffee:

**Let's Get Started**

First thing to do after installing **Git** instructions [Here](https://git-scm.com/).

* **Git** Global configuration:

{% highlight sh %}
$ git config --global user.email "youremail@example.com"
$ git config --global user.name "your name"
{% endhighlight %}

* Initializing repository:

**cd** into you project folder. To initialize **Git** repository of your project just type the following command line:

{% highlight sh %}
$ cd project_folder
$ git init
#=> Initialized empty Git repository in project_folder
{% endhighlight %}
