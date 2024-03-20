An amino acid is made up of 4 bonds
consist of a central carbon($C_\alpha$)
a carboxyl group
a hydrogen
and an amine group

and a side chain that denotes which amino acid it is

```smiles
C(C(=O)O)(*)(N)
```
# Amino acid bonding
Amino acids bond by releasing the hydroxide from the carboxyl group with the Hydrogen from the amine group (releasing water) (This is called dehydration synthesis) and creating a covalent bond
With this bond the amino acids cannot rotate freely.
~~~smiles
NC(*)C(=O)(O)
~~~
![[Pasted image 20230924204926.png]]
# Amino acid Categories
## Hydrophobic
#### Alanine
Abr: Ala/A
```smiles
OC(=O)C(C)N
```
#### Valine
Abr: Val/V
```smiles
OC(=O)C(N)C(C)C
```
#### Isoleucine
Abr: Ile/I
```smiles
OC(=O)C(N)C(C)CC
```
#### Leucine
Abr: Leu/L
```smiles
OC(=O)C(N)CC(C)C
```
#### Methionine
Abr: Met/M
Start Codon
```smiles
OC(=O)C(N)CCSC
```
#### Phenylaline
Abr: Phe/F
```smiles
OC(=O)C(N)CC1=CC=CC=C1
```
#### Tyrosine
Abr: Tyr/Y
```smiles
OC(=O)C(N)CC1=CC(O)=CC=C1
```
#### Tryptophan
Abr: Trp/W
```smiles
OC(=O)C(N)CC1=CNC2=CC=CC=C231
```
## Positive
#### Arginine
Abr: Arg/R
```smiles
OC(=O)C(N)CCCNC(=[NH2])N
```
#### Histidine
Abr: His/H
```smiles
OC(=O)C(N)CC1N=CNC1
```
#TODO: This is supposed to have an additional double bond from the 1 carbon to the right
#### Lysine
Abr: Lys/K
```smiles
OC(=O)C(N)CCCC[NH3]
```
## Negative
- [ ] #### Aspartic Acid
Abr: Aps/D
```smiles
OC(=O)C(N)CC(=O)[O-]
```
#### Glutamic acid
Abr: Glu/E
```smiles
OC(=O)C(N)CCC([O-])=O
```
## Polar Uncharged
#### Serine
Abr: Ser/S
```smiles
OC(=O)C(N)CO
```
#### Threonine
Abr: Thr/T
```smiles
OC(=O)C(N)C(C)O
```
#### Asparagine
Abr: Asn/N
```smiles
OC(=O)C(N)CC(N)=O
```
#### Glutamine
Abr: Glu/Q
```smiles
OC(=O)C(N)CCC(N)=O
```
## Special
### Cysteine
~~~smiles
OC(=O)C(N)CS
~~~
#### Glycine
Abr: Gly/G
```smiles
OC(=O)C(N)
```
#### Proline
Abr: Pro/P
```smiles
OC(=O)C1NCCC1
```
```tikz
\begin{tikzpicture}
\orbital[pos = {(2,5.5)}]{lobe}
\node[above] at (2.5,6) {simple lobe};

\orbital[pos = {(0,5.5)}]{s}
\node[above] at (0,6) {s};

\orbital[pos = {(0,3)}]{px}
\node[above] at (0,4) {p$_x$};
\orbital[pos = {(2,3)}]{py}
\node[above] at (2,4) {p$_y$};
\orbital[pos = {(4,3)}]{pz}
\node[above] at (4,4) {p$_z$};

\orbital[pos = {(0,0)}]{-px}
\node[above] at (0,1) {-p$_x$};
\orbital[pos = {(2,0)}]{-py}
\node[above] at (2,1) {-p$_y$};
\orbital[pos = {(4,0)}]{-pz}
\node[above] at (4,1) {-p$_z$};

\orbital[pos = {(0,-3)}]{dxy}
\node[above] at (0,-2) {d$_{xy}$};
\orbital[pos = {(2,-3)}]{dxz}
\node[above] at (2,-2) {d$_{xz}$};
\orbital[pos = {(4,-3)}]{dyz}
\node[above] at (4,-2) {d$_{yz}$};

\orbital[pos = {(0,-5)}]{dx2y2}
\node[below] at (0,-6) {d$_{x^2-y^2}$};
\orbital[pos = {(2,-5)}]{dz2}
\node[below] at (2,-6) {d$_{z^2}$};
\end{tikzpicture}
```
