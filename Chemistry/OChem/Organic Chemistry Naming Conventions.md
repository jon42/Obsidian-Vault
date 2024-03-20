# IUPAC Naming Conventions
The IUPAC naming conventions is a naming convention that can describe any organic molecule
# Carbon Chains Prefixes
Carbon chains have prefixes that differ from the standard [[Naming Conventions]]. Specifically in the first few numbers. After the prefix there is a standard *-ane* that is added to the end.

| Prefix | Number |
| ---- | ---- |
| Meth- | 1 |
| Eth- | 2 |
| Prop- | 3 |
| But- | 4 |
| pent- | 5 |
| Hex- | 6 |
| Hept- | 7 |
| Oct- | 8 |
| Non- | 9 |
| Dec- | 10 |
When Dealing with a molecule the longest concurrent chain is where the number is derived from. 

*Example*:
```smiles
CCCC(CC)CCCCC
```
This would be a nonane with a ethyl group attached to it
# Adding Functional Groups
# Order the Functional group is added and numbering
If there is a functional group that is added on to a alkane the order in which they appear in the name is determined by what comes first in the alphabet. This only applies to the first letter of the functional group and not the first letter of the prefix. (ie: dibormo still come before cloro).

When adding a functional group the number of the carbon that it is on is placed before the functional group. The numbering of the carbons is based on which carbon has a functional group on it first. If there are multiple methods to orient a chain then the one with the lowest sum of prefix numbers is the correct answer.
## Carbon Chains
### [[Functional Group#Alkane]]
If there are no other functional groups the suffix just becomes ane. If there is a functional group attached to the main carbon chain there is an additional prefix for the functional group. If the functional group is another alkane, there is the number prefix followed by the length prefix with a yl at the end. Then the rest of the name follows.
**Example:**
```smiles
CCCC(CC)CCCC
```
The name of this molecule is 4-ethyloctane
### [[Functional Group#Alkene]]
If there is an alkene the suffix is changed to an ene. Before the ene there is a number indicating which carbon it is on
**Example:**
```smiles
CCCC=CC
```
Name: Hex-2-ene as the Alkene is on the 2nd carbon
**Example 2:** 
```smiles
CCC=CC=CCCC
```
non-3,5-ene
### [[Functional Group#Alkyne]]
If there is an alkyne in a molecule the suffix becomes -yne. Before the yne there is a number indicating which carbon it is on. 
**Example:**
```smiles
CCCC#CC
```
Name: hex-2-yne

### Both Alkene and Alkyne
If there is a alkene and alkyne the names of the the molecules will follow the same rules but it will be 
prefix-#-ene-#-yne
**Example:**
```smiles
CC=CC#CCC
```
## Other Functional groups
### [[Functional Group#Alcohol]]
For an alcohol functional group there is an ol suffix added. 
**Example:**
```smiles
CCCCO
```
Name: Butan-1-ol

### [[Functional Group#Alkyl Halide]]
If there is an alkyl halide the name has a cloro iodo floro or bromo before it. The standard.
**Example:**
```smiles
CC(Cl)C=C
```
this is 2-cloropropylene
**Example 2**
```smiles
CC(I)C=C
```
This is 2-Iodopropylene
### [[Functional Group#Ether]]
When naming an ether it splits the molecule where the ether is. The smaller part connected to the molecule
**Example**
```smiles
CCOCCCC
```
1-ethoxybutane
**Exampe**
```smiles
CC=CCOCCC
```
5-propoxybut-2-ene
### [[Functional Group#Ester]]
When an ester is added to a molecule an ate is added to the end of the molecule. The remaining attached to the oxygen is another sequence with a separate name.
**Example**
```smiles
CCC(=O)OC
```
This is methyl-propanoate
### [[Functional Group#Amine]]
An Amine is added to the end of the name
There may be a a tert next to it for tertiary structure or dimethyl would indicate two methyl groups attached to the amine
### [[Functional Group#Ketone]]
An one is added to the end
### [[Functional Group#Amide]]
An ide is added to the end
if there is something attached to the n it goes in front with N-functional group
### [[Functional Group#Nitrile]]
Nitrile is added to the end
