<h1>Concreto Protendido</h1>

<p align="justify">Como a resistência do concreto à tração é baixa, foi necessário inserir barras de aço nas regiões onde as tensões de tração atuam. No entanto, há um fator geralmente crítico no projeto de elementos que vencem vãos, como vigas e lajes, é o Estado-Limite de Serviço relativo à deformação excessiva (ELS-DEF), ou seja, as flechas resultantes dos deslocamentos verticais. E flechas elevadas são associadas a peças com grandes curvaturas e aberturas de fissuras, e consequentemente grandes deformações na armadura tracionada. Assim é que nas peças fletidas em Concreto Armado não adianta utilizar aços com resistências ainda mais elevadas, pois a tensão de serviço no aço deve ser limitada a uma deformação máxima baixa, aquela do concreto (10 ‰).</p>
<p align="justify">Sendo assim, a aplicação da prontesão ao concreto surgiu de modo natural, com a ideia de pré-comprimmir a região da seção trasversal que depois será tracionada com a atuação do carregamento externo.</p>
<p align="justify">Portanto, os elementos de concreto protendido são aqueles nos quais parte das armaduras é previamente alongada por equipamentos especiais de protensão, com a finalidade de, em condições de serviço, impedir ou limitar a fissuração e os deslocamentos da estrutura, bem como propiciar o melhor aproveitamento de aços de alta resistência no estado-limite último (ELU).</p>

<h2>Exemplo</h2>

<p align="justify">Verificação da segurança de estruturas de concreto protendido</p>

<p align="justify"><b>Dados iniciais:</b></p>
<p>Vão teórico = 7 m <br>
Seção transversal: b = 0,20 m e h = 0,75 m</p>

<p align="justify"><b>Ações em que a viga está sujeita:</b></p>
<p>Peso próprio: \(g = 0,20 \cdot 0,75 \cdot 25 = 3,75 kN/m\) <br> 
Carga acidental q = 15 kN/m <br>
força de protensão P = -600 kN, aplicada com excentricidade ep = 0,125 m com relação ao eixo baricêntro da seção transversal.
</p>

<p align="justify"><b>1) Cálculo das características geométricas e mecânicas da seção transversal</b></p>
<p>\[I= \frac{b\cdot h^{3}}{12}= 7,03\cdot 10^{-3} m^{4}\] <br>
\[y_{1}= -y_{2}= 0,375\] <br>
\[W_{1}= -W_{2}= \frac{I}{y_{1}}= 18,75\cdot 10^{-3}\] <br>
\[A= b\cdot h= 0,150 m^{2}\] <br>
Distância das extremidades do núcleo central da seção ao centro de gravidade = 0,125 m</p>

<p align="justify"><b>2) Cálculo dos esforços solicitantes e tensões normais no meio do vão</b></p>
<p>a) Tensões devidas ao peso próprio</p>
<p>\[M_{g1}= \frac{q\cdot l^{2}}{8}= \frac{3,75\cdot 7^{2}}{8}= 22,97 \: kN\cdot m\] <br>
\[\sigma_{1g1}= \frac{M_{g1}}{W_{1}}= 1,23\:  MPa \: (na\: borda\:  inferior)\] <br>
\[\sigma_{2g1}= \frac{M_{g1}}{W_{2}}=- 1,23\:  MPa \: (na\: borda\:  superior)\] </p>

<p>b) Tensões devidas a carga acidental</p>
<p>\[M_{q}= \frac{q\cdot l^{2}}{8}= \frac{15\cdot 7^{2}}{8}= 91,88 \: kN\cdot m\] <br>
\[\sigma_{1q}= \frac{M_{q}}{W_{1}}= 4,9\:  MPa \: (na\: borda\:  inferior)\] <br>
\[\sigma_{2q}= \frac{M_{q}}{W_{2}}=- 4,9\:  MPa \: (na\: borda\:  superior)\] </p>

<p>c) Tensões devidas à força de protensão</p>
<p>\[P=-600 kN\] <br>
\[M_{P}= P\cdot e_{P}\] <br>
\[\sigma _{1P}= \frac{P}{A_{c}}+\frac{P\cdot e_{P}}{W_{1}}= -8\: MPa\] <br>
\[\sigma _{2P}= \frac{P}{A_{c}}+\frac{P\cdot e_{P}}{W_{2}}= 0\] </p>

<p align="justify"><b>3) Combinação das ações</b></p>
<p>a) Estado em vazio</p>
<p>Representando graficamente as tensões provocadas por cada ação e a sua somatória:</p>
<img src="Estado em vazio.png" /> </p>

<p>a) Estado em serviço</p>
<p>Analogamente ao caso anterior, resulta:</p>
<img src="Estado em serviço.png" /> </p>

<p align="justify"><b>4) Primeira análise dos resultados</b></p>
<p>De imediato, pode-se observar que:</p>
<body>
<ul>
<li>Em ambas as combinações não ocorrem tensões de tração, e as tensões de compressão são relativamente baixas, podendo ser suportadas por um concreto de média resistência;</li>
<li>Como exixte uma tensão de compressão residual na borda inferior, a viga poderia receber carga acidental ainda um pouco maior, sem perigo de fissuração;</li>
<li>No estado em vazio, as tensões de compressão são até maiores que no estado em serviço; ou seja, o acréscimo de cargas não piora a situação.</li>
</ul>
</body>
</html>

<p align="justify"><b>5) Reformulação do problema</b></p>
<p align="justify">Nessa etapa vamos reformular o problema para reavaliar o comportamento da estrutura. Poderíamos ter uma situaçãi em que a força de protensão propiciaria tensões prévias de compressão na borda inferior e tensões prévias de tração na borda superior. Além disso, do ponto de vista econômico, mantida a intensidade da força de protensão, a armadura seria a mesma e o aumento da excentricidade praticmente não acarretaria aumento de custo. Assim, adota-se:</p>
<p>\[e_{P}= 0,375-0,05= 0,325\: m\]</p>
<p align="justify">Além disso, para obter um resultado a ser comparado com o anterior, aumenta-se o valor da carga acidental para 34,6 kN/m.</p>
<p>\[q=34,6\: kN\cdot m\]</p>

<p align="justify"><b>6) Cálculo de esforços solicitantes e tensões normais no meio do vão</b></p>

<p>a) Tensões devidas ao peso próprio</p>
<p>São as mesmas já calculadas.</p>

<p>b) Tensões devidas à carga acidental </p>
<p>\[M_{q}= \frac{q\cdot l^{2}}{8}= \frac{34,6\cdot 7^{2}}{8}= 211,93 \: kN\cdot m\] <br>
\[\sigma_{1q}= \frac{M_{q}}{W_{1}}= 11,3\:  MPa \: (na\: borda\:  inferior)\] <br>
\[\sigma_{2q}= \frac{M_{q}}{W_{2}}=- 11,3\:  MPa \: (na\: borda\:  superior)\] </p>

<p>c) Tensões devidas à força de protensão</p>
<p>\[P=-600 kN\] <br>
\[M_{P}= P\cdot e_{P}\] <br>
\[\sigma _{1P}= \frac{P}{A_{c}}+\frac{P\cdot e_{P}}{W_{1}}= -14,40\: MPa\] <br>
\[\sigma _{2P}= \frac{P}{A_{c}}+\frac{P\cdot e_{P}}{W_{2}}= +6,4\: MPa\] </p>

<p align="justify"><b>7) Combinação das ações</b></p>

<p>a) Estado em vazio</p>
<p>Nesta nova combinação resulta:</p>
<img src="Estado em vazio 2.png" /> </p>

<p>a) Estado em serviço</p>
<p>Analogamente ao caso anterior, resulta:</p>
<img src="Estado em serviço 2.png" /> </p>

<p align="justify"><b>8) Segunda análise de resultados</b></p>

<p>Comparando os resultados agora obtidos com os anteriores, pode-se observar que:</p>
<body>
<ul>
<li>No estado em serviço só existem tensões de compressão, com valores idênticos aos obtidos no cálculo anterior (nota-se que o novo valor da sobre-carga foi adotado propositalmente);</li>
<li>A carga acidental é bem maior (2,31 vezes), o quedemonstra que um simples deslocamento de força normal pode melhorar muito a capacidade portante da estrutura;</li>
<li>No estado em vazio, entretanto, surgem tensões de tração na borda superior (com valor igual a 5,17 MPa), o que mostra que os efeitos da protensão foram exagerados para a situação. Além disso, as tensões de compressão na borda inferior são bem maiores que no exemploinicial do cálculo;</li>
<li>Mais uma vez se observa (agora de modo mais proeminente) que pode ocorrer que no estado em vazio a seção transversal esteja mais solicitada que no estado em serviço. É possível que haja uma surpresa inicialao se constatar que o acréscimo de cargas acarreta a diminuição de esforços. No entanto, é bom lembrar sempre que a protensão também é uma ação, a qual não pode ser esquecida nas combinações de ações, como por exemplo o estado em vazio.</li>
</ul>
</body>
</html>

<p align="justify"><b>9) Conclusões e observações a serem sempre lembradas</b></p>

<p align="justify">Com base nos resultados pode-se analisar um conjunto de observações que deverão nortear qualquer verificação da segurança de estruturas de concreto protendido.</p>

<p>a) Combinação das ações</p>
<p align="justify">É necessário que haja uma verificação cuidadosa de todas as fases de solicitação da peça, uma vez que a pior situação não é necessariamente aquela correspondente à atuação da totalidade das cargas externas. Deve-se ,portanto, no projeto, conhecer pelo menos as prinipais fases da vida da estrutura, inclusive nas suas diversas etapas de construção.</p>

<p>b) Efeitos da força de protensão</p>
<p align="justify">Os efeitos da força de protensão resultam da sua intensidade e da sua excentricidade.</p>
<p align="justify">Variando-se a intensidade e a excentricidade da força de protensão, ôbtem-se os efeitos desejados. No caso de estruturas hiperestáticas, deve-se considerar também a redistribuição de esforços decorrente da existtência de vínculos adicionais, que acarreta os chamados "hiperestáticos de protensão".</p>

<p>c) Solicitações ao longo do vão</p>
<p align="justify">Nos exemplos numéricos, foi analisada somente a seção do meio do vão, que é a mais solicitada pelo carregamento externo.</p>
<p align="justify">Contudo, se analisarmos outras seções, como por exemplo aquelas próximas aos apoios, podemos notar que as tensões provocadas pelas cargas externas diminuem, tendendo a zero. Consequentemente, se forem mantidas as mesmas condições da força de protensão (intensidade e excentricidade), poderão ocorrer situações indesejáveis.</p>
<p align="justify">Assim, é preciso que sejam verificadas as seções ao longo do vão (não apenas as mais solicitadas pelo carregamento externo), procurando-se, na medida do necessário, variar os efeitos de protensão.</p>

<p>d) Estados limites últimos e de utilização</p>
<p align="justify">Uma verificação como essa realizada nos exemplos numéricos é útil para análise da estrutura nas condições de serviço, isto é, para a verificação de estados limites de utilização. É sempre necessário que sejam feitas também verificações dos estados limites útimos, de acordo com procedimentos que serão abordados durante o curso.</p>
