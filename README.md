# TiKZ-figures
Variety of figures using the TikZ package used in papers:
<ul>
  <li> <b> ABM - </b> A crisis of confidence: The counterparty-liquidity risk nexus in an agent-based network model of the interbank market </li>
  <li> <b>NDSGE -  </b> Assessing the role of interbank network structure in business and financial cycle analysis 
 </ul>
 
 Currently configured as a standalone document class (for direct conversion to pdf using pdftex). In order to include in working documents, transfer <font color="#0000FF">\usepackage<\font> and <font color="#0000FF">\usetikzlibrary<\font> commands to document preamble and remove <font color="#0000FF">\documentclass<\font>, <font color="#0000FF">\begin{document}<\font>, <font color="#0000FF">\end{document}<\font> commands. The following latex code can then be used:
 
\begin{figure}[h!]<br>
  \begin{center}<br>
    \input{<tt>Path to figure (relative or absolute)<\tt>}<br>
    \caption{<tt>Figure caption<\tt>}<br>
  \end{center}<br>
  \label{<tt>label for cross-referencing in document<\tt>}<br>
\end{figure}<br>
 
 <a rel="license" href="http://creativecommons.org/licenses/by/2.5/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by/2.5/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by/2.5/">Creative Commons Attribution 2.5 Generic License</a>.

