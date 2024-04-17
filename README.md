# Trabalho-jd

**Estimativa de máxima verossimilhança**
Para estimar os parâmetros do modelo, adaptamos um algoritmo proposto por Anderson (1973). A log-verossimilhaça para o modelo especial linear t-Student é dado por
$\mathcal{L}(\theta) = log(K_{n}(\eta)) - \frac{1}{2}  log(|\Sigma|) - 1/(2\eta)  (1 + n\eta)  log(1 + c(\eta)  \delta),$
 **com** $log (K_{n} (\eta) = \frac{n}{2}log 2 π + log ( 1+n eta 2 eta ) - log(Gamma) * (1/(2eta)) , delta=(Y-X beta)^ top Sigma^ -1 (Y- Χβ) e c( eta)= eta/( 1 - 2eta ), 0 < eta < 1/2$
