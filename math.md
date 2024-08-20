## Math basics for Physical quantities

Using [MathJax](https://www.mathjax.org/) that [math stackoverflow](https://math.meta.stackexchange.com/questions/5020/mathjax-basic-tutorial-and-quick-reference) uses.

___
Observable
$ \Bbb x \in \Bbb X = \{ x \in \Bbb R : K_\Bbb X(x) = k \in \Bbb N^+ \} $
$ x_k := K_\Bbb X^{-1}(k) $

$\Bbb x, \Bbb y \in \Bbb X$

$ \Bbb x = \Bbb y \text{ iff } K_\Bbb X(\Bbb x) = K_\Bbb X(\Bbb y)$

$\Bbb x \pm \Bbb y \in \Bbb X \text{ iff } \exists K_\Bbb X(\Bbb x \pm \Bbb y) \in \Bbb N^+$

$a \in \Bbb R$

$ a\Bbb x \in \Bbb X \text{ iff } \exists K_\Bbb X(a\Bbb x) \in \Bbb N^+ $

$\Delta\Bbb x_k := \Bbb x_k - \Bbb x_{k-1}$

$\delta\Bbb X := \inf( \{ \Delta\Bbb x_k \} )$ need not belong to $\Bbb X$.
___
$\Bbb x \in \Bbb X,\; \Bbb y \in \Bbb Y$

$\Bbb f_{\Bbb X}: \Bbb x \rightarrow \Bbb y = \Bbb f_{\Bbb X}(\Bbb x)$

$\mathrm{domain}( \Bbb f_{\Bbb X} ) \subseteq \Bbb X,\;
\mathrm{range}( \Bbb f_{\Bbb X} ) \subseteq \Bbb Y$

___
$\Bbb x, \Bbb y \in \Bbb X,\; \Bbb a \in \Bbb A $

$(\;\cdot\;,\; \cdot\;)_{\Bbb X}: (\Bbb x, \Bbb y) \rightarrow
\Bbb a = (\Bbb x, \Bbb y)_{\Bbb X} $ an inner product.

$\mathrm{domain}\big( (\;\cdot\;,\; \cdot\; )_{\Bbb X}\big) \subseteq
\Bbb X \cup \{\delta\Bbb X\}$

$\mathrm{range}\big( (\;\cdot\;,\; \cdot\; )_{\Bbb X}\big) \subseteq
\Bbb A \cup \{\delta\Bbb A\}$

$|\cdot|_{\Bbb X}: \Bbb x \rightarrow \sqrt{ (\Bbb x, \Bbb x) } =
|\Bbb x|_{\Bbb X}$

$\mathrm{domain}\big(|\cdot|_{\Bbb X}\big) \subseteq
\Bbb X \cup \{\delta\Bbb X\}$

$\{ |x|: x \in \Bbb X \cup \{\delta\Bbb X\} \} \subseteq
\mathrm{range}\big(|\cdot|_{\Bbb X}\big) \subseteq \Bbb R$

___
$\text{If } \Bbb a \in \Bbb A \cup \{\delta \Bbb A\} \subseteq \Bbb C \text{ then either}$
$\Bbb a = \delta \Bbb A \text{ or } K_\Bbb A(\Bbb a) \in \mathrm N^+$

$\sqrt{\Bbb a} \in \{ x: x \in \Bbb X \cup \{\delta\Bbb X\} \} \text{ iff }$
$\sqrt{\Bbb a} = \delta{\Bbb X} \text{ or }
K_\Bbb X(\sqrt{\Bbb a}) \in \mathrm N^+$

___
$ \Bbb c, \Bbb x \in \Bbb X \subseteq \Bbb R,\; \Bbb y \in \Bbb Y \subseteq \Bbb R $

$ \lim_{\Bbb x \to \Bbb c}^{\Bbb X, \Bbb Y} \Bbb f_{\Bbb X}(\Bbb x) = \Bbb y \text{ iff } $
$ \forall \varepsilon \gt \delta \Bbb Y\; \exists \delta \gt \delta \Bbb X \text{  s.t. }
|\Bbb f(\Bbb x) - y|_{\Bbb Y} \lt \varepsilon\; \forall\; 0 \lt
|\Bbb x - c|_{\Bbb X} \lt \delta $

$ f'_{\Bbb X}(x) := \lim_{\Bbb h \to \delta \Bbb X}^{\Bbb X, \Bbb Y}
\frac{f_{\Bbb X}(x + h) - f_{\Bbb X}(x)}{h} $

$ \mathrm{range}\big( f'_{\Bbb X} ) = \{ z: z \in \Bbb Z \cup \{\delta\Bbb Z\} \} $

$ \delta\Bbb Z = \frac{\delta\Bbb Y}{\delta\Bbb X} $
___

# 4.15.2023

Observable
$ x \in \Bbb X = \{ x \in \Bbb C : K_\Bbb X(x) = k \in \Bbb N_\Bbb X \}, \Bbb N_\Bbb X \subseteq \Bbb N^+ $

$ K_\Bbb X^{-1}(k) := \Bbb X_k = \{ x \in \Bbb X: K_\Bbb X(x) = k \} $

$ \Bbb X_1 \cup \Bbb X_2 \cup ... = \Bbb X $

$ x, y \in \Bbb X $

$ x =_\Bbb X \Bbb y \text{ iff } K_\Bbb X(\Bbb x) = K_\Bbb X(\Bbb y) $

$ z_1 =_\Bbb X z_2 \, \forall z_1, z_2 \in \Bbb X_k $

$ x \pm y \in \Bbb X \text{ iff } \, \exists K_\Bbb X(x \pm y) \in \Bbb N_\Bbb X $

$ a \in \Bbb C $

$ ax \in \Bbb X \text{ iff } \, \exists K_\Bbb X(a\Bbb x) \in \Bbb N_\Bbb X $
___

$ x \in \Bbb X,\; y \in \Bbb Y $

$ \Bbb f_{\Bbb X}: x \rightarrow y = \Bbb f_{\Bbb X}(x) $

$ \mathrm{domain}( \Bbb f_{\Bbb X} ) \subseteq \Bbb X,\; \mathrm{range}( \Bbb f_{\Bbb X} ) \subseteq \Bbb Y $
___

$ x, y \in \Bbb X,\; a \in \Bbb A \subseteq \Bbb C $

$ (\;\cdot\;,\; \cdot\;)_{\Bbb X}: (x, y) \rightarrow \Bbb a = (x, y)_{\Bbb X} $ an inner product.

$ \mathrm{domain}\big( (\;\cdot\;,\; \cdot\; )_{\Bbb X}\big) =
\Bbb X $

$ \mathrm{range}\big( (\;\cdot\;,\; \cdot\; )_{\Bbb X}\big) \subseteq \Bbb A $
___

$ x \in \Bbb X,\; m \in \Bbb M_\Bbb X \subseteq \Bbb R $

$ |\cdot|_{\Bbb X}: x \rightarrow \sqrt{ (x, x) } = m = |x|_{\Bbb X} $

$ \mathrm{domain}\big(|\cdot|_{\Bbb X}\big) = \Bbb X $

$ \mathrm{range}\big(|\cdot|_{\Bbb X}\big) \subseteq \Bbb M_\Bbb X $

$ \Bbb X_s \subseteq \Bbb X $

$ |\Bbb X_s|:= \{ m \in \Bbb M_\Bbb X: m = |x|, x \in \Bbb X_s \} $

$ \delta\Bbb X_k := \inf(|\Bbb X_k|) \in \Bbb R $ need not belong to $ |\Bbb X_k| $

$ \delta\Bbb X := \inf( \{ |\delta\Bbb X_k - \delta\Bbb X_{k-1}| \} )$ need not belong to $\Bbb X $.
___

$ \Bbb c, \Bbb x \in \Bbb X \subseteq \Bbb C,\; \Bbb y \in \Bbb Y \subseteq \Bbb C $

$ \lim_{\Bbb x \to \Bbb c}^{\Bbb X, \Bbb Y} \Bbb f_{\Bbb X}(\Bbb x) = \Bbb y \text{ iff } $
$ \forall \varepsilon \gt \delta \Bbb Y\; \exists \delta \gt \delta \Bbb X \text{  s.t. }
|\Bbb f(\Bbb x) - y|_{\Bbb Y} \lt \varepsilon\; \forall\; 0 \lt
|\Bbb x - c|_{\Bbb X} \lt \delta $

$ f'_{\Bbb X}(x) := \lim_{\Bbb h \to \delta \Bbb X}^{\Bbb X, \Bbb Y}
\frac{f_{\Bbb X}(x + h) - f_{\Bbb X}(x)}{h} $

$ \mathrm{range}\big( f'_{\Bbb X} ) = \{ z: z \in \Bbb Z \cup \{\delta\Bbb Z\} \} $

$ \delta\Bbb Z = \frac{\delta\Bbb Y}{\delta\Bbb X} $ if $ \delta\Bbb X \neq 0 $

___

$\delta\Bbb X := \inf( \{ \Delta\Bbb x_k \} )$ need not belong to $\Bbb X$.
___

# 8.19.2024

Observable
$ \Bbb x \in \Bbb X = \{ x \in \Bbb C : K_\Bbb X(x) = k \in \Bbb N_\Bbb X \}, \Bbb N_\Bbb X \subseteq \Bbb N^+ $

$d\Bbb X $ := A differential measure of an observable. Could be an observable, but not necessarily.

$\Delta\Bbb x_k := \Bbb x_k - \Bbb x_{k-1}$

$\delta\Bbb X := \inf( \{ \Delta\Bbb x_k \} )$ need not belong to $\Bbb X$. = The absolute limit of resolution.

$ \Bbb Position(\Bbb X) = (\Bbb X, d\Bbb X, \delta\Bbb X) $