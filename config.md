<!--
Add here global page variables to use throughout your website.
-->
+++
author = "Student Analysis Group"
mintoclevel = 2

# Add here files or directories that should be ignored by Franklin, otherwise
# these files might be copied and, if markdown, processed by Franklin which
# you might not want. Indicate directories by ending the name with a `/`.
# Base files such as LICENSE.md and README.md are ignored by default.
ignore = ["node_modules/"]

# RSS (the website_{title, descr, url} must be defined to get RSS)
generate_rss = false
website_title = "Student Seminars"
website_descr = "A series of seminars on analysis @ cuhk"
website_url   = "https://tlienart.github.io/FranklinTemplates.jl/"
prepath = "StdSem"
+++

<!--
Add here global latex commands to use throughout your pages.
-->
\newcommand{\R}{\mathbb R}
\newcommand{\scal}[1]{\langle #1 \rangle}
\newcommand{\href}[2]{~~~<a href="!#2" target="_blank">#1</a>~~~}

\newcommand{\venue}[1]{~~~
<span class="seminar-venue-desktop">#1</span>
~~~
~~~
<span class="seminar-venue-mobile">#1</span>
~~~}

\newcommand{\timevenue}[2]{~~~
<span class="timevenue">
<span class="seminar-time"> #1</span> 
<span class="seminar-venue">#2</span>
<br>
</span> 
~~~}
