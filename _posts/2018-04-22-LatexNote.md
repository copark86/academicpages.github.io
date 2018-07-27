---
title: 'Latex Note'
date: 2018-04-22
permalink: /post/2018-04-22-LatexNote
tags:
  - latex
---


Upper & underbrace
-------------------------------
	\usepackage{amsmath}	
	
	z = \overbrace{
	\underbrace{x}_\text{real} +
	\underbrace{iy}_\text{imaginary}
	}^\text{complex number}
  
<div>$z = \overbrace{\underbrace{x}_\text{real} +\underbrace{iy}_\text{imaginary}}^\text{complex number}$</div>


Parentheses
-------------------------------
    \Biggl(\biggl(\Bigl(\bigl((x)\bigr)\Bigr)\biggr)\Biggr)
	
<div>$\Biggl(\biggl(\Bigl(\bigl((x)\bigr)\Bigr)\biggr)\Biggr)$</div>
<div>$\Biggl[\biggl[\Bigl[\bigl[[x]\bigr]\Bigr]\biggr]\Biggr]$</div>

Markdown
-------------------------------
    $\sum_{i=0}^n i^2 = \frac{(n^2+n)(2n+1)}{6}$


<div>$\sum_{i=0}^n i^2 = \frac{(n^2+n)(2n+1)}{6}$</div>

    $$\sum_{i=0}^n i^2 = \frac{(n^2+n)(2n+1)}{6}$$
 
<div>$$\sum_{i=0}^n i^2 = \frac{(n^2+n)(2n+1)}{6}$$</div>


Cancel
-------------------------------
    \usepackage{cancel}
    \cancelto{0}{x} 
    \cancel{x} 
    
<div>$\cancelto{0}{x} $</div>
<div>$\cancel{x} $</div>


Two lined title
-------------------------------

	\title{Project Proposal:  \protect\\ Deep Map Representation }


Figure size with includegraphics
-------------------------------
	\begin{figure}[t]
	\centering{
	\includegraphics[width=240,height=.15\textheight]{figures/PatchSift.pdf}
	}
	\caption{	
	}
	\label{fig:block}
	\end{figure}
	
	

Figure size with input
-------------------------------	
	\begin{figure}[t]
	\centering{
	\def\svgwidth{85mm}
	\input{figures/projected_patch.pdf_tex}
	}
	\caption{
	}
	\label{fig:maps}
	\end{figure}



Figure others
-------------------------------	
Figure top

	\begin{figure}[t]
	\end{figure}
	
Figure bottom and multi colomn	

	\begin{figure*}[b]
	\end{figure*}
	
	
Citation arrangement
-------------------------------	
	\usepackage{balance}
