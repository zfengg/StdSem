+++
# Franklin global vars
author = "Student Analysis Group"
mintoclevel = 2
div_content = "franklin-content"
ignore = ["node_modules/"]
prepath = ""
# RSS
generate_rss = false
website_title = "Student Seminars"
website_descr = "A series of seminars on analysis @ cuhk"
website_url   = "https:/stdsem.me"
+++

<!-- ------------------------ global latex commands ------------------------ -->
<!-- math -->
\newcommand{\R}{\mathbb R}
\newcommand{\scal}[1]{\langle #1 \rangle}
\newcommand{\nalign}[1]{@@no-number \begin{align}#1\end{align}@@}

<!-- envs -->
\newcommand{\href}[2]{~~~<a href="!#2" target="_blank">#1</a>~~~}
\newcommand{\venue}[1]{~~~<span class="seminar-venue">#1</span>~~~}
\newcommand{\venuelink}[2]{~~~<span class="seminar-venue">~~~\href{#1}{#2}~~~</span>~~~}
\newcommand{\inputsmmry}[1]{\textinput{summaries/!#1}}
\newcommand{\inputoutln}[1]{\textinput{outlines/!#1}}
\newcommand{\collapsible}[2]{
  @@collapsible
    @@collapsible-header #1 @@
    @@collapsible-content #2 @@
  @@
}
\newcommand{\figenv}[3]{~~~
<figure style="text-align:center;">
<img src="!#2" style="padding:0;#3" alt="#1"/>
<figcaption>#1</figcaption>
</figure>
~~~}
