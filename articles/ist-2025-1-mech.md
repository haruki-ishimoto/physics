---
title: "東京科学大学院試2025-1 力学"
emoji: "⚛️"
type: "idea" # tech: 技術記事 / idea: アイデア
topics: ["東工大", "東京工業大学", "東京科学大学", "院試", "統計力学"]
published: true
---

# (1)
$$
\rho = \frac{m}{\pi a^2 h}
$$

$$
\mathrm{d} m = \rho \mathrm{\,d} V = \rho \cdot r \mathrm{\,d}r \mathrm{\,d}\phi \mathrm{\,d}z
$$

$$
\begin{aligned}
I
&\equiv \int r^2 \mathrm{\,d}m \\
&= \rho \int_0^a r^3 \mathrm{\,d}r \int_0^{2\pi} \mathrm{\,d}\phi \int_0^h \mathrm{\,d}z \\
&= \rho \frac{a^4}4 \cdot 2\pi \cdot h \\
&= \frac12 ma^2
\end{aligned}
$$

# (2)
$$
\bm{R} = R \begin{pmatrix} \cos\phi \sin\theta \\ \sin\phi \sin\theta \\ \cos\theta \end{pmatrix}
$$

$$\begin{aligned}
\bm{N} 
&= \bm{R} \times \bm{F} \\
&= R \begin{pmatrix} \cos\phi \sin\theta \\ \sin\phi \sin\theta \\ \cos\theta \end{pmatrix}
      \times \begin{pmatrix} 0 \\ 0 \\ -mg \end{pmatrix} \\
&= mgR\sin\theta \begin{pmatrix} -\sin\phi  \\ \cos\phi\\ 0 \end{pmatrix}
\end{aligned}$$

# (3)
$$
\bm{L} = I \omega \frac{\bm{R}}{R} = I\omega\begin{pmatrix} \cos\phi \sin\theta \\ \sin\phi \sin\theta \\ \cos\theta \end{pmatrix}
$$


$$
\bm{L} \equiv \bm{R} \times \bm{p} \implies 
\dot{\bm{L}} = \dot{\bm{R}} \times m\dot{\bm{R}} + \bm{R} \times \dot{\bm{p}} = \bm{R} \times \bm{F} \equiv \bm{N}
$$


# (4)
$$
\dot{L} = I \omega \sin\theta \begin{pmatrix} -\sin\phi  \\ \cos\phi\\ 0 \end{pmatrix} \dot{\phi}
$$

$$
\therefore I\omega \dot{\phi} = mgR \iff \dot{\phi} = \frac{mgR}{I\omega}
$$
