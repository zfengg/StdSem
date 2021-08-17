+++
title = "test"
tags = ["test"]
hasmath = true
+++

$$ \frac{1}{2} $$ 

# A collapsible section with markdown
<!-- <details>
  <summary>Click to expand!</summary>
  ## Heading
  1. A numbered
  2. list
     * With some
     * Sub bullets
</details> -->


$$ \frac{101}{2} $$


\begin{align}
\dfrac{101}{2}
\end{align}


\begin{align}
  \exp(i\pi)+1 &= 0\\
  1+1 &= 2
\end{align}



@@collapsible
button
@@collapse-content
$$ E = m C^2 $$
@@
@@


<!-- collapsible block -->
<!-- \newcommand{\collapsible}[2]{
  @@collapsible
    @@collapsible-header #1 @@
    @@collapsible-content #2 @@
  @@
} -->

- \collapsible{header}{aa feafhea faf ehfaifhoeaf afeafhefa  efafheaofhe a feaief $ \frac{1}{2} $}
  - \collapsible{Summary}{$$ \frac{1}{2} $$}
\collapsible{header}{$$ \frac{1}{2} $$}
\collapsible{header}{$$ \frac{1}{2} $$}