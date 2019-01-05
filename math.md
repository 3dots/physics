

Observable $\Bbb x \in \Bbb X = 
\{ x \in \Bbb C : K_\Bbb X(x) = k \in \Bbb N^+ \}$
$x_k := K_\Bbb X^{-1}(k)$

$\Bbb x, \Bbb y \in \Bbb X$
$ \Bbb x = \Bbb y \text{ iff } K_\Bbb X(\Bbb x) = K_\Bbb X(\Bbb y)$
$\Bbb x \pm \Bbb y \in \Bbb X \text{ iff  } \exists K_\Bbb X(\Bbb x \pm \Bbb y)$

$a \in \Bbb R$
$a\Bbb x \in \Bbb X \text{ iff  } \exists K_\Bbb X(a\Bbb x)$

$\Delta\Bbb x_k := \Bbb x_k - \Bbb x_{k-1}$
$\delta\Bbb X := \inf(\{ \Delta\Bbb x_k \})$ need not belong to $\Bbb X$.
___
$\Bbb x \in \Bbb X,\; \Bbb y \in \Bbb Y$
$\Bbb f_{\Bbb X}: \Bbb x \rightarrow \Bbb y = \Bbb f_{\Bbb X}(\Bbb x)$
$\mathrm{domain}(\Bbb f_{\Bbb X}) \subseteq \Bbb X,\; 
\mathrm{range}(\Bbb f_{\Bbb X}) \subseteq \Bbb Y$

___
$\Bbb x, \Bbb y \in \Bbb X,\; \Bbb a \in \Bbb A$

$(\;\cdot\;,\; \cdot\;)_{\Bbb X}: (\Bbb x, \Bbb y) \rightarrow 
\Bbb a = (\Bbb x, \Bbb y)_{\Bbb X}$
$\mathrm{domain}\big( (\;\cdot\;,\; \cdot\; )_{\Bbb X}\big) \subseteq 
\Bbb X \cup \{\delta\Bbb X\}$
$\mathrm{range}\big( (\;\cdot\;,\; \cdot\; )_{\Bbb X}\big) \subseteq 
\Bbb A \cup \{\delta\Bbb A\}$

$|\cdot|_{\Bbb X}: \Bbb x \rightarrow \sqrt{ (\Bbb x, \Bbb x) } = 
|\Bbb x|_{\Bbb X}$
$\mathrm{domain}\big(|\cdot|_{\Bbb X}\big) \subseteq 
\Bbb X \cup \{\delta\Bbb X\}$
$\mathrm{range}\big(|\cdot|_{\Bbb X}\big) \subseteq 
\Bbb M_{\Bbb X},\; \Bbb X \cup \{\delta\Bbb X\} \subseteq \Bbb M_{\Bbb X}$

$\text{If } \Bbb a \in \Bbb A \cup \{\delta \Bbb A\} \text{ then either}$
$\Bbb a = \delta \Bbb A \text{ or } K_\Bbb A(\Bbb a) \in \mathrm N^+$
$\sqrt{\Bbb a} \in \Bbb X \cup \{\delta\Bbb X\} \text{ iff }$
$\sqrt{\Bbb a} = \delta{\Bbb X} \text{ or } 
K_\Bbb X(\sqrt{\Bbb a}) \in \mathrm N^+$

___
$\Bbb c, \Bbb x \in \Bbb X,\; \Bbb y \in \Bbb Y$
$\lim_{\Bbb x \to \Bbb c}^{\Bbb X, \Bbb Y} \Bbb f(\Bbb x) = \Bbb y \text{ iff}$
$\forall \varepsilon \gt \delta \Bbb Y\; \exists \delta \gt \delta \Bbb X
\text{  s.t. } |\Bbb f(\Bbb x) - y|_{\Bbb Y} \lt \varepsilon\; \forall\;
|\Bbb x - c|_{\Bbb X} \lt \delta$
