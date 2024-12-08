# Random Geometric Graphs

### Differences with Penrose monograph in little blue book 

### Questions for Penrose 

- Question 1:

How could we find the expected vertex degrees in $G(\mathcal{P}_n, r_n)$? We end up needing needing to exchange the limits in 
$$\sum_{m=0}^\infty \left[\mathbb{P}[N_n = m]\int_{x \in [0,1]^d} \lambda(B_x(r_n) \cap [0,1]^d)\mathrm{d}x\right]$$
An idea could be to use Tannery's theorem (a simple consequence of the dominated convergence theorem), which says if $a_k(n) \to b_k$ as $n \to \infty$ with $|a_k(n)| \leq M_k$ and $\sum_{k = 0}^\infty M_k < \infty$ we can write $$\lim_{n \to \infty} \sum_{k = 0}^\infty a_k(n) = \sum_{k = 0}^\infty b_k$$ 
If we try to use this theorem, what is $b_k$? It's going to be $0$ for finite $m$ as $e^n n^m/m! \to 0$ so would we 
write $b_k$ piecewise depending on $n$? But then $b_k$ depends on $n$, bad! So I assume this is illegal and we need another technique. 

- Question 2: 

I know my proof for $\mathbb{E}[\mathcal{E}_n] \sim n^2 r_d^n \theta_d / 2$ via the handshaking lemma is legal, 
but is there a proof using the total law for $\mathbb{E}[\mathcal{E}_n^\prime] \sim n^2 r_d^n \theta_d / 2$ thats legal?
 

### Misc thoughts

Sphere packing is just RGG theory with $r_n = \theta_d^{-1}$. Look at dense limit theory (via scary red book) with such $r_n$ and see if anything looks applicable. Taking limit as $d \to \infty$ may be structurually the same as fixing $d \geq 2$ and taking limit as $n(d) \to \infty$ in book theorems? Results hold for all $d \geq 2$ so this seems fine enough, not sure about the technicalities though needs some thought.  

Formally writing questions out (with intention of asking Penrose) is good. Have solved like half of them just by formalising it and reaslising I'm an idiot. 