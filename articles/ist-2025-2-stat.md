---
title: "東京科学大学院試2025-2 統計力学"
emoji: "⚛️"
type: "idea" # tech: 技術記事 / idea: アイデア
topics: ["東京科学大学", "院試", "2025", "統計力学"]
published: true
---

# (1)
(理想Fermi気体・理想Bose)の一粒子分布関数は

$$
f_{\mathrm{FD}} = \frac{1}{e^{\beta(\epsilon-\mu)} + 1}
, \quad
f_{\mathrm{FD}} = \frac{1}{e^{\beta(\epsilon-\mu)} - 1}
$$

で与えられる．

# (2)
一粒子エネルギーは

$$
\epsilon = \frac{\hbar^2 k^2}{2m}
,\quad
k^2 = \left(\frac{\pi}{L}\right)^2 \sum_{i=1}^{d} n_i^2
$$

と与えられる．状態数は

$$
N(\epsilon) \equiv \int dn = \frac{1}{8} \cdot \frac{4}{3} \pi n^3
$$
であるから，3次元理想気体の状態密度は

$$
D(\epsilon) = \frac{dN(\epsilon)}{d\epsilon}
$$

で求まる．
3次元 ($d=3$) の場合, 積分範囲は $n_i > 0$ の第1八分空間となるため, 半径 $n$ の球の体積を考えて

$$
\begin{aligned}
N(\epsilon) &= \frac{1}{8} \times \frac{4\pi}{3} n^3 \\
&= \frac{\pi}{6} \left( \frac{L}{\pi} \sqrt{\frac{2m\epsilon}{\hbar^2}} \right)^3 \\
&= \frac{V}{6\pi^2} \left( \frac{2m}{\hbar^2} \right)^{3/2} \epsilon^{3/2}
\end{aligned}
$$

となる（ただし $V = L^3$ とした）. したがって, 状態密度 $D(\epsilon)$ はこれを $\epsilon$ で微分して,

$$
\begin{aligned}
D(\epsilon) &= \frac{dN(\epsilon)}{d\epsilon} \\
&= \frac{V}{4\pi^2} \left( \frac{2m}{\hbar^2} \right)^{3/2} \epsilon^{1/2}
\end{aligned}
$$

を得る.
