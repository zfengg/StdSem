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


## insert `.md`
- 8/17 Tuesday \venue{Zoom}\\
  **Caiyun Ma**
  - Feng, D.-J. *\href{Lyapunov exponents for products of matrices and multifractal analysis. I. Positive matrices}{https://link.springer.com/content/pdf/10.1007/BF02783432.pdf}.* Israel J. Math., 2003, 138, 353-376.
  - \collapsible{Summary}{
    To be announced.
    \\
    Just random test...  **hello world** blabla... $ \Sigma = \{1,\ldots,m\}^{\mathbb{N}}$
    @@no-number
    \begin{align}
      \pi & = 3
      + \frac{\displaystyle 1}{\displaystyle 7
      + \frac{\displaystyle 1}{\displaystyle 15
      + \frac{\displaystyle 1}{\displaystyle 1
      + \frac{\displaystyle 1}{\displaystyle 292
      + \frac{\displaystyle 1}{\displaystyle \dots 
      }}}}}\\
     f(x) & = \begin{cases} \exp(\frac{1}{(x-a)(x-b)}) & x \in (a, b) \subset\mathbb{R} \\ 0 & otherwise \end{cases}
    \end{align}
    @@
    \figenv{Fig 1: continued fraction of Pi }{/assets/img/cfPi.png}{width:100%}
    Let $ (X, \mathscr{B}, \mu, T) $ be a measure-preserving system.
    }
- 8/17 Tuesday \venue{Zoom}\\
  **Caiyun Ma**
  - Feng, D.-J. *\href{Lyapunov exponents for products of matrices and multifractal analysis. I. Positive matrices}{https://link.springer.com/content/pdf/10.1007/BF02783432.pdf}.* Israel J. Math., 2003, 138, 353-376.
  - \textinput{summaries/2021/0817.md}


  - \collapsible{Summary}{\textinput{summaries/sample.md}}

  
- \collapsible{Summary}{\inputsmmry{sample.md}}

\textinput{summaries/sample.md}
\inputsmmry{sample.md}
