# Numeri complessi
> [!formule]
> $z=x+iy\in \mathbb{C}$
> $\bar{z}=x-iy$
> $r=|z|=\sqrt{x^{2}+y^{2}}\in \mathbb{R}$
> $$\begin{flalign}\varphi=\mathrm{arg}(z)=\arctan\left( \frac{y}{x} \right)\in \mathbb{R} &&\end{flalign}$$
> $z=r(\cos(\varphi)+i\sin(\varphi))=re^{i\varphi}$
> Formule di Elulero
> $$\begin{flalign}\cos(\varphi)=\frac{e^{i\varphi}+e^{-i\varphi}}{2},\;\sin(\varphi)=\frac{e^{i\varphi}-e^{-i\varphi}}{2i} &&\end{flalign}$$

## Funzioni complesse
> [!definizione]
> $S(v):D\to \mathbb{C}$, $D\subset \mathbb{N},\mathbb{R},\mathbb{C},\dots$
> $S(v)=|S(v)|e^{i\cdot\mathrm{arg}(S(v))}$

> [!formule]
> $|S(v)|=\sqrt{\mathrm{Re}(S(v))^{2}+\mathrm{Im}(S(v))^{2}}$
> $x=\mathrm{Re}(S(v)),\;y=\mathrm{Im}(S(v))$
> $$\begin{flalign}\mathrm{arg}(S(v))=\arctan\left( \frac{y}{x} \right) &&\end{flalign}$$

## Proprietà
> [!proprietà]
> Simmetria:
> - pari: $x(-t)=x(t)\;\forall t\in D$
> - dispari: $x(-t)=-x(t),\;\forall t\in D$
> Causale: se il segnale è nullo $\forall t<t_{0}$
> $$\begin{flalign}x(t)=\begin{cases}
> x_{S}(t),&t\geq t_{0} \\
> 0,&t<t_{0}
> \end{cases} &&\end{flalign}$$
> In $t_{0}$ si verifica un evento, causa del segnale, che non può esistere prima di tale istante

## Funzioni notevoli
> [!definizione] Gradino unitario
> Dispari
> ($t_{0}=0$)
> $$\begin{flalign}u(t)=1(t)=\begin{cases}
> 1, &t\geq 0 \\
> 0, &t<0
> \end{cases}&&\end{flalign}$$

> [!definizione] Rettangolo simmetrico unitario
> Pari
> $$\begin{flalign}\Pi\left( \frac{t}{T} \right)=\Pi_{T}(t)=\begin{cases}
> 1, &|t|\leq \frac{T}{2} \\
> 0, &|t|> \frac{T}{2}
> \end{cases} &&\end{flalign}$$

> [!definizione] Segno
> Dispari
> $$\begin{flalign}s(t)=\begin{cases}
> +1, &t\geq 0 \\
> -1, &t<0
> \end{cases} &&\end{flalign}$$

> [!approfondimento] Relazione
> $$\begin{flalign}u(t)=\frac{1}{2}(s(t)+1) &&\end{flalign}$$

> [!definizione] Triangolo simmetrico unitario
> Pari
> $$\begin{flalign}\Lambda\left( \frac{t}{T} \right)=\Lambda_{T}(t)=\begin{cases}
> \frac{T/2-|t|}{T/2}, &|t|\leq \frac{T}{2} \\
> 0, &|t|> \frac{T}{2}
> \end{cases} &&\end{flalign}$$

> [!definizione] Sinc
> Pari
> $$\begin{flalign}\mathrm{sinc}(t)=\frac{\sin(\pi t)}{\pi t} &&\end{flalign}$$
> $\mathrm{sinc}(0)=1,\;\mathrm{sinc}(k\in \mathbb{\mathbb{Z}})=0$

> [!definizione] Impulso unitario
> Delta di Dirac, distribuzione
> $f$ funzione test, continua e integrabile, allora
> $$\begin{flalign}\delta(t):\forall f(t)\;\int_{-\infty}^{+\infty}f(t)\cdot\delta(t)\,dt=f(0) &&\end{flalign}$$
> $$\begin{flalign}\delta(t)=\lim_{ T \to 0 } \frac{1}{T}\Pi_{T}(t)=\begin{cases}
> +\infty,&t=0 \\
> 0,&t\neq 0
> \end{cases} &&\end{flalign}$$
> Ha area $1$:
> $$\begin{flalign}\int_{-\infty}^{+\infty}\delta(t)\,dt=1 &&\end{flalign}$$

> [!osservazione]
> Per ottenere ampiezze diverse da quella unitaria si moltiplica la funzione per il coefficiente desiderato
