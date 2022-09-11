Here we simulate our $N$-components cat teleamplifier ($N$-CT) device in various situations. Using this code, we created the numerical results and graphs given in our most recent paper in Ref. [1]. 

Our $N$-CT can perform noiseless linear amplification (NLA) with perfect fidelity, if the quantum state can be represented as follows
\begin{align}
    |\psi_{N,\alpha}\rangle \equiv \sum_{a=1}^{N} c_a |\omega_N^a\alpha\rangle, \quad \omega_N\equiv e^{-i2\pi/N}. 
\end{align}
This is a complete basis if $N\to\infty$. Our $N$-CT device is powered by the generalised cat resource state 
\begin{align}
    |😺_{N,\beta}\rangle \equiv \frac{1}{\sqrt{\mathcal{N}}}\sum_{b=1}^{N} \omega^b_N |\omega_N^b\beta\rangle. 
\end{align}
We can efficiently simulate these states using Xanadu's Strawberry Fields library via the bosonic backend [2]. We use the Fock tensorflow backend for simulating the $N$-CT device and entanglement distillation of a lossy two-mode squeezed vacuum (TMSV) state [3,4]. 

[1] Guanzon, J.J., Winnel, M.S., Lund, A.P. and Ralph, T.C., 2022. Perfect Fidelity Noiseless Linear Amplification and Loss-Tolerant Quantum Relay of Continuous-Variable States. (to be published) \
[2] Bourassa, J.E., Quesada, N., Tzitrin, I., Száva, A., Isacsson, T., Izaac, J., Sabapathy, K.K., Dauphinais, G. and Dhand, I., 2021. Fast simulation of bosonic qubits via Gaussian functions in phase space. PRX Quantum, 2(4), p.040315. \
[3] Killoran, N., Izaac, J., Quesada, N., Bergholm, V., Amy, M. and Weedbrook, C., 2019. Strawberry fields: A software platform for photonic quantum computing. Quantum, 3, p.129. \
[4] Bromley, T.R., Arrazola, J.M., Jahangiri, S., Izaac, J., Quesada, N., Gran, A.D., Schuld, M., Swinarton, J., Zabaneh, Z. and Killoran, N., 2020. Applications of near-term photonic quantum computers: software and algorithms. Quantum Science and Technology, 5(3), p.034010. \
