---
layout: page
title: Blogs
---

I would love to share my lessons learnt with everyone here. This page will have blogs from diverse topics written by me and my friends. I would try my best to keep this page updated and maintain high quality and enjoyable content.

## C++

1. [Intermediate C++: Speeding up iostreams in C++](https://dasayan05.github.io/blog-tut/2019/04/06/speeding-up-iostreams-in-c++.html)
	
	*6th April 2019*

	We often come across situations where we need to process large files. Clearly interactive input-output is not helpful in all situations. It is a common practice to use cin and cout for input-output in C++ because of it’s flexibility and ease of use. But there is quite a big problem with iostream, which is by default, much slower than standard IO functions in other languages. In this tutorial, I will quantitatively demonstrate the slowness of iostreams in C++, explain some of the reasons for its slowness and share some tips to speed it up.

1. [Intermediate C++: Static and Dynamic linking](https://dasayan05.github.io/blog-tut/2019/01/05/linking-in-c++.html)

	*5th January 2019*

	C++ is a general-purpose, multi-paradigm programming language designed/developed by Bjarne Stroustrup which alongwith C, forms the backbone of majority of the programming industry today. A very important concept to be grasped by beginner programmers is the idea of “linking”. Linking basically refers to the process of bundling library code into an archive and use it later when necessary. It turns out to be an idea that is used extensively in production. The following article aims at presenting a broad view of “linking”.

## Gaming

1.	[Optimizing Dota 2 Performance on Linux with Vulkan on NVIDIA Graphics Cards]({{ site.baseurl }}{% post_url 2019-06-25-OptimizeDota %})

	*25th June 2019*

	Gaming on the **Linux** platform is extremely underrated and is often completely *rejected* by most gamers when it comes to high-FPS gaming. In this blog, I will present a stark contrast to the above idea. The game of [Dota 2](https://www.dota2.com/play/) does not need any introduction, and being a Linux enthusiast and a Dota addict, I'd love to share a few simple tips on optimizing Dota 2 performance on Linux.

	*Spoilers:* As I will demonstrate, after following the steps given in this blog you should have a significantly higher FPS compared to Dota running on Windows on identical hardware (about 30-40 FPS, depending on your graphics card).

## Linux

1.	[The systemd Controversy]({{ site.baseurl }}{% post_url 2019-08-14-TheSystemdControversy %})

	*14th August 2019*

	*By* [Spandan Ghosh](https://www.linkedin.com/in/spandanghosh2)

	The Linux world has changed rapidly in the past few years. It has become beginner friendly with proper hardware support requiring little or no technical knowledge to get up and running. There are several Linux(more accurately GNU/Linux) distributions out there Debian, Fedora , Arch Linux, Gentoo, Solus, Clear OS, Gentoo and many more. One thing that most of these distros have in common is *Systemd* (Gentoo primarily supports and ecourages OpenRC but has systemd profiles as well). My 11 years of linux usage has taught me to both respect and hate systemd and today hopefully I can convince you of the same. While I myself am not a big fan of systemd I will try to (if I can) be as objective as possible so as to not enforce an opinion on you.