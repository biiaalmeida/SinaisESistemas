## Questão 3

A frequência de corte desse filtro é definida como a frequência na qual a resposta em magnitude é $3\,dB$ inferior ao máximo ganho do circuito. Considerando que o ganho máximo desse sistema ocorre quando $\omega=0$, determine uma expressão para a frequência de corte desse circuito em função dos valores de $R$ e $C$.

---

A resposta em magnitude do filtro passa-baixas RC é dada por:

$$
|H(\omega)|=\frac{1}{\sqrt{1+\omega^2R^2C^2}}
$$

O ganho máximo ocorre quando $\omega=0$. Assim,

$$
|H(0)|=1
$$

Em decibéis:

$$
20\log_{10}(1)=0\,dB
$$

Portanto, o ganho máximo do circuito é $0\,dB$.

A frequência angular de corte ocorre quando a magnitude está $3\,dB$ abaixo do ganho máximo:

$$
|H(\omega_c)|_{dB}=-3\,dB
$$

Como:

$$
|H(\omega)|_{dB}=20\log_{10}|H(\omega)|
$$

temos:

$$
20\log_{10}|H(\omega_c)|=-3
$$

Logo:

$$
|H(\omega_c)|=10^{-3/20}
$$

Como:

$$
10^{-3/20}\approx 0,707 \approx \frac{1}{\sqrt{2}},
$$

podemos escrever:

$$
|H(\omega_c)|=\frac{1}{\sqrt{2}}
$$

Substituindo na expressão da magnitude:

$$
\frac{1}{\sqrt{1+\omega_c^2R^2C^2}}=\frac{1}{\sqrt{2}}
$$

Elevando ambos os lados ao quadrado:

$$
\frac{1}{1+\omega_c^2R^2C^2}=\frac{1}{2}
$$

Multiplicando cruzado:

$$
2=1+\omega_c^2R^2C^2
$$

$$
\omega_c^2R^2C^2=1
$$

Extraindo a raiz quadrada:

$$
\omega_cRC=1
$$

Portanto, a frequência angular de corte é:

$$
\boxed{\omega_c=\frac{1}{RC}}
$$

Como a relação entre frequência angular e frequência em hertz é:

$$
\omega_c=2\pi f_c
$$

então:

$$
2\pi f_c=\frac{1}{RC}
$$

Isolando $f_c$:

$$
f_c=\frac{1}{2\pi RC}
$$

Portanto, a frequência de corte em hertz é:

$$
\boxed{f_c=\frac{1}{2\pi RC}}
$$