# Metodi di integrazione
## Integrali immediati 
**NB:** la primitiva è una vunzione derivabile, dunque queste formule valgono solo dove sono derivabili. Ad esempio  $\int \frac{1}{x} d x=\ln |x|+c$  è valida solo negli intervalli che **non** contengono l'origine

1. $$\int k d x=k x+c \quad k \in R$$
2. $$\int x^{\alpha} d x=\frac{x^{\alpha+1}}{\alpha+1}+c \quad \alpha \in R , \alpha \neq-1$$
3. $$\int \frac{1}{x} d x=\ln |x|+c$$
4. $$\int \sin{x}dx = -\cos{x}+c$$
5. $$\int \cos{x}dx = -\sin{x}+c$$
6. $$\int \frac{1}{\cos^{2}{x}dx}= \int(1+\tan^{2}{x})dx = \tan{x}+c$$
7. $$\int \frac{1}{\sin^{2}{x}dx}= \int(1+\cot^{2}{x})dx = \cot{x}+c$$
8. $$\int e^{x}dx = e^{x}+c$$
9. $$\int a^{x}dx = \frac{a^{x}}{\ln{a}}+c$$
10. $$\int \frac{1}{1+x^{2}}dx = \arctan{x}+c$$
11. $$\int \frac{1}{\sqrt{1-x^{2}}}dx = \arcsin{x}+c$$
## Composte 
![[zzzmedia/stuff/Pasted image 20220517203938.png]]
## Sostituzione
Si sostituisce qualcosa con $t$ e si svolge l'integrale in $dt$, dopodichè si torna a $x$
## Per parti
$$\int f(x)\cdot g'(x) dx = f(x) \cdot g(x) - \int f'(x) \cdot g(x) dx $$
## Razionali frazionarie
1. Si controlla che $D(x)$ abbia grado $\leq$ di $B(x)$ , altrimenti si effettua una divisione tra polinomi da cui: $$\int \frac{A(x)}{B(x)}dx = \int \frac{B(x)Q(x)+R(x)}{B(x)}dx = \int \left( Q(x) + \frac{R(x)}{B(x)} \right) dx $$
### numeratore >  denominatore
2. si riscrive l'integrale e lo si calcola per parti
### denominatore di primo grado
2. si riconduce alla forma $$$\int \frac{f'(x)}{f(x)}$$

## denominatore di secondo grado
### caso 1: discriminante $\geq 0$  
