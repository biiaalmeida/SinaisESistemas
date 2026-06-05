## Questão 1

Demonstre que o sistema apresentado na Figura 1 sempre é estável, independentemente dos valores de \(R\) e \(C\). Dica: Lembre-se que resistência e capacitância são sempre valores positivos.

---

A função de transferência do filtro passa-baixas RC é dada por:

$$
H(s)=\frac{1}{RCs+1}
$$

Para verificar a estabilidade do sistema, determinamos seus polos, que são obtidos igualando o denominador a zero:

$$
RCs+1=0
$$

Logo,

$$
s=-\frac{1}{RC}
$$

Como \(R\) representa a resistência do circuito e \(C\) representa a capacitância, ambos são grandezas físicas que assumem apenas valores positivos. Portanto,

$$
R>0
$$

e

$$
C>0.
$$

Dessa forma,

$$
RC>0.
$$

Consequentemente,

$$
-\frac{1}{RC}<0.
$$

Assim, o único polo do sistema encontra-se sempre no semiplano esquerdo do plano complexo.

Como um sistema contínuo é estável quando todos os seus polos possuem parte real negativa, conclui-se que o sistema é estável para quaisquer valores positivos de resistência e capacitância.

Portanto, o filtro apresentado é sempre estável, independentemente dos valores de \(R\) e \(C\).