Bellman Equation devarition
$G_{t} = R_{t+1}+ G_{t+1}$$
$$\Rightarrow v_{\pi}(s) = \mathbb{E}\Big[R_{t+1}+\gamma G_{t+1}\vert S_{t} = s\Big]$$
$$\Rightarrow \mathbb{E} \Big[R_{t+1}\vert S_{t}=s\Big]+\gamma\mathbb{E}\Big[G_{t+1}\vert S_{t}=s\Big]$$
$$\Rightarrow \sum_a\pi(a\vert s) \sum_rp(r\vert s,a)r + \gamma\mathbb{E}\Big[G_{t+1}\vert S_{t}=s,S_{t+1=s'}\Big]p(s'\vert s$$
$$\Rightarrow \sum_a\pi(a|s)\sum_r p(r|s,a)r +γ\mathbb{E}\Big[G_{t+1}|S_{t+1}=s'\Big]p(s'|s)$$
$$\Rightarrow\sum_a\pi(a\vert s)\sum_rp(r\vert s,a)+\gamma\sum_{s'}v_{\pi}(s')\sum_a\pi(a\vert s)\sum_{s'}p(s'\vert s,a)$$
$$\Rightarrow r_{\pi}(s)+\gamma\sum_{s'}v_{\pi}(s')p(s'\vert s)$$
$$v_{\pi}(s)=\sum_a \pi(a\vert s)\sum_r p(r\vert s,a)+\gamma \sum_a \pi(a\vert s)\sum_{s'}v_{\pi}(s')p(s'\vert s,a)$$




<!--stackedit_data:
eyJoaXN0b3J5IjpbMTIxNzE3NTgxOCwtNzU2MDkxMTM0LDIwMT
g0ODUzNjAsLTMyMDU3ODc3NywzMTUwNzk4NDddfQ==
-->