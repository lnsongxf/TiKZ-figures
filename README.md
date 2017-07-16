# TiKZ-figures
Variety of figures using the TikZ package used in papers:
<ul>
  <li> <b> ABM - </b> A crisis of confidence: The counterparty-liquidity risk nexus in an agent-based network model of the interbank market </li>
  <li> <b>NDSGE -  </b> Assessing the role of interbank network structure in business and financial cycle analysis 
 </ul>
 
 Currently configured as a standalone document class (for direct conversion to pdf using pdftex). In order to include in working documents, transfer \usepackage and \usetikzlibrary commands to document preamble and remove \documentclass, \begin{document}, \end{document} commands. The following latex code can then be used:
 
\begin{figure}[h!]
  \begin{center}
    \input{Path to figure (relative or absolute)}
    \caption{Figure caption}
  \end{center}
  \label{label for cross-referencing in document}
\end{figure}
 
 <a rel="license" href="http://creativecommons.org/licenses/by/2.5/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by/2.5/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by/2.5/">Creative Commons Attribution 2.5 Generic License</a>.

