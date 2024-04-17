# Trabalho-jd

**Estimativa de máxima verossimilhança**
Para estimar os parâmetros do modelo, adaptamos um algoritmo proposto por Anderson (1973). A log-verossimilhaça para o modelo especial linear t-Student é dado por
$\mathcal{L}(\theta) = log(K_{n}(\eta)) - \frac{1}{2}  log(|\Sigma|) - 1/(2\eta)  (1 + n\eta)  log(1 + c(\eta)  \delta),$


 **com** $log (K_{n} (\eta) = \frac{n}{2} log (\frac{ c(\eta)}{\pi}) + log \Gamma (\frac{1+\eta\eta}{2\eta}) - log \Gamma (\frac{1}{2\eta}) , \delta = \boldsymbol{(Y - X \beta)}^{T}\sigma^{-1} \boldsymbol {(Y - X\beta )e} c(\eta) = (\eta)/(1 - 2\eta), 0 < (\eta) < \frac{1}{2}.$

