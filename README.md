# Functions in <img src="https://latex.codecogs.com/gif.latex?\dpi{100}&space;\fn_phv&space;\large&space;L^2(\mathbb{R})" title="\large L^2(\mathbb{R})" /> in terms of the Hermite basis
 The sequence in  <img src="https://latex.codecogs.com/gif.latex?\dpi{80}&space;\large&space;L^2(\mathbb{R})" title="\large L^2(\mathbb{R})" />  (defined for all reals) of Hermite polynomials can be orthonormalized, this constitutes a basis for the <img src="https://latex.codecogs.com/gif.latex?\dpi{80}&space;\large&space;L^2(\mathbb{R})" title="\large L^2(\mathbb{R})" />  space, then, in analogy with the n-dimensional case, any function f can be approximated by a linear combination of this sequence. This code graphs the approximation of various functions in terms of the 'Hermite basis' at <img src="https://latex.codecogs.com/gif.latex?\dpi{80}&space;\large&space;L^2(\mathbb{R})" title="\large L^2(\mathbb{R})" />.   If 
 
 <img src="https://latex.codecogs.com/gif.latex?f(x)&space;\in&space;L^2(\mathbb{R})\longrightarrow&space;f=\sum_{n=0}^{\infty}\sigma_n\psi_n\\" title="f(x) \in L^2(\mathbb{R})\longrightarrow f=\sum_{n=0}^{\infty}\sigma_n\psi_n\\" />

Where <img src="https://latex.codecogs.com/gif.latex?\psi_n" title="\psi_n" /> is the Hermite function of order n, given by:

<img src="https://latex.codecogs.com/gif.latex?\dpi{100}&space;\large&space;\psi_{n}(x)&space;=&space;\frac{1}{(2^{n}n!\sqrt{\pi})^{1/2}}e^{-\frac{x^2}{2}}H_{n}\quad&space;n=0,1,2..," title="\large \psi_{n}(x) = \frac{1}{(2^{n}n!\sqrt{\pi})^{1/2}}e^{-\frac{x^2}{2}}H_{n}\quad n=0,1,2..," />

The last one constitutes a total orthonormal sequence in <img src="https://latex.codecogs.com/gif.latex?\dpi{80}&space;\large&space;L^2(\mathbb{R})" title="\large L^2(\mathbb{R})" />, and the corresponding Hermite polynomial is given by:
<img src="https://latex.codecogs.com/gif.latex?H_0=1,&space;\quad&space;H_n&space;=&space;\sum_{j=0}^{N}n!\frac{(-1)^{j}2^{n-2j}}{j!(n-2j)!}x^{n-2j},&space;\quad&space;n=1,2,3,..." title="H_0=1, \quad H_n = \sum_{j=0}^{N}n!\frac{(-1)^{j}2^{n-2j}}{j!(n-2j)!}x^{n-2j}, \quad n=1,2,3,..." />

Using the properties of orthonormality of the sequence <img src="https://latex.codecogs.com/gif.latex?\dpi{80}&space;\large&space;\{\psi_n\}_n" title="\large \{\psi_n\}_n" /> we can obtain the coefficients of the combination by taking the inner product

<img src="https://latex.codecogs.com/gif.latex?\sigma_n&space;=&space;\langle&space;f,&space;\psi_n&space;\rangle&space;=&space;\int_{-\infty}^{\infty}&space;f&space;\frac{1}{(2^{n}n!\sqrt{\pi})^{1/2}}e^{-\frac{x^2}{2}}H_n&space;dx" title="\sigma_n = \langle f, \psi_n \rangle = \int_{-\infty}^{\infty} f \frac{1}{(2^{n}n!\sqrt{\pi})^{1/2}}e^{-\frac{x^2}{2}}H_n dx" />

With this information we can obtain graphical representations of the approximations.
